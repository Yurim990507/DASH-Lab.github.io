---
layout: page
title: News
permalink: /News/
---

<h1 class="page-title">{{ page.title | escape }}</h1>
<style>
        /* reset */
        /* 여백 초기화 */
              body,div,ul,li,dl,dd,dt,ol,h1,h2,h3,h4,h5,h6,input,fieldset,legend,p,select,table,th,td,tr,textarea,button,form,figure,figcaption{margin:0;padding:0;}
            
        /* a 링크 초기화 */
        a {color: #222; text-decoration: none;}
        a:hover {color: #2698cb;}

        /* 폰트 초기화 */
        body, input, textarea, select, button, table {font-family:  'Nanum Gothic', AppleSDGothicNeo-Regular,'Malgun Gothic','맑은 고딕',dotum,'돋움',sans-serif; color: #222; font-size: 13px; line-height: 1.6;}
        
        /* 폰트 스타일 초기화 */
        em,address {font-style: normal;}

        /* 블릿기호 초기화 */
        ul,li,ol {list-style: none;}

        /* 제목 태그 초기화 */
        h1,h2,h3,h4,h5,h6 {font-size: 13px; font-weight: normal;}
        
        /* 버튼 초기화 */
        button {border: 0;}
        
        /* 반응형 */
        img {width: 100%;}
        
        /* IR 효과 */
        .ir_pm {display:block; overflow:hidden; font-size:0; line-height:0; text-indent:-9999px;} /* 의미있는 이미지의 대체 텍스트를 제공하는 경우(Phark Method) */
        .ir_wa {display:block; overflow:hidden; position:relative; z-index:-1; width:100%; height: 100%;} /* 의미있는 이미지의 대체 텍스트로 이미지가 없어도 대체 텍스트를 보여주고자 할 때(WA IR) */
        .ir_su {overflow: hidden; position:absolute; width:0; height:0; line-height:0; text-indent:-9999px;} /* 대체 텍스트가 아닌 접근성을 위한 숨김 텍스트를 제공할 때 */
        
        /* margin, padding */
        .mt10 {margin-top: 10px !important;}
        .mt15 {margin-top: 15px !important;}
        .mt20 {margin-top: 20px !important;}
        .mt25 {margin-top: 25px !important;}
        .mt30 {margin-top: 30px !important;}
        .mt35 {margin-top: 35px !important;}
        .mt40 {margin-top: 40px !important;}
        .mt45 {margin-top: 45px !important;}
        .mt50 {margin-top: 50px !important;}

        /* style */
        /* 레이아웃 */
        body {background: url(img/header_bg.jpg) repeat-x center top;}
        #header {  }
        #nav {background-color: #f6fdff;}
        #title {background-color: #eaf7fd;}
        #contents .container {border-right: 1px solid #dbdbdb; border-left: 1px solid #dbdbdb;}
        #cont_left {float: left; width: 250px;}
        #cont_center {
            overflow: hidden; 
            margin-right: 250px; 
            min-height: 1300px; 
            border-right: 1px solid #dbdbdb;
            border-left: 1px solid #dbdbdb;
        }
        #cont_right {position: absolute; right: 0; top: 0px; width: 250px;}
        #footer {border-top: 1px solid #dbdbdb;}

        /* 컨테이너 */
        .container {position: relative; width: 1200px; margin: 0 auto; /* background: rgba(0,0,0,0.3) */}

        /* 헤더 */
        .header {height: 327px;}
        .header .header_menu {text-align: right;}
        .header .header_menu a {color: #fff; padding: 8px 0 6px 10px; display: inline-block; transition: color 0.3s ease; font-family: 'Abel', sans-serif;}
        .header .header_menu a:hover {color: #ccc;}
        
        .header .header_tit { text-align: center; text-transform: uppercase; margin-top: 55px; font-family: 'Abel', sans-serif;}
        .header .header_tit h1 {
            font-size: 30px; 
            color: #fff; 
            background: #51b0dc; 
            display: inline-block; 
            padding: 5px 30px 5px 30px; 
            letter-spacing: 2px; 
            font-weight: 900;
            transition: box-shadow 0.25s ease-in-out;
        }
        .header .header_tit h1:hover {
            box-shadow: 
                inset -9em 0 0 0 #257FAC, 
                inset 9em 0 0 0 #257FAC;
        }
        .header .header_tit a {
            font-size: 16px; 
            color: #fff; 
            background: #4a9abf;  
            display: inline-block; 
            padding: 10px 20px 10px 20px; 
            margin-top: -7px; 
            transition: box-shadow 0.3s ease-in-out;
        }
        .header .header_tit a:hover {
            box-shadow: 
                0 0 0 5px rgba(75,154,191,0.9) inset,
                0 0 0 100px rgba(0,0,0,0.1) inset;
        }
        
        .header .header_icon {text-align: center; margin-top: 40px; padding-bottom: 45px;}
        .header .header_icon li {display: inline; margin: 0 2px;}
        .header .header_icon li a {
            position: relative;
            background-color: #3192bf;
            border-radius: 50%;
            width: 60px; 
            height: 60px;  
            color: #fff;
            display: inline-block;
            font-size: 35px;
            line-height: 60px;
            transition: all 0.3s ease;
        }
        .header .header_icon li a span {
            position: absolute; 
            opacity: 0;
            left: 50%; top: -40px;
            transform: translateX(-50%);
            font-size: 12px;
            line-height: 1.6;
            background: #3192bf; 
            padding: 3px 9px;
            border-radius: 6px 0;
            transition: all 0.3s ease;
        }
        .header .header_icon li a span:before {
            content: '';
            position: absolute;
            left: 50%; bottom: -5px;
            margin-left: -5px;
            border-top: 5px solid #3192bf;
            border-left: 5px solid transparent;
            border-right: 5px solid transparent;
        }
        .header .header_icon li a:hover span {
            opacity: 1;
            top: -33px;
        }
        .header .header_icon li a:hover {
            box-shadow: 
                0 0 0 3px rgba(75,154,191,0.9) inset,
                0 0 0 100px rgba(0,0,0,0.1) inset;
        }
        
        /* 전체 메뉴 */
        .nav {overflow: hidden; padding: 25px 0; display: none;}
        .nav > div {float: left; width: 40%;}
        .nav > div:last-child {width: 20%;}
        .nav > div ol {overflow: hidden;}
        .nav > div li {float: left; width: 50%; position: relative; padding-left: 8px; box-sizing: border-box;}
        .nav > div:last-child li {width: 100%;}
        .nav > div li a {position: relative;}
        .nav > div li:before {
            content: '';
            width: 3px; height: 3px;
            background-color: #25a2d0;
            border-radius: 50%;
            position: absolute; left: 0; top: 8px;
        }
        .nav > div h3 {
            font-size: 18px; 
            color: #25a2d0; 
            font-weight: bold; 
            margin-bottom: 4px;
        }
        .nav > div li a:after {
            content: '';
            display: inline-block;
            width: 0;
            height: 1px;
            position: absolute;
            bottom: 0;
            left: 0;
            background: #25a2d0;
            transition: all .2s ease-out;
        }
        .nav > div li:hover a:after {width: 100%;}
        
        /* 타이틀 */
        .title {position: relative; text-align: center; }
        .title h2 {font-family: 'Nanum Brush Script', cursive; font-size: 39px; color: #0093bd; padding: 5px 0;}
        .title .btn {
            position: absolute; right: 0; top: 5px;
            width: 60px; 
            height: 60px; 
            line-height: 60px; 
            background: #3192bf; 
            color: #fff;
            font-size: 35px; 
            border-radius: 50%;
            transition: all 0.3s ease;
        }
        .title .btn:hover {
            box-shadow: 
                0 0 0 3px rgba(75,154,191,0.9) inset,
                0 0 0 100px rgba(0,0,0,0.1) inset;
        }
        
        /* 컨텐츠 영역 */
        .column {padding: 15px; border-bottom: 1px solid #dbdbdb;}
        .column .col_tit {font-size: 20px; color: #2f7fa6; padding-bottom: 5px;}
        .column .col_desc {
            border-bottom: 1px dashed #dbdbdb; 
            padding-bottom: 15px; margin-bottom: 15px;  
            color: #878787;
            line-height: 18px;
        }
        .column.col1 {} 
        .column.col2 {} 
        .column.col3 {border-bottom: 0;} 
        .column.col4 {} 
        .column.col5 {} 
        .column.col6 {border-bottom: 0;} 
        .column.col7 {} 
        .column.col8 {} 
        .column.col9 {border-bottom: 0;} 
        
        /* 메뉴 */
        .menu li {position: relative;}
        .menu li a {
            font-size: 16px; text-transform: uppercase; 
            color: #878787; border-bottom: 1px solid #dbdbdb; 
            padding: 10px; 
            display: block;  
            transition: box-shadow 0.34s ease, background 0.34s ease;
        }
        .menu li a i {position: absolute; right: 10px; top: 15px;}
        .menu li a:hover {
            box-shadow: inset 180px 0 0 0 rgba(36,130,174,0.7); 
            color: #fff; 
            background: rgba(36,130,174,0.9);
        }
        
        /* 게시판1 */
        .notice1 {position: relative;  }
        .notice1 h5 {font-size: 14px; color: #2f7fa6; padding-bottom: 5px;}
        .notice1 li {position: relative; overflow: hidden; text-overflow: ellipsis; white-space: nowrap; padding-left: 8px;}
        .notice1 li:before {
	        content: ''; width: 3px; height: 3px; 
            border-radius: 50%;
            background: #449ce2; 
            position: absolute; left: 0; top: 6px;
        }
        .notice1 .more {
            position: absolute; 
            right: 0; top: 3px; 
            color: #878787; 
            text-transform: uppercase;
            font-size: 10px;
        }
        
        /* 게시판2 */
        .notice2 {position: relative;  }
        .notice2 h5 {font-size: 14px; color: #2f7fa6; padding-bottom: 5px;}
        .notice2 li {
            position: relative; 
            overflow: hidden; 
            text-overflow: ellipsis; 
            display: -webkit-box;
            -webkit-box-orient: vertical;
            -webkit-line-clamp : 2;
            padding-left: 8px;
            padding-bottom: 5px;
            max-height: 40px; /* ie */
        }
        .notice2 li:before {
            content: ''; width: 3px; height: 3px; 
            border-radius: 50%;
            background: #449ce2; 
            position: absolute; left: 0; top: 6px;
        }
        .notice2 .more {
            position: absolute; 
            right: 0; top: 3px; 
            color: #878787; 
            text-transform: uppercase;
            font-size: 10px;
        }
        
        /* 블로그1 */
        .blog1 img {width: 100%;}
        .blog1 .img-retina {display: none;}
        
        @media only screen and (-webkit-min-device-pixel-ratio: 1.5),
               only screen and (min-device-pixel-ratio: 1.5),
               only screen and (min-resolution: 1.5dppx) {
                .blog1 .img-retina {display: initial;}
                .blog1 .img-normal {display: none;}
        }

        /* 블로그2 */
        .blog2 h5 {color: #fff; text-align: center; padding: 30px 30px; text-transform: uppercase;}
        .blog2 p {padding-top: 5px;}
        .blog2 .img-retina {
            background-image: url(img/blog3_@1.jpg);
            background-size: cover;
        }
        @media only screen and (-webkit-min-device-pixel-ratio: 1.5),
               only screen and (min-device-pixel-ratio: 1.5),
               only screen and (min-resolution: 1.5dppx) {
                .blog2 .img-retina {background-image: url(img/blog3_@2.jpg);}
        }
        
        /* 이미지 슬라이드 */
        .slider figure {position: relative;}
        .slider figcaption {position: absolute; bottom: 0; left: 0; width: 100%; padding: 20px;
            box-sizing: border-box;
            background-color: rgba(0,0,0,0.5);
            color: #fff;
            font-size: 18px;
        }
        .slider figcaption em {
            display: block; 
            font-weight: bold; font-size: 28px; text-transform: uppercase; font-family: 'Abel', sans-serif;
            opacity: 0;
            transform: translateX(50px);
            transition: all .84s ease;
        }
        .slider figcaption span {
            display: block;
            overflow: hidden; text-overflow: ellipsis; white-space: nowrap;
            opacity: 0;
            transform: translateX(50px);
            transition: all .84s 0.2s ease;
        }
        .slider .slick-active figcaption em {opacity: 1; transform: translateX(0)}
        .slider .slick-active figcaption span {opacity: 1; transform: translateX(0)}
        
        .slider .slick-dots {display: block; width: 100%; text-align: center;}
        .slider .slick-dots li {display: inline-block; width: 15px; height: 15px; margin: 5px;}
        .slider .slick-dots li button {
            font-size: 0; 
            line-height: 0; 
            display: block; 
            width: 15px; height: 15px;
            cursor: pointer; 
            background: #5dbfeb; 
            border-radius: 50%;
        }
        .slider .slick-dots li.slick-active button {background: #2b91c8;}
        .slider .slick-prev {
            position: absolute; left: 0; bottom: 0; 
            z-index: 1000;
            width: 30px; height: 30px; 
            display: inline-block;
            font: normal normal normal 14px/1 FontAwesome;
            text-indent: -9999px;
        }
        .slider .slick-prev::before {
            content: "\f053";
            color: #5dbfeb;
            text-indent: 0;
            position: absolute; left: 9px; top: 8px;
        }
        .slider .slick-next {
            position: absolute; right: 0; bottom: 0; 
            z-index: 1000;
            width: 30px; height: 30px; 
            display: inline-block;
            font: normal normal normal 14px/1 FontAwesome;
            text-indent: -9999px;
        }
        .slider .slick-next::before {
            content: "\f054";
            color: #5dbfeb;
            text-indent: 0;
            position: absolute; left: 11px; top: 8px;
        }
        
        
        
        /* mediaquery */
        /* 화면 너비 0~1220px */
        @media (max-width: 1220px){
            .container {width: 100%;}
            .row {padding: 0 15px;}
            #cont_center {min-height: 1350px;}
	        #contents .container {border: 0;}
            
            .title .btn {right: 15px;}
        }
        
        /* 화면 너비 0~1024px */
        @media (max-width: 1024px){
            
        }
        
        /* 화면 너비 0~960px */
        @media (max-width: 960px){
            #cont_right {position: static; width: 100%; border-top: 1px solid #dbdbdb;}
	        #cont_center {margin-right: 0; border-right: 0;}
            
            .nav > div {float: none; width: 100%;}
            .nav > div:last-child {width: 100%;}
            .nav > div li {width: 33.333%;}
            .nav > div:last-child li {width: 33.333%;}
            .nav > div ol {margin-bottom: 10px;}
        }
        
        /* 화면 너비 0~768px */
        @media (max-width: 768px){
            #cont_left {float: none; width: 100%;}
	        #cont_center {border-left: 0;}
        }
        
        /* 화면 너비 0~600px */
        @media (max-width: 600px){
            .header {height: auto;}
            .nav > div li {width: 50%;}
	        .nav > div:last-child li {width: 50%;}
            
            .header .header_tit {display: none;}
            .header .header_icon {display: none;}
            .title .btn {display: none;}
            .column.col1 .col_tit {display: none;}
            .column.col1 .col_desc {display: none;}
            .column.col1 .menu li a i {display: none;}
            .column.col1 {padding: 0; border-bottom: 0;}
            .column.col1 .menu ul {overflow: hidden;}
            .column.col1 .menu li {float: left; width: 33.33333%; text-align: center; border-right: 1px solid #dbdbdb; box-sizing: border-box;}
            .column.col1 .menu li:nth-child(3n) {border-right: 0;}
            .column.col1 .menu li a {color: #fff; text-shadow: 0 0 5px rgba(0,0,0,0.7);}
            .column.col1 .menu li a:hover {box-shadow: none; background: rgba(36,130,174,0.3);}
            .column.col2 {background: #fff;}
	        .column.col4 {border-top: 1px solid #dbdbdb;}
            
            .slider figcaption {padding: 10px;}
            .slider figcaption em {font-size: 18px;}
            .slider figcaption span {font-size: 14px;}
        }
        
        /* 화면 너비 0~480px */
        @media (max-width: 480px){

        }

        /* 화면 너비 0~320px */
        @media (max-width: 320px){

        }
    </style>
<section id="cont_center">
                    <h3 class="ir_su">반응형 사이트 가운데 컨텐츠</h3>
                    <article class="column col4">
                        <h4 class="col_tit">Slick Slider</h4>
						<p class="col_desc">slick.js를 이용한 이미지 슬라이드 효과입니다.</p>
						<!-- 이미지 슬라이드 -->
						<div class="slider">
							<div>
                                <figure>
                                    <img src="./img/fiesta.jpg" alt="fiesta">
                                    <figcaption><em>Responsive Site</em><span>슬라이드 플러그인을 이용한 반응형 이미지 슬라이드 입니다.</span></figcaption>
                                </figure>
				            </div>
							<div>
                                <figure>
                                    <img src="./img/iccv.jpg" alt="iccv">
                                    <figcaption><em>Responsive Site</em><span>슬라이드 플러그인을 이용한 반응형 이미지 슬라이드 입니다.</span></figcaption>
                                </figure>
				            </div>
				            <div>
                                <figure>
                                    <img src="./img/iccv2.jpg" alt="iccv2">
                                    <figcaption><em>Responsive Site</em><span>슬라이드 플러그인을 이용한 반응형 이미지 슬라이드 입니다.</span></figcaption>
                                </figure>
				            </div>
						</div>
						<!--//이미지 슬라이드 -->
                    </article>

<div class="section">
    <div class="row">
Nov. 2019. Won the special prize for KoGas Big Data Competition(click) <br>
Nov. 2019. Gave a talk at Authentication Workshop(click) <br>
Oct. 2019. Open Energy Cloud Platform, a joint security + ML project with KAIST and SNU is funded(click) <br>
Dec 2018. Best Paper (국보연원장상) CISC-W <br>
August 2018. Nominated for the "Best Student Paper" at IFIP-SEC 2018 by Keeyoung Kim <br>
August 2018. Won the grant from Korea Aerospace Research Institute (KARI). Thank you for the support! <br>
July 2018. Won the top 7th place (top 3rd among universities) among 400 teams in Korea for AI R&D Challenge on Fake Face Image Detection, Congrats Sangyup, Shahroz, Hoyoung, and Youjin! <br>
July 2018, Gave a keynote talk at International Conference on Software Security and Assurance (ICSSA) 2018 <br>
April 2018, Gave a talk at NetSec-Kr'18 <br>
Dec. 2017. 1 paper is "Accepted" at ACM SIG CHI'18 <br>
Dec. 2017. Won the 2nd place at National Data Science Challenge (http://challenge.cisc.or.kr/), Congrats Sangyup, Shahroz, and Homin! (Media coverage click here) <br>
Dec. 2017. gave a CS Colloquium talk at Hanyang University, Seoul, Korea <br>
Dec. 2017. gave a talk at Inha University, Incheon, Korea <br>
Nov. 2017. Our paper "Towards Machine Generated Passwords" is selected as one of the best papers (우수 논문상) at CISC-W 2017  <br>
Nov. 2017. Our paper "Towards Machine Generated Passwords" is accepted, at CISC-W 2017 <br>
Nov. 2017. Student Research Workshop paper is acceted at ACM CoNEXT2017, Congats Pratik! <br>
Oct.2017. NRF Grant Awarded (2017-2020, KRW 90K) <br>
Sept.2017. Finance Chair for ACM CoNEXT 2017 <br>
Aug. 2016. gave a talk at Korea University, Seoul, Korea <br>
Aug.2016. ETNews on 3D CAPTCHAs, 2016 (Korean Article Click Here) <br> 
Aug. 2016. Our paper "3D CAPTCHAs" was selected as the best paper at WISA 2016 <br>
    </div>
</div>
