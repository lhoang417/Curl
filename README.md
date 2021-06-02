# Curl

curl https://domain.com/    Check URL
curl -o website https://domain.com/   Save the output of the URL to a file
curl -O https://domain.com/file.zip   Download files - In this example, the ‘file.zip’ zip archive will be downloaded to the current working directory.
curl -o archive.zip https://domain.com/file.zip   This way the ‘file.zip’ archive will be downloaded and saved as ‘archive.zip’.
curl -O https://domain.com/file.zip -O https://domain.com/file2.zip   cURL can also be used to download multiple files simultaneously
curl -I http://domain.com   Get HTTP header information from a website
curl ftp://ftp.domain.com --user username:password   Access an FTP server
curl ftp://ftp.domain.com/filename.extension --user username:password   download files via FTP
curl -T filename.extension ftp://ftp.domain.com/ --user username:password    upload a file onto the FTP server
