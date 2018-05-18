<head>
  <meta charset="utf-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <title>{% if page.title %}{{ page.title }}{% else %}{{ site.title }}{% endif %}</title>
  <meta name="description" content="{% if page.description %}{{ page.description | strip_html | strip_newlines | truncate: 160 }}{% else %}{{ site.description }}{% endif %}" />
  <meta name="keywords" content="Weblog, Design, Art, Huy, Quang, Pham" />

  <meta property="og:url" content="{% if page.url %}{{ page.url | absolute_url }}{% else %}{{ site.url }}{% endif %}" />
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="{{ site.title }}" />
  <meta property="og:title" content="{% if page.og-title %}{{ page.og-title }}{% elsif page.title %}{{ page.title }}{% else %}{{ site.title }}{% endif %}" />
  <meta property="og:description" content="{% if page.og-description %}{{ page.og-description | strip_html | strip_newlines | truncate: 160 }}{% elsif page.description %}{{ page.description | strip_html | strip_newlines | truncate: 160 }}{% else %}{{ site.description }}{% endif %}" />
  <meta property="og:image" content="{% if page.imgThumbnailUrl %}{{ page.imgThumbnailUrl | absolute_url }}{% else %}{{ site.imgOg | absolute_url }}{% endif %}" />

  <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,300,700' rel='stylesheet' type='text/css' />

  <!-- Styles -->
  <link type="text/css" rel="stylesheet" href="{{ "/css/main.css?v=2" }}" />

  <link rel="canonical" href="{{ page.url | replace:'index.html','' | prepend: site.baseurl | prepend: site.url }}" />
  <link rel="alternate" type="application/rss+xml" title="{{ site.title }}" href="{{ "/feed.xml" | prepend: site.baseurl | prepend: site.url }}" />

  <link rel="shortcut icon" href="/favicon-16.png?v=2" size="16x16" />
  <link rel="shortcut icon" href="/favicon-32.png?v=2" size="32x32" />
  <link rel="shortcut icon" href="/favicon-64.png?v=2" size="64x64" />
  <link rel="shortcut icon" href="/favicon-120.png?v=2" size="120x120" />
  <link rel="apple-touch-icon" href="/touch-icon-iphone.png?v=2" />
  <link rel="apple-touch-icon" sizes="76x76" href="/touch-icon-ipad.png?v=2" />
  <link rel="apple-touch-icon" sizes="120x120" href="/touch-icon-iphone-retina.png?v=2" />
  <link rel="apple-touch-icon" sizes="152x152" href="/touch-icon-ipad-retina.png?v=2" />
</head>
