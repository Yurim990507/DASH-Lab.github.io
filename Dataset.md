---
layout: page
title: Dataset
permalink: /Dataset/
---

<!--<p><a href="https://dash-lab.github.io/Dataset_kor.html">Kor</a></p>-->
<p><a href="https://dash-lab.github.io/Dataset_kor/">Kor</a></p>


<h1 class="page-title">FakeAVCeleb Dataset</h1>
  <p>In FakeAVCeleb, we propose a novel Audio-Video Deepfake dataset (FakeAVCeleb) that contains not only deepfake videos but also respective synthesized lip-synced fake audios. Our FakeAVCeleb is generated using recent most popular deepfake generation methods. To generate a more realistic dataset, we selected real YouTube videos of celebrities having four racial backgrounds (Caucasian, Black, East Asian, and South Asian) to counter the racial bias issue. <p><br>
  
 <p align=center><img border=0  src="/img/teaser.png"></p> 
 <p> Dataset download: https://sites.google.com/view/fakeavcelebdash-lab/home?authuser=0</p>
 <p>GitHub: https://github.com/hasamkhalid/FakeAVCeleb</p>

<h1 class="page-title">VFP290K dataset</h1>
  <p>Vision-based Fallen Person (VFP290K) dataset consists of 294,714 frames of fallen persons extracted from 178 videos from 49 backgrounds, composing 131 scenes. We empirically demonstrate the effectiveness of the features through extensive experiments comparing the performance shift based on object detection models. In addition, we evaluate our VFP290K dataset with properly divided datasets by measuring the performance of fallen person detecting systems.

We ranked first in the first round of the anomalous behavior recognition track of AI Grand Challenge 2020, South Korea, using our VFP290K dataset, which can further extend to other applications, such as intelligent CCTV or monitoring systems, as well. <p><br>
  
 <p align=center><img border=0  src="img/VFP.JPG"></p> 
 <p> Dataset download:https://sites.google.com/view/dash-vfp300k/home?authuser=0</p>
 <p>GitHub: https://github.com/DASH-Lab/VFP290K</p>



 
<h1 class="page-title">SKKU AGC Anomaly Detection Dataset</h1>
  <p>SKKU AGC Anomaly Detection Dataset was acquired with a stationary camera mounted at an elevation, overlooking pedestrians, both day and night from various locations. Abnormal event is when a person's head touches the ground. The data was split into detection data and classification data.<p><br>
 
<h6><b>1. Detection Data</b></h6>
  <p>It consits of images and anomaly labels. Images(1920x1080) are in day and night folders. Labels(.xml files) are in day_anno and night_anno folders.</p>
  <p>day: 3000<br>night: 2000</p><br>

<h6><b>2. Classification Data</b></h6>
  <p>Images cropped only by humans. There are two classes, normal and falldown. Images are in normal_day, normal_night, falldown_night, and falldown_day folders.</p>
  <p>normal_day: 3200<br>normal_night: 1300<br>falldown_day: 3700<br>falldown_night: 900</p>
  <br>
<p><b>Dataset Link</b></p>
  <a href="https://drive.google.com/drive/folders/1JfEMxKb70GSEEUKMBqr62UFOsMbpPK8s?usp=sharing">SKKU AGC Anomaly Detection Dataset</a><br><br>
<hr>
<p><b>Examples of Detection data</b></p>
<table>
  <tr>
    <td width="33%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection3.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection4.jpg"></p>
    </td>
  </tr>
  <tr>
    <td width="33%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection1.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection2.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection5.jpg"></p>
    </td>
  </tr>
</table>
<br>
<hr>
<p><b>Examples of Classification data</b></p>
<table>
  <tr>
    <td width="33%" valign=top>
      <p align=center><img border=0  src="/img/AGC_classification.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0  src="/img/AGC_classification1.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0  src="/img/AGC_classification2.jpg"></p>
    </td>
  </tr>
  <tr>
    <td width="33%" valign=top>
      <p align=center><img border=0  src="/img/AGC_classification3.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0  src="/img/AGC_classification4.jpg"></p>
    </td>
    <td width="33%" valign=top>
      <p align=center><img border=0  src="/img/AGC_classification5.jpg"></p>
    </td>
  </tr>
</table>
