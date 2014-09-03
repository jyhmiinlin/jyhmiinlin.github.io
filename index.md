---
layout: page
title: Jyh-Miin Lin 
tagline: <i>Fast Iterative Reconstruction for PROPELLER</i> 
---

Jyh-Miin employes many matrix methods to reconstruct MR signals and non-Cartesian MRI. The ultimate goal of my study is to improve the accuracy and reduce the influences of noises. 

Jyh-Miin is currently a PhD candidate at <a href="http://www.medschl.cam.ac.uk/radiology/" >University of Cambridge, Department of Radiology</a>

# Software

1.<a href="https://github.com/jyhmiinlin/pynufft">pynufft</a> is a python version of NUFFT. The GPU version has only been tested for iterative PROPELLER reconstruction. The software requires numpy, scipy, reikna <a href="https://pypi.python.org/pypi/reikna"> to use GPU acceleration. 

# Journal Articles

1.Quantification of Non-Water-Suppressed MR Spectra with Correction for Motion-Induced Signal Reduction. Lin JM, Chuang TC, Chung HW, Tsai SY.
Magn Reson Med. 2009 Dec;62(6):1394-403<a href="http://www.ncbi.nlm.nih.gov/pubmed/19780180"> doi: 10.1002/mrm.22119 </a>

2.Quantitative Comparison of Post-Processing Methods for Reduction of Frequency Modulation Sidebands in Non-water Suppression (1) H MRS. Lin JM, Chuang TC, Chung HW, Tsai SY. NMR Biomed. Article first published online: 12 December 2012; Volume 26, Issue 4, pages 400–409, April 2013 
<a href="http://www.ncbi.nlm.nih.gov/pubmed/23233288">doi: 10.1002/nbm.2877 </a>

# Conference Abstracts

1.Jyh-Miin Lin, Andrew Patterson, Chengcheng Zhu, Jonathan Gillard, Martin Graves (2014) Carotid Imaging with PROPELLER and Fast Iterative NUFFT on GPU, ISMRM-BC (Oral Presentation), Edinburgh

2.Jyh-Miin Lin, Andrew Patterson, Jonathan Gillard, Martin Graves. (2014) Evaluation for High Resolution Under-Sampled PROPELLER with PICO reconstruction, ISMRM-BC, Edinburgh

3.J-M Lin, T-C Chuang, W-C Wu, H-W Chung.(2012) Elimination of Frequency-modulated Sideband Artifacts for in vivo Non-Water Suppressed MRS

4.J-M Lin, T-C Chuang, H-C Chang, W-C Wu, H-W Chung, S-Y Tsai. (2012) Non-expensive Iterative Reconstruction for Under-sampled PROPELLER MRI

5.J-M Lin, and S-Y Tsai (2009). Separation of EMCL and IMCL in musculoskeletal 1H MR spectra by Filter-Diagonalization method.17 th ISMRM annual meeting, (May 2009), Hawaii.

6.J-M Lin, S-Y Tsai, H-S Liu, H-W Chung, C-M Cheng, T-C Yeh, R. Mulkern, and N-K Chen (2008). An Automatic Time-Domain Algorithm for the Quantification of In Vivo Non-water-suppressed MR Spectroscopy: the FDM, 16 th ISMRM annual meeting (May,2008), Toronto, Canada.

7.J-M Lin, S-Y Tsai, C-M Cheng, T-C Yeh, H-S Liu, RV Mulkern, H-W Chung, N-K Chen. (2007). High-Quality Non-Water Suppressed MR Spectra with Correction for Motion Induced Signal Reduction, 15 th ISMRM annual meeting, (May 2007), Berlin, Germany.

# Talk

1.An Introduction to PROPELLER, Nov, 2013, Cambridge

2.How to Use Less Data with Compressed Sensing Technology?, Taiwan Scientific Symposium, 2013, Oxford

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


