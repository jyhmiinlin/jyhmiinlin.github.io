---
layout: page
title: Jyh-Miin Lin 
tagline: <i>Fast Iterative Reconstruction for PROPELLER</i>
---

Jyh-Miin developed a novel iterative reconstruction for PROPELLER. The method employs k-space (the spatial frequency, see <a href="http://en.wikipedia.org/wiki/K-space_(MRI)">k-space</a>) density and accelerates the gridding process with 10x faster speed.

Jyh-Miin is currently a PhD candidate at <a href="http://www.medschl.cam.ac.uk/radiology/" >University of Cambridge, Department of Radiology</a>


# Journal Articles

1. Quantification of Non-Water-Suppressed MR Spectra with Correction for Motion-Induced Signal Reduction. Lin JM, Chuang TC, Chung HW, Tsai SY.
Magn Reson Med. 2009 Dec;62(6):1394-403<a href="http://www.ncbi.nlm.nih.gov/pubmed/19780180"> doi: 10.1002/mrm.22119 </a>

2. Quantitative Comparison of Post-Processing Methods for Reduction of Frequency Modulation Sidebands in Non-water Suppression (1) H MRS. Lin JM, Chuang TC, Chung HW, Tsai SY. NMR Biomed. Article first published online: 12 December 2012; Volume 26, Issue 4, pages 400–409, April 2013 
<a href="http://www.ncbi.nlm.nih.gov/pubmed/23233288">doi: 10.1002/nbm.2877 </a>



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


