---
layout: page
title: Getting Started
tagline: 
---
{% include JB/setup %}

## Objectives

For our worksops, we will be using a few applications to download, manipulate, visualize and store our data. 

Once completed with this secion, you'll have an installation of QGIS on your computer, a registered account at iPlant Collaborative to access the iPlant Data Store, and the iRods plugin for QGIS installed and configured for connecting to the iPlant Data Store.

## Topics

<ol class="posts">
  {% for post in site.posts %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ol>

----

## More Resources

<ul class="more-resources">
<li><a href="http://www.qgis.org/en/site/forusers/download.html" target="_blank">QGIS Download</a></li>
<li><a href="https://user.iplantcollaborative.org/register/" target="_blank">iPlant Collaborative registration</a></li>
<li><a href="https://github.com/BioComputing/irods-qgis/blob/master/README.md">About iRods-QGIS</a></li>
</ul>

