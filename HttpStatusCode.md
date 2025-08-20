# HTTP Status Codes

| Name                        | Value | Description |
|-----------------------------|-------|-------------|
| Continue                    | 100   | Equivalent to HTTP status 100. Continue indicates that the client can continue with its request. |
| SwitchingProtocols          | 101   | Equivalent to HTTP status 101. SwitchingProtocols indicates that the protocol version or protocol is being changed. |
| Processing                  | 102   | Equivalent to HTTP status 102. Processing indicates that the server has accepted the complete request but hasn't completed it yet. |
| EarlyHints                  | 103   | Equivalent to HTTP status 103. EarlyHints indicates to the client that the server is likely to send a final response with the header fields included in the informational response. |
| OK                          | 200   | Equivalent to HTTP status 200. OK indicates that the request succeeded and that the requested information is in the response. This is the most common status code to receive. |
| Created                     | 201   | Equivalent to HTTP status 201. Created indicates that the request resulted in a new resource created before the response was sent. |
| Accepted                    | 202   | Equivalent to HTTP status 202. Accepted indicates that the request has been accepted for further processing. |
| NonAuthoritativeInformation | 203   | Equivalent to HTTP status 203. NonAuthoritativeInformation indicates that the returned meta information is from a cached copy instead of the origin server and therefore may be incorrect. |
| NoContent                   | 204   | Equivalent to HTTP status 204. NoContent indicates that the request has been successfully processed and that the response is intentionally blank. |
| ResetContent                | 205   | Equivalent to HTTP status 205. ResetContent indicates that the client should reset (not reload) the current resource. |
| PartialContent              | 206   | Equivalent to HTTP status 206. PartialContent indicates that the response is a partial response as requested by a GET request that includes a byte range. |
| MultiStatus                 | 207   | Equivalent to HTTP status 207. MultiStatus indicates multiple status codes for a single response during a Web Distributed Authoring and Versioning (WebDAV) operation. The response body contains XML that describes the status codes. |
| AlreadyReported             | 208   | Equivalent to HTTP status 208. AlreadyReported indicates that the members of a WebDAV binding have already been enumerated in a preceding part of the multistatus response, and are not being included again. |
| IMUsed                      | 226   | Equivalent to HTTP status 226. IMUsed indicates that the server has fulfilled a request for the resource, and the response is a representation of the result of one or more instance-manipulations applied to the current instance. |
| Ambiguous                   | 300   | Equivalent to HTTP status 300. Ambiguous indicates that the requested information has multiple representations. Ambiguous is a synonym for MultipleChoices. |
| MultipleChoices             | 300   | Equivalent to HTTP status 300. MultipleChoices indicates that the requested information has multiple representations. MultipleChoices is a synonym for Ambiguous. |
| Moved                       | 301   | Equivalent to HTTP status 301. Moved indicates that the requested information has been moved. Moved is a synonym for MovedPermanently. |
| MovedPermanently            | 301   | Equivalent to HTTP status 301. MovedPermanently indicates that the requested information has been moved. MovedPermanently is a synonym for Moved. |
| Found                       | 302   | Equivalent to HTTP status 302. Found indicates that the requested information is located at the URI specified. Found is a synonym for Redirect. |
| Redirect                    | 302   | Equivalent to HTTP status 302. Redirect indicates that the requested information is located at the URI specified. Redirect is a synonym for Found. |
| RedirectMethod              | 303   | Equivalent to HTTP status 303. RedirectMethod automatically redirects after POST with a GET. Synonym for SeeOther. |
| SeeOther                    | 303   | Equivalent to HTTP status 303. SeeOther automatically redirects after POST with a GET. Synonym for RedirectMethod. |
| NotModified                 | 304   | Equivalent to HTTP status 304. NotModified indicates that the client's cached copy is up to date. |
| UseProxy                    | 305   | Equivalent to HTTP status 305. UseProxy indicates that the request should use the proxy server. |
| Unused                      | 306   | Equivalent to HTTP status 306. Unused is a proposed extension not fully specified. |
| RedirectKeepVerb            | 307   | Equivalent to HTTP status 307. RedirectKeepVerb indicates temporary redirect using same method. Synonym for TemporaryRedirect. |
| TemporaryRedirect           | 307   | Equivalent to HTTP status 307. TemporaryRedirect indicates temporary redirect using same method. Synonym for RedirectKeepVerb. |
| PermanentRedirect           | 308   | Equivalent to HTTP status 308. PermanentRedirect indicates that the request information has been moved permanently, while preserving the request method. |
| BadRequest                  | 400   | Equivalent to HTTP status 400. BadRequest indicates that the request could not be understood by the server. |
| Unauthorized                | 401   | Equivalent to HTTP status 401. Unauthorized indicates that the requested resource requires authentication. |
| PaymentRequired             | 402   | Equivalent to HTTP status 402. PaymentRequired is reserved for future use. |
| Forbidden                   | 403   | Equivalent to HTTP status 403. Forbidden indicates that the server refuses to fulfill the request. |
| NotFound                    | 404   | Equivalent to HTTP status 404. NotFound indicates that the requested resource does not exist. |
| MethodNotAllowed            | 405   | Equivalent to HTTP status 405. MethodNotAllowed indicates that the request method is not allowed. |
| NotAcceptable               | 406   | Equivalent to HTTP status 406. NotAcceptable indicates that the client will not accept any of the available representations. |
| ProxyAuthenticationRequired | 407   | Equivalent to HTTP status 407. ProxyAuthenticationRequired indicates that the proxy requires authentication. |
| RequestTimeout              | 408   | Equivalent to HTTP status 408. RequestTimeout indicates that the client did not send a request in time. |
| Conflict                    | 409   | Equivalent to HTTP status 409. Conflict indicates a request conflict on the server. |
| Gone                        | 410   | Equivalent to HTTP status 410. Gone indicates that the resource is no longer available. |
| LengthRequired              | 411   | Equivalent to HTTP status 411. LengthRequired indicates that the required Content-length header is missing. |
| PreconditionFailed          | 412   | Equivalent to HTTP status 412. PreconditionFailed indicates that a condition set for this request failed. |
| RequestEntityTooLarge       | 413   | Equivalent to HTTP status 413. RequestEntityTooLarge indicates that the request is too large. |
| RequestUriTooLong           | 414   | Equivalent to HTTP status 414. RequestUriTooLong indicates that the URI is too long. |
| UnsupportedMediaType        | 415   | Equivalent to HTTP status 415. UnsupportedMediaType indicates unsupported request type. |
| RequestedRangeNotSatisfiable| 416   | Equivalent to HTTP status 416. RequestedRangeNotSatisfiable indicates invalid range requested. |
| ExpectationFailed           | 417   | Equivalent to HTTP status 417. ExpectationFailed indicates an Expect header condition failed. |
| MisdirectedRequest          | 421   | Equivalent to HTTP status 421. MisdirectedRequest indicates wrong target server. |
| UnprocessableContent        | 422   | Equivalent to HTTP status 422. Synonym for UnprocessableEntity. |
| UnprocessableEntity         | 422   | Equivalent to HTTP status 422. Synonym for UnprocessableContent. |
| Locked                      | 423   | Equivalent to HTTP status 423. Locked indicates resource is locked. |
| FailedDependency            | 424   | Equivalent to HTTP status 424. FailedDependency indicates dependent request failed. |
| UpgradeRequired             | 426   | Equivalent to HTTP status 426. UpgradeRequired indicates protocol switch required. |
| PreconditionRequired        | 428   | Equivalent to HTTP status 428. PreconditionRequired indicates that the request must be conditional. |
| TooManyRequests             | 429   | Equivalent to HTTP status 429. TooManyRequests indicates too many requests. |
| RequestHeaderFieldsTooLarge | 431   | Equivalent to HTTP status 431. RequestHeaderFieldsTooLarge indicates headers too large. |
| UnavailableForLegalReasons  | 451   | Equivalent to HTTP status 451. Resource blocked for legal reasons. |
| InternalServerError         | 500   | Equivalent to HTTP status 500. Generic server error. |
| NotImplemented              | 501   | Equivalent to HTTP status 501. NotImplemented indicates unsupported functionality. |
| BadGateway                  | 502   | Equivalent to HTTP status 502. BadGateway indicates a proxy error. |
| ServiceUnavailable          | 503   | Equivalent to HTTP status 503. ServiceUnavailable indicates temporary server overload or maintenance. |
| GatewayTimeout              | 504   | Equivalent to HTTP status 504. GatewayTimeout indicates proxy timeout. |
| HttpVersionNotSupported     | 505   | Equivalent to HTTP status 505. HttpVersionNotSupported indicates unsupported HTTP version. |
| VariantAlsoNegotiates       | 506   | Equivalent to HTTP status 506. VariantAlsoNegotiates indicates improper content negotiation. |
| InsufficientStorage         | 507   | Equivalent to HTTP status 507. InsufficientStorage indicates insufficient storage. |
| LoopDetected                | 508   | Equivalent to HTTP status 508. LoopDetected indicates infinite loop in WebDAV processing. |
| NotExtended                 | 510   | Equivalent to HTTP status 510. NotExtended indicates further extensions required. |
| NetworkAuthenticationRequired | 511 | Equivalent to HTTP status 511. NetworkAuthenticationRequired indicates that client must authenticate for network access. |
