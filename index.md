<!DOCTYPE html>
<html lang="en">
<head>
    <title>NMPU-W3.CSS</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="author" content="harsh">
    <link rel="stylesheet" href="../css/w3.css"> <!--W3.CSS FRamework file-->
    <link rel="stylesheet" href="../css/style.css"> <!--CONTAINS styling except nav-->
    <link rel="stylesheet" href="../css/navstyle.css"> <!--CONTAINS navstyling -->
    <link rel="stylesheet" href="../css/gallerystyle.css"> <!--HOME PAGE GAL-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"> <!--SM ICONS-->
    
</head>
<body>
<!-- Sidebar Navigation -->
<div class=" sidebor w3-text-light-grey w3-sidebar w3-black w3-bar-block w3-mobile" style="width:16.5%">
      <h1 class="bartitle w3-bar-item w3-animate-left" style="cursor:context-menu;">&#60;<b>Tt</b>&#62; </h1>
    <a href="#homeid" class="home  w3-large w3-bar-item w3-button w3-hover-none w3-hover-text-teal w3-mobile w3-animate-left">&#9780; Home</a>
    <a href="../html/Feed.html#lafeed" class="w3-large w3-bar-item w3-button w3-hover-none w3-hover-text-teal w3-mobile w3-animate-left">&#9832; Latest Feeds</a>
    <a href="../html/tipsntricks.html#trip" class="w3-large w3-bar-item w3-button w3-hover-none w3-hover-text-teal w3-mobile w3-animate-left">&#9902; Tips & Tricks</a>
    <a href="../html/Aboutme.html#bout" class="w3-large w3-bar-item w3-button w3-hover-none w3-hover-text-teal w3-mobile w3-animate-left">&#9957; About ME</a>
    <a href="#cont" class="w3-large w3-bar-item w3-button w3-hover-none w3-hover-text-teal w3-mobile w3-animate-left">&#9742; Contact</a>
    
    <div id="mySidebar" class="searchbarcl w3-sidebar w3-bar-block w3-mobile" style="display:none; height: 80px;" >
      <button onclick="w3_close()" class="w3-bar-item w3-button w3-large ">Close &times;</button>
        <form action="" style="padding-left: 10px;">
            <input type="text" placeholder="Search.." name="search" >
        </form>
    </div>
    <div class="searchbarop">
        <button id="searchid" class="w3-button w3-xlarge w3-animate-left w3-mobile" onclick="w3_open()" style="margin-top: 25px;">&#9862; SEARCH</button>
    </div>
</div>

<!--NOTE:- SEPARATE TECHTONIC AND IMGSLIDER-->
<!-- Page Content -->
<div id=homeid class="w3-mobile" style="margin-left:16.5%">
    <!-- <label onclick="toggle()" id="dark-change"></label>-->
    <div class="w3-container w3-teal w3-mobile" >
      <p class="title w3-mobile" style="cursor: context-menu;">TeCHToNIC</p>
    </div>

    <div class="w3-mobile">
      <div class="imgslider w3-mobile w3-image">
      </div>
      <div class="frontcon w3-container w3-mobile" >
            <p class="wel w3-text-light-grey w3-border-bottom w3-animate-zoom" style="cursor:context-menu;">Welcome To <br>The<br><b class="tech w3-wide" style="text-shadow:9px 9px 0 rgb(45, 11, 73);"> &#10096;Techside! &#10097;</b></p>
      </div>
    </div>

</div>
<!-------break--------><!--<div class="w3-display-hover w3-display-middle w3-container"><p>Top Left</p></div>-->
<div class="main w3-container w3-padding w3-topbar w3-margin-top w3-margin-bottom w3-mobile " style="margin-left:18%; margin-top:10px; ">
  <div class="gallery">
    <div class="w3-display-container w3-text-white">
      <a href="#">
        <img src="../IMAGES/gal2.jpg" style="border-radius: 10px;">
        <a class="w3-button w3-display-hover w3-display-middle w3-xlarge w3-hover-none w3-hover-text-amber " href="../html/Feed.html#lafeed" style="text-transform:capitalize;">xiaomi's tab </a> 
      </a>
    </div>
    <div class="v-stretch w3-display-container w3-text-white">
      <a href="#">
        <img src="../IMAGES/gal4.jpg" style="border-radius: 10px;">
        <a class="w3-button w3-display-hover w3-display-middle w3-xlarge w3-hover-none w3-hover-text-amber" href="../html/Feed.html#smart" style="text-transform:capitalize;">best compact smartphones </a> 
      </a>
    </div>
    <div class="h-stretch w3-display-container w3-text-white">
      <a href="#">
        <img src="../IMAGES/gal1.jpg" style="border-radius: 10px;">
        <a class="w3-button w3-display-hover w3-display-middle w3-xlarge w3-hover-none w3-hover-text-amber" href="../html/Feed.html#specs" style="text-transform:capitalize;">specifications of xiaomi pad 5</a> 
      </a>
    </div>
    
    <div class="w3-display-container w3-text-white">
      <a href="#">
        <img src="../IMAGES/gal3.jpg" style="border-radius: 10px;">
        <a class="w3-button w3-display-hover w3-display-middle w3-xlarge w3-hover-none w3-hover-text-amber" href="../html/tipsntricks.html#tipid1" style="text-transform:capitalize;">limit screen time</a> 
      </a>
    </div>
    
    <div class="w3-display-container w3-text-white">
      <a href="#">
        <img src="../IMAGES/gal5.jpg" style="border-radius: 10px;">
        <a class="w3-button w3-display-hover w3-display-middle w3-xlarge w3-hover-none w3-hover-text-amber" href="../html/tipsntricks.html#tipid" style="text-transform:capitalize;">use original chargers</a> 
      </a>
    </div>
    
    <div class="w3-display-container w3-text-white"> <!--v-stretch-->
      <a href="#">
        <img src="../IMAGES/gal6.jpg" style="border-radius: 10px;"><a class="w3-button w3-display-hover w3-display-middle w3-xlarge w3-hover-none w3-hover-text-amber" href="../html/../html/feed.html#12mini" style="text-transform:capitalize;">iphone 12 mini specs</a> 
      </a>
    </div>
    
    <div class="w3-display-container w3-text-white"><!--big-stretch-->
      <a href="#">
        <img src="../IMAGES/gal7.jpg" style="border-radius: 10px;"><a class="w3-button w3-display-hover w3-display-middle w3-xlarge w3-hover-none w3-hover-text-amber " href="../html/../html/tipsntricks.html#tipdid2" style="text-transform:capitalize;">limit screen time on IOS</a> 
      </a>
    </div>
    
    <div class="w3-display-container w3-text-white">
      <a href="#">
        <img src="../IMAGES/gal8.jpg" style="border-radius: 10px;"><a class="w3-button w3-display-hover w3-display-middle w3-xlarge w3-hover-none w3-hover-text-amber" href="../html/feed.html#rev" style="text-transform:capitalize;">review of pad 5</a> 
      </a>
    </div>

    <div class="w3-display-container w3-text-white"><!--h-stretch-->
      <a href="#">
        <img src="../IMAGES/gal9.jpg" style="border-radius: 10px;"><a class="w3-button w3-display-hover w3-display-middle w3-xlarge w3-hover-none w3-hover-text-amber" href="../html/feed.html#s10e" style="text-transform:capitalize;">samsung s10e</a> 
      </a>
    </div>

    <div class="w3-display-container w3-text-white" >
      <a href="#">
        <img src="../IMAGES/gal10.jpg" style="border-radius: 10px;">
        <a class="w3-button w3-display-hover w3-display-middle w3-xlarge w3-hover-none w3-hover-text-amber" href="../html/tipsntricks.html#ipad" style="text-transform:capitalize;">how to take SS on ipad</a> 
      </a>
    </div>

    <div class="w3-display-container w3-text-white" >
      <a href="#">
        <img src="../IMAGES/gal12.jpg" style="border-radius: 10px;">
        <a class="w3-button w3-display-hover w3-display-middle w3-xlarge w3-hover-none w3-hover-text-amber" href="../html/feed.html#i13" style="text-transform:capitalize;">iphone 13 specs</a> 
      </a>
    </div>
</div>
</div>

<!-- COntact FORM -->
<div id="cont" class="formm w3-container w3-mobile " style="cursor:context-menu;">
<form action="welscreenaftersub.html" class="forum  w3-container w3-card-2 w3-pale-blue w3-text-teal w3-margin w3-margin-left w3-round-large w3-mobile">
    <h2 class="w3-center">Contact</h2>
     
    <div class="w3-row w3-section">   <!-- first name-->
      <div class="w3-col" style="width:52px"><i class="w3-xxlarge fa fa-user"></i></div>
        <div class="w3-rest">
          <input class="w3-input w3-border w3-hover-border-teal" name="first" type="text" placeholder="First Name" required>
        </div>
    </div>
    
    <div class="w3-row w3-section">  <!-- last name-->
      <div class="w3-col" style="width:52px"><i class="w3-xxlarge fa fa-user"></i></div>
        <div class="w3-rest">
          <input class="w3-input w3-border w3-hover-border-teal" name="last" type="text" placeholder="Last Name" required>
        </div>
    </div>
     
    <div class="w3-row w3-section">   <!-- Email-->
      <div class="w3-col" style="width:52px"><i class="w3-xxlarge fa fa-envelope-o"></i></div>
        <div class="w3-rest">
          <input class="w3-input w3-border w3-hover-border-teal" name="email" type="text" placeholder="Email" required>
        </div>
    </div>
    
    <div class="w3-row w3-section">    <!-- Phone-->
      <div class="w3-col" style="width:52px"><i class="w3-xxlarge fa fa-phone"></i></div>
        <div class="w3-rest">
          <input class="w3-input w3-border w3-hover-border-teal" name="phone" type="text" placeholder="Phone" required>
        </div>
    </div>
    
    <div class="w3-row w3-section">
      <div class="w3-col" style="width:52px"><i class="w3-xxlarge fa fa-pencil"></i></div>
        <div class="w3-rest">
          <input class="w3-input w3-border w3-hover-border-teal" name="message" type="text" placeholder="Message" required>
        </div>
    </div>
    
    <button class="w3-button w3-block w3-section w3-teal w3-ripple w3-padding">Submit</button>
    </form>
</div>

<!--Footer-->
<footer id="foot" class="foot w3-container w3-center w3-margin-top w3-mobile" style="margin-left:16.5%; cursor: context-menu;">
  <h5 class="w3-mobile"><b>Techtonic &copy; 2022-2023</b></h5>
    
    <a href="#" class="fa fa-facebook"></a>
    <a href="#" class="fa fa-twitter"></a>
    <a href="#" class="fa fa-instagram"></a>
    <a href="#" class="fa fa-youtube"></a>
    <a href="#" class="fa fa-pinterest"></a>
    
</footer>

<!-- JAVASCRIPT -->
<script>
  function w3_open() {
      document.getElementById("mySidebar").style.width = "16.5%";   //it'll show width of search bar
      document.getElementById("mySidebar").style.display = "block"; //block
    }
    
    function w3_close() {
      document.getElementById("mySidebar").style.display = "none";
    } 
  </script>

</body>
</html>
