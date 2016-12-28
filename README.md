# aws-lambda-gevents

This is a `zip` of the Python 2.7 library `gevent` and its dependency `greenlet`, both required for the `grequests` library.

Because `gevent` and `greenlet` depend on binary files, in order to run them on `AWS Lambda`, you have to build them on an AWS Linux machine. 

I've done that, so, if you need them, just include these folders in your `zip` in lieu of your locally-compiled versions.
