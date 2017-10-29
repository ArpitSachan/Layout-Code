<html>
<head>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<style>
body{
overflow-x:hidden;
background-color:#e3ecef;
}
.header {
margin-top: -6;
margin-left: -14;
    background-color: #225a7a;
    color: #ffffff;
    padding: 70px;
	height:0px;
	box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 1), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    width: 1232px;
    
    
	}
.title{
padding: 0px 200px 12px 40px;
font-size:25px;
margin:-55px;
color:white;
}
#nav {
list-style-type: none;
margin:0;
padding: 0;
overflow: hidden;
background-color: #225a7a;
}
#element {

margin-top: 30px;
padding: 0px 2px 10px 0px;
float: right;

}

#element #color {
    font-size: 12px;
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

#element #color:hover {
    background-color: #014660;
}
input[type=text]{
height: 29px;
width: 240px;
box-sizing: border-box;
border: 2px solid #d7e3e8;
border-radius: 4px;
font-size: 16px;
background-color: #e0f2f9;
background-image: url('searchicon.png');
background-position: 10px 10px; 
background-repeat: no-repeat;
padding: 12px 20px 12px 10px;
  }
.search{
float: right;
margin-top: -100px;
padding: 0px 17px 12px 44px;
}
.bar {

list-style-type: none;
padding: -6;

overflow: hidden;
background-color: #225a7a;
}
#text3 {
height:10px;

font-weight:bold;
margin-top: 0px;
margin-right:0;
padding: 0px 2px 10px 20px;
float: left;

}

#text3, #home,.dropbtn{

    font-size: 13px;
    display: inline-block;
    color: white;
    text-align: center;
    padding: 12px 16px;
    text-decoration: none;
	
}


.dropdown-content {
display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    
	
    z-index: 1;
	}


	.dropdown-content #block {
    color: black;
    padding: 10px 16px;
    text-decoration: none;
    display: block;

    text-align: left;
}
.dropdown .dropbtn:hover{
background-color: #014660;
}
#text3 #home:hover{
background-color: #014660;
}


.dropdown-content :hover 
{
background-color: #225a7a;
}

.dropdown:hover .dropdown-content {
    display: block;
	}
	.Navigation{
	margin-top:-7;
	margin-left:-40;
	margin-right:-12px;;
	
	box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 1), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
	}
	




.mySlides {display:none}


#container {

foat: right;
box-sizing:border-box;
max-width:800px;
  position: relative;
  margin: auto;

  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 1), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
  margin:0px;
}

.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}
.dot {
  height: 8px;
  width: 8px;
  margin: 10 0px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
  overflow:hidden;
}

.active {
  background-color: #225a7a;
}
.fade {

  -webkit-animation-name: fade;
  -webkit-animation-duration: 3.5s;
  animation-name: fade;
    animation-duration: 3.5s;
}

@-webkit-keyframes fade {
  from {opacity: 0} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: 0.1} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}
.overlay {
  position: absolute;
  top:0;
  left: 0;
  right: 0;
  background-color: #225a7a;
  overflow: hidden;
  width: 100%;
  height: 0;
  transition: .5s ease;
  opacity: 0.8;
    

}

.con:hover .overlay {
  top:0;
  height: 10%;
}

.text2 {
 
  color: white;
  font-size: 20px;
  position: absolute;
  overflow: hidden;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
    opacity: 10;
	
	font-family:Serif;
}
.box{

  background-color: #b6c0c6;
    width: 209px;
    height:349px;
    padding: 20px;
    margin-top: -384px;
    overflow-y: scroll;
	 border-style: solid ;
	border-bottom-width: 15px;
	border-color:#b6c0c6;
	 border-right: 0px ;
	 border-left: 0px ;
	}
.news{
    list-style-type: none;
    margin-top: -455;
    padding: 1;
    width: 250px;
    background-color: #225a7a;
	boder: 2px;
	}
	
#announcements
 {
  font-family:Verdana;
    margin-right:30;
    display:block;
    color: white;
	margin-top:12px;
    padding: 0px 7px;
    text-align: center;
	font-size:16px;
}
.box2{
float:right;
  background-color: #b6c0c6;
    width: 209px;
    height:352px;
    padding: 20px;
    margin-top: -1px;
    overflow-y: scroll;
	border-bottom-width: 18px;
	border-color:#b6c0c6;
	 border-right: 0px ;
	 border-left: 0px ;
	}
.frame{
    float:right;
    
    margin-top: -50;
	margin-right:-251;
	padding: 1;
    width: 250px;
    background-color: #225a7a;
	
	}
	#events
 {
 font-family:Verdana;
    margin-right:30;
    display:block;
    color: white;
	margin-top:12px;
    padding: 0px 7px;
    text-align: center;
	font-size:16px;
	
}
::-webkit-scrollbar {
width: 10px;

}

::-webkit-scrollbar-track {
background-color:lightgrey;
border: 1px solid lightgrey;

}

::-webkit-scrollbar-thumb {
background: #919799;  

}

::-webkit-scrollbar-thumb:hover {
background: #b1b4b5;  
}
.arrange {
    list-style-type: none;

	margin-left:-30;
	margin-top:0;
}
#list{
font-family:georgian;
font-size:14px;
}
#list:link {
    color:#2d373a;
    text-decoration: none;
}
#list:visited {
    color: #2d373a;
    
    text-decoration: none;
}
#list:hover {
    color:#225a7a ;
  
    text-decoration: none;
}
#list:active {
    color: red;
   
    text-decoration: none;
}
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding:10px;
  margin-top: -22px;
  color: lightgrey;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;


}


.next {
  right: 0;
 
}


.prev:hover, .next:hover {
  background-color: #225a7a;
   opacity:0.8;
}
.links
 {
    list-style-type: none;
    margin-top: 400;
	margin-left:250;
    padding: 1;
	height:30;
    width: 247px;
    background-color:#225a7a;
	boder: 2px;
	
}
#quick{

 font-family:Verdana;
    margin-right:30;
    display:block;
    color: white;
	margin-top:6px;
    padding: 0px 7px;
    text-align: center;
	font-size:14px;
}
.box3{

float:left;
margin-top: 0;
margin-left:250;
  background-color: #b6c0c6;
    width: 209px;
    height:154px;
    padding: 20px;
   overflow-y:scroll;
   border-style:solid;
	border-bottom-width: 15px;
	border-color:#b6c0c6;
	 border-right: 0px ;
	 border-left: 0px ;
	}

.forms
 {
    list-style-type: none;
    margin-top:-32;
	margin-left:848;
    padding: 1;
	height:30;
    width: 247px;
    background-color:#225a7a;
	boder: 2px;
	
}
#forms1{

 font-family:Verdana;
    margin:0;
    display:block;
    color: white;
	margin-top:6px;
    padding: 0px 7px;
    text-align: center;
	font-size:14px;
}
.box5{

float:left;
margin-top: -215;
margin-left:848;
  background-color: #b6c0c6;
    width: 209px;
    height:156px;
    padding: 20px;
   overflow-y:scroll;
   border-style:solid;
	border-bottom-width: 15px;
	border-color:#b6c0c6;
	 border-right: 0px ;
	 border-left: 0px ;
	}
	#list1{
font-weight:bold;
font-size:14px;
}
#list1:link {
    color:#2d373a;
    text-decoration: none;
}
#list1:visited {
    color: #2d373a;
    
    text-decoration: none;
}
#list1:hover {
    color:#225a7a ;
  
    text-decoration: none;
}
#list1:active {
    color: red;
   
    text-decoration: none;
}
.video{
margin-left:520;
margin-top:-2;
}
.life
 {
    list-style-type: none;
    margin-top:-245;
	margin-left:520;
    padding: 1;
	height:30;
    width: 300px;
    background-color:#225a7a;
	boder: 2px;
	
}
#life1{

 font-family:Verdana;
    margin:0;
    display:block;
    color: white;
	margin-top:6px;
    padding: 0px 7px;
    text-align: center;
	font-size:14px;
}
.box4{

float:left;
margin-top: 40;
margin-left:-20;
  background-color:#535659;
    width: 1409px;
    height:106px;
    padding: 20px;
  
opacity:0.8;

	}
#footer {
list-style-type: none;
text-decoration:none;
}
#footer_1 {
margin-right:180px;
margin-top: 30px;
padding: 0px -100px -100px 0px;
float: right;

}
</style>

<body>
<!---Start of header--->
<div class="header">
<p class="title"><img src="C:\Users\arpit\Desktop\iit2.jpg" height="100" width="100" align="middle" hspace="20">भारतीय प्रौद्योगिकी संस्थान जम्मू</p>
<p class="title" style="padding:0px 200px 10px 180px; font-size:20px;">Indian Institute of Technology Jammu</p>

<ul id="nav">
<li id="element"><a id="color" href="#news">News</a></li>
<li id="element"><a id="color" href="#contact">Contact</a></li>
<li id="element"><a id="color" href="#about">About</a></li>
<li id="element"><a id="color" class="active" href="#home">Home</a></li>
</ul>
<div class="search">
<form method="get" action="http://www.google.com/search" target="_blank">
  <input href="" type="text" name="search" placeholder="Search...">
</form>
</div>
</div>
<!---End of header--->
<!---Navigation Bar--->
<div class="Navigation">
<ul class="bar">
<li id="text3"><a id="home" style="margin-top:-14;" href="#home">HOME</a></li>
<li id="text3"><a id="home" style="margin-top:-14;" href="#AboutJammu">ABOUT JAMMU</a></li>
<li id="text3" class="dropdown">
<a href="#" style="margin-top:-14;"  class="dropbtn">CAMPUS</a>
<div class="dropdown-content">
<a id="block" href="#">TEMPORARY CAMPUS</a>
<a id="block" href="#">PERMANENT CAMPUS</a>
</div>
</li>
<li id="text3" class="dropdown">
<a href="#" style="margin-top:-14;"  class="dropbtn">ACADEMICS</a>
<div  class="dropdown-content">
<a id="block" href="#">COURSES</a>
<a id="block" href="#">SCHEDULE SUMMARY</a>
<a id="block" href="#">SEMESTER-1 SCHEDULE</a>
</div>
</li>
<li id="text3" class="dropdown">
<a href="#" style="margin-top:-14;"  class="dropbtn">ADMINISTRATION</a>
<div  class="dropdown-content">
<a id="block" href="#">DIRECTOR</a>
<a id="block" href="#">PROFESSOR IN-CHARGE</a>
<a id="block" href="#">INCHARGES IIT JAMMU</a>
<a id="block" href="#">A.R IN-CHARGE</a>
</div>
</li>
<li id="text3" class="dropdown">
<a href="#"style="margin-top:-14;" class="dropbtn">DEPARTMENTS</a>
<div  class="dropdown-content">
<a id="block" href="#">COMPUTER SCIENCE</a>
<a id="block" href="#">CIVIL ENGINEERING</a>
<a id="block" href="#">ELECTRICAL ENGINEERING</a>
<a id="block" href="#">MECHANICAL ENGINEERING</a>
</div>
</li>
<li id="text3" class="dropdown">
<a href="#" style="margin-top:-14;"  class="dropbtn">PEOPLE</a>
<div class="dropdown-content">
<a id="block" href="#">FACULTY</a>
<a id="block" href="#">STAFF</a>
</div>
</li>
<li id="text3"><a id="home" style="margin-top:-14;"  href="#forms">FORMS</a></li>
<li id="text3"><a id="home" style="margin-top:-14;"  href="#faq's">FAQ's</a></li>
<li id="text3"><a id="home" style="margin-top:-14;"  href="#gallery">GALLERY</a></li>


</ul>
</div>
<div id="container">

<div class="mySlides fade">
<div class="con">

  <div class="numbertext">1 / 3</div>
  <img src="http://iitjammu.ac.in/sites/default/files/campus/iitjammu1.jpg" style="width:100%;" height="400px" >
  <div class="overlay">
    <div class="text2">Permanent Campus</div>
  </div>
  </div>

</div>

<div class="mySlides fade">
<div class="con">
<div class="numbertext">2 / 3</div>
  <img src="http://iitjammu.ac.in/sites/default/files/campus/iitjammu2.jpg" style="width:100%;" height="400px" >
  <!---<div class="text">Bird Eye View</div>--->
  <div class="overlay">
    <div class="text2">Bird Eye View 1</div>
  </div>
  </div>
  
</div>

<div class="mySlides fade">
<div class="con">
  <div class="numbertext">3 / 3</div>
  <img src="http://iitjammu.ac.in/sites/default/files/campus/iitjammu3.jpg" style="width:100%;" height="400px" >
<div class="overlay">
    <div class="text2">Bird Eye view 2</div>
  </div>
  </div>
  </div>
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>
    <div style="text-align:center; background-color:#225a7a;">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>
  
</div>

<div class="box">
<ul class="arrange">
<li><strong ><a id="list"href="http://iitjammu.ac.in/sites/default/files/registration/forms/welcome%20letter%20director%20IIT%20Jammu.pdf" target="_blank">Welcome address by Director</a></strong></li></br>
<svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
 <li><strong><a id="list" href="http://iitjammu.ac.in/sites/default/files/registration/forms/welcome%20letter%20IIT%20Jammu.pdf" target="_blank">Welcome address by In-charge Students</a></strong></li></br>
<svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
 <li><strong><a id="list" href="http://iitjammu.ac.in/sites/default/files/registration/forms/SemSchISem201718.pdf" target="_blank">Semester Schedule for I Semester 2017-18</a></strong></li></br>
<svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
  <li><strong><a id="list" href="http://iitjammu.ac.in/academics/FSSEMI201718.pdf" target="_blank">Fee Structure (Ist Semester 2017-18)</a></strong></li></br>
<svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
 <li><strong><a id="list" href="http://iitjammu.ac.in/sites/default/files/registration/forms/REG_IITJ_2017M2.pdf" target="_blank">Undergraduate Orientation and Registration,2017</a></strong></li></br>
<svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
  <li><strong><a id="list" href="http://iitjammu.ac.in/sites/default/files/registration/forms/LIST_OF_DOCUMENTS_NEW_UG_STUDENTS_2017.pdf" target="_blank">List of Documents to be brought by UG students</a></strong></li></br>
<svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
 </ul>

</div>

<div class="news">
<p id="announcements">NEWS</p>
</div>
</div>
<div class="box2">
<ul class="arrange">
<svg height="1" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
<li><strong ><a style="font-size:14px; color:#2d373a;">Orientation Programme</a></br><a style="font-size:14px; color:#aa0330;">09 Aug 2017</a></strong></li></br>
<svg height="1" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
 <li><strong ><a style="font-size:14px; color:#2d373a;">Independence Day</a></br><a style="font-size:14px; color:#aa0330;">15 Aug 2017</a></strong></li></br>

 </ul>
</div>
<div class="frame">
<p id="events">EVENTS</p>
</div>
<div class="links">
<p id="quick">QUICK LINKS</p>
</div>
<div class="box3">
<ul class="arrange">
</svg>
 <li><a  id="list1" href="#" target="_blank">Webmails</a></li>
 <svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
 <li><a id="list1" href="#" target="_blank">Freshers Portals</a></li>
 <svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
  <li><a id="list1" href="#" target="_blank">Campus Map</a></li>
  <svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
   <li><a id="list1" href="#" target="_blank">JEE(Advanced)</a></li>
   <svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
    <li><a id="list1" href="https://drive.google.com/file/d/0ByCginLehw4fUHVOdDduSFhibnc/view" target="_blank">Prospectus 2017-18</a></li>
	<svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
	

 </ul>
</div>

<div class="video">
<embed width="300" height="210" src="https://www.youtube.com/v/kHGV_BSj5iw" type="applicatiom/x-shockwave-flash">
</embed>
</div>
<div class="life">
<p id="life1">CAMPUS LIFE</p>
</div>

<div class="box5">
<li><a id="list1" href="http://iitjammu.ac.in/sites/default/files/registration/forms/FORM_A_2017.pdf" target="_blank">Form A</a></li>
	<svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
 


<li><a id="list1" href="http://iitjammu.ac.in/sites/default/files/registration/forms/FORM_B_2017.pdf" target="_blank">Form B</a></li>
	<svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
 <li><a id="list1" href="http://iitjammu.ac.in/sites/default/files/registration/forms/Form_C_D_2017.pdf" target="_blank">Form C&D</a></li>
	<svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
 <li><a id="list1" href="http://iitjammu.ac.in/sites/default/files/registration/forms/FORM_E_HONOUR_CODE_2017.pdf" target="_blank">Form E</a></li>
	<svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
 <li><a id="list1" href="http://iitjammu.ac.in/sites/default/files/registration/forms/FORM_F_G_2017.pdf" target="_blank">Form F&G</a></li>
	<svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
  <li><a id="list1" href="http://iitjammu.ac.in/sites/default/files/registration/forms/FORM_H1_H2_H3_2017.pdf" target="_blank">Form H1,H2&H3</a></li>
	<svg height="20" width="200">
  <g fill="none">
    <path stroke="#757f82" d="M0 0 l215 0" />
   </g>
 </svg>
 
</div>
<div class="forms">
<p id="forms1">FORMS</p>

</div>
<div class="box4">
<ul id="nav">
<li id="element"><a id="color" href="#news">News</a></li>
<li id="element"><a id="color" href="#contact">Contact</a></li>
<li id="element"><a id="color" href="#about">About</a></li>
<li id="element"><a id="color" class="active" href="#home">Home</a></li>
</ul>
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    for (i = 0; i < slides.length; i++) {
       slides[i].style.display = "none";  
    }
    slideIndex++;
    if (slideIndex> slides.length) {slideIndex = 1}    
    for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex-1].style.display = "block";  
    dots[slideIndex-1].className += " active";
    setTimeout(showSlides, 10000); // Change image every 2 seconds
}
</script>




 </body>
</html>
