---
layout: page
title: Jyh-Miin Lin 
---

Jyh-Miin is currently a PhD candidate at <a href="http://www.medschl.cam.ac.uk/radiology/" >University of Cambridge, Department of Radiology</a>

# Software

1.<a href="https://github.com/jyhmiinlin/pynufft">pynufft</a> is a python version of NUFFT, using the split-Bregman method and coil combination. The GPU version has only been tested for iterative PROPELLER reconstruction. The software requires numpy, scipy, reikna <a href="https://pypi.python.org/pypi/reikna"> to use GPU acceleration. 

2.<a href="https://github.com/jyhmiinlin/rfov">rfov</a> an accelerated version of pynufft, using rFOV

# Journal Articles

1.J-M Lin, A.J. Patterson, H-C Chang, J.H. Gillard, M.J. Graves, An Iterative Reduced Field-of-View Reconstruction for PROPELLER MRI, Medical Physics, 42(10), 2015 (In Press)

2.J-M Lin, T-C Chuang, H-W Chung, S-Y Tsai, Quantitative Comparison of Post-Processing Methods for Reduction of Frequency Modulation Sidebands in Non-water Suppression (1) H MRS. Lin JM, Chuang TC, Chung HW, Tsai SY. NMR Biomed. Article first published online: 12 December 2012; Volume 26, Issue 4, pages 400–409, April 2013 
<a href="http://www.ncbi.nlm.nih.gov/pubmed/23233288">doi: 10.1002/nbm.2877 </a>

3.J-M Lin, S-Y Tsai, H-S Liu, H-W Chung, RV Mulkern, C-M Cheng, T-C Yeh and N-K Chen, Quantification of Non-Water-Suppressed MR Spectra with Correction for Motion-Induced Signal Reduction. Lin JM, Chuang TC, Chung HW, Tsai SY.
Magn Reson Med. 2009 Dec;62(6):1394-403<a href="http://www.ncbi.nlm.nih.gov/pubmed/19780180"> doi: 10.1002/mrm.22119 </a>


# Conference Abstracts

1.J-M Lin, C Zhu, H-W Chung, M.J. Graves, A.J. Patterson. Optimized free-breathing inner-volume black-blood (FB-IV-BB) cine FSE of the descending aorta. In Proceedings of the 23rd Annual Meeting of ISMRM. Toronto, Canada (2015)

2.J-M Lin, A.J. Patterson, H-C Chang, T-C Chuang, H-W Chung, J.H. Gillard, M.J. Graves. Whitening of colored noise in PROPELLER using iterative regularized PICO reconstruction. In Proceedings of the 23rd Annual Meeting of ISMRM. Toronto, Canada (2015)

3.J-M Lin, A.J. Patterson, J.H. Gillard, M.J. Graves. Evaluation for High Resolution Under-Sampled PROPELLER with PICO reconstruction. ISMRM British Chapter, Edinburgh (2014)

4.J-M Lin, T-C Chuang, W-C Wu, H-W Chung. Elimination of Frequency-modulated Sideband Artifacts for in vivo Non-Water Suppressed MRS. In Proceedings of the 20th Annual Meeting of ISMRM. Melbourne, Australia (2012)

5.J-M Lin, T-C Chuang, H-C Chang, W-C Wu, H-W Chung, S-Y Tsai. Non-expensive Iterative Reconstruction for Under-sampled PROPELLER MRI. In Proceedings of the 20th Annual Meeting of ISMRM. Melbourne, Australia (2012)

6.J-M Lin, and S-Y Tsai. Separation of EMCL and IMCL in musculoskeletal 1H MR spectra by Filter-Diagonalization method. In Proceedings of the 17th Annual Meeting of ISMRM. Hawaii (2009)

7.J-M Lin, S-Y Tsai, H-S Liu, H-W Chung, C-M Cheng, T-C Yeh, R. Mulkern, and N-K Chen. An Automatic Time-Domain Algorithm for the Quantification of In Vivo Non-water-suppressed MR Spectroscopy: the FDM, In Proceedings of the 16th Annual Meeting of ISMRM. Toronto, Canada (2008)

8.J-M Lin, S-Y Tsai, C-M Cheng, T-C Yeh, H-S Liu, RV Mulkern, H-W Chung, N-K Chen. High-Quality Non-Water Suppressed MR Spectra with Correction for Motion Induced Signal Reduction, In Proceedings of the 15th Annual Meeting of ISMRM, Berlin, Germany (2007)


# Oral Presentation

1.Carotid Imaging with PROPELLER and Fast Iterative NUFFT on GPU, ISMRM British Chapter, Edinburgh (2014)

2.An Introduction to PROPELLER, Nov, 2013, Cambridge

3.How to Use Less Data with Compressed Sensing Technology? Taiwan Scientific Symposium, 2013, Oxford


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


