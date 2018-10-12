Based on https://github.com/wonjohnchoi/Simple-Python-File-Server-With-Browse-Upload-and-Authentication

#Simple Python File PrintServer With Upload, and Authentication
### What is this?
This is a simple file server that
* supports file upload to the server, print file in default printer with cups and then delete file.
* supports authentication

It is tested with Debian 9, python 2.7.6


###How To Install
Read and edit settings.py.

`sudo ./install`

Once the script is completed, this file server should be registered as an upstart service.

Check the file server at http://host:port/base_url

###How To Uninstall
`sudo ./uninstall`

###Credit
This is a fork of https://github.com/wonjohnchoi/Simple-Python-File-Server-With-Browse-Upload-and-Authentication of http://li2z.cn/?s=SimpleHTTPServerWithUpload written by bones7456 (who also forked from http://www.opensource.apple.com/source/python/python-3/python/Lib/SimpleHTTPServer.py)

This fork basically modify to print file upload.