---
layout: post
title: My JavaScript CMF
categories:
- Projects
tags:
- CMF
- JavaScript
- Node
published: true
comments: true
---

I've<a href="https://github.com/TaylorHuston/JSCMF" target="_blank"> started a repo</a> for a JavaScript based CMS system I plan on making. Well, I'm not even sure if CMS is the proper term. Right now I don't think it will be a Content Management System so much as a Content Management Framework built on top of Node. Less of a way to manage content, and more of a way for Web Designers to create sites quickly and efficiently.<br />
Here's what I envision:

Three directories:<br />
Skeletons<br />
Themes<br />
Content

In the Skeletons directory you will place one or more HTML skeletons that control the, well, HTML skeleton of the website. The only requirements will be that it has to have a navigation are with the id of mainNav and a div with the id of mainContent.

In the Themes directory you will place the CSS files that control all of the styling of the website.

In the Content directory will be HTML (maybe markdown?) files for each page.

Essentially, the application will read the Content directory and generate a page for each file. It will start with the chosen skeleton HTML file, link the chose CSS file from the Themes directory, generate the mainNav based on the contents of the Content directory, and then fill in the mainContent div with the appropriate file from the Content directory.

So it's not really a CMS in the traditional sense. No web interface. No database. A designer still has to hand code the HTML skeleton, the CSS layout, and each of the page contents. The app will then generate pure HTML files for the designer to use. Just an easier way to work on a hand coded site that has a large amount of pages.

Since I really have no idea what I am doing yet, and mostly making it up as I go at the moment, I wouldn't be surprised if most (if not all) of this changes by the time it's 'complete', but in any case it should be a really fun learning project!

EDIT: Turns out this is really similar (I think) to what <a href="http://jekyllrb.com/" target="_blank">Jekyll </a>does, although Jekyll is ruby based. Oh well.
