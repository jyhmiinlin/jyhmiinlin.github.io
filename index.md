---
layout: page
title: Jyh-Miin Lin 
tagline: <i>Fast Iterative Reconstruction for PROPELLER</i> 
---

Many novel analyses for MR signals ignore the very basics. One among the many fundamental ideas of MRI is the k-space. 

Jyh-Miin employs k-space (the spatial frequency, see <a href="http://en.wikipedia.org/wiki/K-space_(MRI)">k-space</a>) density to speed up the iterative PROPELLER by 5x acceleration on CPU and 10x on GPU. This method reduces the time spent on gridding which is known as the bottleneck for iterative NUFFT. The reconstruction system can reconstruction high-resolution PROPELLER in one (for normal 2D 256x256 images) or several minutes (depending on the problem size).

Jyh-Miin is currently a PhD candidate at <a href="http://www.medschl.cam.ac.uk/radiology/" >University of Cambridge, Department of Radiology</a>


# Journal Articles

Quantification of Non-Water-Suppressed MR Spectra with Correction for Motion-Induced Signal Reduction. Lin JM, Chuang TC, Chung HW, Tsai SY.
Magn Reson Med. 2009 Dec;62(6):1394-403<a href="http://www.ncbi.nlm.nih.gov/pubmed/19780180"> doi: 10.1002/mrm.22119 </a>

Quantitative Comparison of Post-Processing Methods for Reduction of Frequency Modulation Sidebands in Non-water Suppression (1) H MRS. Lin JM, Chuang TC, Chung HW, Tsai SY. NMR Biomed. Article first published online: 12 December 2012; Volume 26, Issue 4, pages 400–409, April 2013 
<a href="http://www.ncbi.nlm.nih.gov/pubmed/23233288">doi: 10.1002/nbm.2877 </a>

# Conference Abstracts

Jyh-Miin Lin, Andrew Patterson, Chengcheng Zhu, Jonathan Gillard, Martin Graves (2014) Carotid Imaging with PROPELLER and Fast Iterative NUFFT on GPU, ISMRM-BC (Oral Presentation), Edinburgh
Jyh-Miin Lin, Andrew Patterson, Jonathan Gillard, Martin Graves. (2014) Evaluation for High Resolution Under-Sampled PROPELLER with PICO reconstruction, ISMRM-BC, Edinburgh
J-M Lin, T-C Chuang, W-C Wu, H-W Chung.(2012) Elimination of Frequency-modulated Sideband Artifacts for in vivo Non-Water Suppressed MRS
J-M Lin, T-C Chuang, H-C Chang, W-C Wu, H-W Chung, S-Y Tsai. (2012) Non-expensive Iterative Reconstruction for Under-sampled PROPELLER MRI
J-M Lin, and S-Y Tsai (2009). Separation of EMCL and IMCL in musculoskeletal 1H MR spectra by Filter-Diagonalization method.17 th ISMRM annual meeting, (May 2009), Hawaii.
J-M Lin, S-Y Tsai, H-S Liu, H-W Chung, C-M Cheng, T-C Yeh, R. Mulkern, and N-K Chen (2008). An Automatic Time-Domain Algorithm for the Quantification of In Vivo Non-water-suppressed MR Spectroscopy: the FDM, 16 th ISMRM annual meeting (May,2008), Toronto, Canada.
J-M Lin, S-Y Tsai, C-M Cheng, T-C Yeh, H-S Liu, RV Mulkern, H-W Chung, N-K Chen. (2007). High-Quality Non-Water Suppressed MR Spectra with Correction for Motion Induced Signal Reduction, 15 th ISMRM annual meeting, (May 2007), Berlin, Germany.

# Lecture

An Introduction to PROPELLER, Nov, 2013, Cambridge
How to Use Less Data with Compressed Sensing Technology?, Taiwan Scientific Symposium, 2013, Oxford

# Software



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


