[Back to the Ling/SimpleCurl api](https://github.com/lingtalfi/SimpleCurl/blob/master/doc/api/Ling/SimpleCurl.md)<br>
[Back to the Ling\SimpleCurl\SimpleCurl class](https://github.com/lingtalfi/SimpleCurl/blob/master/doc/api/Ling/SimpleCurl/SimpleCurl.md)


SimpleCurl::call
================



SimpleCurl::call — Calls an url and returns the corresponding response.




Description
================


public [SimpleCurl::call](https://github.com/lingtalfi/SimpleCurl/blob/master/doc/api/Ling/SimpleCurl/SimpleCurl/call.md)(string $url) : [SimpleCurlResponseInterface](https://github.com/lingtalfi/SimpleCurl/blob/master/doc/api/Ling/SimpleCurl/Response/SimpleCurlResponseInterface.md) | false




Calls an url and returns the corresponding response.
Returns false in case of an error, in which case errors are available via the getErrors method.

This method was designed to call a simple url.
For instance, if you want to ping a google server to ask them to crawl your website,
you want to call this url:

http://www.google.com/ping?sitemap=https://example.com/sitemap.xml

See more info here: https://support.google.com/webmasters/answer/183668?hl=en&ref_topic=4581190




Parameters
================


- url

    


Return values
================

Returns [SimpleCurlResponseInterface](https://github.com/lingtalfi/SimpleCurl/blob/master/doc/api/Ling/SimpleCurl/Response/SimpleCurlResponseInterface.md) | false.


Exceptions thrown
================

- [SimpleCurlException](https://github.com/lingtalfi/SimpleCurl/blob/master/doc/api/Ling/SimpleCurl/Exception/SimpleCurlException.md).&nbsp;







See Also
================

The [SimpleCurl](https://github.com/lingtalfi/SimpleCurl/blob/master/doc/api/Ling/SimpleCurl/SimpleCurl.md) class.

Previous method: [__construct](https://github.com/lingtalfi/SimpleCurl/blob/master/doc/api/Ling/SimpleCurl/SimpleCurl/__construct.md)<br>Next method: [getErrors](https://github.com/lingtalfi/SimpleCurl/blob/master/doc/api/Ling/SimpleCurl/SimpleCurl/getErrors.md)<br>

