---
layout: page
title: Publications
permalink: /Publications/
---

<h1 class="page-title">Publications</h1>

<div style="margin-top:2vw;">
    <p style="font-family: times, serif; font-size:30pt; font-style:italic">
        <center>    
<!--              How: Change the number after the Conference Name to indicate # of paper accepted -->
            <sup>Since 2018:</sup>   
            <img alt="CIKM"     src="https://img.shields.io/badge/CIKM-9-brightgreen?style=social"      height="20">&nbsp;
            <img alt="WWW"      src="https://img.shields.io/badge/WWW-6-brightgreen?style=social"       height="20"  >&nbsp;            
            <img alt="NeurIPSDataset"  src="https://img.shields.io/badge/NeurIPSDataset-2-brightgreen?style=social"   height="20">&nbsp;
            <img alt="KDD"      src="https://img.shields.io/badge/KDD-2-brightgreen?style=social"       height="20">&nbsp;
            <img alt="AAAI"     src="https://img.shields.io/badge/AAAI-1-brightgreen?style=social"      height="20">&nbsp;            
            <img alt="ICML"     src="https://img.shields.io/badge/ICML-1-brightgreen?style=social"      height="20">&nbsp;
            <img alt="ACMMM"    src="https://img.shields.io/badge/ACMMM-1-brightgreen?style=social"     height="20">&nbsp;
            <img alt="CHI"      src="https://img.shields.io/badge/CHI-1-brightgreen?style=social"       height="20">&nbsp;
            <img alt="ACSAC"    src="https://img.shields.io/badge/ACSAC-1-brightgreen?style=social"     height="20">&nbsp;
            <img alt="RAID"     src="https://img.shields.io/badge/RAID-1-brightgreen?style=social"      height="20">&nbsp;
            <img alt="ECCV"     src="https://img.shields.io/badge/ECCV-1-brightgreen?style=social"      height="20">&nbsp;
            <img alt="SCIE"     src="https://img.shields.io/badge/SCIE-16-brightgreen?style=social"     height="20">
        </center>
    </p>
    <h4 style="margin-top:40px"><b>2022</b></h4>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Accelerating CNN via Dynamic Pattern‑based Pruning Network</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Gwanghan Lee, Saebyeol Shin, and <i><b> Simon Woo*</b> </i></small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>31st ACM International Conference on Information & Knowledge Management (CIKM), Georgia, USA, 2022</b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>BK Computer Science IF=3</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"><small>Most dynamic pruning methods fail to achieve actual acceleration due to the extra overheads caused by indexing and weight-copying to implement the dynamic sparse patterns for every input sample. To address this issue, we propose Dynamic Pattern-based Pruning Network, which preserves the advantages of both static and dynamic networks. Unlike previous dynamic pruning methods, our novel method dynamically fuses static kernel patterns, enhancing the kernel's representational power without additional overhead. Moreover, our dynamic sparse pattern enables an efficient process using BLAS libraries, accomplishing actual acceleration. We demonstrate the effectiveness of the proposed network on CIFAR and ImageNet, outperforming the state-of-the-art methods achieving better accuracy with lower computational cost.</small> </p>
                    </tr>                             
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="cikm22_gwanhan.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Samba: Identifying Inappropriate Videos for Young Children on YouTube</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Binh M. Le, Rajat Tandon, Chingis Oinar, Jeffrey Liu, Uma Durairaj, Jiani Guo, Spencer Zahabizadeh,<br>  Sanjana Ilango, Jeremy Tang, Fred Morstatter, <i><b> Simon Woo*</b></i>, and Jelena Mirkovic*</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>31st ACM International Conference on Information & Knowledge Management (CIKM), Georgia, USA, 2022</b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>BK Computer Science IF=3</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"><small>In this paper, we propose a fusion model, called Samba, which uses both metadata and video subtitles for content classifying YouTube videos for kids. Previous studies utilized metadata, such as video thumbnails, title, comments, ect., for detecting inappropriate videos for young viewers.  Such metadata-based approaches achieve high accuracy but still have significant misclassifications due to the reliability of input features. By adding representation features from subtitles, which are pretrained with a self-supervised contrastive framework, our Samba model can outperform other state-of-the-art classifiers by at least 7%. We also publish a large-scale, comprehensive dataset of 70K videos for future studies.</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small>  <a
                                    href="https://github.com/leminhbinh0209/samba"> <img  alt="github" src="github.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;">  </a> </small> </p>
                    </tr>
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="cikm22_binh.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Towards an Awareness of Time Series Anomaly Detection Models' Adversarial Vulnerability</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Shahroz Tariq, Binh M. Le , and <i><b> Simon Woo*</b> </i></small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>31st ACM International Conference on Information & Knowledge Management (CIKM), Georgia, USA, 2022</b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>BK Computer Science IF=3</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"><small>Time series anomaly detection is studied in statistics, ecology, and computer science. Numerous time series anomaly detection strategies have been presented utilizing deep learning. Many of these methods exhibit state-of-the-art performance on benchmark datasets, giving the false impression that they are robust and deployable in a wide variety of real-world scenarios. In this study, we demonstrate that adding modest adversarial perturbations to sensor data severely weakens anomaly detection systems.   Under well-known adversarial attacks such as Fast Gradient Sign Method (FGSM) and Projected Gradient Descent (PGD), we demonstrate that the performance of state-of-the-art deep neural networks (DNNs) and graph neural networks (GNNs), which claim to be robust against anomalies and possibly be used in real-world systems, drops to 0%. We demonstrate for the first time, to our knowledge, the vulnerability of anomaly detection systems to adversarial attacks. This study aims to increase awareness of the adversarial vulnerabilities of time series anomaly detectors.</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small>  <a
                                    href="https://github.com/shahroztariq/Adv_Timeseries"> <img  alt="github" src="github.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;">  </a> </small> </p>
                    </tr>
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="cikm22_shah.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Sliding Cross Entropy for Self-Knowledge Distillation</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Hanbeen Lee, Jeongho Kim, and <i><b> Simon Woo*</b> </i></small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>31st ACM International Conference on Information & Knowledge Management (CIKM), Georgia, USA, 2022</b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>BK Computer Science IF=3</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"><small>Knowledge distillation (KD) is a powerful technique for improving the performance of a small model by leveraging the knowledge of a larger model. Despite its remarkable performance boost, KD has a drawback with the substantial computational cost of pre-training larger models in advance. Recently, a method called self-knowledge distillation has emerged to improve the model's performance without any supervision. In this paper, we present a novel plug-in approach called Sliding Cross Entropy (SCE) method, which can be combined with existing self-knowledge distillation to significantly improve the performance. Specifically, to minimize the difference between the output of the model and the soft target obtained by self-distillation, we split each softmax representation by a certain window size, and reduce the distance between sliced parts. Through this approach, the model evenly considers all the inter-class relationships of a soft target during optimization. The extensive experiments show that our approach is effective in various tasks, including classification, object detection, and semantic segmentation. We also demonstrate SCE consistently outperforms existing baseline methods.</small> </p>
                    </tr>                             
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="cikm22_hanbeen.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Selective Tensorized Multi-layer LSTM for Orbit Prediction</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Youjin Shin, Eun-Ju Park, and <i><b> Simon Woo*</b></i>, Okchul Jung and Daewon Chung</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>31st ACM International Conference on Information & Knowledge Management (CIKM), Georgia, USA, 2022</b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>BK Computer Science IF=3</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"><small>Although the collision of space objects not only incurs a high cost but also threatens human life, the risk of collision between satellites has increased, as the number of satellites has rapidly grown due to the significant interests in many space applications. However, it is not trivial to monitor the behavior of the satellite in real-time since the communication between the ground station and spacecraft are dynamic and sparse, and there is an increased latency due to the long distance. Accordingly, it is strongly required to predict the orbit of a satellite to prevent unexpected contingencies such as a collision. Therefore, the real-time monitoring and accurate orbit prediction is required. Furthermore, it is necessarily to compress the prediction model, while achieving a high prediction performance in order to be deployable in the real systems. Although several machine learning and deep learning-based prediction approaches have been studied to address such issues, most of them have applied only basic machine learning models for orbit prediction without considering the size, running time, and complexity of the prediction model. In this research, we propose Selective Tensorized multi-layer LSTM (ST-LSTM) for orbit prediction, which not only improves the orbit prediction performance but also compresses the size of the model that can be applied in practical deployable scenarios. To evaluate our model, we use the real orbit dataset collected from the Korea Multi-Purpose Satellites (KOMPSAT-3 and KOMPSAT-3A) of the Korea Aerospace Research Institute (KARI) for 5 years. In addition, we compare our ST-LSTM to other machine learning-based regression models, LSTM, and basic tensorized LSTM models with regard to the prediction performance, model compression rate, and running time.</small> </p>
                    </tr>                             
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="cikm22_youjin.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>GLAMD: Global and Local Attention Mask Distillation for Object Detectors</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Younho Jang<sup>&dagger;</sup>,  Wheemyung Shin<sup>&dagger;</sup>, Jinbeom Kim, <i><b> Simon Woo*</b> </i>, and Sung-Ho Bae*</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>European Conference on Computer Vision (ECCV), Tel Aviv, Oct., 2022</b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>BK Computer Science IF=2 (Acceptance Rate ~ 28%)</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"><small>Knowledge distillation (KD) is a well-known model compression strategy to improve models' performance with fewer parameters. However, recent KD approaches for object detection have faced two limitations. First, they distill nearby foreground regions, ignoring potentially useful background information. Second, they only consider global contexts, thereby the student model can hardly learn local details from the teacher model. To overcome such challenging issues, we propose a novel knowledge distillation method, GLAMD, distilling both global and local knowledge from the teacher. We divide the feature maps into several patches and apply an attention mechanism for both the entire feature area and each patch to extract the global context as well as local details simultaneously. Our method outperforms the state-of-the-art methods with 40.8 AP on COCO2017 dataset, which is 3.4 AP higher than the student model (ResNet50 based Faster R-CNN) and 0.7 AP higher than the previous global attention-based distillation method.</small> </p>
                    </tr>                             
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="jinpum_eccv22.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Design and Evaluation of Highly Accurate Smart Contract Code Vulnerability Detection Framework</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Sowon Jeon, Gilhee Lee, Hyoungshick Kim, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>Data Mining and Knowledge Discovery</b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>Accepted, SCIE IF = 3.67 </font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"><small> Smart contracts are self-executing programs stored and executed on a blockchain platform. However, previous studies demonstrated that developing secure smart contracts is not easy. Unfortunately, the use of insecure smart contracts results in a significant financial loss for service providers or customers. Therefore, identifying security vulnerabilities in smart contracts would be essential in blockchain platforms using smart contracts. In this paper, we present <i>SmartConDetect</i> as a tool for detecting security vulnerabilities in Solidity smart contracts. <i>SmartConDetect</i> is a static analysis tool that extracts code fragments from Solidity smart contracts and uses a pre-trained BERT model to find susceptible code patterns. To demonstrate the performance of <i>SmartConDetect</i>, we use two public datasets, and our dataset (SmartConDataset) collected from the real-world Ethereum blockchain network. Our experimental results show that <i>SmartConDetect</i> significantly outperforms all state-of-the-art methods, achieving 90.9\% F1-score when using our own dataset. Specifically, <i>SmartConDetect</i> is about 2 times faster than SmartCheck in detection. Furthermore, we conduct a real-world case study to analyze the distribution of detected vulnerabilities.</small> </p>
                    </tr>                             
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="sowon.JPG" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>다중 스케일 특성 생성 네트워크</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Gwanghan Lee, Saebyeol Shin, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>한국컴퓨터종합학술대회 (KCC), 2022</b> </small> </p>
                    </tr>
                    <tr>
              
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>조기 종료 네트워크(early-exit network)는 추론 시 동적으로 모델 복잡도를 낮춤으로써 신경망의 효율성을 높인다. 기존 연구들은 입력 샘플이나 모델 구조의 중복성(redundancy)을 줄이는 데 집중하였으나 고차원 특징 정보가 부족한 초기 분류기들이 전체 네트워크 성능에 치명적인 영향을 끼치는 문제를 해결하지 못했다. 본 연구는 중복성을 줄이는 것뿐만 아니라 합성곱 커널(convolution kernel) 중앙에서 가중치들을 공유하면서 효율적으로 다중 스케일(multi-scale) 특징을 생성하여 조기 종료 네트워크의 성능을 향상시킨다. 또한 이 논문의 게이팅 네트워크(gating network)는 네트워크의 서로 다른 위치에 있는 각 합성곱 레이어에 따라 최적의 다중 스케일 특징 비율을 결정하도록 학습된다.</small> </p>
                    </tr>                             
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             
            </div>
         </div>
        <hr> 
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>이미지 전처리 방법을 통한 딥페이크 탐지 회피 연구</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Jeongho Kim, Jeonghyun Kim, Taejune Kim, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>한국컴퓨터종합학술대회 (KCC), 2022, <font color="blue">우수논문상 (Top 7%)</font></b> </small> </p>
                    </tr>
                    <tr>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>오늘날 국제사회에서 딥페이크(Deepfake) 기술에 대한 우려가 점점 커지고 있다. 딥페이크는 여러 종류의 이미지, 영상들의 얼굴을 짧은 시간 만에 바꿀 수 있는 기술로, 손쉽게 왜곡된 정보를 전파할 수 있기 때문이다. 이에따라딥페이크이미지,영상에대응하기위한탐지기술연구및시도가이뤄졌다. 그러나,탐지기술연구를 가능케 만들어 줄 수 있는 고품질의 데이터셋(dataset)을 생성하는 연구는 더디게 이뤄졌다. 본 논문에서는 딥페 이크 탐지 기술 발전에 필수 불가결한 요소인 고품질 데이터 생성에 대한 새로운 방법론을 제시하고 이를 통해 딥페이크 탐지 기술의 한계 및 발전 방향성에 대해 살펴보고자 한다. </small> </p>
                    </tr>                             
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            </div>
         </div>
    <hr>    
    
            <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Deep Learning Algorithm for Postmortem Face Reconstruction (딥러닝 기술을 활용한 사후 시신 얼굴 복원)
                            </b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Hajin Kim, Chingis Oinar, UiHyeon Shin, <b>Woo Simon S</b>, and Moon-Young Kim </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>제29회 대한기초의학 학술대회 (대한법의학회), 2022 <font color="blue">우수포스터상 </font></b> </small> </p>
                    </tr>
                    <tr>
              
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>As the number of lonely deaths increases due to the aging population and the increase in single-person households, the frequency of discovery of decomposed corpses in death cases is gradually increasing. In the wake of the strengthening of on-site guidelines by the National Police Agency and the adjustment of the prosecution and police investigation rights, the need for identification and autopsy at the scene is being emphasized. Although the existing forensic face restoration technology using face bones has accumulated a number of previous studies, there is a limitation in that the restoration results may vary due to many factors such as the thickness and nature of facial soft tissue, shape of eyes or nose, and distribution of body hair. Based on the fact that facial recognition technology using facial landmarks is becoming common all over the world, this study aims to help quickly and accurately identify the faces of corrupt bodies that expand due to postmortem-change.
In this study, living data such as ID cards and post-mortem data were collected for bodies identified with fingerprints, and compared pairs were formed, and face recognition technology used the MTCNN model, which is currently widely used in the field. The artificial intelligence model, which determines whether live data and post-data match, selected and analyzed Arcface, which is the same among a total of seven open-source models (VGG-Face, FaceNet, OpenFace, DeepFace, DeepID, ArcFace, Dlib).
The performance of the artificial intelligence model (Arcface) was evaluated by comparing the results of the judgment of the expert group, the general public group, and the entire human group. As a result of comparison using 107 pairs of original data, the same person judgment rate was found to be 51.4% in the expert group, 22.4% in the general population, and 29.0% in the total human group, and the artificial intelligence model was 47.7%. As a result of reviewing the original data, it was determined that changes in skin color due to decomposition could affect the performance of artificial intelligence models According to this judgment, when the original data were preprocessed in gray scale, the judgment rate of the same person as the artificial intelligence model was 50.5%, which showed an improvement in performance of about 3%. 
Through this study, it was found that only the currently developed artificial intelligence model showed facial recognition performance close to that of a group of experts. It is expected that face recognition performance can be further improved if various pretreatment technologies reflecting the characteristics of the postmortem change are developed and applied in the future. 
                            
                            <br>
                            
                            인구 고령화 및 1인 가구의 증가는 고독사의 증가로 이어져 변사사건에서 부패 시신이 발견되는 빈도가 점차 높아지고 있다. 경찰청의 현장 지침 강화 및 검경 수사권 조정 등을 계기로 현장에서는 신원 확인 및 부검의 필요성이 강조되고 있다. 얼굴뼈를 활용한 기존의 법의학적 얼굴 복원 기술은 다수의 선행연구 결과가 축적되어 있지만, 얼굴 연부조직의 두께나 성상, 눈이나 코의 형태, 체모의 분포 등의 고려 요소가 많아 복원 결과가 달라질 수 있다는 한계가 존재한다. 본 연구는 얼굴의 특징점(face landmark)을 활용하는 얼굴 인식 기술이 전세계적으로 보편화되고 있다는 점에 착안하여, 사후변화로 인해 연부조직이 팽창된 부패 시신의 얼굴을 복원하거나 생전의 사진과 비교하여 동일인 여부를 판정함으로써 신속하고 정확한 신원확인에 도움을 주고자 한다. 
 본 연구에서는 지문 등으로 신원이 확인된 시신을 대상으로 신분증 등의 생전 데이터와 검안 또는 부검 당시 촬영된 사후데이터를 수집한 뒤 각각 짝을 지어 비교쌍을 구성하였으며, 얼굴 인식 기술은 현재 해당 분야에서 많이 활용되고 있는 MTCNN 모델을 활용하였다. 생전데이터와 사후데이터의 일치 여부를 판단하는 인공지능모델은 총 7개의 open source 모델(VGG-Face, FaceNet, OpenFace, DeepFace, DeepID, ArcFace, Dlib) 중 가장 동일인 판정률의 빈도가 가장 높게 나타난 Arcface를 선정하여 분석하였다.
 인공지능모델(Arcface)의 성능은 전문가집단과 일반인 집단, 전체 사람 집단의 판정 결과와 비교하여 평가하였다. 원본 데이터 107쌍을 이용한 비교 결과, 동일인 판정률은 전문가집단 51.4%, 일반인 22.4%, 전체 사람 집단 29.0%로 조사되었으며, 인공지능모델은 47.7%로 나타났다. 원본 데이터를 검토한 결과, 부패로 인한 피부색의 변화가 인공지능모델의 성능에 영향을 줄 가능성이 있다고 판단되었다. 이러한 판단에 따라 원본 데이터를 회색조(gray scale)로 전처리하였을 때 인공지능모델의 동일인 판정률은 50.5%로, 약 3%의 성능이 향상되는 것을 볼 수 있었다. 
본 연구를 통해 현재 개발되어 있는 인공지능모델만으로도 전문가 집단에 근접한 얼굴 인식 성능을 보이는 것을 알 수 있었다. 향후 사후변화의 특성을 반영한 다양한 전처리 기법을 개발하여 적용할 경우 얼굴 인식 성능을 더욱 향상시킬 수 있을 것으로 기대된다.

</small> </p>
                    </tr>                             
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="dead.JPG" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Learning Sparse Latent Graph Representations for Anomaly Detection in Multivariate Time Series</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Siho Han and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>ACM SIG KDD, Washington, DC, USA, 2022</b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>BK Computer Science IF=4 (Short Oral Talk) </font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Anomaly detection in high-dimensional time series is typically tackled using either reconstruction- or forecasting-based deep learning algorithms. Both streams of approach have seen enormous success in terms of detection accuracy due to their abilities to learn compressed data representations and model temporal dependencies, respectively. However, most existing methods disregard the relationships between features, information that would be extremely useful when incorporated into the model. How can we effectively combine the best of reconstruction and forecasting models while also capturing feature interdependencies? In this work, we introduce Fused Sparse Autoencoder and Graph Net (FuSAGNet), which jointly optimizes reconstruction and forecasting while explicitly modeling the relationships within multivariate time series. Our approach combines Sparse Autoencoder and Graph Neural Network, the latter of which predicts future time series behavior from sparse latent representations learned by the former as well as graph structures learned through recurrent feature embedding. Experimenting on three real-world cyber-physical system datasets, we empirically demonstrate that the proposed method enhances the overall anomaly detection performance, outperforming baseline approaches. Moreover, we show that mining sparse latent patterns from high-dimensional time series improves the robustness of the graph-based forecasting model. Lastly, we conduct visual analyses to investigate the interpretability of both recurrent feature embedding vectors and sparse latent representations. </small> </p>
                    </tr>                             
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="kdd22_sean.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    
        <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Evading Deepfake Detectors via High-Quality Face Pre-Processing Methods</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>JeongHo Kim<sup>&dagger;</sup>, Taejune Kim<sup>&dagger;</sup>, Jeonghyeon Kim, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>International Conference on Pattern Recognition, Montreal Quebec, 2022</b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>BK Computer Science IF=1 </font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Today, various multimedia content can be accessed and shared from any location via the Internet. In addition to normal content, there is an extensive amount of manipulated multimedia that can raise various social issues and concerns. Among the various types of manipulated media, deepfakes can be abused in impersonation or spreading fake information. Therefore, numerous studies have been performed to detect deepfakes to alleviate these concerns, and studies such as FaceForensics++ (FF++) and DeepFake Detection Challenge (DFDC) have sparked these studies by providing deepfake datasets. The deepfake datasets were utilized for supervised learning in conjunction with developing sophisticated neural networks and showed a high detection performance. Since powerful neural networks can learn even subtle details about an image, they must be trained on realistic deepfakes created by advanced deepfake generation technologies to improve the robustness of existing detectors. In order to boost the performance of deepfake detection models, we propose an approach to creating more realistic deepfake images by removing "detectable" artifacts from existing deepfake datasets' images. By applying the proposed method to the original deepfake dataset, we demonstrate that our technique can significantly reduce the detection performance of existing deepfake detectors. Our experimental results show the vulnerability of deployed detectors and pave the way for further improvement. </small> </p>
                    </tr>                             
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="ICPR_2022_Evading_deepfake.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>

    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Efficient Two-stage Model Retraining for Machine Unlearning</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Junyaup Kim and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>CVPR Workshop on Human-centered Intelligent Services: Safe and Trustworthy, 2022</b> </small> </p>
                    </tr>                 
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>With the rise of the General Data Protection Regulation (GDPR), user data holders should guarantee the “individual’s right to be forgotten”. It means user data holders must completely remove user data when they receive the request. However, enabling a deep learning model to exclude specific data used during training is challenging. We can’t define what is ”forgetting” in deep learning and how to do it. To address this issue, we propose an efficient machine unlearning architecture to be used for computer vision classification models. Our approach consists of two-stage, where in the first stage we render a deep learning model that loses information with contrastive labels in the requested dataset. Second, we retrain the first stage output model with knowledge distillation (KD). Using this two-stage approach, we can substantiate the removal or forgetness of the requested dataset in the deep learning model. With various datasets used for multimedia applications, we demonstrate that our approach achieves performance on par or even higher accuracy than the original model, while effectively removing the requested data. </small> </p>
                    </tr>                             
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="junjyuap_cvprw22.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Negative Adversarial Example Generation Against Naver’s Celebrity Recognition API</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Keeyoung Kim and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>Workshop on the security implications of Deepfakes and Cheapfakes (WDC), ACM ASIACCS, 2022</b> </small> </p>
                    </tr>                 
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Deep Neural Networks (DNNs) are very effective in image classification, detection and recognition due to a large number of available data. However, they can be easily fooled by adversarial examples and produce incorrect results, which can cause problems for many applications. In this work, we focus on generating adversarial images and exploring and assessing possible negative impacts caused by these examples. As a case study, we create adversarial images against Naver’s celebrity recognition (NCR) API, as Naver is the leading machine learning APIs service provider in South Korea. We demonstrate that it is extremely easy to fool the online DNN-based APIs using adversarial examples and discuss possibe negative impacts resulting from these adversarial examples.
 </small> </p>
                    </tr>                             
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="wdc_kim.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>A Face Pre-Processing Approach to Evade Deepfade Detector</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Taejune Kim, Jeonghyeon Kim, Jongho Kim, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>Workshop on the security implications of Deepfakes and Cheapfakes (WDC), ACM ASIACCS, 2022</b> </small> </p>
                    </tr>                 
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Recently, various image synthesis technologies have increased the prevalence of impersonation attacks, and with the development of such technologies, the amount of damage such as defamation has also increased. Deepfake, the representative of the impersonation technique, has already evolved to the point where people cannot distinguish, leading to an urgent need for detection methods. Currently, in order to detect deepfakes, many deepfake datasets are widely used in deep neural networks using supervision learning. However, although this method is robust to the images synthesized by deepfake generation methods already known, it remains undefined whether deepfakes created by unknown techniques can be detected. Accordingly, to detect more challenging deepfakes, we present a pre-processing technique that mitigates the artifacts of deepfakes and makes them appear more natural. The proposed method can be combined with the existing deepfake creation method to generate a more threatening deepfake image. Furthermore, through extensive experiments, we demonstrate that our method can significantly lower the performance of state-of-the-art detectors and expose the vulnerability of deployed detectors.
 </small> </p>
                    </tr>                              
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="wdc2_taejune.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b> Deepfake Detection for Facial Images with Facemasks</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Donggeun Ko, Sangjun Lee, Jinyong Park, Saebyeol Shin, Donghee Hong, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>Workshop on the security implications of Deepfakes and Cheapfakes (WDC), ACM ASIACCS, 2022</b> </small> </p>
                    </tr>                 
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Hyper-realistic face image generation and manipulation have givenrise to numerous unethical social issues, e.g., invasion of privacy,threat of security, and malicious political maneuvering, which re-sulted in the development of recent deepfake detection methodswith the rising demands of deepfake forensics. Proposed deepfakedetection methods to date have shown remarkable detection perfor-mance and robustness. However, none of the suggested deepfakedetection methods assessed the performance of deepfakes withthe facemask during the pandemic crisis after the outbreak of theCovid-19. In this paper, we thoroughly evaluate the performance ofstate-of-the-art deepfake detection models on the deepfakes withthe facemask. Also, we propose two approaches to enhance themasked deepfakes detection:face-patchandface-crop. The experi-mental evaluations on both methods are assessed through the base-line deepfake detection models on the various deepfake datasets.Our extensive experiments show that, among the two methods,face-cropperforms better than theface-patch, and could be a trainmethod for deepfake detection models to detect fake faces withfacemask in real world.
 </small> </p>
                    </tr>                             
                </tbody>
            </table>
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Zoom-DF: A dataset for Video Conferencing Deepfake</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Geonwoo Park, Eunju Park, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>Workshop on the security implications of Deepfakes and Cheapfakes (WDC), ACM ASIACCS, 2022</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>With the growth of deep learning studies, the technologies of generating deepfake videos have been advanced. While the manipulated videos are so sophisticated that one cannot differentiate between real and fake, one can create such videos with little effort. These technologies are likely to be abused by people with malicious intent. To address the problem, the algorithms for detecting deepfakes have been researched abundantly. The performance of the detectors, however, depends on the amount and the domain of the training data. In this paper, we introduce a new deepfake dataset generated by an algorithm changing an original image to a sequence of fake images. We evaluate existing models detecting deepfakes on the new dataset and demonstrate that the accuracy of the models degrades. Their performance is recovered when trained with the new dataset. </small> </p>
                    </tr>     
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="wdc22_deonwoo.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>PasswordTensor: Analyzing and Explaining Password Strength using Tensor Decomposition</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Youjin Shin and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>Elsevier Computers & Security, Jan 2022</b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'> SCIE Q1 IF=4.4</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>A textual password is widely used for user authentication for a variety of applications. Passwords that are easy to remember are also easy to be guessed, while complex and long passwords that provide strong security are difficult to remember. Also, there has been limited quantitative research to understand the factors that make passwords strong. In this research, we aim to expand our understanding of passwords through the lenses of data-driven analysis by characterizing a large number of password datasets with four different hypotheses. In particular, we use the tensor decomposition method that is effective in analyzing unlabeled high dimensional data. We first obtain 362,805 passwords from four different leaked password datasets. Next, we generate syntactic and semantic features for each password, then classify it into three strength groups using a statistical guessing attack model. Finally, we construct a 3rd-order password tensor and decompose it using the PARAFAC2 algorithm to examine the main characteristics which make passwords strong. </small> </p>
                    </tr>                
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.sciencedirect.com/science/article/pii/S0167404822000335"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="computer_security_2022_yj.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>A Survey of Deep Learning-based Object Detection Methods and Datasets for Overhead Imagery</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>JunHyung Kang, Shahroz Tariq, Han Oh, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>IEEE Access </b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'> SCIE</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Although extensive studies in deep learning-based object detection have achieved remarkable performance and success, they are still ineffective yielding a low detection performance, due to the underlying difficulties in overhead images. Thus, high-performing object detection in overhead images is an active research field to overcome such difficulties. This survey paper provides a comprehensive overview and comparative reviews on the most up-to-date deep learning-based object detection in overhead images. Especially, our work can shed light on capturing the most recent advancements of object detection methods in overhead images and the introduction of overhead datasets that have not been comprehensively surveyed before.
</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://ieeexplore.ieee.org/abstract/document/9703336"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                  
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="ieee_access_junhyung.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Am I a Real or Fake Celebrity? Evaluating Face Recognition and Verification APIs under Deepfake Impersonation Attack</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Shahroz Tariq, Sowon Jeon, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>The 31st Web Conference (WWW), France, April 2022</b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>BK Computer Science IF=4 </font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Recent advancements in web-based multimedia technologies, such as face recognition web services powered by deep learning, have been significant. However, such technologies face persistent threats, as virtually anyone with access to deepfakes can quickly launch impersonation attacks, which pose a serious threat to authentication services. Despite its gravity, deepfake abuse involving commercial web services have not been investigated. Thus, we examine the robustness of black-box commercial face recognition web APIs (Microsoft, Amazon, Naver, and Face++) and open-source tools (VGGFace and ArcFace) against Deepfake Impersonation (DI) attacks. We demonstrate the vulnerability of face recognition technologies to DI attacks, achieving respective success rates of 78.0% for targeted (TA) attacks; we also propose mitigation strategies, lowering respective attack success rates to as low as 1.26% for TA attacks with adversarial training.
</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://arxiv.org/abs/2103.00847"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; <a
                                    href="https://anonymous.4open.science/r/DI_Attack"> <img  alt="github" src="github.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;">  </a> </small> </p>
                    </tr>
                  
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="www22_shah.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>

     
    <hr>    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>BZNet: Unsupervised Multi-scale Branch Zooming Network for Detecting Low-quality Deepfake Videos</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Sangyup Lee, Jaeju An, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>The 31st Web Conference (WWW), France, April 2022</b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>BK Computer Science IF=4 </font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Generating a deep learning-based fake video has become no longer rocket science. The advancement of automated Deepfake (DF) generation tools that mimic certain targets has rendered society vulnerable to fake news or misinformation propagation. In real-world scenarios, DF videos are compressed to low-quality (LQ) videos, taking up less storage space and facilitating dissemination through the web and social media. Such LQ DF videos are much more challenging to detect than high-quality (HQ) DF videos. To address this challenge, we rethink the design of standard deep learning-based DF detectors, specifically exploiting feature extraction to enhance the features of LQ images. We propose a novel LQ DF detection architecture, multi-scale Branch Zooming Network (BZNet), which adopts an unsupervised super-resolution (SR) technique and utilizes multi-scale images for training. We train our BZNet only using highly compressed LQ images and experiment under a realistic setting, where HQ training data are not readily accessible. Extensive experiments on the FaceForensics++ LQ and GAN-generated datasets demonstrate that our BZNet architecture improves the detection accuracy of existing CNN-based classifiers by 4.21\% on average. Furthermore, we evaluate our method against a real-world Deepfake-in-the-Wild dataset collected from the internet, which contains 200 videos featuring 50 celebrities worldwide, outperforming the state-of-the-art methods by 4.13%. 
</small> </p>
                    </tr>  
             </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="www22_jaeju.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>

     
    <hr>
    
    
       <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Residual Size is Not Enough for Anomaly Detection: Improving Detection Performance using Residual Similarity in Multivariate Time Series</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Jeong-Han Yun, Jonguk Kim, Won-Seok Hwang, Young Geun Kim, <b><i>Simon S. Woo</i></b> and Byung-Gil Min </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>ACM-SAC, Virtual, 2022</b> </small> </p>
                    </tr>
                    <tr>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>BK Computer Science IF=1 </font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>To Be Updated ...
</small> </p>
                    </tr>
                    
                </tbody>
            </table>
           </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
    
    <hr>
    
    
        <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>PTD: Privacy-Preserving Human Face Processing Framework using Tensor Decomposition</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Jeongho Kim, Shahroz Tariq, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>ACM-SAC, Virtual, 2022</b> </small> </p>
                    </tr>
                    <tr>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>BK Computer Science IF=1 </font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Training data may include personal information such as human faces, which requires anonymization to provide user privacy. However, after anonymization, the performance of the original machine learning (ML) model degrades due to the reduced or missing information. In this work, we introduce a novel privacy-preserving tensor decomposition (PTD) method to anonymize human faces. Further, we evaluate
real vs. fake human face detection task as a practical use case scenario. Our approach achieves high performance as well as training data efficiency, where the essence of our approach is based on tensor decomposition to ensure face data privacy. In particular, we demonstrate that the core tensor of Tucker decomposition generated from the original face input can effectively represent the underlying characteristics of the original face data; that is, learning only from the core tensors is sufficient for differentiating real human face images from deepfakes. Also, we show that the original human face inputs are anonymized and cannot be recovered from the core tensors under different attacker models from the randomized HOOI algorithm. Through extensive experiments and analysis, we demonstrate that our method can result in high detection performance comparable to those of popular anonymization methods. Therefore, we show that our work strikes the balance between privacy and performance through the novel use of tensor decomposition.
</small> </p>
                    </tr> 
                </tbody>
            </table>
            </div>
            <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
             <img src="tensor.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
            </div>
         </div>
     
    <hr>
            
            
    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>ADD: Frequency Attention and Multi-View based Knowledge Distillation to Detect Low-Quality Compressed Deepfake Images</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Binh M. Le and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>Thirty-Sixth AAAI Conference on Artificial Intelligence, Canada, 2022</b> </small> </p>
                    </tr>
                    <tr>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                               <font color='blue'>BK Computer Science IF=4 (Acceptance Rate ~ 15%)</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Despite significant advancements of deep learning-based forgery detectors for distinguishing manipulated deepfake images, most detection approaches suffer from moderate to significant performance degradation with low-quality compressed deepfake images.
Because of the limited information in low-quality images, detecting low-quality deepfake remains an important challenge. In this work, we apply frequency domain learning and optimal transport theory in knowledge distillation (KD) to specifically improve the detection of low-quality compressed deepfake images. We explore transfer learning capability in KD to enable a student network to learn discriminative features from low-quality images effectively. In particular, we propose the Attention-based Deepfake detection Distiller (ADD), which consists of two novel distillations: 1) frequency attention distillation that effectively retrieves the removed high-frequency components in the student network, and 2) multi-view attention distillation that creates multiple attention vectors by slicing the teacher’s and student’s tensors under different views to transfer the teacher tensor’s distribution to the student more efficiently. Our extensive experimental results demonstrate that our approach outperforms state-of-the-art baselines in detecting low-quality compressed deepfake images.
</small> </p>
                    </tr>
                
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://ojs.aaai.org/index.php/AAAI/article/view/19886"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; <a
                                    href="https://github.com/Leminhbinh0209/ADD"> <img  alt="github" src="github.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;">  </a> </small> </p>
                    </tr>
                  
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="aaai22_binh.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>ORVAE: One-Class Residual Variational Autoencoder for Voice Activity Detection in Noisy Environment</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Hasam Khalid, Shahroz Tariq, TaeSoo Kim, Jong Hwan Ko, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>Neural Processing Letters <font color="blue">(SCIE IF=2.9)</font> </b> </small> </p>
                    </tr>
                    <tr>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Detecting human speech is foundational for a wide range of emerging intelligent applications. However, accurately detecting human speech is challenging, especially in the presence of unknown noise patterns. Generally, deep learning-based methods have shown to be more robust and accurate than statistical methods and other existing approaches. However, typically creating a noise-robust and more generalized deep learning-based Voice Activity Detection (VAD) system requires the collection of an enormous amount of annotated audio data. In this work, we develop a generalized model trained on limited types of human speeches with noisy backgrounds. Yet, it can detect human speech in the presence of various unseen noise types, which were not present in the training set. To achieve this, we propose a One-Class Residual connections-based Variational Autoencoder (ORVAE), which only requires a limited number of human speech data with noisy background for training, thereby eliminating the need for collecting data with diverse noise patterns. Evaluating ORVAE with three different datasets (synthesized TIMIT and NOI
SEX-92, synthesized LibriSpeech and NOISEX-92, and a Publicly Recorded dataset), our method outperforms other one-class baseline methods, achieving 1-scores of over 90% for multiple Signal-to-Noise Ratio (SNR) levels.
</small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify; margin-left: 20px;"> <small> <a
                                href="https://link.springer.com/article/10.1007%2Fs11063-021-10695-4"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a></small> </p>
                </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="orvae_npl.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <h4 style="margin-top:20px"><b>2021</b></h4>
    <hr>    
    <div style="display: flex;flex-direction: row;justify-content: space-between;">
    <div style="margin-left: 25px;margin-right: 10px;">
        <table>
            <thead>
                <tr>
                    <a><b>Evaluation of an Audio-Video Multimodal Deepfake Dataset using Unimodal and Multimodal Detectors</b></a>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Hasam Khalid, Minha Kim, Shahroz Tariq, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                </tr>
                <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>Proceedings of the 1st Workshop on Synthetic Multimedia - Audiovisual Deepfake Generation and Detection</b> </small> </p>
                </tr>
                <tr>
                <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                           <font color='blue'></font>
                            </b> </small> </p>
                </tr>
                <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Significant advancements made in the generation of deepfakes have caused security and privacy issues. Attackers can easily impersonate a person's identity in an image by replacing his face with the target person's face. Moreover, a new domain of cloning human voices using deep-learning technologies is also emerging. Now, an attacker can generate realistic cloned voices of humans using only a few seconds of audio of the target person. With the emerging threat of potential harm deepfakes can cause, researchers have proposed deepfake detection methods. However, they only focus on detecting a single modality, i.e., either video or audio. On the other hand, to develop a good deepfake detector that can cope with the recent advancements in deepfake generation, we need to have a detector that can detect deepfakes of multiple modalities, i.e., videos and audios. To build such a detector, we need a dataset that contains video and respective audio deepfakes. We were able to find a most recent deepfake dataset, Audio-Video Multimodal Deepfake Detection Dataset (FakeAVCeleb), that contains not only deepfake videos but synthesized fake audios as well. We used this multimodal deepfake dataset and performed detailed baseline experiments using state-of-the-art unimodal, ensemble-based, and multimodal detection methods to evaluate it. We conclude through detailed experimentation that unimodals, addressing only a single modality, video or audio, do not perform well compared to ensemble-based methods. Whereas purely multimodal-based baselines provide the worst performance.
</small> </p>
                </tr>

                <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                href="https://dl.acm.org/doi/10.1145/3476099.3484315"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a></small> </p>
                </tr>

            </tbody>
        </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
         <img src="ADGD21_hasam.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
     </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>FakeAVCeleb: A Novel Audio-Video Multimodal Deepfake Dataset</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Hasam Khalid, Shahroz Tariq, Minha Kim, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>Thirty-fifth Conference on Neural Information Processing Systems (NeurIPS) Datasets and Benchmarks Track  </b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>While the significant advancements have made in the generation of deepfakes using deep learning technologies, its misuse is a well-known issue now. Deepfakes can cause severe security and privacy issues as they can be used to impersonate a person's identity in a video by replacing his/her face with another person's face. Recently, a new problem of generating synthesized human voice of a person is emerging, where AI-based deep learning models can synthesize any person's voice requiring just a few seconds of audio. With the emerging threat of impersonation attacks using deepfake audios and videos, a new generation of deepfake detectors is needed to focus on both video and audio collectively. A large amount of good quality dataset is typically required to capture the real-world scenarios to develop a competent deepfake detector. Existing deepfake datasets either contain deepfake videos or audios, which are racially biased as well. Hence, there is a crucial need for creating a good video as well as audio deepfake dataset, which can be used to detect audio and video deepfake simultaneously. To fill this gap, we propose a novel Audio-Video Deepfake dataset (FakeAVCeleb) that contains not only deepfake videos but also respective synthesized lip-synced fake audios. We generate this dataset using the current most popular deepfake generation methods. We selected real YouTube videos of celebrities with four racial backgrounds (Caucasian, Black, East Asian, and South Asian) to develop a more realistic multimodal dataset that addresses racial bias, and further help develop multimodal deepfake detectors. We performed several experiments using state-of-the-art detection methods to evaluate our deepfake dataset and demonstrate the challenges and usefulness of our multimodal Audio-Video deepfake dataset.
</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://arxiv.org/abs/2108.05080"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; <a
                                    href="https://github.com/hasam6400/fakevaceleb"> <img  alt="github" src="github.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;">  </a> <a
                                    href="https://datasets-benchmarks-proceedings.neurips.cc/paper/2021">Proceeding</a></small> </p>
                       
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="fakeceleb_nips2021.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>VFP290K: A Large-Scale Benchmark Dataset for Vision-based Fallen Person Detection</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Jaeeju An, Jeongho Kim, Hanbeen Lee, Jinbeoom Kim, Junhyung Kang, Minha Kim, Saebyeol Shin, Minha Kim, Donghe Hong and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>Thirty-fifth Conference on Neural Information Processing Systems (NeurIPS) Datasets and Benchmarks Track  </b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Detection of fallen persons due to, for example, health problems, violence, or accidents, is a critical challenge. Accordingly, detection of these anomalous events is of paramount importance for a number of applications, including but not limited to CCTV surveillance, security, and health care. Given that many detection systems rely on a comprehensive dataset comprising fallen person images collected under diverse environments and in various situations is crucial. However, existing datasets are limited to only specific environmental conditions and lack diversity. To address the above challenges and help researchers develop more robust detection systems, we create a novel, large-scale dataset for the detection of fallen persons composed of fallen person images collected in various real-world scenarios, with the support of the South Korean government. Our Vision-based Fallen Person (VFP290K) dataset consists of 294,714 frames of fallen persons extracted from 178 videos, including 131 scenes in 49 locations. We empirically demonstrate the effectiveness of the features through extensive experiments analyzing the performance shift based on object detection models. In addition, we evaluate our VFP290K dataset with properly divided versions of our dataset by measuring the performance of fallen person detecting systems. We ranked first in the first round of the anomalous behavior recognition track of AI Grand Challenge 2020, South Korea, using our VFP290K dataset, which can be found here. Our achievement implies the usefulness of our dataset for research on fallen person detection, which can further extend to other applications, such as intelligent CCTV or monitoring systems. The data and more up-to-date information have been provided at our VFP290K site.
</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://openreview.net/pdf?id=y2AbfIXgBK3"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; <a
                                    href="https://sites.google.com/view/dash-vfp300k/">Project</a> &nbsp; <a
                                    href="https://datasets-benchmarks-proceedings.neurips.cc/paper/2021">Proceeding</a></small> </p>
                       
                       
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="vfp290_nips.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>IVDR: Imitation learning with Variational inference and Distributional Reinforcement learning to find Optimal Driving Strategy</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Kihyung Joo and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>20th IEEE International Conference on Machine Learning and Applications (ICMLA), Pasadena, Dec, 2021   </b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Current state-of-the-art autonomous driving technology significantly advanced, leveraging reinforcement learning (RL) algorithms, because it is not easy to apply a rule-based driving method that reflects all the various traffic conditions. Indeed, reinforcement learning can produce the possible optimal driving strategy of urban, rural, and motorway roads in various environmental conditions such as speed limits and school zones. However, it is challenging to adjust the parameters of the reward mechanism in RL, because the driving style of each user is very different. And it takes a massive amount of time and resources to conduct RL by reflecting all complex traffic conditions. However, if RL imitates the driving behavior of an expert, RL algorithm can proceed more quickly. Therefore, we propose a novel imitation learning framework, which combines an expert's driving behavior with a continuous behavior of an agent. Further, a deep reinforcement learning approach is used to mimic the expert's driving behavior. Therefore, we propose imitation learning with variational inference and distributional reinforcement learning (IVDR) algorithm. Our results show that IVDR achieves 80% better learning speed than the learning speed of other approaches and outperforms 12% higher in average reward. Our work shows great promise of using RL for autonomous driving and real vehicle driving simulation.
</small> </p>
                    </tr>
                    <tr>
                       
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="ivdr.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>EMGNet: Efficient Multi-Scale Feature Generation Adaptive Network</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Gwanghan Lee, Minha Kim, Minha Kim, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>30th ACM International Conference on Information and Knowledge Management </b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'>BK Computer Science IF=3</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Recently, an early exit network, which dynamically adjusts the model complexity during inference time, has achieved remarkable performance. However, they were unsuccessful at resolving the performance drop of early classifiers that make predictions with insufficient high-level feature information. Consequently, the performance degradation of early classifiers had a devastating effect on the entire network performance sharing the backbone. In this paper, we propose an Efficient Multi-Scale Feature Generation Adaptive Network (EMGNet), which not only reduced the redundancy of the architecture but also generates multi-scale features to improve the performance of the early exit network.
</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/abs/10.1145/3459637.3482337"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; <a
                                    href="https://github.com/lee-gwang/EMGNet"> <img  alt="github" src="github.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;">  </a> </small> </p>
                       
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="cikm22_gh.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Crew Resource Management in Industry 4.0 : focusing on human-autonomy teaming</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Sunny Yun and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>Korean Journal of Aerospace and Environmental Medicine(KJAsEM), August 2021 </b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>In the era of the 4th industrial revolution, the aviation industry is also growing remarkably with the development of artificial intelligence and networks, so it is necessary to study a new concept of CRM, which is required in the process of operating state-of-the-art equipment. The automation system, which has been treated only as a tool, is changing its role as a decision-making agent with the development of AI, and it is necessary to set clear standards for the role and responsibility in the safety-critical field. We present a new perspective on the automation system in the CRM program through the understanding of the autonomous system. In the future, autonomous system will develop as an agent for human pilots to cooperate, and accordingly, changes in role division and reorganization of regulations are required.</small> </p>
                    </tr>
                    <tr>
                        
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
    
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>DLPNet: Dynamic Loss Parameter Network using Reinforcement Learning for Aerial Imagery Detection</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>JunHyung Kang and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>4th International Conference on Artificial Intelligence and Pattern Recognition, 2021 </b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>We propose DLPNet, a novel RL module to enable robust and stable training while achieving high performance in practical small mini-batch size conditions. DLPNet observes input image patches and acts to select the optimal parameters of the dynamic focal loss function for the baseline detector with every mini-batch training iteration during the training phase.</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/abs/10.1145/3488933.3489031"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp;  <a
                                    href="https://github.com/JunHyungKang/DLPNet"> <img  alt="github" src="github.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;">  </a></small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="dlpnet_icpr21.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>CoReD: Generalizing Fake Media Detection with Continual Representation using Distillation</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>  Minha Kim, Shahroz Tariq and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The 29th ACM International Conference on Multimedia (ACMMM '21), Chengdu, China, Oct 20-24, 2021 </b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'>BK Computer Science IF=4 (Oral Talk)</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>In this work, we apply continuous learning to neural networks' learning dynamics, emphasizing its potential to increase data efficiency significantly. We propose Continual Representation using Distillation (CoReD) method that employs the concept of Continual Learning (CoL), Representation Learning (ReL), and Knowledge Distillation (KD). We design CoReD to perform sequential domain adaptation tasks on new deepfake and GAN-generated synthetic face datasets, while effectively minimizing the catastrophic forgetting in a teacher-student model setting. Our extensive experimental results demonstrate that our method is efficient at domain adaptation to detect low-quality deepfakes videos and GAN-generated images from several datasets, outperforming the-state-of-art baseline methods.</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://arxiv.org/abs/2107.02408"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; <a
                                    href="https://github.com/alsgkals2/CoReD"> <img  alt="github" src="github.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;">  </a></small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="acmm21_minha.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>SmartConDetect: Highly Accurate Smart Contract CodeVulnerability Detection Mechanism using BERT</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>  Sowon Jeon, Gilhee Lee, Hyoungshick Kim and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> 2021 KDD Workshop on Programming Language Processing (PLP 2021) <a href="https://cs.skku.edu/ko/edures/research/view/6073"><font color="red">The Best Paper Award</font></a></b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>In this paper, we propose SmartConDetect to detect security vulnerabilities in smart contracts written in Solidity, which the most popular programming language for writing smart contracts on the Ethereum platform. SmartConDetect is designed as a static analysis tool to extract code fragments from smart contracts in Solidity and analyze code patterns using a pre-trained BERT model and a bidirectional LSTM model.</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.google.com/search?q=SmartConDetect%3A+Highly+Accurate+Smart+Contract+CodeVulnerability+Detection+Mechanism+using+BERT&oq=SmartConDetect%3A+Highly+Accurate+Smart+Contract+CodeVulnerability+Detection+Mechanism+using+BERT&aqs=chrome..69i57j69i58.269j0j7&sourceid=chrome&ie=UTF-8"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="smartcondetect.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    
    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Exploring the Asynchronous of the Frequency Spectra of GAN-generated Facial Images</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Le Minh Binh and <i><b>Simon S. Woo*</b> </i></small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b><a href="https://ssdl2021.github.io/">International Workshop on Safety and Security of Deep Learning</a>, IJCAI 2021 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>In this paper, we propose a new approach that explores the asynchronous frequency spectra of color channels, which is simple but effective for training both unsupervised and supervised learning models to distinguish GAN-based synthetic images.</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://arxiv.org/abs/2112.08050"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; <a
                                    href="https://github.com/Leminhbinh0209/Asynchronous-in-Frequency-domain-of-GAN-images"><img  alt="github" src="github.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"></a></small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="ijcai2021_overall_diag.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    
    


    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b> FReTAL: Generalizing Deepfake Detection using Knowledge Distillation and Representation
                                Learning</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Minha Kim, Shahroz
                                Tariq, <i><b>Simon S. Woo*</b> </i></small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> <a
                                        href="https://sites.google.com/view/mediaforensics2021/"> WORKSHOP ON MEDIA
                                        FORENSICS</a>, CVPR 2021 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>As GAN-based video
                                and image manipulation technologies become more sophisticated and easily accessible,
                                there is an urgent need for effective deepfake detection technologies. Moreover, various
                                deepfake generation techniques have emerged over the past few years.</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://openaccess.thecvf.com/content/CVPR2021W/WMF/html/Kim_FReTAL_Generalizing_Deepfake_Detection_Using_Knowledge_Distillation_and_Representation_Learning_CVPRW_2021_paper.html"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; <a
                                    href="https://github.com/alsgkals2/FReTAL-Generalizing_Deepfakes_using_Knowledge_Distillation_and_Representation_Learning"> <img  alt="github" src="github.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;">  </a></small>
                        </p>
                    </tr>

                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="fretalgd.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>


    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b> Neural Network Laundering: Removing Black-Box Backdoor Watermarks from Deep Neural
                                Networks</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> William Aiken,
                                Hyoungshick Kim, <i><b>Simon S. Woo*</b> </i>, and Jungwoo Ryoo </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Elsevier
                                    Computers & Security, accepted on April 2021 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>SCIE Q1 IF=3.58</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>Creating a
                                state-of-the-art deep-learning system requires vast amounts of data, expertise, and
                                hardware, yet research into embedding copyright protection for neural networks has been
                                limited. One of the main methods for achieving such protection involves relying on the
                                susceptibility of neural networks to backdoor attacks, but the robustness of these
                                tactics has been primarily evaluated against pruning, fine-tuning, and model inversion
                                attacks. </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.sciencedirect.com/science/article/pii/S0167404821001012"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a></small>
                        </p>
                    </tr>

                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="nb.jpg" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>

    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b> Will EU’s GDPR Act as an Effective Enforcer to Gain Consent?</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Oh, Junhyoung and Hong, Jinhyoung and Lee, Changsoo and Lee, Jemin Justin and <i><b>Simon S. Woo*</b> </i> and Lee, Kyungho </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>IEEE Access</b> </small> </p>
                    </tr>
                    <tr>
                    <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>SCIE Q1 IF=3.67</font>
                                </b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>In this study, we analyze GDPR provisions and recitals as well as relevant EU guidelines to propose quantifiable consent conditions to check whether website providers are compliant with the GDPR. We then evaluate the extent to which various popular web service providers meet these conditions.</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9440969"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a></small>
                        </p>
                    </tr>

                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="gdpr.PNG" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>

    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right:10px;">
            <table>
                <thead>
                    <tr>
                        <a><b> Am I a Real or Fake Celebrity? Measuring Commercial Face Recognition Web APIs under
                                Deepfake Impersonation Attack</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Shahroz Tariq, Sowon
                                Jeon, and <i><b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>arXiv</b>
                            </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>This work provides a
                                measurement study on the robustness of black-box commercial face recognition APIs
                                against Deepfake Impersonation (DI) attacks using celebrity recognition APIs as an
                                example case study We achieved maximum success rates of 78.0% and 99.9% for targeted
                                (ie, precise match) and non-targeted (ie, match with any celebrity) attacks,
                                respectively. Moreover, we propose practical defense strategies to mitigate DI attacks,
                                reducing the attack success rates to as low as 0% and 0.02% for targeted and
                                non-targeted attacks, respectively.</small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://arxiv.org/abs/2103.00847"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>
                                <a
                                    href="https://www.biometricupdate.com/202103/researchers-show-deepfakes-can-beat-face-biometric-web-services-propose-defense-strategy">News-1</a>
                                <a
                                    href="https://www.digitalinformationworld.com/2021/03/social-media-users-warned-of-deepfake.html">News-2</a>
                                <a
                                    href="https://medium.com/paradigm-fund/bt-biometric-digital-id-providers-partner-with-microsoft-on-decentralized-id-passwordless-pilot-c7c2aab797d1">News-3</a>
                                <a
                                    href="https://venturebeat.com/2021/03/05/study-warns-deepfakes-can-fool-facial-recognition/">
                                    News-4</a>
                                <a
                                    href="https://epocanegocios.globo.com/Tecnologia/noticia/2021/03/deepfakes-podem-enganar-ate-mesmo-inteligencia-artificial.html">News-5</a>
                                <a
                                    href="https://www.etcentric.org/study-suggests-deepfakes-fool-top-facial-recognition-tech/">News-6</a>
                                <a
                                    href="https://www.archyworldys.com/deepfakes-can-trick-facial-recognition/">News-7</a>
                                <a
                                    href="https://www.thespuzz.com/study-warns-deepfakes-can-fool-facial-recognition/">News-8</a>
                                <a
                                    href="https://publicnews.in/tech/study-warns-deepfakes-can-fool-facial-recognition/">News-9</a>
                                <a
                                    href="https://famousnews.org/study-warns-deepfakes-can-recognize-the-face/">News-10</a>
                                <a
                                    href="https://www.trendyvoice.in/study-warns-deepfakes-can-fool-facial-recognition/?amp">News-11</a>
                            </small> </p>
                    </tr>

                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle; text-align:center">
            <img src="airor.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b> Revitalizing Self-Organizing Map: Anomaly Detection using Forecasting Error
                                Patterns</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Young Geun Kim,
                                    Jeong-Han Yun, Siho Han, Hyoung Chun Kim, and <b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>36th
                                    International Conference on ICT Systems Security and Privacy Protection – IFIP SEC
                                    2021, 22–24 June 2021 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>BK Computer Science IF=1</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> In this work, we
                                focus on improving the anomaly detection performance by leveraging the forecasting error
                                patterns generated from prediction models, such as Sequence-to-Sequence (seq2seq),
                                Mixture Density Networks (MDNs), and Recurrent Neural Networks (RNNs). To this end, we
                                introduce Self-Organizing Map-based Anomaly Detector (SOMAD), an anomaly detection
                                framework based on a novel test statistic, SomAnomaly, for Cyber-Physical System (CPS)
                                security.

                            </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.google.com/search?q=Revitalizing+Self-Organizing+Map%3A+Anomaly+Detection+using+Forecasting+Error+Patterns&oq=Revitalizing+Self-Organizing+Map%3A+Anomaly+Detection+using+Forecasting+Error+Patterns&aqs=chrome..69i57.216j0j7&sourceid=chrome&ie=UTF-8"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a></small> </p>
                    </tr>

                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="rsom.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>




    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>TAR: Generalized Forensic Framework to Detect Deepfakes using Weakly Supervised
                                Learning</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Sangyup Lee,
                                    Shahroz Tariq, Junyaup Kim, and <b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>36th
                                    International Conference on ICT Systems Security and Privacy Protection – IFIP SEC
                                    2021, 22–24 June 2021 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>BK Computer Science IF=1</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> This work introduces
                                a practical digital forensic tool to detect different types of deepfakes simultaneously
                                and proposes Transfer learning-based Autoencoder with Residuals (TAR). The ultimate goal
                                of this work is to develop an uni fied model to detect various types of deepfake videos
                                with high accuracy, with only a small number of training samples that can work well in
                                real-world settings. To achieve this, this work develops an autoencoder-based detection
                                model with Residual blocks and sequentially performs transfer learning to detect
                                different types of deepfakes simultaneously. The detection model shows a high detection
                                performance not only on the FF++ dataset but also on 200 real-world Deepfake-in-the-wild
                                videos. </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.google.com/search?q=Towards+a+Generalized+Framework+to+Detect+Deepfakes+using+Weakly+Supervised+Learning&oq=Towards+a+Generalized+Framework+to+Detect+Deepfakes+using+Weakly+Supervised+Learning&aqs=chrome..69i57.941j0j7&sourceid=chrome&ie=UTF-8"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>

                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="tgddw.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>




    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Detecting Handcrafted Facial Image Manipulations and GAN-Generated Facial Images using
                                Shallow-FakeFaceNet </b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Sangyup Lee,
                                    Shahroz Tariq, Youjin Shin, and <b>Simon S. Woo*</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Elsevier Applied
                                    Soft Computing, accepted on Feb 2021 </b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>SCIE Q1 IF=5.47</font>
                                </b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small>In this work, we introduce a novel Handcrafted Facial Manipulation (HFM) image dataset and soft computing neural network models (Shallow-FakeFaceNets) with an efficient facial manipulation detection pipeline. Our neural network classifier model, Shallow-FakeFaceNet (SFFN), shows the ability to focus on the manipulated facial landmarks to detect fake images. This study is targeted for developing an automated defense mechanism to combat fake images used in different online services and applications, leveraging our state-of-the-art handcrafted fake facial dataset (HFM) and the neural network classifier Shallow-FakeFaceNet (SFFN).</small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.sciencedirect.com/science/article/pii/S1568494621001794"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>

                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="dhfi.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>


    <div style="display: flex;flex-direction: row;justify-content: space-between;">

        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Exploring Racial Bias in Classifiers for Face Recognition</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Jaeju An,
                                    Jeongho Kim, Bosung Yang, Geonwoo Park, <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Third Workshop
                                    on Fairness, Accountability, Transparency, Ethics and Society on the Web (FATES)
                                    Joint with The Web Conference 2021, Ljubljana, Slovenia, </b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Recent advancements
                                in deep learning have allowed, among others,various applications of face recognition
                                systems, where a largeamount of face image data are typically required for training.
                            </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://arxiv.org/abs/2004.08945"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp;  <a
                                    href="https://www.youtube.com/watch?v=tgQ9TQc2jdU"><img  alt="video" src="talk.svg" style="right: 15px; position:relative; top:5px; width: 20px; height: 18px;"></a></small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="ExploringRacialBias.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>One Detector to Rule Them All: Towards a General Deepfake Attack Detection
                                Framework</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Shahroz Tariq,
                                    Sangyup Lee, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The 30th Web
                                    Conference (WWW), Ljubljana, Slovenia, April 19, 2021 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'><u>BK Computer Science IF=4, Acceptace rate = 20.6%</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Beyond detecting a single type of DF from benchmark deepfake datasets, we focus on developing a generalized approach to detect multiple types of DFs, including deepfakes from unknown generation methods such as DeepFake-in-the-Wild (DFW) videos. To better cope with unknown and unseen deepfakes, we introduce a Convolutional LSTM-based Residual Network (CLRNet), which adopts a unique model training strategy and explores spatial as well as the temporal information in a deepfakes. Through extensive experiments, we show that existing defense methods are not ready for real-world deployment. Whereas our defense method (CLRNet) achieves far better generalization when detecting various benchmark deepfake methods (97.57% on average). Furthermore, we evaluate our approach with a high-quality DeepFake-in-the-Wild dataset, collected from the Internet containing numerous videos and having more than 150,000 frames. Our CLRNet model demonstrated that it generalizes well against high-quality DFW videos by achieving 93.86% detection accuracy, outperforming existing state-of-the-art defense methods by a considerable margin. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/abs/10.1145/3442381.3449809"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; <a href="https://www.youtube.com/watch?v=RV_jA5lS7Ws"><img  alt="video" src="talk.svg" style="right: 15px; position:relative; top:5px; width: 20px; height: 18px;"></a></small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="odtr.png" style="max-height:200px;width: 360px; margin-bottom:10px">
        </div>
    </div>
    <hr>


    <div style="display: flex;flex-direction: row;justify-content: space-between;">



        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>A Security Analysis of Blockchain-based DID Services</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Bong Gon Kim,
                                    Young-Seob Cho, Seok-hyun Kim, Hyoungshick Kim, and <b>Simon S. Woo</b> </i>
                            </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> IEEE Access, Jan
                                    2021 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>SCIE Q1 IF=4.09</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Decentralized
                                identifiers (DID) has shown great potential for sharing user identities across different
                                domains and services without compromising user privacy. DID is designed to enable the
                                minimum disclosure of the proof from a user’s credentials on a need-to-know basis with a
                                contextualized delegation. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://ieeexplore.ieee.org/document/9336711"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="secBlock.jpg" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>BertLoc: Duplicate Location Record Detection in a Large-Scale Location Dataset</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Sujin Park,
                                    Sangwon Lee, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> SAC: The 36th
                                    ACM/SIGAPP Symposium On Applied Computing, Gwangju, Korea, 2021. </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='blue'><u>BK Computer Science IF=1</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> In this work, we
                                propose BertLoc, a novel deep learning-based architecture to detect the duplicate
                                location represented in different ways (e.g., Cafe vs. Coffee House) and effectively
                                merge them into a single and consistent location record. BertLoc is based on
                                Multilingual Bert Model followed by BiLSTM and CNN to effectively compare and determine
                                whether given location strings are the same location or not. We evaluate BertLoc trained
                                with more than half a million location data used in real service in South Korea and
                                compare the results with other popular baseline methods. Our experimental results show
                                that BertLoc outperforms other popular baseline methods with 0.952 F1-score, and shows
                                great promise in detecting duplicate records in a large-scale location dataset. </small>
                        </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3412841.3441969"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; 
                                    <a
                                    href="https://www.youtube.com/watch?v=zYsJigpb_jc"><img  alt="video" src="talk.svg" style="right: 15px; position:relative; top:5px; width: 20px; height: 18px;"></a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="bertLoc.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>



    <h4 style="margin-top:40px"><b>2020</b></h4>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Image hashing algorithm to defend FGSM attacks on Neural Network</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Junyaup Kim,
                                    Siho Han and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Cyber Defence
                                    Next Generation Technology and Science Conference.(2020), March 2020 </b> </small>
                        </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> In this research, we
                                present a performance evaluation of existing image hashing algorithms on defending deep
                                learning models against adversarial attacks as an initial work to developing a new, time
                                efficient image hashing algorithm. Upon experimenting with existing image hashing
                                algorithms, we conclude that the wavelet hashing algorithm achieves the highest accuracy
                                (75%) when detecting images generated from Neural Networks attacked by the FGSM, with a
                                time complexity of 𝑂(𝑁). </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="jy.pdf"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a></small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="jy.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>


    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>오픈소스 기반 격자 방식 PQC 알고리즘 분석 (Open-Source Code Analysis on
                                Lattice-Based Post Quantum Cryptography)</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Minha Kim,
                                    Hakjun Moon and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>CISC-W, 2020 </b>
                            </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Currently used
                                cryptography algorithms like RSA are vulnerable to quantum computers and are at risk of
                                being deciphered in polynomial time. As the commercialization of quantum computers is
                                soon to be realized, there is an urgent need for developing post-quantum
                                cryptography(PQC) algorithms. In this paper, we analyze several lattice-based PQC
                                algorithms from NIST Post-Quantum Cryptography Standardization project and test them in
                                some representative security protocols to show their practicality. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="pqc.pdf"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="pqc.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">
        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Compensating for the Lack of Extra Training Data by Learning Extra Representation</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Hyeonseong Jeon,
                                    Siho Han, Sangwon Lee and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> 15th Asian
                                    Conference on Computer Vision (ACCV), Kyoto, Japan, 2020 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK Computer Science IF=1</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> We introduce a novel
                                framework, Extra Representation (ExRep), to surmount the problem of not having access to
                                the JFT-300M data by instead using ImageNet and the publicly available model that has
                                been pre-trained on JFT-300M. We take a knowledge distillation approach, treating the
                                model pre-trained on JFT-300M as well as on ImageNet as the teacher network and that
                                pre-trained only on ImageNet as the student network. Our proposed method is capable of
                                learning additional representation effects of the teacher model, bolstering the student
                                model’s performance to a similar level to that of the teacher model, achieving high
                                classification performance even without extra training data. </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://openaccess.thecvf.com/content/ACCV2020/html/Jeon_Compensating_for_the_Lack_of_Extra_Training_Data_by_Learning_ACCV_2020_paper.html"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; <a
                                    href="https://github.com/cutz-j/ExRep"><img  alt="github" src="github.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"></a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="ctle.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>ITAD: Integrative Tensor-based Anomaly Detection System for Reducing False Postives of
                                Satellite Systems</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Youjin Shin,
                                    Shahroz Tariq, Sangyup Lee, Myeong Shin Lee, Okchul Jung, Daewon Chung, and <b>Simon
                                        S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> CIKM ’20: The
                                    29th ACM International Conference on Information and Knowledge Management, Galway,
                                    Ireland </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK Computer Science IF=3</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Reducing false
                                positives while detecting anomalies is of growing importance for various industrial
                                applications and mission-critical infrastructures, including satellite systems.
                                Undesired false positives can be costly for such systems, bringing the operation to a
                                halt for human experts to determine if the anomalies are true anomalies that need to be
                                mitigated </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/abs/10.1145/3340531.3412716"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="itad.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">

        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>ZoomNet: Detecting Low-Quality Deepfakes In The Wild by Zooming In</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Sangyup Lee, <b>Simon S. Woo</b>, Jinhwan Kim, Okyeop Jeon </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Proceedings of the Korean Information Science Society Conference 2020 (한국법과학회 2020 추계학술대회) </b> </small> </p>
                    </tr>
                 
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Deepfakes have become a critical social problem, and detecting them is of utmost importance. Detecting high-quality deepfake videos from widely released datasets is more straightforward to detect than low-quality ones. Most of the prior research achieve above 90% accuracy for detecting the high-quality deepfake videos from the open dataset. However, in real life, many deepfake videos that are leaked through social networks such as YouTube and instant messaging applications are highly compressed. As a result, the distributed video's resolution becomes extremely lower, making the state-of-the-art detection methods harder. In this work, we propose ZoomNet, a practical framework to detect low-quality deepfakes with high accuracy. We build ZoomNet to have the ability to zoom into low-quality images effectively and can learn to distinguish deepfakes from real videos.
                            </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://scholar.google.com/"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a></small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="zoomnet_2020.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">

        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Who is Delivering My Food? Detecting Food Delivery Abusers using Variational Reward
                                Inference Networks</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> DaeYoung Yoon
                                    and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> CIKM ’20: The
                                    29th ACM International Conference on Information and Knowledge Management, Galway,
                                    Ireland </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK Computer Science IF=3</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> The recent paramount
                                success of the gig economy has introduced new business opportunities in different areas
                                such as food delivery service. However, there are food delivery ride abusers who break
                                the company rule by driving unauthorized vehicles that are not stated in the contract
                            </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3340531.3412750"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; 
                                    </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="yoon.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Can We Create a Cross-Domain Federated Identity for Industrial Internet of Things without
                                Google?</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Eunsoo Kim,
                                    Young-Seob Cho, Bedeuro Kim, Woojoong Ji, Seok-hyun Kim and <b>Simon S. Woo</b> </i>
                            </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> IEEE Internet of
                                    Things Magazine, 2020 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Providing a
                                cross-domain federated identity is essential for next-generation Internet services
                                because information about user identity should be seamlessly exchanged across different
                                domains for authentication and authorization. </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://ieeexplore.ieee.org/document/9319620"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; </small> </p>
                    </tr>

                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="bc.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Applying Deep Learning to Reconstruct Pottery from Thousands Shards,</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Keeyoung Kim,
                                    Jinseok Hong, Sang-Hoon Rhee and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> ECML-PKDD,
                                    Ghent, Belgium 2020 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>Acceptance Rate=28%</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href=""> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp;  </small> </p>
                    </tr>

                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>OC-FakeDect: Classifying Deepfakes Using One-class Variational Autoencoder</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Hasam Khalid and
                                    <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> IEEE Biometrics
                                    Council newsletter</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> An image forgery
                                method called Deepfakes can cause security and privacy issues by changing the identity
                                of a person in a photo through the replacement of his/her face with a computer-generated
                                image or another person’s face. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://openaccess.thecvf.com/content_CVPRW_2020/papers/w39/Khalid_OC-FakeDect_Classifying_Deepfakes_Using_One-Class_Variational_Autoencoder_CVPRW_2020_paper.pdf"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; <a href="https://fb.watch/5v0wiOGnsg/"><img  alt="video" src="talk.svg" style="right: 15px; position:relative; top:5px; width: 20px; height: 18px;"></a>  &nbsp;  <a href="http://ieee-biometrics.org/images/pdf/Vol35-Newsletter.pdf">letter</a>
                                </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="ocvae.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Forecasting Error Pattern-based Anomaly Detection in Multivariate Time Series</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Seoyoung Park*,
                                    Siho Han* and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> ECML-PKDD,
                                    Ghent, Belgium 2020 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>Acceptance Rate=28%</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> We propose novel
                                Functional Data Analysis (FDA) and Autoencoder-based approaches for anomaly detection in
                                the Secure Water Treatment (SWaT) dataset, which realistically represents a scaled-down
                                industrial water treatment plant. We demonstrate that our methods can capture the
                                underlying forecasting error patterns of the SWaT dataset generated by Mixture Density
                                Networks (MDNs). </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.researchgate.net/publication/349556890_Forecasting_Error_Pattern-Based_Anomaly_Detection_in_Multivariate_Time_Series"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  <a
                                    href="https://slideslive.com/38932309/forecasting-error-patternbased-anomaly-detection-in-multivariate-time-series?ref=speaker-39040-latest"><img  alt="video" src="talk.svg" style="right: 15px; position:relative; top:5px; width: 20px; height: 18px;"></a></small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="fepb.jpg" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>국내 딥페이크 기술 현황 및 제도적 대응방안 연구</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Sowon Jeon,
                                    Junhyung Kang, Jinhee Hwang and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> CISC-S, 2020
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>우수논문상</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> 최근 한국에서 ‘가짜 연예인 음란
                                동영상’ 및 ‘지인 능욕’에 사용되는 딥페이크(Deepfakes) 포르노 문제가 사회적인 이슈로 불거지고 있다. 딥페이크 기술은 인공지능 기술의 발전에 맞추어
                                더욱더 빠르게 발전하고 있으나 관련 규제와 대응방안이 부족한 실정이다. 따라서 본 논문에서는 딥페이크 기술의 현황과 딥페이크 관련 국내외 법적 규제 및
                                현행법의 한계점을 살펴보고, 이로부터 각 개인 및 기관의 역할과 대응방안을 제안한다. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href=""> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="sowon1.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>T-GD: Transferable GAN-generated Images Detection Framework</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Hyeonseong Jeon,
                                    Youngoh Bang, Junyaup Kim, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Thirty-seventh
                                    International Conference on Machine Learning (ICML), Vienna, Austria, 2020 </b>
                            </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>BK Computer Science IF=4, Acceptance Rate=18.48%</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> In this work, we
                                present the Transferable GAN-images Detection framework (T-GD), a robust transferable
                                framework for an effective detection of GAN-images. T-GD is composed of a teacher and a
                                student model that can iteratively teach and evaluate each other to improve the
                                detection performance. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://arxiv.org/abs/2008.04115"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> &nbsp; <a
                                    href="https://github.com/cutz-j/T-GD"><img  alt="github" src="github.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"></a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="tgd.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Real Time Localized Air Quality Monitoring and Prediction Through Mobile and Fixed IoT
                                Sensing Network</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Dan Zhang, and
                                    <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> IEEE Access, May
                                    2020 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>SCIE Q1 IF=4.09</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Air pollution and
                                its harm to human health has become a serious problem in many cities around the world.
                                In recent years, research interests in measuring and predicting the quality of air
                                around people has spiked. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://ieeexplore.ieee.org/document/9090830"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> 
                                    </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>CAN-ADF: The Controller Area Network Attack Detection Framework</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Shahroz Tariq,
                                    Sangyup Lee, Huy Kang Kim, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Elsevier
                                    Computers & Security, December 2020 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>SCIE Q1 IF=3.58</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> In recent years,
                                there has been significant interest in developing autonomous vehicles such as
                                self-driving cars. In-vehicle communications, due to simplicity and reliability, a
                                Controller Area Network (CAN) bus is widely used as the de facto standard to provide
                                serial communications between Electronic Control Units (ECUs) </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.sciencedirect.com/science/article/pii/S0167404820301292#:~:text=In%20this%20work%2C%20we%20propose,system%20for%20a%20CAN%20bus.&text=Our%20detection%20algorithm%20achieves%20accurate,CAN%20datasets%2C%20outperforming%20prior%20approach."> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="canadf.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>OC-FakeDect: Classifying Deepfakes Using One-class Variational Autoencoder</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Hasam Khalid and
                                    <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Workshop on
                                    Media Forensics, CVPR 2020, Monday, 15th June 2020, Seattle, USA </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> An image forgery
                                method called Deepfakes can cause security and privacy issues by changing the identity
                                of a person in a photo through the replacement of his/her face with a computer-generated
                                image or another person’s face. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://openaccess.thecvf.com/content_CVPRW_2020/papers/w39/Khalid_OC-FakeDect_Classifying_Deepfakes_Using_One-Class_Variational_Autoencoder_CVPRW_2020_paper.pdf"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> <a href="https://fb.watch/5v0wiOGnsg/"><img  alt="video" src="talk.svg" style="right: 15px; position:relative; top:5px; width: 20px; height: 18px;"></a></small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="ocvae.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Design and Evaluation of Enumeration Attacks on Package Tracking Systems</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Hanbin Jang,
                                    Woojung Ji, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The 25th
                                    Australasian Conference on Information Security and Privacy, Perth, Australia, 2020
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>Acceptance rate ~ = 20%</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Most shipping
                                companies provide a package tracking system where customers can easily track their
                                package delivery status when the package is being shipped. However, we present a
                                security problem called enumeration attacks against package tracking systems...</small>
                        </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://link.springer.com/chapter/10.1007/978-3-030-55304-3_28"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>How do we Create a Fantabulous Password?</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The 29th Web
                                    Conference (WWW), Taipei, Taiwan, 2020 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK Computer Science IF=4, Acceptance Rate=19%</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> </small> Although
                            pronounceability can improve password memorability, most existing password generation
                            approaches have not properly integrated the pronounceability of passwords in their designs.
                            In this work, we demonstrate several shortfalls of current pronounceable password generation
                            approaches, and then propose, ProSemPass, a new method of generating passwords that are
                            pronounceable and semantically meaningful. </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3366423.3380222"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>
                                     </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>I've Got Your Packages: Harvesting customers' delivery order data using package tracking
                                number enumeration attacks</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>,Hanbin Jang, Woojung Ji and Hyoungshick Kim </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The 29th Web
                                    Conference (WWW), Taipei, Taiwan, 2020 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK Computer Science IF=3, Acceptance Rate=19%</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> A package tracking
                                number (PTN) is widely used to monitor and track a shipment. Through the lenses of
                                security and privacy, however, a package tracking number can possibly reveal certain
                                personal information, leading to security and privacy breaches. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3366423.3380062"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> 
                                     </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>FDFtNet: Facing Off Fake Images using Fake DetectionFine-tuning Network</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Hyeonseong
                                        Jeon, Youngoh Bang, and Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> SEC 2020
                                    International Conference on Information Security and Privacy Protection (IFIP-SEC),
                                    Solvenia, Sept 2020</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK Computer Science IF=1</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Creating fake images
                                and videos such as "Deepfake" has become much easier these days due to the advancement
                                in Generative Adversarial Networks (GANs). Moreover, recent research such as the
                                few-shot learning can create highly realistic personalized fake images with only a few
                                images.</small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://arxiv.org/abs/2001.01265"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> 
                                     </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>PassTag: A Graphical-Textual Hybrid Fallback Authentication System</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Joon Kuy
                                    Han, Xiaojun Bi, Hyoungshick Kim, and  <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> ASIACCS: The
                                    13th ACM Asia Conference on Computer and Communications Security, Taipei, Taiwan,
                                    2020.</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK Computer Science IF=1</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Designing a fallback
                                authentication mechanism that is both memorable and strong is a challenging problem
                                because of the trade-off between usability and security. Security questions are
                                popularly used as a fallback authentication method for password recovery. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3366423.3380222"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> 
                                     </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Tale of Two Browsers: Understanding Users' Web Browser Choices in South Korea</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Jihye Woo, Ji
                                    Won Choi, Soyoon Jeon, Joon Han, Hyoungshick Kim, and <b>Simon S. Woo</b> </i>
                            </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> AsiaUSEC, Feb.
                                    2020 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Internet users in
                                South Korea seem to have clearly different web browser choices and usage patterns
                                compared to the rest of the world, heavily using Internet Explorer (IE) or multiple
                                browsers.</small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://link.springer.com/chapter/10.1007/978-3-030-54455-3_1"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>CANTransfer: Transfer Learning based Intrusion Detection on a Controller Area Network
                                using Convolutional LSTM Network</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Shahroz Tariq,
                                    Sangyup Lee, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The 35th
                                    ACM/SIGAPP Symposium On Applied Computing (SAC), Brno, Czech Republic, March 2020
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK Computer Science IF=1</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> In-vehicle
                                communications, due to simplicity and reliability, a Controller Area Network (CAN) bus
                                is widely used as the de facto standard to provide serial communications between
                                Electronic Control Units (ECUs). </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3341105.3373868"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> 
                                    </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="cantransfer.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <h4 style="margin-top:40px"><b>2019</b></h4>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Designing for fallible humans</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Jelena Mirkovic
                                    and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> 2019 IEEE Humans
                                    and Cyber Security (HACS) workshop in conjunction with IEEE CogMI (Cognitive Machine
                                    Intelligence), IEEE CIC (Collaboration and Internet Computing) and IEEE TPS (Trust,
                                    Privacy and Security of Intelligence Systems, and Applications) Los Angeles,
                                    California, USA, December 14, 2019.</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Security and privacy
                                solutions today are designed with an assumption of a rational user. System designers
                                assume that the user is able to review all information shown to them, consider it along
                                with other information they have, and user priorities, and make a conscious, rational
                                decision in their best interest. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://ieeexplore.ieee.org/document/8998513"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> 
                                    
                                     </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Poster: Classifying Genuine Face images from Disguised Face Images</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Junyaup Kim,
                                    Siho Han, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> 2019 IEEE
                                    International conference on Big Data (IEEE BigData 2019), Los Angeles, CA, USA</b>
                            </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> In this preliminary
                                work, we aim to detect a target person's face from different similar individuals,
                                Doppelgangers, leveraging the dataset from Disguised Faces in the Wild (DFW) 2018. We
                                use well-known off-the-shelf face detection classifiers, such as ShallowNet, VGG-16, and
                                Xception to evaluate the classification performance. In order to further improve the
                                detection performance, we apply data augmentation. Our preliminary result shows that the
                                Xception model can classify one from different individuals with a 62% accuracy. </small>
                        </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://ieeexplore.ieee.org/abstract/document/9005683"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> 
                                    
                            </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="cgfi.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Poster: Nickel to Lego: Using Foolgle to Create Adversarial Examples to fool Google Cloud
                                Speech-to-Text API,</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Joon Kuy Han,
                                    Hyoungshick Kim and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The 26th ACM
                                    Conference on Computer and Communications Security, London, UK, 2019</b> </small>
                        </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Many companies offer
                                automatic speech recognition or Speech-to-Text APIs for use in diverse applications.
                                However, audio classification algorithms trained with deep neural networks (DNNs) can
                                sometimes misclassify adversarial examples, posing a significant threat to critical
                                applications. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3319535.3363264"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>
                                     </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Deep Learning for Blast Furnaces: Skip-Dense Layers Deep Learning Model to Predict the
                                Remaining Time to Close Tap-holes for Blast Furnaces</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Keeyoung Kim,
                                    Byeongrak Seo, Sang-Hoon Rhee, Seungmoon Lee, and <b>Simon S. Woo</b> </i> </small>
                        </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> CIKM'19,
                                    Beijing, China, Nov, 2019</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>Acceptance rate=21%, BK Computer Science IF=3</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Manufacturing steel
                                requires extremely challenging industrial processes. In particular, predicting the exact
                                time instance of opening and closing tap-holes in a blast furnace has a great influence
                                on steel production efficiency and operating cost, in addition to human safety. </small>
                        </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3357384.3357803"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>
                                     </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>FakeTalkerDetect: Effective and Practical Realistic Neural Talking Head Detection with a
                                Highly Unbalanced Datase</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Hyeonseong Jeon,
                                    Youngoh Bang, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> 10th
                                    International Workshop on Human Behavior Understanding (HBU), held in conjunction
                                    with ICCV'19 Nov, 2019 - Seoul, S. Korea</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Detecting realistic
                                fake images and videos is an increasingly important and urgent problem because they can
                                be
                                maliciously used. In this work, we propose FakeTalkerDetect, which is based on siamese
                                networks to detect the recently proposed realistic talking head with few-shot learning.
                            </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.researchgate.net/publication/338187408_FakeTalkerDetect_Effective_and_Practical_Realistic_Neural_Talking_Head_Detection_with_a_Highly_Unbalanced_Dataset"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Tensor Decomposition for Anomaly Detection in Space</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Youjin Shin,
                                    Sangyup Lee, Shahroz Tariq, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Workshop on
                                    Tensor Methods for Emerging Data Science Challenges (TMEDSC), held in conjunction
                                    with KDD'19 Aug 5, 2019 - Anchorage, Alaska, USA</b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://milets19.github.io/papers/milets19_poster_6.pdf"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> 
                                    
                            </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="tdfad.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Contextual Anomaly Detection by Correlated Probability Distributions using
                                Kullback-Leibler Divergence</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Jinwoo Cho,
                                    Shahroz Tariq, Sangyup Lee, Young Geun Kim, Jeong-Han Yun, Jonguk Kim, Hyoung Chun
                                    Kim and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> 5th Workshop on
                                    Mining and Learning from Time Series, held in conjunction with KDD'19 Aug 5, 2019 -
                                    Anchorage, Alaska, USA</b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3292500.3330776"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> 
                                    </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="cad.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Detecting Anomalies in Space using Multivariate Convolutional LSTM with Mixtures of
                                Probabilistic PCA</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Shahroz Tariq,
                                    Sangyup Lee, Youjin Shin, Myeong Shin Lee, Okchul Jung, Daewon Chung, and <b>Simon
                                        S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> ACM SIG KDD,
                                    Alaska, USA, 2019.</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK Computer Science IF=4</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Detecting an anomaly
                                is not only important for many terrestrial applications on Earth but also for space
                                applications. Especially, satellite missions are highly risky because unexpected
                                hardware and software failures can occur due to sudden or unforeseen space environment
                                changes. </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href=""> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> 
                                     </small> </p>
                    </tr>

                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="dais.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Understanding Users Risk Perceptions about Personal Health Records Shared on Social
                                Networking Services</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Yuri Son,
                                    Geumhwan Cho, Hyoungshick Kim and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> ASIACCS: The
                                    12th ACM Asia Conference on Computer and Communications Security, Auckland, New
                                    Zealand, 2019</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK Computer Science IF=1, Acceptance Rate = 22.5%</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> To understand users'
                                risk perceptions about sharing their PHR on SNS, we first conducted a qualitative user
                                study by interviewing 16 participants. Next, we conducted a large-scale online user
                                study with 497 participants in the U.S. to validate our qualitative results from the
                                first study. </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3321705.3329838"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  
                                     </small>
                        </p>
                    </tr>

                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>You Walk, We Authenticate: Lightweight Seamless Authentication based on Gait in Wearable
                                IoT Systems</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Pratik Musale,
                                    Duin Baek, Nuwan Werellagama, <b>Simon S. Woo</b>, and and Bong Jun Choi </i>
                            </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> IEEE Access,
                                    Early Access, 2019</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>SCIE Q1 IF= 3.557</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> With a plethora of
                                wearable IoT devices available today, we can easily monitor human activities, many of
                                which are unconscious or subconscious. Interestingly, some of these activities exhibit
                                distinct patterns for each individual, which can provide an opportunity to extract
                                useful features for user authentication. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://ieeexplore.ieee.org/document/8672772"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> 
                                     </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>What Is in Your Password? Analyzing Memorable and Secure Passwords using a Tensor
                                Decomposition</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Youjin Shin and
                                    <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The Web
                                    Conference (WWW), May 2019</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK Computer Science 우수학회 IF=3, Acceptance Rate 19.9% </u>
                                    </font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> In the past, there
                                have been several studies in analyzing password strength and structures. However, there
                                are still many unknown questions to understand what really makes passwords both
                                memorable and strong. In this work, we aim to answer some of these questions by
                                analyzing password dataset through the lenses of data science and machine learning
                                perspectives. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3308558.3313690"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Using Episodic Memory for User Authentication</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, Le Xiao, Ron Artstein, Elsi Kaiser, and Jelena Mrikovic </i> </small>
                        </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> ACM Transactions
                                    on Transactions on Privacy and Security (TOPS), January 2019</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>SCIE Q1 IF=2.1</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Passwords are widely
                                used for user authentication, but they are often difficult for a user to recall, easily
                                cracked by automated programs, and heavily reused. Security questions are also used for
                                secondary authentication. They are more memorable than passwords, because the question
                                serves as a hint to the user, but they are very easily guessed. We propose a new
                                authentication mechanism, called "life-experience passwords (LEPs)." </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3308992"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>GAN is a Friend or Foe? A Framework to Detect Various Fake Face Images</b></a>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Shahroz Tariq,
                                    Sangyup Lee, Youjin Shin, Ho Young Kim, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> ACM SAC Cyprus
                                    April 2019</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK Computer Science 우수학회 IF=1, Acceptance Rate 25%</u>
                                    </font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Creating fake images
                                such as replacing one's face with other person's face has become much easier due to the
                                advancement of sophisticated image editing tools. In addition, Generative Adversarial
                                Networks (GANs) enable creating natural looking human faces. However, fake images can
                                cause many potential problems, as they can be misused to abuse information, hurt people,
                                and generate fake identification. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3297280.3297410"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="ganfof.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <h4 style="margin-top:40px"><b>2018</b></h4>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Design and Evaluation of 3D CAPTCHAs</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Elsevier
                                    Computers & Security, December 2018</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>SCIE Q1 IF=3.06</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Most current 2D
                                CAPTCHAs are vulnerable to automated character recognition attacks and the latest
                                attacks can successfully break the 2D text CAPTCHAs at a rate of more than 90%. In this
                                work, we present two novel 3D CAPTCHAs, which are more secure than current 2D text
                                CAPTCHAs against automated character recognition attacks. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.sciencedirect.com/science/article/pii/S0167404818301238"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> 
                                    </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Poster: Memorability and Security of Image and Text Integrated Authentication
                                System</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Joonkyu Han and
                                    <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The 34th Annual
                                    Computer Security Applications Conference (ACSAC)</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>Puerto Rico, USA, 2018</font>
                                </b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href=""> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Evaluating and Breaking Naver’s Audio CAPTCHA using Off-the-Shelf Speech-to-text
                                APIs</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Soyoon Jeon,
                                    Jihye Woo, Ji Won Choi, Hyoungshick Kim, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Conference on
                                    Information Security and Cryptography 2017 Winter (CISC-W 2018) Seoul, Korea,
                                    2018</b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href=""> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Understanding Users’ Perception on Digital Certificate and Their Web Browser Usages in
                                Korea</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Jihye Woo,
                                    Soyoon Jeon, Ji Won Choi, Hyoungshick Kim, and <b>Simon S. Woo</b> </i> </small>
                        </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Conference on
                                    Information Security and Cryptography 2017 Winter (CISC-W 2018) Seoul, Korea,
                                    2018</b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href=""> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Password typographical error resilience in honey encryption</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> H. Choi, J.
                                    Jeong,<b>Simon S. Woo</b>, K. Kang, and J. Hur </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Elsevier
                                    Computers & Security, October 2018</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>SCIE Q1 IF=2.86</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Honey encryption
                                (HE) is a novel password-based encryption scheme that is secure against brute-force
                                attacks even if users’ passwords have min-entropy. However, in HE, decryption with an
                                incorrect key produces fake messages that appear valid. Hence, password typographical
                                errors may confuse even legitimate users. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.sciencedirect.com/science/article/pii/S0167404818311246#:~:text=Honey%20encryption%20(HE)%20is%20a,may%20confuse%20even%20legitimate%20users."> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Poster: Adversarial Product Review Generation with Word Replacements</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Yimin Zhu and
                                    <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> 25th ACM
                                    Conference on Computer and Communications Security (CCS 2018), Toronto, USA,
                                    2018</b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Machine learning
                                algorithms including Deep Neural Networks (DNNs) have shown great success in many
                                different areas. However, they are frequently susceptible to adversarial examples, which
                                are maliciously crafted inputs to fool machine learning classifiers. On the other hand,
                                humans cannot distinguish between non-adversarial and adversarial inputs. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3243734.3278492"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> 
                                    </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="aprg.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Detecting In-Vehicle CAN Message Attacks using Heuristics and RNNs</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Shahroz Tariq,
                                    Sangyup Lee, Huy Kang Kim, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> 3rd
                                    International workshop on Information & Operational Technology (IT & OT) security
                                    systems (IOSec 2018), co-located with 21st International Symposium on Research in
                                    Attacks, Intrusions and Defenses (RAID 2018), Crete, Greece, Sept 2018 </b> </small>
                        </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> In vehicle
                                communications, due to simplicity and reliability, a Controller Area Network (CAN) bus
                                is used as the de facto standard to provide serial communication between Electronic
                                Control Units (ECUs). However, prior research reveals that several network-level attacks
                                can be performed on the CAN bus due to the lack of underlying security mechanism.
                            </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://link.springer.com/chapter/10.1007/978-3-030-12085-6_4"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="dican.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Detecting Both Machine and Human Created Fake Face Images In the Wild</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Shahroz Tariq,
                                    Sangyup Lee, Youjin Shin, Ho Young Kim, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> 2nd
                                    International Workshop on Multimedia Privacy and Security (MPS 2018), co-located
                                    with 25th ACM Conference on Computer and Communications Security (CCS 2018),
                                    Toronto, USA, 2018 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Due to the
                                significant advancements in image processing and machine learning algorithms, it is much
                                easier to create, edit, and produce high quality images. However, attackers can
                                maliciously use these tools to create legitimate looking but fake images to harm others,
                                bypass image detection algorithms, or fool image recognition classifiers. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3267357.3267367"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="dbmh.png" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>GuidedPass: Guiding users to create both more memorable and strong passwords</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b> and and Jelena Mirkovic </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> 21st
                                    International Symposium on Research in Attacks, Intrusions and Defenses (RAID 2018),
                                    Crete, Greece, Sept 2018 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK우수학회 IF=2, Acceptance Rate 22.8% </u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Password meters and
                                policies are currently the only tools helping users to create stronger passwords.
                                However, such tools often do not provide consistent or useful feedback to users, and
                                their suggestions may decrease memorability of resulting passwords. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.researchgate.net/publication/327469039_GuidedPass_Helping_Users_to_Create_Strong_and_Memorable_Passwords_21st_International_Symposium_RAID_2018_Heraklion_Crete_Greece_September_10-12_2018_Proceedings"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>

    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Poster: Leveraging Semantic Transformation to Investigate Password Habits and Their
                                Causes</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Ameya
                                    Hanesamgar, <b>Simon S. Woo</b>, Chris Kanich, and Jelena Mirkovic </i> </small>
                        </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Usenix The
                                    Fourteenth Symposium on Usable Privacy and Security (SOUPS 2018), Baltimore, USA,
                                    2018 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> It is no secret that
                                users have difficulty choosing and remembering strong passwords, especially when asked
                                to choose different passwords across different accounts. While research has shed light
                                on password weaknesses and reuse, less is known about user motivations for following bad
                                password practices. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3173574.3174144"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>When George Clooney is not George Clooney: Using GenAttack to Deceive Amazon’s and Naver’s
                                Celebrity Recognition APIs</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Keeyoung Kim and
                                    <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> 33rd IFIP TC-11
                                    SEC 2018 International Conference on Information Security and Privacy Protection
                                    (IFIP-SEC), Poznan, Poland, Sept 2018 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK우수학회 IF=1, Acceptance Rate 36% </u>, Best Student Paper
                                        Nominated</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> In recent years,
                                significant advancements have been made in detecting and recognizing contents of images
                                using Deep Neural Networks (DNNs). As a result, many companies offer image recognition
                                APIs for use in diverse applications. However, image classification algorithms trained
                                with DNNs can misclassify adversarial examples, posing a significant threat to critical
                                applications. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://link.springer.com/chapter/10.1007/978-3-319-99828-2_25"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Generating Adversarial Images using Genetic Algorithm</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Keeyoung Kim and
                                    <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The Second
                                    International Workshop on The Bright and Dark Sides of Computer Vision: Challenges
                                    and Opportunities for Privacy and Security (CV-COPS2018) In conjunction with the
                                    IEEE CVPR 2018 , Salt Lake City, USA, June 2018 </b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.researchgate.net/publication/339840424_Generating_Adversarial_Images_using_Genetic_Algorithm"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Poster: I can’t hear this because I am human: A novel design of audio CAPTCHA
                                system</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Jusop Choi,
                                    Taekkyung Oh, William Aiken, <b>Simon S. Woo</b> and Hyoungshick Kim </i> </small>
                        </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The 11th ACM
                                    Asia Conference on Computer and Communications Security (ACM ASIACCS), Incheon,
                                    Korea, 2018 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> A CAPTCHA
                                (Completely Automated Public Turing test to tell Computers and Humans Apart) provides
                                the first line of defense to protect websites against bots and automatic crawling.
                                Recently, audio-based CAPTCHA systems are started to use for visually impaired people in
                                many internet services. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3196494.3201590"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Benefits and Challenges of Long Term Self-Tracking to Prevent Lonely Deaths and Detect
                                Signs of Life</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> A Short Workshop
                                    on Next Steps Towards Long Term Self Tracking at ACM SIG CHI2018, April, 2018,
                                    Montreal, Canada </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> We explore the
                                benefit of a new long-term self-tracking application for the elderly population. In the
                                last few years, there has been a significant increase in number of people dying alone or
                                remaining undiscovered for a long period time in Korea and Japan. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="http://longtermtracking.offis.de/wp-content/uploads/2018/03/Woo.pdf"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Leveraging Semantic Transformation to Investigate Password Habits and Their Causes</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Ameya
                                    Hanesamgar, <b>Simon S. Woo</b>, Chris Kanich, and Jelena Mirkovic </i> </small>
                        </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> ACM SIG CHI2018,
                                    April, 2018, Montreal, Canada </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u>BK우수학회 IF=4, Acceptance Rate 25.7%</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> It is no secret that
                                users have difficulty choosing and remembering strong passwords, especially when asked
                                to choose different passwords across different accounts. While research has shed light
                                on password weaknesses and reuse, less is known about user motivations for following bad
                                password practices. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/3173574.3174144"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Memorablity and Security of Different Passphrase Generation Methods</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, and Jelena Mirkovic </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Review of KIISC
                                    (정보보호학회지), Feb. 2018 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Passphrases are
                                considered to be more secure than passwords since they are longer than passwords.
                                However, users choose predictable word patterns and common phrases to make passphrases
                                memorable, which in turn significantly lowers security. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE07399563"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Survey on Current Password Composition Policies</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, Kyeong Joo Jung, and Bong Jun Choi </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Review of KIISC
                                    (정보보호학회지), Feb. 2018 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Textual passwords
                                are widely used for accessing online accounts. Despite the problems of current textual
                                passwords, research has shown that there is no other strong alternatives for a textual
                                password due to its simplicity. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE07399565"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>


    <h4 style="margin-top:40px"><b>2017</b></h4>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Lightweight Authentication for IoT</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Pratik Musale,
                                    Duin Baek, <b>Simon S. Woo</b>, Bong Jun Choi </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Proc. ACM
                                    CoNEXT, Seoul, South Korea, Dec. 2017. (Student Workshop) </b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href=""> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Toward Machine Generated Passwords</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, Wenzhi Li, and, Hyeran Jeon </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Conference on
                                    Information Security and Cryptography 2017 Winter (CISC-W), Seoul, Korea, Dec. 2017
                                    (Best paper (우수 논문상)) </b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href=""> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Computer Vision Attacks against 3D CAPTCHAs</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The First
                                    International Workshop on The Bright and Dark Sides of Computer Vision: Challenges
                                    and Opportunities for Privacy and Security (CV-COPS2017) In conjunction with the
                                    IEEE CVPR 2017 , Honolulu, USA, July 2017 </b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href=""> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Life-Experience Passwords (LEPs)</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, Jelena Mirkovic, Ron Artstein, and Elsi Kaiser </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Usenix The
                                    Thirteenteenth Symposium on Usable Privacy and Security (SOUPS 2017), Santa Clara,
                                    USA, July 2017 </b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/2991079.2991107"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <h4 style="margin-top:40px"><b>2016</b></h4>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Improving Recall and Security of Passphrases Through Use of Mnemonics</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b> and Jelena Mirkovic </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Proceedings of
                                    the 10th International Conference on Passwords (Passwords), Bochum, Germany, 2016
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Passphrases are
                                regarded as more secure than passwords because they are longer than passwords. Yet,
                                users use predictable word patterns and common phrases to make passphrases memorable,
                                which in turn significantly lowers security. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.semanticscholar.org/paper/Improving-Recall-and-Security-of-Passphrases-Use-of-Woo-Mirkovic/308e48f46bdcde59f1224fe178d36bd242a542cd"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Life Experience Passwords (LEPs)</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, Jelena Mirkovic, Elsi Kaiser, and Ron Artstein </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The 32nd Annual
                                    Computer Security Applications Conference (ACSAC), Los Angeles, 2016 </b> </small>
                        </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'><u> BK우수학회 IF=2, Acceptance Rate 22.8%</u></font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://dl.acm.org/doi/10.1145/2991079.2991107"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small>
                        </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Good Automatic Authentication Question Generation</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, Zuyao Li, and Jelena Mirkovic </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The 9th SIGGEN
                                    International Natural Language Generation Conference (INLG), Edinburgh, 2016 </b>
                            </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> We explore a novel
                                application of Question Generation (QG) for authentication use, where questions are
                                widely used to verify user identity for online accounts. In our approach, we prompt
                                users to provide a few sentences about their personal life events. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.aclweb.org/anthology/W16-6632.pdf"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a></small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Exploration of 3D Texture and Projection for New CAPTCHA Design</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, Jingul Kim, Duoduo Yu, and Beomjun Kim </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> The 17th World
                                    Conference on Information Security Applications (WISA), Jeju, 2016 </b> </small>
                        </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>Best Conference Paper (우수논문상)</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Most of current
                                text-based CAPTCHAs have been shown to be easily breakable. In this work, we present two
                                novel 3D CAPTCHA designs, which are more secure than current 2D text CAPTCHAs, against
                                automated attacks. Our approach is to display CAPTCHA characters onto 3D objects to
                                improve security. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://link.springer.com/chapter/10.1007/978-3-319-56549-1_30"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>



    <h4 style="margin-top:40px"><b>2015</b></h4>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Empirical Data Analysis on User Privacy and Sentiment in Personal Blogs</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b> and Harsha Manjunatha </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> 2nd ACM SIGIR
                                    Workshop on Privacy-Preserving Information Retrieval, Chilie, 2015 </b> </small>
                        </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href=""> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small>   </p>
                    </tr>

                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Engaging Novices in Cybersecurity Competitions: A Vision and Lessons Learned at ACM Tapia
                                2015</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Jelena Mirkovic,
                                    Aimee Tabor, <b>Simon S. Woo</b> and Portia Pusey </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> USENIX Summit on
                                    Gaming, Games, and Gamification in Security Education (3GSE), D.C, 2015 </b>
                            </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Cybersecurity
                                competitions are popular tools for attracting students to cybersecurity field. Yet, many
                                competitions require extensive preparation, strong coding skills and solid background
                                knowledge, not just in security, but also in system administration, networking and
                                operating systems. </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.usenix.org/conference/3gse15/summit-program/presentation/mirkovic"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>

                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>


    <h4 style="margin-top:40px"><b>2014</b></h4>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Optimal application allocation on multiple public clouds</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b> and Jelena Mirkovic </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Elsevier
                                    Computer Networks, February 2014. </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>SCIE Q1 IF=2.52</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Cloud computing
                                customers currently host all of their application components at a single cloud provider.
                                Single-provider hosting eases maintenance tasks, but reduces resilience to failures.
                                Recent research (Li et al., 2010) also shows that providers’ offers differ greatly in
                                performance and price, and no single provider is the best in all service categories.
                            </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.sciencedirect.com/science/article/abs/pii/S1389128614000371"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Life-Experice Passwords</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, Jelena Mikovic, Ron Artstein, and Elsi Kaiser </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Who are you?!
                                    Adventures in Authentication: ACM SOUPS-WAY Workshop, 2014, Menlo Park, CA </b>
                            </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Passwords are widely
                                used for user authentication, but they are often difficult for a user to recall, easily
                                cracked by automated programs and heavily reused. Security questions are also used for
                                secondary authentication. They are more memorable than passwords, but are very easily
                                guessed. We propose a new authentication mechanism, called "life-experience passwords
                                (LEPs)," which outperforms passwords and security questions, both at recall and at
                                security. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://cups.cs.cmu.edu/soups/2014/workshops/papers/lep_woo_12.pdf"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Poster: 3DOC: 3D Object CAPTCHA</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, and B. Kim </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Information
                                    Sciences Institute Graduate Student Symposium (ISI-GSS), Nov, 2014 (Best Student
                                    Paper) </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Current 2D CAPTCHA
                                mechanisms can be easily defeated by character recognition and segmentation attacks by
                                automated machines. Recently, 3D CAPTCHA schemes have been proposed to overcome the
                                weaknesses of 2D CAPTCHA for a few websites. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://openreview.net/forum?id=rkWY4b-dWS"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>3DOC: 3D Object CAPTCHA</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, and B. Kim </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> 23rd
                                    International World Wide Web (WWW) Conference, 2014 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Current 2D CAPTCHA
                                mechanisms can be easily defeated by character recognition and segmentation attacks by
                                automated machines. Recently, 3D CAPTCHA schemes have been proposed to overcome the
                                weaknesses of 2D CAPTCHA for a few websites. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.researchgate.net/publication/261961424_3DOC_3D_object_CAPTCHA"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Life Experience-Passwords</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, Jelena Mirkovic, and Elsi Kaiser </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Network and
                                    Distributed System Security (NDSS) Symposium, Feb, 2014 </b> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://cups.cs.cmu.edu/soups/2014/workshops/papers/lep_woo_12.pdf"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>


    <h4 style="margin-top:40px"><b>2011</b></h4>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Analysis of Proximity-1 Space Link Interleaved Time Synchronization Protocol</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo*</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> IEEE Globecom
                                    2011, Houston, TX </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b>
                                    <font color='purple'>Acceptance rate: 36%</font>
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> To synchronize
                                clocks between spacecraft in proximity, the Proximity-1 Space Link Interleaved Time
                                Synchronization (PITS) Protocol has been proposed. PITS is based on the NTP Interleaved
                                On-Wire Protocol and is capable of being adapted and integrated into CCSDS Proximity-1
                                Space Link with minimal modifications. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://ieeexplore.ieee.org/document/6134144"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>



    <h4 style="margin-top:40px"><b>2010</b></h4>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>MACHETE: A Protocol Evaluation Tool for Space- Based Networking Architecture and
                                Simulation</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> E. Jennings, J.
                                    Segui, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> AIAA SpaceOps
                                    2010, Huntsville, AL </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Space Exploration
                                missions requires the design and implementation of space networking that differs from
                                terrestrial networks. In a space networking architecture, interplanetary communication
                                protocols need to be designed, validated and evaluated carefully to support different
                                mission requirements. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://arc.aiaa.org/doi/10.2514/6.2010-2260"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a></small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Space Time Distribution and Synchronization Protocol Development for Mars Proximity
                                Link</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, David Mills, and J. Gao </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> AIAA SpaceOps
                                    2010 (Invited for Book Chapter) </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Time distribution
                                and synchronization in deep space network are challenging due to long propagation
                                delays, spacecraft movements, and relativistic effects. Further, the Network Time
                                Protocol (NTP) designed for terrestrial networks may not work properly in space </small>
                        </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://arc.aiaa.org/doi/10.2514/6.2010-2360"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>


    <h4 style="margin-top:40px"><b>2009</b></h4>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Space Communications and Navigation (SCaN) Network Simulation Tool Development and Its Use
                                Cases</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> E. Jennings, R.
                                    Borgen, C. Chevalier, E. Wesley, Sam Nguyen, John Segui, Tudor Stoenescu, Shin-Ywan
                                    Wang, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> AIAA, Modeling
                                    and Simulation Technologies (AIAA MST) Conference, 2009 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> In this work, we
                                focus on the development of a simulation tool to assist in analysis of current and
                                future (proposed) network architectures for NASA. Specifically, the Space Communications
                                and Navigation (SCaN) Network is being architected as an integrated set of new assets
                                and a federation of upgraded legacy systems. The SCaN architecture for the initial
                                missions for returning humans to the moon and beyond will include the Space Network (SN)
                                and the Near-Earth Network (NEN). </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.researchgate.net/publication/268556870_Space_Communications_and_Navigation_SCaN_Network_Simulation_Tool_Development_and_Its_Use_Cases"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Efficient File Sharing by multicast - P2P protocol using network coding and rank based
                                peer selection</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b> and Tudor Stoenescu </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> IEEE 69th
                                    Vehicular Technology Conference (IEEE VTC) 2009-Spring, Barcelona, Spain, April,
                                    2009 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> In this work, we
                                consider information dissemination and sharing in a highly dynamic peer-to-peer (P2P)
                                communication network. In particular, we explore a network coding technique for
                                transmission and a rank based peer selection (RBPS) method for network formation.
                            </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://ieeexplore.ieee.org/document/5073526"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <h4 style="margin-top:40px"><b>2008</b></h4>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Interfacing Space Communications and Navigation Network Simulation with Distributed System
                                Integration Laboratories (DSIL)</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Esther H.
                                    Jennings, Sam P. Nguyen, Shin-Ywan Wang, and <b>Simon S. Woo</b> </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> AIAA SpaceOps
                                    2008 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> NASA’s planned Lunar
                                missions will involve multiple NASA centers where each participating center has a
                                specific role and specialization. In this vision, the Constellation program (CxP)’s
                                Distributed System Integration Laboratories (DSIL) architecture consist of multiple
                                System Integration Labs (SILs), with simulators, emulators, testlabs and control centers
                                interacting with each other over a broadband network to perform test and verification
                                for mission scenarios. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://arc.aiaa.org/doi/10.2514/6.2008-3462"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Prioritized LT codes</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b> and Mike Cheng </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> IEEE Annual
                                    Conference on Information Sciences and Systems (CISS), Princeton, NJ, March 2008.
                                </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> It is common in data
                                transmissions that some information is more important than others. This is especially
                                true in space communications where mission critical information or science data are high
                                priority. In this work, we propose a simple yet constructive scheme to send high
                                priority data reliably and efficiently using Luby transform (LT) codes. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://ieeexplore.ieee.org/document/4558589"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>
    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>A Simulation Tool for ASCTA Microsensor Network Architecture</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b>, Esther Jennings, and Loren Clare </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> IEEE Aerospace
                                    Conference, Big Sky, MT, March, 2008 </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> Advances in
                                technology have made the large-scale deployment of low-cost networked sensors possible
                                for situational awareness. We developed a Simulation Tool for the Advanced Sensors
                                Collaborative Technology Alliance (ASCTA) Microsensor Network Architecture (STAMINA) to
                                evaluate the performance of networked sensor systems. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://ieeexplore.ieee.org/document/4526447"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a> </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>

    </div>
    <hr>

    <h4 style="margin-top:40px"><b>2007</b></h4>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>Improved In Situ Communications Using Network Coding</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> Mike Cheng,
                                    <b>Simon S. Woo</b>, Kar-Ming Cheung, Sam Dolinar, and Jon Hamkins </i> </small>
                        </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> Research and
                                    Technology Development Poster session, (R&TD), Pasadena, Nov, 2007 </b> </small>
                        </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href=""> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

    <h4 style="margin-top:40px"><b>2006</b></h4>
    <hr>

    <div style="display: flex;flex-direction: row;justify-content: space-between;">


        <div style="margin-left: 25px;margin-right: 10px;">
            <table>
                <thead>
                    <tr>
                        <a><b>CFDP Performance Over Weather-Dependent Ka-Band Channel</b></a>
                    </tr>
                </thead>
                <tbody>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <i> <b>Simon S.
                                        Woo</b> and Jay Gao </i> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> <b> AIAA SpaceOps
                                    2006, Rome, Italy </b> </small> </p>
                    </tr>
                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;"> <small> This study presents
                                an analysis of the delay performance of the CCSDS File Delivery Protocol (CFDP) over
                                weather-dependent Ka-band channel. The Ka-band channel condition is determined by the
                                strength of the atmospheric noise temperature, which is weather dependent. </small> </p>
                    </tr>

                    <tr>
                        <p style="margin-top: 0px;margin-bottom: 0px;text-align: justify;margin-left: 20px;"> <small> <a
                                    href="https://www.researchgate.net/publication/255624199_CFDP_Performance_over_Weather-Dependent_Ka-band_Channel"> <img  alt="paper" src="paper_grey.svg" style="right: 15px; position:relative; top:5px; width: 18px; height: 18px;"> </a>  </small> </p>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="col-lg-3" style="vertical-align: middle;display:flex;flex-direction:row;justify-content:center">
            <img src="" style="max-height: 225px;max-width: 360px; margin-bottom: 10px; height: auto;aspect-ratio: auto;">
        </div>
    </div>
    <hr>

</div>
<!-- 
<div class="divider"></div>
<div class="section">
    <h5>2018</h5>
    <div class="row">
<p> Simon S. Woo*, "Design and Evaluation of 3D CAPTCHAs", Elsevier Computers & Security, December 2018 (<b><font color='purple'>SCIE Q1 IF=3.06</font></b>) </p>
        
<p> Joonkyu Han and Simon S. Woo*, "Poster: Memorability and Security of Image and Text Integrated Authentication System," The 34th Annual Computer Security Applications Conference (ACSAC), Puerto Rico, USA, 2018 </p>

<p> Soyoon Jeon, Jihye Woo, Ji Won Choi, Hyoungshick Kim, and Simon S. Woo*, "Evaluating and Breaking Naver’s Audio CAPTCHA using Off-the-Shelf Speech-to-text APIs," Conference on Information Security and Cryptography 2017 Winter (CISC-W 2018), Seoul, Korea, 2018 </p>

<p> Jihye Woo, Soyoon Jeon, Ji Won Choi, Hyoungshick Kim, and Simon S. Woo*, "Understanding Users’ Perception on Digital Certificate and Their Web Browser Usages in Korea," Conference on Information Security and Cryptography 2017 Winter (CISC-W 2018), Seoul, Korea, 2018 (Best Paper, 국보연 원장상) </p>

<p> H. Choi, J. Jeong, Simon S Woo, K. Kang, and J. Hur, "Password typographical error resilience in honey encryption", Elsevier Computers & Security, October 2018 (<b><font color='purple'>SCIE Q1 IF=2.86</font></b>) </p>

<p> Yimin Zhu and Simon S. Woo* "Poster: Adversarial Product Review Generation with Word Replacements," 25th ACM Conference on Computer and Communications Security (CCS 2018), Toronto, USA, 2018 </p>

<p> Shahroz Tariq, Sangyup Lee, Huy Kang Kim, and Simon S. Woo* <strong>"Detecting In-Vehicle CAN Message Attacks using Heuristics and RNNs",</strong> 3rd International workshop on Information & Operational Technology (IT & OT) security systems (IOSec 2018), co-located with 21st International Symposium on Research in Attacks, Intrusions and Defenses (RAID 2018), Crete, Greece, Sept 2018 </p>

<p> Shahroz Tariq, Sangyup Lee, Youjin Shin, Ho Young Kim, and Simon S. Woo* <strong>"Detecting Both Machine and Human Created Fake Face Images In the Wild",</strong> 2nd International Workshop on Multimedia Privacy and Security (MPS 2018), co-located with 25th ACM Conference on Computer and Communications Security (CCS 2018), Toronto, USA, 2018 </p>

<p> Simon S. Woo* and Jelena Mirkovic "GuidedPass: Guiding users to create both more memorable and strong passwords", 21st International Symposium on Research in Attacks, Intrusions and Defenses (RAID 2018), Crete, Greece, Sept 2018 (<b><font color='blue'>Acceptance Rate 22.8%, BK우수학회 IF=2</font></b>). </p>

<p> Ameya Hanesamgar, Simon S. Woo*, Chris Kanich, and Jelena Mirkovic, "Poster: Leveraging Semantic Transformation to Investigate Password Habits and Their Causes," Usenix The Fourteenth Symposium on Usable Privacy and Security (SOUPS 2018), Baltimore, USA, 2018 </p>

<p> Keeyoung Kim and Simon S. Woo*, "When George Clooney is not George Clooney: Using GenAttack to Deceive Amazon’s and Naver’s Celebrity Recognition APIs", 33rd IFIP TC-11 SEC 2018 International Conference on Information Security and Privacy Protection (IFIP-SEC), Poznan, Poland, Sept 2018 (<b><font color='blue'>Acceptance Rate 36%, BK우수학회 IF=1, Best Student Paper Nominated</font></b>). </p>

<p> Keeyoung Kim and Simon S. Woo*, "Generating Adversarial Images using Genetic Algorithm", The Second International Workshop on The Bright and Dark Sides of Computer Vision: Challenges and Opportunities for Privacy and Security (CV-COPS2018) In conjunction with the IEEE CVPR 2018 , Salt Lake City, USA, June 2018. </p>

<p> Jusop Choi, Taekkyung Oh, William Aiken, Simon S. Woo and Hyoungshick Kim, “Poster: I can’t hear this because I am human: A novel design of audio CAPTCHA system”, The 11th ACM Asia Conference on Computer and Communications Security (ACM ASIACCS), Incheon, Korea, 2018 </p>

<p> Simon S. Woo*, "Benefits and Challenges of Long Term Self-Tracking to Prevent Lonely Deaths and Detect Signs of Life," A Short Workshop on Next Steps Towards Long Term Self Tracking at ACM SIG CHI2018, April, 2018, Montreal, Canada (pdf) </p>

<p> Ameya Hanesamgar, Simon S. Woo*, Chris Kanich, and Jelena Mirkovic, "Leveraging Semantic Transformation to Investigate Password Habits and Their Causes," ACM SIG CHI2018, April, 2018, Montreal, Canada (<b><font color='blue'>Acceptance Rate 25.7%, BK우수학회 IF=4</font></b>)(pdf) </p>

<p> Simon S. Woo*, and Jelena Mirkovic, "Memorablity and Security of Different Passphrase Generation Methods,"Review of KIISC (정보보호학회지), Feb. 2018 (pdf) </p>

<p> Simon S. Woo*, Kyeong Joo Jung, and Bong Jun Choi, "Survey on Current Password Composition Policies,"Review of KIISC (정보보호학회지), Feb. 2018 (pdf) </p>
    </div>
</div>

<div class="divider"></div>
<div class="section">
    <h5>2017</h5>
    <div class="row">

<p> Pratik Musale, Duin Baek, Simon S. Woo, Bong Jun Choi, “Lightweight Authentication for IoT,” Proc. ACM CoNEXT, Seoul, South Korea, Dec. 2017. (Student Workshop) </p>

<p> Simon S. Woo, Wenzhi Li, and, Hyeran Jeon, “Toward Machine Generated Passwords,” Conference on Information Security and Cryptography 2017 Winter (CISC-W), Seoul, Korea, Dec. 2017 (Best paper (우수 논문상)) </p>

<p> Simon S. Woo*, "Computer Vision Attacks against 3D CAPTCHAs", The First International Workshop on The Bright and Dark Sides of Computer Vision: Challenges and Opportunities for Privacy and Security (CV-COPS2017) In conjunction with the IEEE CVPR 2017 , Honolulu, USA, July 2017 (pdf). </p>

<p> Simon S. Woo, Jelena Mirkovic, Ron Artstein, and Elsi Kaiser, "Life-Experience Passwords (LEPs)", Usenix The Thirteenteenth Symposium on Usable Privacy and Security (SOUPS 2017), Santa Clara, USA, July 2017. </p>
    </div>
</div>
<div class="divider"></div>
<div class="section">
    <h5>2016</h5>
    <div class="row">
<p> Simon S. Woo* and Jelena Mirkovic. <strong> "Improving Recall and Security of Passphrases Through Use of Mnemonics" </strong>, Proceedings of the 10th International Conference on Passwords (Passwords), Bochum, Germany, 2016 <a href="../../raw/master/Publications/Improving Recall and Security of Passphrases Through Use of Mnemonics.pdf" download> (PDF) </a>
 </p>

<p> Simon S. Woo, Jelena Mirkovic, Elsi Kaiser, and Ron Artstein "Life Experience Passwords (LEPs)", The 32nd Annual Computer Security Applications Conference (ACSAC), Los Angeles, 2016 (<b><font color='blue'>Acceptance Rate 22.8%, BK우수학회 IF=2</font></b>) (pdf) </p>

<p> Simon S. Woo*, Zuyao Li, and Jelena Mirkovic, "Good Automatic Authentication Question Generation", The 9th SIGGEN International Natural Language Generation Conference (INLG), Edinburgh, 2016 (pdf) </p>

<p> Simon S. Woo, Jingul Kim, Duoduo Yu, and Beomjun Kim, "Exploration of 3D Texture and Projection for New CAPTCHA Design", The 17th World Conference on Information Security Applications (WISA), Jeju, 2016 (Best Conference Paper) (pdf) </p>
     </div>
</div>
<div class="divider"></div>
<div class="section">
    <h5>2015</h5>
    <div class="row">
<p> Simon S. Woo and Harsha Manjunatha, "Empirical Data Analysis on User Privacy and Sentiment in Personal Blogs", 2nd ACM SIGIR Workshop on Privacy-Preserving Information Retrieval, Chilie, 2015 (pdf) </p>

<p> Jelena Mirkovic, Aimee Tabor, Simon S. Woo, and Portia Pusey, "Engaging Novices in Cybersecurity Competitions: A Vision and Lessons Learned at ACM Tapia 2015", 2015 USENIX Summit on Gaming, Games, and Gamification in Security Education (3GSE), D.C, 2015 (pdf) </p>
    </div>
</div>
<div class="divider"></div>
<div class="section">
    <h5>2014</h5>
    <div class="row">
<p> Simon S. Woo and Jelena Mirkovic, "Optimal application allocation on multiple public clouds", Elsevier Computer Networks, February 2014. (<b><font color='purple'>SCIE Q1 IF=2.52</font></b>) (pdf) </p>

<p> Simon S. Woo, Jelena Mikovic, Ron Artstein, and Elsi Kaiser, "Life-Experice Passwords", Who are you?! Adventures in Authentication: ACM SOUPS-WAY Workshop, 2014, Menlo Park, CA (pdf) </p>

<p> Simon S. Woo, and B. Kim, "3D Object CAPTCHA", Information Sciences Institute Graduate Student Symposium (ISI-GSS), Nov, 2014 (Best Student Paper) </p>

<p> Simon S. Woo*, B. Kim, W. Jun, and J. Kim, "3DOC: 3D Object CAPTCHA", 23rd International World Wide Web (WWW) Conference, 2014 (Poster) </p>

<p> Simon S. Woo, Jelena Mirkovic, and Elsi Kaiser, "Life Experience-Passwords", Network and Distributed System Security (NDSS) Symposium, Feb, 2014 (Poster) </p>
    </div>
</div>
<div class="divider"></div>
<div class="section">
    <h5>2011</h5>
    <div class="row">
<p> Simon S. Woo*, "Analysis of Proximity-1 Space Link Interleaved Time Synchronization Protocol", IEEE Globecom 2011, Houston, TX (Acceptance rate: 36%) (pdf) </p>
    </div>
</div>

<div class="divider"></div>
<div class="section">
    <h5>2010</h5>
    <div class="row">
<p> E. Jennings, J. Segui, and Simon S. Woo*, "MACHETE: A Protocol Evaluation Tool for Space- Based Networking Architecture and Simulation", AIAA SpaceOps 2010, Huntsville, AL (pdf) </p>

<p> Simon S. Woo, David Mills, and J. Gao, "Space Time Distribution and Synchronization Protocol Development for Mars Proximity Link", AIAA SpaceOps 2010 (Invited for Book Chapter) (pdf) </p>
    </div>
</div>

<div class="divider"></div>
<div class="section">
    <h5>2009</h5>
    <div class="row">
<p> E. Jennings, R. Borgen, C. Chevalier, E. Wesley, Sam Nguyen, John Segui, Tudor Stoenescu, Shin-Ywan Wang, and Simon S. Woo, "Space Communications and Navigation (SCaN) Network Simulation Tool Development and Its Use Cases", AIAA, Modeling and Simulation Technologies (AIAA MST) Conference, 2009 (pdf) </p>

<p> Simon S. Woo* and Tudor Stoenescu, "Efficient File Sharing by multicast - P2P protocol using network coding and rank based peer selection",IEEE 69th Vehicular Technology Conference (IEEE VTC) 2009-Spring, Barcelona, Spain, April, 2009 (pdf) </p>
    </div>
</div>

<div class="divider"></div>
<div class="section">
    <h5>2008</h5>
    <div class="row">
<p> Esther H. Jennings, Sam P. Nguyen, Shin-Ywan Wang, and Simon S. Woo*, "Interfacing Space Communications and Navigation Network Simulation with Distributed System Integration Laboratories (DSIL)", AIAA SpaceOps 2008 (pdf) </p>

<p> Simon S. Woo* and Mike Cheng, "Prioritized LT codes", IEEE Annual Conference on Information Sciences and Systems (CISS), Princeton, NJ, March 2008. (pdf) </p>
 
<p> Simon S. Woo, Esther Jennings, and Loren Clare, "A Simulation Tool for ASCTA Microsensor Network Architecture", IEEE Aerospace Conference, Big Sky, MT, March, 2008 (pdf) </p>
    </div>
</div>
<div class="divider"></div>
<div class="section">
    <h5>2007</h5>
    <div class="row">
Mike Cheng, Simon S. Woo, Kar-Ming Cheung, Sam Dolinar, and Jon Hamkins, "Improved In Situ Communications Using Network Coding", Research and Technology Development Poster session, (R&TD), Pasadena, Nov, 2007 </p>
    </div>
</div>
<div class="divider"></div>
<div class="section">
    <h5>2006</h5>
    <div class="row">
<p> Simon S. Woo and Jay Gao, "CFDP Performance Over Weather-Dependent Ka-Band Channel", AIAA SpaceOps 2006, Rome, Italy (pdf) </p>
    </div>
</div> -->
