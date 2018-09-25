<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}
body, html {
    height: 100%;
    line-height: 1.8;
}
/* Full height image header */
.bgimg-1 {
    background-position: center;
    background-size: cover;
    background-image: url("https://images.freecreatives.com/wp-content/uploads/2015/10/Photorealistic-Basketball-Background.jpg");
    min-height: 100%;
}
.w3-bar .w3-button {
    padding: 16px;
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-card" id="myNavbar">
    <a href="#home" class="w3-bar-item w3-button w3-wide">Joseph Johnson</a>
    <!-- Right-sided navbar links -->
    <div class="w3-right w3-hide-small">
      <a href="#about" class="w3-bar-item w3-button">Intrest</a>
      <a href="#team" class="w3-bar-item w3-button"><i class="fa fa-user"></i> Information</a>
      <a href="#work" class="w3-bar-item w3-button"><i class="fa fa-th"></i>Minfulness</a>
      <a href="#pricing" class="w3-bar-item w3-button"><i class="fa fa-usd"></i> CS Mindfulness</a>
      <a href="#contact" class="w3-bar-item w3-button"><i class="fa fa-envelope"></i> CONTACT</a>
    </div>
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">Intrest</a>
  <a href="#team" onclick="w3_close()" class="w3-bar-item w3-button">Information</a>
  <a href="#work" onclick="w3_close()" class="w3-bar-item w3-button">Mindfulness</a>
  <a href="#pricing" onclick="w3_close()" class="w3-bar-item w3-button">CS Mindulness</a>
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">CONTACT</a>
</nav>

<!-- Header with full-height image -->
<header class="bgimg-1 w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-left w3-text-white" style="padding:48px">
    <span class="w3-jumbo w3-hide-small">About Me</span><br>
    <span class="w3-xxlarge w3-hide-large w3-hide-medium">Start something that matters</span><br>
    <span class="w3-large">This is A website about me and what I like to do on my own time. I talk about my favorite sports and my favorite things to do when Im bored. I am a 3.0 highschool student looking to bring my GPA to around 3.5. I want to go to college at SF State because they have good classes for majoring in Designing. </span>
    <p><a href="#about" class="w3-button w3-white w3-padding-large w3-large w3-margin-top w3-opacity w3-hover-opacity-off">Joseph Johnson</a></p>
  </div> 
  <div class="w3-display-bottomleft w3-text-grey w3-large" style="padding:24px 48px">
  </div>
</header>

<!-- About Section -->
<div class="w3-container" style="padding:128px 16px" id="about">
  <h3 class="w3-center">My Intrest</h3>
  <p class="w3-center w3-large">Joseph Johnson</p>
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <p class="w3-large">Sports</p>
      <p>My favorite sports are Basketball, Football, and UFC/MMA. My favortie out of these three to watch is UFC/MMA because I like the art of fighting.</p>
    </div>
    <div class="w3-quarter">
      <i class=""></i>
      <p class="w3-large">Video Games</p>
      <p>When Im bored I like to play my PS4. My favorite games on my PS4 is Fortnite, GTA, and NBA2K.</p>
    </div>
    <div class="w3-quarter">
      <i class=""></i>
      <p class="w3-large">Clothes</p>
      <p>I love clothes and I one day want to have my own clothing brand that will grow bigger than all designer retail companies.</p>
    </div>
    <div class="w3-quarter">
      <i class=""></i>
      <p class="w3-large">Music</p>
      <p>When Im in school or when im working on something I like to listen to music because for some reason it puts me in a zone to keep on working.</p>
    </div>
  </div>
</div>
<!-- Team Section -->
<div class="w3-container" style="padding:128px 16px" id="team">
  <h3 class="w3-center">My Information</h3>
  <p class="w3-center w3-large">Joseph Johnson</p>
  <div class="w3-row-padding w3-grayscale" style="margin-top:64px">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://making-waves.org/wp-content/uploads/2017/07/MakingWavesAcademy_boldtypea-289x300.jpg" alt="Joseph Johnson" style="width:100%">
        <div class="w3-container">
          <h3>Making Waves Academy</h3>
          <p class="w3-opacity">Richmond, CA</p>
          <p>This is my school I started at this school in 5th grade and im still continuing now in the 10th grade..</p>
          <p><button class="w3-button w3-light-grey w3-block">
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://news.sfsu.edu/sites/default/files/u34/gator_web.png" alt="Joseph Johnson" style="width:100%">
        <div class="w3-container">
          <h3>Sanfransico State</h3>
          <p class="w3-opacity">Sanfransico, CA</p>
          <p>This is the college that I want to go to I have family members who went here and they have good classes for majoring in some of my intrest.</p>
              </div>
  </div>
</div>
<!-- Mindfulness -->
    </div>
  </div>
</div>
<div class="w3" style="padding:128px 16px" id="work">
  <h3 class="w3-center">Mindfulness</h3>
  <p class="w3-center w3-large">Joseph Johnson</p>
  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-col l3 m6">
      <img src="https://cms.jotform.com/uploads/image_upload/image_upload/global/63279_Screen Shot 2018-07-24 at 11.22.01 AM.png" style="width:275%">
    </div>
    <br>
   
    <div class="w3-col l3 m6">
      <img src="https://cms.jotform.com/uploads/image_upload/image_upload/global/63285_Screen Shot 2018-07-26 at 10.45.58 AM.png" style="width:275%">
    </div>
    <br>

    <div class="w3-col l3 m6">
      <img src="https://cms.jotform.com/uploads/image_upload/image_upload/global/63287_Screen Shot 2018-07-26 at 11.09.33 AM.png" style="width:100%">
    </div>
    <br>
    
    <div class="w3-col l3 m6">
      <img src="https://cms.jotform.com/uploads/image_upload/image_upload/global/63290_Screen Shot 2018-07-26 at 11.13.06 AM.png" style="width:100%"onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 6/21/18">
    </div>

    <div class="w3-col l3 m6">
      <img src="https://cms.jotform.com/uploads/image_upload/image_upload/global/63292_Screen Shot 2018-07-26 at 11.24.13 AM.png" style="width:100%"onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 6/25/18">
    </div>
    
    <div class="w3-col l3 m6">
      <img src="https://cms.jotform.com/uploads/image_upload/image_upload/global/63291_Screen Shot 2018-07-26 at 11.20.00 AM.png" style="width:100%"onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 6/26/18">
    </div>
    <div class="w3-col l3 m6">
      <img src="" style="width:100%"onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 6/27/18">
    </div>
    
    <div class="w3-col l3 m6">
      <img src="" style="width:100%"onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 6/28/18">
          </div>

    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 7/02/18">
    </div>
    
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 7/03/18">
    </div>
    
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 7/05/18">
    </div>
    
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 7/09/18">
    </div>
    
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 7/10/18">
    </div>
     
     <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 7/11/18">
    </div>
    
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 7/18/18">
    </div>
    
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 7/19/18">
    </div>
    
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Mindfulness 7/23/18">
    </div>


    </div>
  </div>
</div>
<!-- CS Mindfulness -->
    </div>
  </div>
</div>
<div class="w3-container w3-center w3-dark-grey" style="padding:128px 16px" id="pricing">
  <h3 class = "w3-center">CS Mindfulness"</h3>
  <p class="w3-center w3-large">Joseph Johnson</p>
  <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="CS Mindfulness 6/20/18">
    </div>
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="CS Mindfulness 6/21/18">
    </div>
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="CS Mindfulness 6/25/18">
    </div>
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="CS Mindfulness 6/26/18">
    </div>
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="CS Mindfulness 7/02/18">
    </div>
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="CS Mindfulness 7/03/18">
    </div>
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="CS Mindfulness 7/09/18">
    </div>
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="CS Mindfulness 7/11/18">
    </div>
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="CS Mindfulness 7/12/18">
    </div>
    <div class="w3-col l3 m6">
      <img src="" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="CS Mindfulness 7/23/18">
    </div>



    </div>
  </div>
</div>
<!-- Contact Section -->
    </div>
  </div>
</div>
<div class="w3-container w3-light-grey" style="padding:128px 16px" id="contact">
  <h3 class="w3-center">CONTACT</h3>
  <p class="w3-center w3-large">Lets get in touch. Send me a message:</p>
  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-half">
      <p><i class="fa fa-map-marker fa-fw w3-xxlarge w3-margin-right"></i>Richmond,CA </p>
      <p><i class="fa fa-phone fa-fw w3-xxlarge w3-margin-right"></i> Phone: 5103677418</p>
      <p><i class="fa fa-envelope fa-fw w3-xxlarge w3-margin-right"> </i> Email: Joseph.Johnson@hgs.hiddengeniusproject.org</p>
      <br>
      <form action="/action_page.php" target="_blank">
        <p><input class="w3-input w3-border" type="text" placeholder="Name" required name="Name"></p>
        <p><input class="w3-input w3-border" type="text" placeholder="Email" required name="Email"></p>
        <p><input class="w3-input w3-border" type="text" placeholder="Subject" required name="Subject"></p>
        <p><input class="w3-input w3-border" type="text" placeholder="Message" required name="Message"></p>
        <p>
          <button class="w3-button w3-black" type="submit">
            <i class="fa fa-paper-plane"></i> SEND MESSAGE
          </button>
        </p>
      </form>
    </div>
    <div class="w3-half">
