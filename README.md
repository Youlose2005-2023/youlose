<?php
require 'IP2Location.php';

$loc = new IP2Location('databases/IP-COUNTRY.BIN', IP2Location::FILE_IO);
$record = $loc->lookup($_SERVER['REMOTE_ADDR'], IP2Location::ALL);

if($record == 'BB') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.youtube.com');
	exit;
}

if($record == 'BO') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'BR') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'BG') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'CA') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'CL') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'CO') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'FI') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'EC') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'GB') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'DE') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'JP') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'PL') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'HU') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'US') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'KR') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'AR') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'LT') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'MX') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

if($record == 'PH') {
	header('HTTP/1.1 301 Moved Permanently');
	header('Location: https://www.rico.com');
	exit;
}

?>
