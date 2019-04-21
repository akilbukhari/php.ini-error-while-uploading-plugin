# The uploaded file exceeds the upload_max_filesize directive in php.ini error while uploading plugin
It’s a common error and it can be easily fixed. This error message is an indication of that the file you are trying to upload is larger than your web host allows (WordPress default file upload size is 2 MB).

# Solution
We will find the php.ini in the following locations. Windows: `C:/xampp/php/php.ini`
you can also do  `crt + R` and pest `C:/xampp/php/php.ini` and hit enter.

After open php.ini file. press `ctr + F` and write `upload_max` and press find button.
and replace it following numbers

```` upload_max_filesize = 64M ````

Save the changes and refresh your website and try uploading the file again.
You will now get success.
