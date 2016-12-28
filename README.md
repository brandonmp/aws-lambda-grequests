# aws-lambda-grequests

This is a `zip` of the Python 2.7 library `grequests` and its dependencies, `gevent` and `greenlet`.

Because `gevent` and `greenlet` depend on binary files, in order to run them (and, by extension, `grequests`) on `AWS Lambda`, you have to build them on an AWS Linux machine. 

I've done that, so, if you need them, just include these folders/files in your `zip` in lieu of your locally-compiled versions.
