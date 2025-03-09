# HTTP Headers Constants for Go ![Go Reference](https://pkg.go.dev/badge/github.com/HARB1I/httpheaders.svg)

Полный набор предопределенных констант для работы с HTTP-заголовками в Go приложениях.

## Содержание
- [HTTP Headers Constants for Go ](#http-headers-constants-for-go-)
  - [Содержание](#содержание)
  - [Заголовки](#заголовки)
  - [Content-Type](#content-type)
  - [Cache-Control](#cache-control)
  - [Connection](#connection)
  - [Безопасность](#безопасность)
    - [X-Content-Type-Options](#x-content-type-options)
    - [X-Frame-Options](#x-frame-options)
    - [X-XSS-Protection](#x-xss-protection)
    - [Content-Security-Policy](#content-security-policy)
  - [Кодирование](#кодирование)
  - [CORS](#cors)
  - [Другие значения](#другие-значения)
  - [Установка](#установка)

## Заголовки
| Константа | Значение |
|-----------|----------|
| `Accept` | "Accept" |
| `AcceptCharset` | "Accept-Charset" |
| `AcceptEncoding` | "Accept-Encoding" |
| `AcceptLanguage` | "Accept-Language" |
| `AcceptRanges` | "Accept-Ranges" |
| `AccessControlAllowOrigin` | "Access-Control-Allow-Origin" |
| `Age` | "Age" |
| `Allow` | "Allow" |
| `Authorization` | "Authorization" |
| `CacheControl` | "Cache-Control" |
| `Connection` | "Connection" |
| `ContentDisposition` | "Content-Disposition" |
| `ContentEncoding` | "Content-Encoding" |
| `ContentLanguage` | "Content-Language" |
| `ContentLength` | "Content-Length" |
| `ContentLocation` | "Content-Location" |
| `ContentRange` | "Content-Range" |
| `ContentType` | "Content-Type" |
| `Cookie` | "Cookie" |
| `Date` | "Date" |
| `ETag` | "ETag" |
| `Expect` | "Expect" |
| `Expires` | "Expires" |
| `Forwarded` | "Forwarded" |
| `From` | "From" |
| `Host` | "Host" |
| `IfMatch` | "If-Match" |
| `IfModifiedSince` | "If-Modified-Since" |
| `IfNoneMatch` | "If-None-Match" |
| `IfRange` | "If-Range" |
| `IfUnmodifiedSince` | "If-Unmodified-Since" |
| `LastModified` | "Last-Modified" |
| `Location` | "Location" |
| `MaxForwards` | "Max-Forwards" |
| `Pragma` | "Pragma" |
| `ProxyAuthenticate` | "Proxy-Authenticate" |
| `ProxyAuthorization` | "Proxy-Authorization" |
| `Range` | "Range" |
| `Referer` | "Referer" |
| `RetryAfter` | "Retry-After" |
| `Server` | "Server" |
| `SetCookie` | "Set-Cookie" |
| `TE` | "TE" |
| `Trailer` | "Trailer" |
| `TransferEncoding` | "Transfer-Encoding" |
| `Upgrade` | "Upgrade" |
| `UserAgent` | "User-Agent" |
| `Vary` | "Vary" |
| `Via` | "Via" |
| `WWWAuthenticate` | "WWW-Authenticate" |
| `Warn` | "Warning" |
| `XContentTypeOptions` | "X-Content-Type-Options" |
| `XForwardedFor` | "X-Forwarded-For" |
| `XForwardedHost` | "X-Forwarded-Host" |
| `XForwardedProto` | "X-Forwarded-Proto" |
| `XFrameOptions` | "X-Frame-Options" |
| `XPoweredBy` | "X-Powered-By" |
| `XRealIP` | "X-Real-IP" |
| `XRequestedWith` | "X-Requested-With" |
| `XSSProtection` | "X-XSS-Protection" |

## Content-Type
| Константа | Значение |
|-----------|----------|
| `TextHTML` | "text/html" |
| `TextPlain` | "text/plain" |
| `TextCSS` | "text/css" |
| `TextJavaScript` | "text/javascript" |
| `ApplicationJSON` | "application/json" |
| `ApplicationXML` | "application/xml" |
| `ApplicationPDF` | "application/pdf" |
| `ApplicationZip` | "application/zip" |
| `ImagePNG` | "image/png" |
| `ImageJPEG` | "image/jpeg" |
| `ImageGIF` | "image/gif" |
| `ImageSVG` | "image/svg+xml" |
| `MultipartForm` | "multipart/form-data" |
| `ApplicationForm` | "application/x-www-form-urlencoded" |

## Cache-Control
| Константа | Значение |
|-----------|----------|
| `CacheNoCache` | "no-cache" |
| `CacheNoStore` | "no-store" |
| `CacheNoTransform` | "no-transform" |
| `CacheMustRevalidate` | "must-revalidate" |
| `CachePublic` | "public" |
| `CachePrivate` | "private" |
| `CacheMaxAge` | "max-age=" |
| `CacheProxyRevalidate` | "proxy-revalidate" |
| `CacheStaleWhileRevalidate` | "stale-while-revalidate=" |

## Connection
| Константа | Значение |
|-----------|----------|
| `ConnectionKeepAlive` | "keep-alive" |
| `ConnectionClose` | "close" |

## Безопасность
### X-Content-Type-Options
| Константа | Значение |
|-----------|----------|
| `XCTO_NoSniff` | "nosniff" |

### X-Frame-Options
| Константа | Значение |
|-----------|----------|
| `XFO_Deny` | "DENY" |
| `XFO_SameOrigin` | "SAMEORIGIN" |
| `XFO_AllowFrom` | "ALLOW-FROM" |

### X-XSS-Protection
| Константа | Значение |
|-----------|----------|
| `XSSP_Enable` | "1" |
| `XSSP_Block` | "1; mode=block" |
| `XSSP_Report` | "1; report=" |

### Content-Security-Policy
| Константа | Значение |
|-----------|----------|
| `CSP_DefaultSrc` | "default-src" |
| `CSP_ScriptSrc` | "script-src" |
| `CSP_StyleSrc` | "style-src" |
| `CSP_ImgSrc` | "img-src" |
| `CSP_ConnectSrc` | "connect-src" |
| `CSP_FontSrc` | "font-src" |
| `CSP_ObjectSrc` | "object-src" |
| `CSP_MediaSrc` | "media-src" |
| `CSP_FrameSrc` | "frame-src" |
| `CSP_Sandbox` | "sandbox" |
| `CSP_ReportURI` | "report-uri" |
| `CSP_FrameAncestors` | "frame-ancestors" |
| `CSP_BaseURI` | "base-uri" |
| `CSP_FormAction` | "form-action" |

## Кодирование
| Константа | Значение |
|-----------|----------|
| `EncodingGzip` | "gzip" |
| `EncodingBrotli` | "br" |
| `EncodingDeflate` | "deflate" |

## CORS
| Константа | Значение |
|-----------|----------|
| `ACAO_AllowAll` | "*" |

## Другие значения
| Константа | Значение |
|-----------|----------|
| `ServerValue` | "Server" |
| `LocationValue` | "Location" |
| `SetCookieValue` | "Set-Cookie" |

## Установка
```bash
go get github.com/HARB1I/httpheaders
