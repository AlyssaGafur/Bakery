<!DOCTYPE html>
<html lang="en">
<head>
  <title>Cakes, Cookies, Confections</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link href="https://fonts.googleapis.com/css?family=Caveat" rel="stylesheet" type="text/css">
  <link href="https://fonts.googleapis.com/css?family=Yellowtail" rel="stylesheet" type="text/css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <style>
  body {
      font: 400 30px Caveat, cursive;
      line-height: 1.8;
      color: #818181;
      background: url('http://1.bp.blogspot.com/-PPYoo52OMpA/TpKtRqQaNMI/AAAAAAAAB5k/2Pr1EEDkzrs/s1600/09-polaroid.newyork.193a.jpg');
    background-size: 79%;
    image opacity: 0.9;
  }
  h2 {
      font-size: 36px;
      text-transform: uppercase;
      color: #F7DC6F  ;
      font-weight: 600;
      margin-bottom: 30px;
  }
  h4 {
      font-size: 34px;
      line-height: 1.375em;
      color: #F8A048;
      font-weight: 400;
      margin-bottom: 30px;
  }  
  p {
	  color: #F1948A;
  }
  .jumbotron {
      background-color: #FF9966;
      color: #CCFFFF;
      padding: 100px 25px;
      font-family: Yellowtail, cursive;
  }
  .container-fluid {
      padding: 60px 50px;
      
  }
  .bg-grey {
      background-color: #CC6699;
      
  }
  .logo-small {
      color: #FF9966;
      font-size: 50px;
  }
  .logo {
      color: #8CE0D1;
      font-size: 200px;
  }
  .thumbnail {
      padding: 0 0 15px 0;
      border: none;
      border-radius: 0;
  }
  .thumbnail img {
      width: 100%;
      height: 100%;
      margin-bottom: 10px;
  }
  .carousel-control.right, .carousel-control.left {
      background-image: none;
      color: #CC99CC;
  }
  .carousel-indicators li {
      border-color: #CC99CC;
  }
  .carousel-indicators li.active {
      background-color: #CC99CC;
  }
  .item h4 {
      font-size: 32px;
      line-height: 1.375em;
      font-weight: 400;
      font-style: italic;
      margin: 70px 0;
  }
  .item span {
      font-style: normal;
  }
  .panel {
      border: 1px solid #CC99CC; 
      border-radius:0 !important;
      transition: box-shadow 0.5s;
  }
  .panel:hover {
      box-shadow: 5px 0px 40px rgba(0,0,0, .2);
  }
  .panel-footer .btn:hover {
      border: 1px solid #CC99CC;
      background-color: #fff !important;
      color: #f4511e;
  }
  .panel-heading {
      color: #fff !important;
      background-color: #CC99CC !important;
      padding: 25px;
      border-bottom: 1px solid transparent;
      border-top-left-radius: 0px;
      border-top-right-radius: 0px;
      border-bottom-left-radius: 0px;
      border-bottom-right-radius: 0px;
  }
  .panel-footer {
      background-color: white !important;
  }
  .panel-footer h3 {
      font-size: 32px;
  }
  .panel-footer h4 {
      color: #aaa;
      font-size: 14px;
  }
  .panel-footer .btn {
      margin: 15px 0;
      background-color: #CC99CC;
      color: #fff;
  }
  .navbar {
      margin-bottom: 0;
      background-color: #CC99CC;
      z-index: 9999;
      border: 0;
      font-size: 14px !important;
      line-height: 1 !important;
      letter-spacing: 2px;
      border-radius: 0;
      font-family: Yellowtail, cursive;
  }
  .navbar li a, .navbar .navbar-brand {
      color: #99FFCC;
      font-size: 16px;
  }
  .navbar-nav li a:hover, .navbar-nav li.active a {
      color: #99FFFF !important;
      background-color: #FFCC33   !important;
  }
  .navbar-default .navbar-toggle {
      border-color: transparent;
      color: #fff !important;
  }
  footer .glyphicon {
      font-size: 20px;
      margin-bottom: 20px;
      color: #CC99CC;
  }
  .slideanim {visibility:hidden;}
  .slide {
      animation-name: slide;
      -webkit-animation-name: slide;
      animation-duration: 1s;
      -webkit-animation-duration: 1s;
      visibility: visible;
  }
  @keyframes slide {
    0% {
      opacity: 0;
      transform: translateY(70%);
    } 
    100% {
      opacity: 1;
      transform: translateY(0%);
    }
  }
  @-webkit-keyframes slide {
    0% {
      opacity: 0;
      -webkit-transform: translateY(70%);
    } 
    100% {
      opacity: 1;
      -webkit-transform: translateY(0%);
    }
  }
  @media screen and (max-width: 768px) {
    .col-sm-4 {
      text-align: center;
      margin: 25px 0;
    }
    .btn-lg {
        width: 100%;
        margin-bottom: 35px;
    }
  }
  @media screen and (max-width: 480px) {
    .logo {
        font-size: 150px;
    }
  }
  </style>
</head>
<body id="myPage" data-spy="scroll" data-target=".navbar" data-offset="60">

<nav class="navbar navbar-default navbar-fixed-top">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#myPage">We'll make any day a sweet day!</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#about">ABOUT</a></li>
        <li><a href="#services">THE CLASSICS</a></li>
        <li><a href="#portfolio">THE SWEETS OF THE WORLD</a></li>
        <li><a href="#pricing">SWEETS</a></li>
        <li><a href="#contact">CONTACT US</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="jumbotron text-center">
  <h1>Cakes, Cookies, Confections</h1> 
  <p>We specialize in all sweet treats!</p> 
  <form>
    <div class="input-group">
      <input type="email" class="form-control" size="50" placeholder="Email Address" required>
      <div class="input-group-btn">
        <button type="button" class="btn btn-danger">Subscribe</button>
      </div>
    </div>
  </form>
</div>

<!-- Container (About Section) -->
<div id="about" class="container-fluid">
  <div class="row">
    <div class="col-sm-8">
      <h2>About Cakes, Cookies, Confections</h2><br>
      <h4>Starting out in a small town in Brooklyn, three best friends came together to return their blessings to the world. Beginning to have a passion for baking all sorts of things since they were children, they grew up to open their own sweet shop in their very own hometown which soon expanded around the world.</h4><br>
      <p>At Cakes, Cookies, Confections, we specialize in all sorts of sweet treats. From cakes and cookies, to cannolies and tarts. We even make our own cotton candy! We serve anyone, at any age, no matter what size; for big occasions we make our Cannoli tray, or even the classic Assorted Cookie tray. For those lazy mornings, try out our rainbow bagels or our Breakfast Tray with crumb buns, pecan, and various flavors of pastries. We are best known for our custom cakes, especially our pies; from the classic Apple Pie to the obnoxious Lemon Crumb Pie. At Cakes, Cookies, Confections we bring the sweetnesses of the world right to the taste buds of your mouth.  .</p>
      <br><button class="btn btn-default btn-lg">Get in Touch</button>
    </div>
    <div class="col-sm-4">
      <img src=https://s-media-cache-ak0.pinimg.com/originals/e5/e8/3c/e5e83c163997220740683f0efd1fb1a4.jpg>
    </div>
  </div>
</div>

<div class="container-fluid bg-grey">
  <div class="row">
    <div class="col-sm-4">
      <span class="glyphicon glyphicon-globe logo slideanim"></span>
    </div>
    <div class="col-sm-8">
      <h2>Our Values</h2><br>
      <h4><strong>MISSION:</strong> Our mission at Cakes, Cookies, Confections is to provide everyone with the oppurtunity to experince something out of this world, since we're not all astronauts. .</h4><br>
      <p><strong>VISION:</strong> Our vision at Cakes, Cookies, Confections is to challenge the social norms of society; we have a vision of a world where there is no such thing as hunger. Especially in the lower classes of society, hunger is something that is considered normal, and that is not a good thing. We want to change that.
      Here at at Cakes, Cookies, Confections we donate 37% of our proceeds to various organizations that contribute to stop the expansion of hunger, it has invaded too many lives. With your help, every dollar spent at one of our stores, is a step towards getting the many lives exposed to hunger the help they need to battle such an affliction .</p>
    </div>
  </div>
</div>

<!-- Container (Services Section) -->
<div id="services" class="container-fluid text-center">
  <h2>Through Time</h2>
  <h4>The Timeline Of The Classic Confections</h4>
  <br>
  <div class="row slideanim">
    <div class="col-sm-4">
      <img src=https://img.huffingtonpost.com/asset/561e63011400002200c79e4a.jpeg?ops=scalefit_600_noupscale width="250" height="250">
      <h4>Cherry Squares</h4>
      <p style="color:#990000">The first of our classic sweet treats in 1999!</p>
    </div>
    <div class="col-sm-4">
      <img src=https://img.huffingtonpost.com/asset/561e62fb1400002b003c832e.jpeg?ops=scalefit_600_noupscale width="250" height="250">
      <h4>Meyer Lemon Bars</h4>
      <p style="color:#FFFF00">In 2002, we took those lemon, and made them into something sweet!</p>
    </div>
    <div class="col-sm-4">
      <img src=http://www.lovethispic.com/uploaded_images/41325-Ice-Cream-And-Apple-Pie.jpg width="250" height="250">
      <h4>Apple Pie Ice Cream</h4>
      <p style="color:#996633">Our twist on an old-fashioned confection began in 2007!</p>
    </div>
  </div>
  <br><br>
  <div class="row slideanim">
    <div class="col-sm-4">
      <img src=https://img.huffingtonpost.com/asset/561e63001400006f003c8338.jpeg?ops=scalefit_600_noupscale width="250" height="250">
      <h4>Brown Butter Rum Canoli</h4>
      <p style="color:#663333">This tangy sweet treat has been perfect for those who need a drink before lunch, since 2009!</p>
    </div>
    <div class="col-sm-4">
      <img src=https://img.huffingtonpost.com/asset/561e63031400002a00c79e4c.jpeg?ops=scalefit_600_noupscale width="250" height="250">
      <h4>Mini Pineapple Upside Down Cakes</h4>
      <p style="color:#FF9933">With all natural, organic ingredients, these cakes have been turning minds upside down since 2012!</p>
    </div>
    <div class="col-sm-4">
      <img src=https://img.huffingtonpost.com/asset/561e62fc1200002e007e5140.jpeg?ops=scalefit_600_noupscale width="250" height="250">
      <h4 style="color:#303030;">Butterfinger Cookie Dough Cheesecake Bars</h4>
      <p style="color:#FFCC99">Our latest Confection (est. 2018) is a masterpiece by itself, no introduction necessary!</p>
    </div>
  </div>
</div>

<!-- Container (Portfolio Section) -->
<div id="portfolio" class="container-fluid text-center bg-grey">
  <h2>The Sweet Past</h2><br>
  <h4>What we have created</h4>
  <div class="row text-center slideanim">
    <div class="col-sm-4">
      <div class="thumbnail">
        <img src=https://assets.bonappetit.com/photos/57ace09bf1c801a1038bc874/16:9/w_1200,c_limit/matcha-doughnuts.jpg alt="Brooklyn" width="400" height="300">
        <p><strong>Brooklyn</strong></p>
        <p>Our very first location in Brooklyn, New York City is where our Matcha Donut  was not only born, but it's become a tradition to our schedules...it's a great end to any day.</p>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="thumbnail">
        <img src=https://assets.marthastewart.com/styles/wmax-750/d28/dutch-baby-0077-hero-d113086/dutch-baby-0077-hero-d113086_horiz.jpg?itok=eNRsFc_s alt="Paris" width="400" height="300">
        <p><strong>Paris</strong></p>
        <p>In Paris, France, our Apple Dutch Baby is everyones favorite, especially with a hint of blueberries.</p>
      </div>
    </div>
    <div class="col-sm-4">
      <div class="thumbnail">
        <img src=https://us.hellomagazine.com/images/stories/1/2016/01/26/000/125/074/featured_5_3.jpg alt="Sydney" width="400" height="300">
        <p><strong>Sydney</strong></p>
        <p>Our last Cakes, Cookies, Confections to open was down under in Sydney, Austrailia, and their favorite dessert is our Cotton Candy "Shake". </p>
      </div>
    </div>
  </div><br>
  
  <h2>What our customers say</h2>
  <div id="myCarousel" class="carousel slide text-center" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
      <li data-target="#myCarousel" data-slide-to="3"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
      <div class="item active">
        <h4>"This company is the best, especially when it comes to catering work occasions!. I am always overwhelmed with what they deliver!"<br><span>Michael Roe, Vice President, Colorfast</span></h4>
      </div>
      <div class="item">
        <h4>"One word... WOW!!"<br><span>Sandya Persuade, President, Google</span></h4>
      </div>
      <div class="item">
        <h4>"Could I... BE any more happy with this company? I think not!"<br><span>Sandra Sandor, Fashion Designer, NYFW</span></h4>
      </div>
      <div class="item">
	 <h4>"I never knew something was misisng from my mornings until I devoured my first Cinnamon-Date Buns!"<br><span>Abella Anderson, Reporter, French Times</span></h4>
     </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>

<!-- Container (Pricing Section) -->
<div id="pricing" class="container-fluid">
  <div class="text-center">
    <h2>$weet$</h2>
    <h4>View the prices of our unlimited Confections for your time of day!</h4>
  </div>
  <div class="row slideanim">
    <div class="col-sm-4 col-xs-12">
      <div class="panel panel-default text-center">
        <div class="panel-heading">
          <h1>Breakfast</h1>
        </div>
        <div class="panel-body">
          <p><strong>Cinnamon-Date Buns</strong></p>
          <p><strong>Apple-Almond Turnover</strong></p>
          <p><strong>Matcha Doughnuts</strong></p>
          <p><strong>Cheddar-Walnut Scones</strong></p>
          <p><strong>Strawberry Jam Biscuits</strong></p>
        </div>
        <div class="panel-footer">
          <h3>$2</h3>
          <h4>per sweet</h4>
          <button class="btn btn-lg">Love</button>
        </div>
      </div>      
    </div>     
    <div class="col-sm-4 col-xs-12">
      <div class="panel panel-default text-center">
        <div class="panel-heading">
          <h1>Brunch</h1>
        </div>
        <div class="panel-body">
          <p><strong>Blueberry Muffins with Oat Crumble</strong> Lorem</p>
          <p><strong>Pumpkin Bread with Toasted Coconut</strong></p>
          <p><strong>Apple Dutch Baby</strong></p>
          <p><strong>Kouign-Amann</strong></p>
          <p><strong>Plum Tarts with Honey and Black Pepper</strong></p>
        </div>
        <div class="panel-footer">
          <h3>$7</h3>
          <h4>per sweet</h4>
          <button class="btn btn-lg">Love</button>
        </div>
      </div>      
    </div>       
    <div class="col-sm-4 col-xs-12">
      <div class="panel panel-default text-center">
        <div class="panel-heading">
          <h1>Desert</h1>
        </div>
        <div class="panel-body">
          <p><strong>French Yogurt Cake</strong> </p>
          <p><strong>Black Sesame-Pear Tea Cake</strong></p>
          <p><strong>Raspberry-Hazelnut Galette</strong></p>
          <p><strong>Chocolate Tea Cake</strong></p>
          <p><strong>Cinnamon Sugar-Topped Cardamon Tea Cakes</strong></p>
        </div>
        <div class="panel-footer">
          <h3>$12</h3>
          <h4>per sweet</h4>
          <button class="btn btn-lg">Love</button>
        </div>
      </div>      
    </div>    
  </div>
</div>

<!-- Container (Contact Section) -->
<div id="contact" class="container-fluid bg-grey">
  <h2 class="text-center">CONTACT</h2>
  <div class="row">
    <div class="col-sm-5">
      <p>Contact us and we'll get back to you within 24 hours.</p>
      <p><span class="glyphicon glyphicon-map-marker"></span> New York, US</p>
      <p><span class="glyphicon glyphicon-phone"></span> +00 52186314897</p>
      <p><span class="glyphicon glyphicon-envelope"></span> alyssa.gafur@gmail.com</p>
    </div>
	<form action="http://www.SnapHost.com/captcha/send.aspx" id="ContactUsCaptchaWebForm" method="post" onsubmit="return ValidateForm(this);" target="_top">
	<input name="skip_WhereToSend" type="hidden" value="your@email.com" />
	<input name="skip_SnapHostID" type="hidden" value="A7HUUW2HESJ7" />
	<input name="skip_WhereToReturn" type="hidden" value="http://www.YourWebsiteAddress.com/ThankYouPage.htm" />
	<input name="skip_Subject" type="hidden" value="Contact Us Form" />
	<input name="skip_ShowUsersIp" type="hidden" value="1" />
	<input name="skip_SendCopyToUser" type="hidden" value="1" />
	<script type="text/javascript">
	function ValidateForm(frm) {
	if (frm.Name.value == "") {alert('Name is required.');frm.Name.focus();return false;}
	if (frm.FromEmailAddress.value == "") {alert('Email address is required.');frm.FromEmailAddress.focus();return false;}
	if (frm.FromEmailAddress.value.indexOf("@") < 1 || frm.FromEmailAddress.value.indexOf(".") < 1) {alert('Please enter a valid email address.');frm.FromEmailAddress.focus();return false;}
	if (frm.Comments.value == "") {alert('Please enter comments or questions.');frm.Comments.focus();return false;}
	if (frm.skip_CaptchaCode.value == "") {alert('Enter web form code.');frm.skip_CaptchaCode.focus();return false;}
	return true; }
	function ReloadCaptchaImage(captchaImageId) {
	var obj = document.getElementById(captchaImageId);
	var src = '' + obj.src;
	obj.src = '';
	var date = new Date();
	var pos = src.indexOf('&rad=');
	if (pos >= 0) { src = src.substr(0, pos); }
	obj.src = src + '&rad=' + date.getTime();
	return false; }
	</script>
	<table border="0" cellpadding="5" cellspacing="0" width="600">
	<tr>
	<td><b>Name*:</b></td>
	<td><input name="Name" type="text" maxlength="60" style="width:350px;" /></td>
	</tr><tr>
	<td><b>Phone number:</b></td>
	<td><input name="PhoneNumber" type="text" maxlength="43" style="width:350px;" /></td>
	</tr><tr>
	<td><b>Email address*:</b></td>
	<td><input name="FromEmailAddress" type="text" maxlength="60" style="width:350px;" /></td>
	</tr><tr>
	<td><b>Comments and questions*:</b></td>
	<td><textarea name="Comments" rows="7" cols="40" style="width:350px;"></textarea></td>
	</tr><tr>
	<td colspan="2" align="center"> <br />
	<table border="0" cellpadding="0" cellspacing="0">
	<tr><td colspan="2" style="padding-bottom:18px;">
	<!-- Please check our ProCaptcha service which is ad-free:
	http://www.SnapHost.com/captcha/ProCaptchaOverview.aspx -->
	<a href="http://www.snaphost.com/captcha/captchaguestbook.aspx" alt="guestbook page" title="guestbook page">
	guestbook page</a></td></tr>
	<tr valign="top"><td> <i>Enter web form code*:</i>
	<input name="skip_CaptchaCode" type="text" style="width:80px;" maxlength="6" />
	</td><td>
	<a href="http://www.snaphost.com/captcha/ReadyForms/ContactUsForm.aspx"><img id="CaptchaImage" alt="Contact Us form" title="HTML code for Contact Us form"
	style="margin-left:20px;"
	src="http://www.SnapHost.com/captcha/CaptchaImage.aspx?id=A7HUUW2HESJ7&ImgType=2" /></a><br />
	<a href="#" onclick="return ReloadCaptchaImage('CaptchaImage');"><span style="font-size:12px;">reload image</span></a> </td></tr>
	</table> <br />
	* - required fields. &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
	<input name="skip_Submit" type="submit" value="Submit" />
	</td></tr>
	</table><br />
	</form>
    
<html>
<body>


<!-- Add Google Maps -->
<div id="googleMap" style="height:400px;width:100%;"></div>
<script>
function myMap() {
var myCenter = new google.maps.LatLng(40.6451594,-74.0850804);
var mapProp = {center:myCenter, zoom:12, scrollwheel:false, draggable:false, mapTypeId:google.maps.MapTypeId.ROADMAP};
var map = new google.maps.Map(document.getElementById("googleMap"),mapProp);
var marker = new google.maps.Marker({position:myCenter});
marker.setMap(map);
}
</script>
<script src="https://maps.googleapis.com/maps/api/js?callback=myMap"></script>
<!--
To use this code on your website, get a free API key from Google.
Read more at: https://www.w3schools.com/graphics/google_maps_basic.asp
-->

<footer class="container-fluid text-center">
  <a href="#myPage" title="To Top">
    <span class="glyphicon glyphicon-chevron-up"></span>
  </a>
  <p>Established by <a href="http://www.bettybakery.com/" title="Visit our friends!">www.bettybakery.com</a></p>
</footer>

<script>
$(document).ready(function(){
  // Add smooth scrolling to all links in navbar + footer link
  $(".navbar a, footer a[href='#myPage']").on('click', function(event) {
    // Make sure this.hash has a value before overriding default behavior
    if (this.hash !== "") {
      // Prevent default anchor click behavior
      event.preventDefault();

      // Store hash
      var hash = this.hash;

      // Using jQuery's animate() method to add smooth page scroll
      // The optional number (900) specifies the number of milliseconds it takes to scroll to the specified area
      $('html, body').animate({
        scrollTop: $(hash).offset().top
      }, 900, function(){
   
        // Add hash (#) to URL when done scrolling (default click behavior)
        window.location.hash = hash;
      });
    } // End if
  });
  
  $(window).scroll(function() {
    $(".slideanim").each(function(){
      var pos = $(this).offset().top;

      var winTop = $(window).scrollTop();
        if (pos < winTop + 600) {
          $(this).addClass("slide");
        }
    });
  });
})
</script>

</body>
</html>
