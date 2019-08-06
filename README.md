Local-CORS
===========

Allows CORS requests from your localhost to any API by setting 'Access-Control-Allow-Origin: *' 
header. 

This extension is meant to be used by web developers who need to test UI changes from their 
local machines against a remote API that doesn't allow localhost CORS requests.

Make sure you understand how CORS works (https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) 
before enabling this extension. As a best practice, you should lock down the intercepted URL 
pattern to only the API you are actually trying to test.


Installation
=============

From the Chrome App Store:

Chrome extension: https://chrome.google.com/webstore/detail/local-cors/bhachhlaofmplbfnefenmlnflolelkff


Thanks!
========

Thank you to [Vitvad](https://github.com/vitvad) for the original repo, 
[Access-Control-Allow-Origin](https://github.com/vitvad/Access-Control-Allow-Origin) that this code 
was forked from. 
