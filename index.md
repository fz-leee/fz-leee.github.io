<!DOCTYPE html>
<html>
<head>
<title>PH.QF Official</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="stylesheet.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif;}

body, html {
    height: 100%;
    color: #6b6c8e;
    line-height: 1.8;
}

p {
	text-align: justify;
}

figcaption {
	text-align: center;
}

/* Create a Parallax Effect */
.bgimg-1, .bgimg-2, .bgimg-3, .bgimg-4 {
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

/* First image (Logo. Full height) */
.bgimg-1 {
    background-image: url('background1.gif');
    min-height: 100%;
}

/* Forth image (Projects) */
.bgimg-4 {
    background-image: url('background2.gif');
    min-height: 70%;
}

/* Second image (Portfolio) */
.bgimg-2 {
    background-image: url('background5.gif');
    min-height: 70%;
	opacity: 0.5;
}

/* Third image (Contact) */
.bgimg-3 {
    background-image: url('background3 (2).gif');
    min-height: 70%;
}

.w3-wide {letter-spacing: 10px;}
.w3-hover-opacity {cursor: pointer;}

::-webkit-scrollbar { 
    display: none; 
}

.w3-white,.w3-hover-white:hover{color:#6b6c8e!important;background-color:#fff!important}

/* Turn off parallax scrolling for tablets and phones */
@media only screen and (max-device-width: 1024px) {
    .bgimg-1, .bgimg-2, .bgimg-3 {
        background-attachment: scroll;
    }
}
</style>
</head>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar" id="myNavbar" style="color:white;">
    <a class="w3-bar-item w3-button w3-hover-black w3-hide-medium w3-hide-large w3-right" href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
      <i class="fa fa-bars"></i>
    </a>
    <a href="#home" class="w3-bar-item w3-button">HOME</a>
    <a href="#about" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-user"></i> ABOUT</a>
	<a href="#projects" class="w3-bar-item w3-button w3-hide-small"><i class="glyphicon glyphicon-file"></i> PROJECTS</a>
    <a href="#portfolio" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-th"></i> MERCHANDISE</a>
	<a href="#contact" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-envelope"></i> CONTACT</a>
  </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium">
    <a href="#about" class="w3-bar-item w3-button" onclick="toggleFunction()">ABOUT</a>
    <a href="#portfolio" class="w3-bar-item w3-button" onclick="toggleFunction()">MERCHANDISE</a>
    <a href="#contact" class="w3-bar-item w3-button" onclick="toggleFunction()">CONTACT</a>
    <a href="#" class="w3-bar-item w3-button">SEARCH</a>
  </div>
</div>

<!-- First Parallax Image with Logo Text -->
<div class="bgimg-1 w3-display-container w3-opacity-min" id="home">
  <div class="w3-display-middle" style="white-space:nowrap;">
    <!-- <span class="w3-center w3-padding-large w3-black w3-xlarge w3-wide w3-animate-opacity">MY <span class="w3-hide-small">WEBSITE</span> LOGO</span> -->
	<img src="Pluto4a.png" class="w3-animate-opacity" /> 
  </div>
</div>

<!-- Container (About Section) -->
<div class="w3-content w3-container w3-padding-64" id="about">
  <h3 class="w3-center">ABOUT US</h3>
  <p class="w3-center"><em>We're design freaks</em></p>
  <div class="w3-row">
    <div class="w3-col m6 w3-center w3-padding-large">
      <p><b><i class="fa fa-user w3-margin-right"></i>Fauzi Lee & Thaqif Sharafuddin</b></p><br>
      <img src="astronaut1.jpg" class="w3-round w3-image w3-opacity w3-hover-opacity-off" alt="Photo of Me" width="500" height="333">
    </div>

    <!-- Hide this text on small devices -->
    <div class="w3-col m6 w3-hide-small w3-padding-large">
      <p style="padding-top: 65px;">My partner and I started making sticker designs earlier this semester. 
	  When we got good response from our first sticker design, we were inspired to start up our own brand. 
	  For now, we're trying to release more stickers and hopefully sell them. 
	  After this, we'd like to release other merchandise such as embroided badges, t-shirts, hoodies and bomber jackets. </p>
    </div>
  </div>
<!--	<p class="w3-wide"><i class="fa fa-camera"></i>Photography</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:90%">90%</div>
  </div>
  <p class="w3-wide"><i class="fa fa-laptop"></i>Web Design</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:85%">85%</div>
  </div>
  <p class="w3-wide"><i class="fa fa-photo"></i>Photoshop</p>
  <div class="w3-light-grey">
    <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:75%">75%</div>
  </div>
</div>
-->
<div style="padding-top: 20px;">
	<p class="w3-wide" style="padding-top: 10px;"><i class="fa fa-camera"></i>Photography</p>
  <div class="w3-light-grey" style="border: 2px solid #6b6c8e;" onclick="photography()">
    <div class="w3-container w3-padding-small w3-center" id="photographybar" style="width:1%; color: #fff; background-color: #6b6c8e;"></div>
  </div>
  <p class="w3-wide" style="padding-top: 10px;"><i class="fa fa-laptop"></i>Web Design</p>
  <div class="w3-light-grey" style="border: 2px solid #6b6c8e;" onclick="webdesign()">
    <div class="w3-container w3-padding-small w3-center" id="webdesignbar" style="width:1%; color: #fff; background-color: #6b6c8e"></div>
  </div>
  <p class="w3-wide" style="padding-top: 10px;"><i class="fa fa-photo"></i>Photoshop</p>
  <div class="w3-light-grey" style="border: 2px solid #6b6c8e;"onclick="photoshop()">
    <div class="w3-container w3-padding-small w3-center" id="photoshopbar" style="width:1%; color: #fff; background-color: #6b6c8e"></div>
  </div>
  	<p style="text-align:right;">* click the bars to load progress</p>
</div>
</div>

<div class="w3-row w3-center w3-padding-16" style="background-color: #6b6c8e; color: #fff;">
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">27+</span><br>
    Stickers Sold
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">4+</span><br>
    Projects Done
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">13+</span><br>
    Happy Clients
  </div>
  <div class="w3-quarter w3-section">
    <span class="w3-xlarge">24+</span><br>
    Future Merchandise
  </div>
</div>

<!-- Second Parallax Image with Merchandise Text -->
<div class="bgimg-4 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
    <span class="w3-xxlarge w3-text-white w3-wide">PROJECTS</span>
  </div>
</div>


<!-- Container (Project Section) -->
<div class="w3-content w3-container w3-padding-64" id="projects">
  <h3 class="w3-center">PH.QF CHARACTERS</h3>
  <p class="w3-center">List of PH.QF characters<em><br> Click on characters to know more.</em></p><br>

  <!-- Responsive Grid. Four columns on tablets, laptops and desktops. Will stack on mobile devices/small screens (100% width) -->
  <div class="w3-row-padding w3-center" >
	<div class="w3-col m3">
		<img src="Pluto1.png" style="width:100%;" onclick="onClick(this)" class="w3-hover-opacity projimg" alt="[Pluto] An office worker that always wanted to be an astronaut. He got sick of his job and quit to smoke lots of weed and get high.">
		<figcaption>Pluto</figcaption>
	</div>
	
	<div class="w3-col m3">
		<img src="comingsoon.jpg" style="width:100%;" class="w3-hover-opacity projimg" alt="Coming Soon">
		<figcaption>Hazard</figcaption>
	</div>

	<div class="w3-col m3">
		<img src="comingsoon.jpg" style="width:100%" class="w3-hover-opacity projimg" alt="Coming Soon">
		<figcaption>Quinn</figcaption>
	</div>

	<div class="w3-col m3">
		<img src="comingsoon.jpg" style="width:100%" class="w3-hover-opacity projimg" alt="Coming Soon">
		<figcaption>Flaco</figcaption>
	</div>
  </div>
</div>

<!-- Second Parallax Image with Merchandise Text -->
<div class="bgimg-2 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
    <span class="w3-xxlarge w3-text-white w3-wide">MERCHANDISE</span>
  </div>
</div>

<!-- Container (Portfolio Section) -->
<div class="w3-content w3-container w3-padding-64" id="portfolio">
  <h3 class="w3-center">OUR WORK</h3>
  <p class="w3-center"><em>Here are some of our merchandise so far.<br> Click on the images to make them bigger</em></p><br>

  <!-- Responsive Grid. Four columns on tablets, laptops and desktops. Will stack on mobile devices/small screens (100% width) -->
  <div class="w3-row-padding w3-center">
    <div class="w3-col m3">
      <img src="PHQF Premium Sticker.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="[Premium] PH.QF Sticker (First Edition)">
    </div>

    <div class="w3-col m3">
      <img src="PHQF Standard Sticker.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="[Standard] PH.QF Sticker (First Edition)">
    </div>

    <div class="w3-col m3">
      <img src="Pluto_v1a.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="[Premium] Pluto Sticker">
    </div>

    <div class="w3-col m3">
      <img src="Pluto_v2.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="[Standard] Pluto Sticker">
    </div>
  </div>

<!-- <div class="w3-row-padding w3-center w3-section">
    <div class="w3-col m3">
      <img src="/w3images/p5.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="The mist">
    </div>

    <div class="w3-col m3">
      <img src="/w3images/p6.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="My beloved typewriter">
    </div>

    <div class="w3-col m3">
      <img src="/w3images/p7.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Empty ghost train">
    </div>

    <div class="w3-col m3">
      <img src="/w3images/p8.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Sailing">
    </div>
    <!-- <button class="w3-button w3-padding-large w3-light-grey" style="margin-top:64px">LOAD MORE</button>
  </div> -->
</div>

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-large w3-black w3-display-topright" title="Close Modal Image"><i class="fa fa-remove"></i></span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>

<!-- Third Parallax Image with Contact Text -->
<div class="bgimg-3 w3-display-container" style="opacity: 0.5;">
  <div class="w3-display-middle">
     <span class="w3-xxlarge w3-text-white w3-wide">CONTACT</span>
  </div>
</div>

<!-- Container (Contact Section) -->
<div class="w3-content w3-container w3-padding-64" id="contact">
  <h3 class="w3-center">WHERE WE WORK</h3>
  <p class="w3-center"><em>We'd love your feedback!</em></p>

  <div class="w3-row w3-padding-32 w3-section">
    <div class="w3-col m4 w3-container">
      <div class="w3-round-large w3-greyscale" style="width:100%;height:400px;background:url('Pluto of Spades.png');background-size: 100%; background-repeat: no-repeat; background-position: center; border: 2px solid black;"></div>
    </div>
    <div class="w3-col m8 w3-panel">
      <div class="w3-large w3-margin-bottom">
        <i class="fa fa-map-marker fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Taylor's University Lakeside Campus<br>
        <i class="fa fa-phone fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Phone: +60 19-339 8834<br>
        <i class="fa fa-envelope fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Email: phaqof@gmail.com<br>
      </div>
      <p>Swing by for a cup of <i class="fa fa-coffee"></i>, or leave us a note:</p>
      <form action="/action_page.php" target="_blank">
        <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
          <div class="w3-half">
            <input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
          </div>
          <div class="w3-half">
            <input class="w3-input w3-border" type="text" placeholder="Email" required name="Email">
          </div>
        </div>
        <input class="w3-input w3-border" type="text" placeholder="Message" required name="Message">
        <button class="w3-button w3-black w3-right w3-section" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </form>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <!-- <i class="fa fa-facebook-official w3-hover-opacity"></i> -->
    <a href="https://www.instagram.com/ph.qf/"><i class="fa fa-instagram w3-hover-opacity"></i></a>
    <!--<i class="fa fa-snapchat w3-hover-opacity" onclick="onClick(this)"></i> -->
    <!-- <i class="fa fa-pinterest-p w3-hover-opacity"></i> -->
    <a href="https://twitter.com/phqf_official"><i class="fa fa-twitter w3-hover-opacity"></i></a>
    <!-- <i class="fa fa-linkedin w3-hover-opacity"></i> -->
  </div>
  
</footer>
 
 

<script>
function myMap()
{
  myCenter=new google.maps.LatLng(41.878114, -87.629798);
  var mapOptions= {
    center:myCenter,
    zoom:12, scrollwheel: false, draggable: false,
    mapTypeId:google.maps.MapTypeId.ROADMAP
  };
  var map=new google.maps.Map(document.getElementById("googleMap"),mapOptions);

  var marker = new google.maps.Marker({
    position: myCenter,
  });
  marker.setMap(map);
}

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}

// Change style of navbar on scroll
window.onscroll = function() {myFunction()};
function myFunction() {
    var navbar = document.getElementById("myNavbar");
    if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
        navbar.className = "w3-bar" + " w3-card" + " w3-animate-top" + " w3-white";
    } else {
        navbar.className = navbar.className.replace(" w3-card w3-animate-top w3-white", "");
    }
}

// Used to toggle the menu on small screens when clicking on the menu button
function toggleFunction() {
    var x = document.getElementById("navDemo");
    if (x.className.indexOf("w3-show") == -1) {
        x.className += " w3-show";
    } else {
        x.className = x.className.replace(" w3-show", "");
    }
}

// Progress Bar
function photography() {
    var elem = document.getElementById("photographybar"); 
    var width = 1;
    var id = setInterval(frame, 10);
    function frame() {
        if (width >= 69) {
            clearInterval(id);
        } else {
            width++; 
            elem.style.width = width + '%'; 
        }
    }
}

function webdesign() {
    var elem = document.getElementById("webdesignbar"); 
    var width = 1;
    var id = setInterval(frame, 10);
    function frame() {
        if (width >= 55) {
            clearInterval(id);
        } else {
            width++; 
            elem.style.width = width + '%'; 
        }
    }
}

function photoshop() {
    var elem = document.getElementById("photoshopbar"); 
    var width = 1;
    var id = setInterval(frame, 10);
    function frame() {
        if (width >= 89) {
            clearInterval(id);
        } else {
            width++; 
            elem.style.width = width + '%'; 
        }
    }
}

// Snapchat Show Image

function showImage(){
        document.getElementById('loadingImage').style.visibility=visible;
}

</script>
<!--<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBu-916DdpKAjTmJNIgngS6HL_kDIKU0aU&callback=myMap"></script>

To use this code on your website, get a free API key from Google.
Read more at: https://www.w3schools.com/graphics/google_maps_basic.asp
-->

</body>
</html>
