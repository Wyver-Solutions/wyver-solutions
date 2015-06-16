---
title: Creating rich, portable learning experiences without SCORM
author: Wyver Solutions Admin
excerpt: We discuss H5P, a new alternative to SCORM packaged HTML5 content which allows content to be created, edited and displayed in any H5P-enabled content management system, and then embedded just like a Youtube video.
layout: post
permalink: /2015/04/24/creating-rich-portable-learning-experiences-without-scorm/
categories:
  - Analysis and design
  - Content development
  - Five minute briefing
  - xAPI
---
<div id="attachment_1372" style="width: 160px" class="wp-caption alignright">
  <a href="http://www.wyversolutions.co.uk/cms/wp-content/uploads/2015/04/Screen-Shot-2015-04-24-at-14.00.13.png"><img class="wp-image-1372" src="http://www.wyversolutions.co.uk/cms/wp-content/uploads/2015/04/Screen-Shot-2015-04-24-at-14.00.13-300x276.png" alt="H5P modules" width="150" height="138" /></a>
  
  <p class="wp-caption-text">
    H5P modules
  </p>
</div>

<a href="http://www.adlnet.gov/capabilities/scorm.html" target="_blank">SCORM</a> has, for a long time, been the de facto method of packaging online content for use within learning management systems (LMS). It allows content to be produced separately from the LMS and then used in multiple LMS&#8217;s. It also allows the content to send and receive data to and from the LMS, enabling tracking of learner progress and attainment.

One of the problems with SCORM is its requirement for a learning management system, in particular the fact that these content packages are often very hard to find once they&#8217;re inside the LMS. Some people even consider the learning management system to be the greatest barrier to learning we have &#8211; especially given the generally accepted idea that informal, user-driven learning is where we should be focussing our energies.

Our position has long been that content is best managed and delivered from within a <a href="http://en.wikipedia.org/wiki/Content_management_system" target="_blank">Content Management System</a> (CMS). Learning Management Systems should be the place where formal programmes and assessment are managed, using content from the CMS as required.

To this mix, we also have the potential opened up by <a href="http://www.wyversolutions.co.uk/cms/2014/06/12/exploring-the-potential-of-the-xapi-aka-tin-can-api/" target="_blank">xAPI (Tin Can)</a> which allows any application, to which a learner has logged in, to send and receive data in a standard way to a Learning Record Store.

The problem has been creating, editing and displaying interactive learning materials within the CMS. But now, from Norway, we have the HTML5 Package (known as <a href="http://h5p.org/" target="_blank">H5P</a>). This provides a means of using any CMS, that understands H5P, to create, edit and display a whole range of interactive content types, including:

  * Drag &amp; drop
  * Image hotspots
  * Interactive video (as the video plays, interactions can be overlaid on top of it)
  * Multiple choice questions
  * Presentations (which can also include many of the other interactive elements)
  * Interactive timelines
  * Social media feeds

Responsiveness, the ability to resize based on the size of the screen, has been built in from the start.

Once the content has been created it can be embedded in other websites (just like a Youtube video) or even downloaded and copied into another H5P-ready CMS, where it can be edited further.

> To get really good rich content, the cost of producing such content must be reduced. And in order to do so, the content needs to become reusable. This is one of the main ideas behind H5P. H5P makes it easy for others to share their rich content with the rest of the world. It should be just as easy to translate and customize content that others have created.
> 
> <p style="text-align: right;">
>   <a href="http://h5p.org/getting-involved" target="_blank">H5P.org/getting-involved</a>
> </p>

<p style="text-align: left;">
  H5P content is <a href="http://h5p.org/documentation/x-api" target="_blank">xAPI-enabled</a>, in that all the interactions that a learner might undertake transmit xAPI-statements. Given a suitably-equipped CMS these xAPI statements can be picked up and transmitted to a connected Learning Record Store along with details of the user who is logged in to the system.
</p>

<p style="text-align: left;">
  All of the H5P modules can be placed anywhere on a page within the CMS, so you could have a page containing a timeline and some text on the page, and then a multiple-choice quiz &#8211; all built separately. Or you could combine things into a single H5P presentation.
</p>

<p style="text-align: left;">
  Creating and editing H5P content is all done within the CMS, using simple forms. As shown in these two screenshots:
</p>

<div id="attachment_1375" style="width: 310px" class="wp-caption aligncenter">
  <a href="http://www.wyversolutions.co.uk/cms/wp-content/uploads/2015/04/Screen-Shot-2015-04-24-at-14.21.29.png"><img class="size-medium wp-image-1375" src="http://www.wyversolutions.co.uk/cms/wp-content/uploads/2015/04/Screen-Shot-2015-04-24-at-14.21.29-300x177.png" alt="Question set example" width="300" height="177" /></a>
  
  <p class="wp-caption-text">
    Question set example
  </p>
</div>

<div id="attachment_1376" style="width: 310px" class="wp-caption aligncenter">
  <a href="http://www.wyversolutions.co.uk/cms/wp-content/uploads/2015/04/Screen-Shot-2015-04-24-at-14.24.54.png"><img class="size-medium wp-image-1376" src="http://www.wyversolutions.co.uk/cms/wp-content/uploads/2015/04/Screen-Shot-2015-04-24-at-14.24.54-300x222.png" alt="Editing an H5P question set" width="300" height="222" /></a>
  
  <p class="wp-caption-text">
    Editing an H5P question set
  </p>
</div>

The interactive video displayed below was created using H5P directly within this website. Feel free to download it to use in your own CMS, or to embed it on any web page.

[h5p id=&#8221;6&#8243;]