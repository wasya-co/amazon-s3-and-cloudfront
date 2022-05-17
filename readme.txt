
From: https://wordpress.org/support/topic/svg-files-are-not-being-uploaded-to-aws-s3/

function allowed_mime_types ( $types ) {
	$types['svg'] = 'image/svg+xml';
	$types['svgz'] = 'image/svg+xml';
	$types['doc'] = 'application/msword';
	$types['json'] = 'application/json';
	return $types;
}