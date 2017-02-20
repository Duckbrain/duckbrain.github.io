---
layout: post
title:  "\"Search this Site\" from any site with a Bookmarklet or Chrome Omnibox"
date:   2014-04-03 20:15:01 -0800
categories: chrome
---
If you don't already have Google Chrome, I recommend it. Otherwise this can be adapted for FireFox, Internet Explorer, Safari, or any other web browser.

For Google Chrome just copy and paste the code in the URL field for a new Search engine.
Just click the Wrench icon>Options>Manage>Add
```
javascript:Qr="%s";if(Qr)location.href='http://www.google.com/search?&q=site:'+encodeURIComponent(window.location.hostname)+'+'+escape(Qr)
```

![](https://lh3.googleusercontent.com/proxy/AaqTswvVHBvKmgsn_tlUEXx6pUrcZAx98rZOgmt6vRu1ZNauy20a1JWltXYWctd5kLRq_yh5AcArKmtBdC-aoxBCnEyW513vTUZh5NURZ0HNXgo=s0-d)

To use this just type the keyword you chose followed by what you want to search for.

If you want a bookmark that you can use in any browser, including Chrome, just make a new bookmark with the URL set to this.

```
javascript:Qr=prompt("Search this Site");if(Qr)location.href='http://www.google.com/search?&q=site:'+encodeURIComponent(window.location.hostname)+'+'+escape(Qr)
```

To use this one just click on your favorite, bookmark, or link and type what you want to search in the box.