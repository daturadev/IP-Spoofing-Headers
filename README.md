### IP Spoofing Headers

List of headers to identify and exploit attacks through IP spoofing header injection, like bypass restrictions (403, etc.), hop-by-hop, request smuggling, and log injection:

* Forwarded
* X-Forwarded
* X-Forwarded-Host
* X-Forwarded-By
* X-Forwarded-For
* X-Forwarded-Server
* X-Real-IP
* X-Forwarded-Proto
* X-Forwarded-For-Original
* X-Forward-For
* Forwarded-For-IP
* X-Originating-IP
* X-Forwarded-For-IP
* X-Forwarded-Port
* X-Remote-IP
* X-Remote-Addr
* X-Remote-Host
* X-Server-Name
* X-Client-IP
* Client-Ip
* X-Host
* Origin
* Access-Control-Allow-Origin
* X-Custom-IP-Authorization
* X-ProxyUser-Ip
* Via
* X-Cluster-Client-Ip
* CF-Connecting-IP
* True-Client-IP

### Scope

This headers can be used with any framework language, with providers like Google Cloud, AWS & Azure, and cloud architectures using proxy components.

### References

* https://docs.aws.amazon.com/elasticloadbalancing/latest/application/x-forwarded-headers.html
* https://cloud.google.com/appengine/docs/flexible/go/reference/request-headers
* https://azure.microsoft.com/en-in/blog/rewrite-http-headers-with-azure-application-gateway/
* https://www.nginx.com/resources/wiki/start/topics/examples/forwarded/
