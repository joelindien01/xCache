xCache install
@Author: me
#install xCache for WAMP server 2.5

#1
First download xCache from http://xcache.lighttpd.net/pub/Releases/3.2.0/

#2
then choose XCache-3.2.0-php-5.5.16-Win32-VC11-x64.zip version if your computer is a 64bits processor

#3
unzip it and copy the "php_xcache.dll" from unzipped directory to "path-to-your-wamp-directory\bin\php\php-version" 

#4
add this "extension=php_xcache.dll" (without " " ) in your php.ini file and it's done !!!


