---
layout: post
title: Open *.xbap Files in Google Chrome
date: '2010-09-05T11:38:00.000-07:00'
author: Jonathan Duck
tags:
- tricks
- wpf
- google chrome
modified_time: '2015-02-16T16:06:28.889-08:00'
blogger_id: tag:blogger.com,1999:blog-3837863739089365212.post-6875391323502641790
blogger_orig_url: http://duck-producktions.blogspot.com/2014/04/open-xbap-files-in-google-chrome.html
---

> **OUTDATED**: This will no longer work because Chrome only allows using the Pepper Plugin API for plugins. On a side note, I was very new to programming when I wrote this, (it says published 2014, but I copied it from a site I don't use written in 2010). I would now dissuade anyone from using the .NET framework, especially the WPF,  for most projects due to vendor lock-in. The appropriate post date has been updated.

> **UPDATE 2**: The link is broken too.

You may have happened across a web program that can only be opened in Windows in Internet Explorer or Firefox. The program may have had the extension .xbap this is the extension for what is called a WPF (Windows Presentation Foundation) program. If this is the case then you may want to open this in Google Chrome. I did so I came up with a solution.

1. If you want the quick solution then unzip these files into your Google Chrome directory using the following steps. Sorry but this still only will work on Windows, no fixes for Mac or Linux yet.
2. Download the "[Xbap for Chrome.zip](https://sites.google.com/site/duckproducktionssoftware/computer-tips/openxbapfilesingooglechrome/XbapforChrome.zip?attredirects=0)" file and open it.
3. Select everything in the file and copy (Ctrl+C) them.
4. Find a shortcut to Chrome (you should have one if you use it) and right-click on it and choose properties
5. Click on the button "Find Target" or "Open File Location" to open  the Google Chrome Application folder.
6. Paste the files into this folder (Ctrl+V)
7. You should be able to open an `*.xbap` file and see the application.