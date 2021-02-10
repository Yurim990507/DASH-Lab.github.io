---
layout: page
title: Dataset
permalink: /Dataset/
---

<p> SKKU AGC Anomaly Detection Dataset Page</p>

<h1 class="page-title">SKKU AGC Anomaly Detection Dataset</h1>
  <p>SKKU AGC Anomaly Detection Dataset was acquired with a stationary camera mounted at an elevation, overlooking pedestrians, both day and night from various locations. Abnormal event is when a person's head touches the ground. The data was split into detection data and classification data.<p><br>
  
<h6><b>1. Anomaly Detection Data</b></h6>
  <p>Organized into subfolders of day, day_anno, night, and night_anno. The day and night floders are composed of images. The day_anno and night_anno are composed of xml files for adnormal data.</p>
  <p>day: 3000<br>night: 2000</p><br>

<h6><b>2. Classification Data</b></h6>
  <p>Organized into normal_day, normal_night, falldown_night, and falldown_day. Each folder contains images cropped only by humans.</p>
  <p>normal_day: 3200<br>normal_night: 1300<br>falldown_day: 3700<br>falldown_night: 900</p>
  <br>
<p><b>Dataset Link</b></p>
  <a href="https://drive.google.com/drive/folders/1JfEMxKb70GSEEUKMBqr62UFOsMbpPK8s?usp=sharing">SKKU AGC Anomaly Detection Dataset</a><br><br>
<hr>
<p><b>Examples of Anomaly Detection data</b></p>
<table>
  <tr>
    <td width="50%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection.jpg"></p>
    </td>
    <td width="50%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection1.jpg"></p>
    </td>
  </tr>
</table>

<p><b>Examples of Classification data</b></p>
<table>
  <tr>
    <td width="50%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_detection.jpg"></p>
    </td>
    <td width="50%" valign=top>
      <p align=center><img border=0 width=240 height=135 src="/img/AGC_classification.jpg"></p>
    </td>
  </tr>
</table>
