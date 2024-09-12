---
permalink: /
title: ""
excerpt: "About the paper"
author_profile: false
redirect_from:
    /about/
    /about.html
layout: single
---

<style>
  .masthead {
    display: none !important;
  }
  .page__hero--overlay {
    margin-top: 0 !important;
  }
</style>

<h1 style="text-align: center; font-size: 36px; font-family: 'system-ui';">Multi-View Stereo with Geometric Encoding for Dense Scene Reconstruction</h1>
<h2  style="text-align: center; font-size: 18px; font-family: 'Sama Devanagari';">
    Submitted to 2024 IEEE International Conference on Robotics and Automation
</h2>
<div style=" text-align: center; font-size: 17px;">
Guidong Yang, Rui Cao, Junjie Wen, Benyun Zhao, Qingxiang Li, Yijun Huang, <br> Xi Chen, Alan Lam, Yun-Hui Liu, <i>Fellow, IEEE</i>, and Ben M. Chen<sup>*</sup>, <i>Fellow, IEEE</i>
</div>
<div  style="text-align: center; font-size: 17px;" >
The Chinese University of Hong Kong, Hong Kong SAR, China

</div>
<div style="display: flex; flex-direction: row; margin: 10px auto; justify-content: center"> 

<button style="background-color: #000000; color: white;margin-right: 15px; padding: 10px 15px;border: none; border-radius: 5px;">
<a href="files/Multi-View Stereo with Geometric Encoding for Dense Scene Reconstruction.pdf" style="color: white; text-decoration: none;">Paper</a>
</button>

<button style="background-color: #000000; color: white;margin-right: 15px; padding: 10px 15px; border: none; border-radius: 5px;">
<a href="https://github.com/CUHK-USR-Group/GE_MVS" style="color: white; text-decoration: none;">Code</a>
</button>

<button style="background-color: #000000; color: white;margin-right: 15px; padding: 10px 15px; border: none; border-radius: 5px;">
<a href="files/Appendix_Multi-View Stereo with Geometric Encoding for Dense Scene Reconstruction.pdf" style="color: white; text-decoration: none;">Appendix</a>
</button>

</div>

<div style="text-align: center; font-family: 'American Typewriter'; font-weight: 400; "> 
<h2>Abstract</h2>
</div>
<div style="text-align: justify; text-justify:inter-ideograph;">

Multi-view stereo (MVS) implicitly encodes photometric and geometric cues into the cost volume for multi-view correspondence matching, transferring insufficient geometric cues essential to depth estimation and reconstruction. This paper proposes GE-MVS, a novel multi-view stereo network with geometric encoding for more accurate and complete depth estimation and point cloud reconstruction. First, the cross-view adaptive cost volume aggregation module is proposed to strengthen multi-view geometric cues encoding during cost volume construction. Then, the depth consistency optimization is performed in the 3D point space during learning by invoking ground-truth depth cues from adjacent views. Finally, the surface normal geometries are explicitly encoded to refine the sampled depth hypotheses to be consistent in the local neighbor regions. Extensive experiments on the standard MVS benchmarks including DTU, Tanks and Temples, and BlendedMVS demonstrate the state-of-the-art depth estimation and point cloud reconstruction performance of GE-MVS. The GE-MVS is further deployed in real-world experiments for UAV-based large-scale reconstruction, where our method outperforms the prevalent industrial reconstruction solutions concerning reconstruction efficiency and efficacy.

</div>

<div style="text-align: center; font-family: 'American Typewriter'; font-weight: 400; "> 
<h2>Demo Video</h2>
</div>

<div style="text-align: center; margin: 0 auto;">
    <iframe width="100%" height="500" src="https://www.youtube.com/embed/mNHuVhbylU4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

<div style="text-align: center; font-family: 'American Typewriter'; font-weight: 400; "> 
<h2>Acknowledgements</h2>
</div>

<div style="text-align: justify">This work was supported by the InnoHK of the Government of the Hong Kong Special Administrative Region via the Hong Kong Centre for Logistics Robotics.
<br> <br>
We sincerely thank all the ICRA reviewers for their time and efforts.
</div>
