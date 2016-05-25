# HEAD

A collection of HTML head elements.

## Recommended Minimum

Below are the essential tags for basic, minimalist websites:

```html
<meta charset="utf-8">
<meta http-equiv="x-ua-compatible" content="ie=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Page Title</title>
```

## Elements

``` html
<title>Page Title</title>
<!-- The <base> tag defines a base URL for all relative links in the document --> 
<base href="https://example.com/page.html">
<style>
  body { color: red; }
</style>
<script src="script.js"></script>
```

## Meta Element

``` html
<meta charset="utf-8">
<meta http-equiv="x-ua-compatible" content="ie=edge">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
<meta name="application-name" content="Application Name">
<meta name="keywords" content="your,keywords,here,comma,separated,no,spaces">
<meta name="description" content="150 chars">
<meta name="subject" content="your website's subject">
<meta name="robots" content="index,follow,noodp">
<meta name="googlebot" content="index,follow">
<meta name="google" content="nositelinkssearchbox">
<meta name="google-site-verification" content="verification_token">
<meta name="abstract" content="">
<meta name="topic" content="">
<meta name="summary" content="">
<meta name="classification" content="business">
<meta name="url" content="https://example.com/">
<meta name="identifier-URL" content="https://example.com/">
<meta name="directory" content="submission">
<meta name="category" content="">
<meta name="coverage" content="Worldwide">
<meta name="distribution" content="Global">
<meta name="rating" content="General">
<meta name="referrer" content="never">
<meta http-equiv="Content-Security-Policy" content="default-src 'self'">
```

### Not Recommended
Below are the meta attributes which are not recommended for use:

```html
<!-- Used to declare the document language, but not well supported. Better to use <html lang=""> -->
<meta name="language" content="en">

<!-- No evidence of current use in any search engines -->
<meta name="revised" content="Sunday, July 18th, 2010, 5:15 pm">

<!-- Provides an easy way for spam bots to harvest email addresses -->
<meta name="reply-to" content="email@example.com">

<!-- Better to use <link rel="author"> or humans.txt file -->
<meta name="author" content="name, email@example.com">
<meta name="designer" content="">
<meta name="owner" content="">

<!-- Tells search bots to revisit the page after a period. This is not supported because most Search Engines now use random intervals for re-crawling a webpage -->
<meta name="revisit-after" content="7 days">

<!-- Google strongly advises not to use this. Better to set up server-side (e.g. Apache, nginx) redirects instead -->
<meta http-equiv="refresh" content="300;url=https://example.com/">

<!-- Cache Control -->
<!-- Better to configure cache control server side -->
<meta http-equiv="Expires" content="0">
<meta http-equiv="Pragma" content="no-cache">
<meta http-equiv="Cache-Control" content="no-cache">
```

## Link Element

``` html
<link rel="copyright" href="copyright.html">
<link rel="stylesheet" href="https://example.com/styles.css">
<link rel="alternate" href="https://feeds.feedburner.com/martini" type="application/rss+xml" title="RSS">
<link rel="alternate" href="https://example.com/feed.atom" type="application/atom+xml" title="Atom 0.3">
<link rel="alternate" href="https://es.example.com/" hreflang="es">
<link rel="me" href="https://google.com/profiles/thenextweb" type="text/html">
<link rel="me" href="mailto:name@example.com">
<link rel="me" href="sms:+15035550125">
<link rel="archives" href="https://example.com/2003/05/" title="May 2003">
<link rel="index" href="https://example.com/" title="DeWitt Clinton">
<link rel="start" href="https://example.com/photos/pattern_recognition_1_about/" title="Pattern Recognition 1">
<link rel="prev" href="https://example.com/opensearch/opensearch-and-openid-a-sure-way-to-get-my-attention/" title="OpenSearch and OpenID? A sure way to get my attention.">
<link rel="search" href="/open-search.xml" type="application/opensearchdescription+xml" title="Search Title">
<link rel="self" type="application/atom+xml" href="https://example.com/atomFeed.php?page=3">
<link rel="first" href="https://example.com/atomFeed.php">
<link rel="next" href="https://example.com/atomFeed.php?page=4">
<link rel="previous" href="https://example.com/atomFeed.php?page=2">
<link rel="last" href="https://example.com/atomFeed.php?page=147">
<link rel="shortlink" href="https://example.com/?p=43625">
<link rel="canonical" href="https://example.com/2010/06/9-things-to-do-before-entering-social-media.html">
<link rel="amphtml" href="https://www.example.com/url/to/amp-version.html">
<link rel="EditURI" href="https://example.com/xmlrpc.php?rsd" type="application/rsd+xml" title="RSD">
<link rel="pingback" href="https://example.com/xmlrpc.php">
<link rel="webmention" href="https://example.com/webmention">
<link rel="manifest" href="manifest.json">
<link rel="author" href="humans.txt">
<link rel="import" href="component.html">

<!-- Prefetching, preloading, prebrowsing -->
<link rel="dns-prefetch" href="//example.com/">
<link rel="preconnect" href="https://www.example.com/">
<link rel="prefetch" href="https://www.example.com/">
<link rel="prerender" href="https://example.com/">
<link rel="subresource" href="styles.css">
<link rel="preload" href="image.png">
<!-- More info: https://css-tricks.com/prefetching-preloading-prebrowsing/ -->
```


