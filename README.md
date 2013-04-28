Dropbox Uploader
==========
Dropbox Uploader is a PHP class which can be used to upload files to Dropbox

Usage
==========
require 'DropboxUploader.php';

$uploader = new DropboxUploader('email@address.com', 'password');
$uploader->upload('path/to/a/file.txt');