<!DOCTYPE html>
<html>
<head>
<title></title>
<meta charset="utf-8">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<link href="https://fonts.googleapis.com/css?family=Bad+Script|Caveat|Comfortaa|Encode+Sans+Condensed|Shadows+Into+Light" rel="stylesheet">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script> 
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css" integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU" crossorigin="anonymous">
  <link href="https://fonts.googleapis.com/css?family=Bai+Jamjuree" rel="stylesheet">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>
<style>
 html, body {
        height: 100%;
        margin: 0;
        padding: 0;
      
      }
  body{
    font-family: 'Bai Jamjuree', sans-serif;
    line-height: 1.8;
    background-color:white;
  }
   .navbar {
      margin-bottom: 0;
      background: #FDC830;
      background: -webkit-linear-gradient(to right, #F37335, #FDC830);  
      background: linear-gradient(to right, #F37335, #FDC830);
      z-index: 9999;
      border: 0;
      font-size: 12px !important;
      letter-spacing: 3px;
      border-radius: 0;
      font-family: Montserrat, sans-serif;
  }
  .navbar li a, .navbar .navbar-brand {
      color: #fff !important;
      margin-top:10px;
  }
  .navbar-nav li a:hover, .navbar-nav li.active a {
      color: #f4511e !important;
      background-color: #fff !important;
     margin-top:10px;
  }
  .navbar-default .navbar-toggle {
      border-color: transparent;
      color: #fff !important;
  }
  .navbar-brand{
  font-size:20px;
  font-family: 'Bai Jamjuree', sans-serif;
  margin:3px;
  padding:10px 6px;
  }
  .nav{
    font-size:15px;
    font-weight:900px;
  }
.container-fluid{
background: #FDC830;
background: -webkit-linear-gradient(to right, #F37335, #FDC830); 
background: linear-gradient(to right, #F37335, #FDC830);
        color:white;
 }  
 .li{
    margin:5px;
    padding-left:250px;
  }
  .lovebar{
        box-shadow: 0px 5px 10px rgba(0,0,0,.5);
        background-color:#262626;     
  }
  .hell{
    color:black;
    }
  
/*EDITING FOR SEARCHING*/
h1{
  text-align: center;
  font-size: 6vw;
  text-shadow:0px 1px 2px rgba(0,0,0,.5);
  font-family: 'Bai Jamjuree', sans-serif;
  font-weight:700;
}
  h2{
    font-family: 'Bai Jamjuree', sans-serif;
    letter-spacing:1px;
  }
  p{
    letter-spacing:2px;
    line-spacing:150%;
  }
h3{
    font-family: 'Bai Jamjuree', sans-serif;
  line-height:1.375em;
  color:#303030;
  margin-bottom:30px;
}

 /*EDITING FOR FORM*/                               

input[type=text]{
    width: 100%;
    padding: 12px 20px;
    margin:5px 2px;
    display: inline-block;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
  }
.jokey{
     font-size:16px;
}
            /*CARD EDITING*/
                                   /*BUTTON EDITING*/
                                    
  .btn-success{
    width:100%;
  }
  .btn-success:hover{
    box-shadow:8px 6px 16px rgba(0,0,0,.5);
    cursor:pointer;
  }
  .btn-information{
    margin:5px 2px;
  }
  /*FOR IMAGE GALERY AND JUMBOTRON*/
  .obey{
    float:right;
    border:1px solid;
    color:white;
    border-radius: 10px;
    background: green;
    padding:5px;
    width:100%;
  }
  
  .fas{
    color:#f4511e;
    font-size:100px;
    margin:30px;
  }    
  .fab{
    color:#f4511e;
    font-size:150px;
    margin-left:30px;
  }
  .far{
    color:#f4511e;
    font-size:150px;
    margin-left:30px;
  }
  .glyphicon-qrcode{
    font-size:54px;
  }
  .glyphicon-qrcode:hover{
    box-shadow:2px 4px 8px rgba(0,0,0,.5);
  }
  
  /*log-in*/
  .decor{
    background-color:green;
    border:none;
    text-align:center;
    color:white;
    border-radius:15px;
    cursor:pointer;
  }
 
/*Button*/
  button{
    background-color:green;
    border:none;
    color:white;
    border-radius:10px;
  }
  /* Parallax Effect */
 .parallax{
    background-image:url("https://images.unsplash.com/photo-1536141052286-b860cb7dca4b?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=451aa6efccfd7b5fe0f92d5287c1c757&auto=format&fit=crop&w=1052&q=80");
    background-image:fixed; 
    min-height: 500px;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover; 
    margin-top:-50px;
  }
   .parallax2{
    background-image:url("https://images.pexels.com/photos/139398/thermometer-headache-pain-pills-139398.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260");
    background-image:fixed; 
    min-height: 500px;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover; 
  }
   .parallax3{
    background-image:url("https://images.unsplash.com/photo-1520931674431-de5b4b2cc562?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=cf892a06a8141d8d0823c4b4c6cce613&auto=format&fit=crop&w=1950&q=80");
    background-image:fixed; 
    min-height: 700px;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover; 
  }
  .parallax4{
    background-image:url("");
    background-image:fixed; 
    min-height: 800px;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover; 
  }
   .parallax5{
    background-image:url("https://images.unsplash.com/photo-1512428559087-560fa5ceab42?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=665f85219b6ad4ee4b274871593f3394&auto=format&fit=crop&w=1950&q=80");
    background-image:fixed; 
    min-height: 500px;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover; 
  }
  .test h5{
    width:300px;
    background-color:rgba(0,0,0,0.6);
    color:#fff;
    display:inline;
    padding:20px;
    top:950px;
    text-transform:uppercase;
    left:20px;
    font-weight:900px;
    letter-spacing:2px;
    position:absolute;
    font-size:50px;
  }
  
  .panel-default:hover{
    box-shadow:2px 4px 8px rgba(0,0,0,.5);
  }
  #appoint{
    background-color:#eee;
    margin-top:-200px;
    margin-bottom:-30px;
    
  }
  #myVideo {
    right: 0;
    bottom: 0;
    min-width: 100%; 
    min-height: 100%;
}
  #online{
 margin-bottom:-10px;
  }
  .slideanim {visibility:hidden;}
.slide {
    /* The name of the animation */
    animation-name: slide;
    -webkit-animation-name: slide; 
    /* The duration of the animation */
    animation-duration: 1s; 
    -webkit-animation-duration: 1s;
    /* Make the element visible */
    visibility: visible; 
}

/* Go from 0% to 100% opacity (see-through) and specify the percentage from when to slide in the element along the Y-axis */
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
  .jumbotron {
    color: #fff;
    padding: 100px 25px;
    text-align:center;
    font-size:3vw;
    font-family: 'Bai Jamjuree', sans-serif;
  }
  
 /*All about different medicines*/ 
.different{
   margin-top:-200px;
   margin-left:0;
   margin-right:0; 
   margin-bottom:150px; 
   text-align:center;
background: #FDC830;
background: -webkit-linear-gradient(to right, #F37335, #FDC830); 
background: linear-gradient(to right, #F37335, #FDC830);
  }
  .about{
      width:80%;
      background-color:#f4511e;
      height:200px;
      border:none;
      margin:10px;
      padding:10px 20px;
      font-size:40px;
      text-align:center;
      border-radius:100px 50px 90px 50px;
      box-shadow:0px 1px 3px rgba(0,0,0,.5);
    color:white;
    transition:0.5s;
  }
  .about:hover{
    width:80%;
    heigth:200px;
    background-color:rgb(0,0,0);
    color:white;
    opacity:0.5;
    border-radius:50px 50px 50px 50px;
  }
.about .back{
     position:absolute;
     width:100%;
  heigth:60%;
  bottom:0;
  padding:20px;
  box-sizing:border-box;
  text-align:center;
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
.about .content{
   position:absolute;
  width:100%;
  height:60%;
  bottom:-100%;
  padding:20px;
  box-sizing:border-box;
  text-align:center;
  transition:0.5s;
}
.about:hover .content{
 bottom:0; 
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
  
/*------------------------------Slideshow-------------------*/  
  .carousel-inner{
    margin-top:0;
    text-align:center;
    margin-bottom:-5%;
  }
  .item{
    margin-top:0;
    margin-bottom:500px;
    text-align:center;
  }
  .item h4 {
    font-size: 19px;
      line-height: 1.375em;
      font-weight: 400;
      font-style: italic;
      margin:20px 0;
  }
  .item span {
      font-style: normal;
  }
  
  /*-------------------------------------Modal------------------------------------------*/  
  .modal{
    text-align:center;
    padding:0;
  }
   .modal-dialog{
     cursor:pointer;
     font-size:30px;
     margin-top:20px;
     margin-left:0px;
     text-align:left;
     vertical-align:middle;
     background-color:white;
     display:inline-block;
   }
   .modal-heading{
     margin-left:15px;
   }
   .modal-body{
     margin-left:10px;
     text-align:left;
   }
   .btn-danger{
    font-size:16px;
    margin-left:20px;  
   }
  .modal:before{
    content:'';
    display:inline-block;
    vertical-align:middle;
    margin-right:4px;
  }
  
/*---------------------------------------------------------------------------------*/  
  
  
                              /*All about languages*/
  .language{
    font-size:25px;
    font-weight:900px;
    width:100%;
    height:100%;
  }
  </style>
  <script>
  $(window).scroll(function() {
  $(".slideanim").each(function(){
    var pos = $(this).offset().top;

    var winTop = $(window).scrollTop();
    if (pos < winTop + 600) {
      $(this).addClass("slide");
    }
  });
});
</script>
  <!--.................   GAPE HTML START .........-->   
<body> 
  <script>
  function myFun(){
  alert("Your appointment is fixed with Dr.Ravi Kumar");
  alert("You receive a message");
}  
  </script>  
<body id="myPage" data-spy="scroll" data-target=".navbar" data-offset="60">
<nav class="navbar navbar-default navbar-fixed-top">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#myPage">JUST CHECK IN</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#about">HOME</a></li>
       <li><a href="/guide">GUIDE</a></li> 
        <li><a href="/donatefile">DONATE</a></li>
        <li><a href="/verified">VERIFIED MEDICAL STORES</a></li>
         <li><a href="/experts">EXPERT</a></li>
        <li><a href="/button">LOG-IN</a></li>
      </ul>
    </div>
  </div>
</nav><br> 
<!--FORM FOR SEARCHING-->
<div class="jumbotron text-center"style="background: #FDC830;
background: -webkit-linear-gradient(to right, #F37335, #FDC830);
background: linear-gradient(to right, #F37335, #FDC830);
">
  <h1>QUICK SEARCH</h1> 
  <p></p> 
  <form>
    <div class="input-group">
      <input type="text" onclick="myEnter()"class="form-control"placeholder="Enter medicine name" required>
      <div class="input-group-btn">
        <button type="button"onclick="myEnter()"class="btn btn-success">Search</button>
      </div>
    </div>
  </form>
</div>
<br>

<!--NEW FEATURE-->                                    
  <div class="hell"id="about">
 <div class="container"> 
  <div class="row">  
  <div class="col-md-8">
<h2>ABOUT US</h2>
<p>Actually our Company create for you people,we are obliged to help you people we are always ready <strong>24/7</strong> in your service.WE provide a quick search to quickly search medicine that your near one's need,at your nearest distance.People who live without goals have no purpose and it is obvious even in their body language. They are on permanent idle, they slouch, they list from side to side. Their conversations dawdle. They telephone you: “Hey, I’m just calling. I wasn’t doing anything, so I thought I’d call you.” Well, don’t call ME. I’VE got things to do.
<strong>Happy To Help You</strong>
</p>
 </div>
   <div class="col-md-4">
<button type="button" class="btn btn-information  language" data-toggle ="modal" data-target ="#myModal">Select a language :)</button> 
  <div class="modal fade" id="myModal">
  <div class="modal-dialog modal-dialog-centered modal-lg">
    <div class="content">
  <div class="modal-heading">
    <h2 class="modal-title">Select a language</h2>
    <hr>
      </div>
    <div class="modal-body">
      <h2>Select a Language</h2>
      <button class="btn btn-success language"><a href="https://translate.google.com/translate?sl=en&tl=hi&js=y&prev=_t&hl=en&ie=UTF-8&u=https%3A%2F%2Ffathomless-spire-48410.herokuapp.com%2Fload&edit-text=">Hindi</a></button>
      <button class="btn btn-success language"><a href="https://translate.google.com/translate?hl=en&sl=en&tl=ta&u=https%3A%2F%2Ffathomless-spire-48410.herokuapp.com%2Fload">Tamil</a></button>
      <button class="btn btn-success language"><a href="https://translate.google.com/translate?hl=en&sl=en&tl=gu&u=https%3A%2F%2Ffathomless-spire-48410.herokuapp.com%2Fload">Gujarati</a></button>
            <button class="btn btn-success language"><a href="https://translate.google.com/translate?hl=en&sl=en&tl=pa&u=https%3A%2F%2Ffathomless-spire-48410.herokuapp.com%2Fload">Punjabi</a></button>
            <button class="btn btn-success language"><a href="https://translate.google.com/translate?hl=en&sl=en&tl=ru&u=https%3A%2F%2Ffathomless-spire-48410.herokuapp.com%2Fload">Russian</a></button>
            <button class="btn btn-success language"><a href="https://translate.google.com/translate?hl=en&sl=en&tl=ne&u=https%3A%2F%2Ffathomless-spire-48410.herokuapp.com%2Fload">Nepali</a></button>
            <button class="btn btn-success language"><a href="https://translate.google.com/translate?hl=en&sl=en&tl=ur&u=https%3A%2F%2Ffathomless-spire-48410.herokuapp.com%2Fload">Urdu</a></button>
            <button class="btn btn-success language"><a href="https://translate.google.com/translate?hl=en&sl=en&tl=te&u=https%3A%2F%2Ffathomless-spire-48410.herokuapp.com%2Fload">Telugu</a></button>
      <div class="modal-fotter">
        <button type="button" class="btn btn-danger" data-dismiss="modal">Close</button>
      </div>   
  </div>  
  </div>
  </div>
  </div>
</div>
</div>
</div>
    
    <div class="parallax5"></div> 
   <!--
  <video autoplay muted loop id="myVideo">
  <source src="http://mazwai.com/system/posts/videos/000/000/085/original/joel_wolter--finding_the_path.mp4?1407079011" type="video/mp4">
</video>
-->
      <div class="test">
        <h5>Shortcut cut life short</h5>
      </div>
<!--WE PROVIDE--> 
    
    
<div class="jumbotron">    
<h2 style="color:black; font-size:50px;font-weight:100px;">DOCTOR ADVICE</h2>
<hr>
<div class="container"id="online">    
  <div class="row">
  <div class="col-md-4">
  <div class="thumbnail">
  <img src="https://images.unsplash.com/photo-1496345875659-11f7dd282d1d?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=a0f994eef47e5fb1a67849703cc961b3&auto=format&fit=crop&w=1050&q=80"style="width:100%;">
      <div class="caption slideanim">
      <h2>Dr.CHRISTOPHER</h2>
       <hr>
      <p style="text-align:center; font-size:12px;">Enjoy your life more. After all, if everything in your life can be taken with a grain of positivity, you’ll find that life is so much more enjoyable!That creates a positivity.</p>
      </div>
      </div>
      </div>
      <div class="col-md-4">
      <div class="thumbnail">
      <img src="https://images.unsplash.com/photo-1485274466491-6c0baa1cfc2a?ixlib=rb-0.3.5&s=832ec77b34b13e88d5d281fc11618d09&auto=format&fit=crop&w=1050&q=80"style="width:100%;">
      <div class="caption slideanim">
      <h2>Dr.ALISTEN</h2>
        <hr>
      <p style="text-align:center; font-size:12px;">Boost your self-esteem. Once you get in the habit of thinking positively about external situations, you will soon get in the habit of being positive about yourself.</p>
      </div>
      </div>
  </div>
        <div class="col-md-4">
        <div class="thumbnail">
        <img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-0.3.5&s=0470e941c9ae0b47671d63f32f2fca1b&auto=format&fit=crop&w=1050&q=80"style="width:100%;">
        <div class="caption slideanim">
        <h2>Dr.STERLIN</h2> 
        <hr>  
        <p style="text-align:center; font-size:12px;">Form healthy, positive relationships. Being positive will cause you to look for the good in others, which will help you to form positive, productive relationships with them.</p>
        </div>
        </div>
        </div>
  </div>
  </div>
  </div>
  </div>   
<!--PARALLAX EFFECT--> 
<div class="parallax"></div>
 <!--                            -->
 <!-- OUR SERVICES -->  
<div id="services" class="container text-center slideanim">
<h3>OUR SERVICES</h3>
<p>WE PROVIDE YOU THE BEST OF US</p>
<div class="row">
<div class="col-md-4">
<i class="fas fa-shipping-fast slideanim"></i>
  <p>FASTEST DELIVERY</p>
</div>
<div class="col-md-4">
 <i class="fas fa-medkit slideanim"></i>
  <p>WE CARE</p>
</div>
<div class="col-md-4">
<i class="fas fa-glasses slideanim"></i>
  <p>NEAREST</p>
</div>
<div class="col-md-4">
 <i class="fas fa-phone slideanim"></i> 
  <p>WE ARE ALWAYS AVAILABLE</p>
</div>
<div class="col-md-4">
  <i class="fas fa-sitemap slideanim"></i>
  <p>SMALLEST ROUTE</p>
</div>
<div class="col-md-4">
  <i class="fas fa-award slideanim"></i>
  <p>FASTEST GROWING</p>
</div>
</div>
</div>
</div>
</div>
<br>
<!--              Parallax2           -->
<div class="parallax2"> </div>
  
  
                        <!--Different types of medicines-->
<div class="different">
  <h2 style="color:black; font-size:50px;font-weight:100px;">PROBLEMS</h2>  
  <br>
<div class="row">
  <div class="col-md-3 col-sm-12 col-lg-3 slideanim">
<button type="button" class="about" data-toggle ="modal" data-target ="#myModal2">Brain</button> 
  <div class="modal fade" id="myModal2">
  <div class="modal-dialog modal-dialog-centered modal-lg">
    <div class="content">
  <div class="modal-heading">
    <h1 class="modal-title">Brain Problem</h1>
    <hr>
      </div>
    <p class="modal-body">
      <input type="checkbox" name="Brain Cancer"> Brain Cancer<br>
        <input type="checkbox" name="Alzheimer"> Alzheimer<br>
        <input type="checkbox" name="Alcoholism"> Alcoholism<br>
        <input type="checkbox" name="Amnesia"> Amnesia<br>
      <input type="checkbox" name="Autism"> Autism<br>
        <input type="checkbox" name="TBI"> TBI<br>
        <input type="checkbox" name="Epilepsy"> Epilepsy<br>
        <input type="checkbox" name="Brain Abscess"> Brain Abscess<br>
       <input type="checkbox" name="Stroke"> Stroke<br>
        <input type="checkbox" name="Mental Retardation"> Mental Retardation<br>
        <input type="checkbox" name="Brain Hemorrhage"> Brain Hemorrhage<br>
      </p> 
      <div class="modal-fotter">
        <button type="button" class="btn btn-danger" data-dismiss="modal">Close</button>
      </div>   
  </div>  
  </div>
  </div>
  </div>
  <div class="col-md-3 col-sm-12 col-lg-3 slideanim">
     <button class="about"data-toggle ="modal" data-target ="#myModal1">Heart</button>
     <div class="modal fade" id="myModal1">
  <div class="modal-dialog modal-lg">
    <div class="content">
  <div class="modal-heading">
    <h1 class="modal-title">Heart Problem</h1>
    <hr>
      </div>
    <p class="modal-body">
      <input type="checkbox" name="Heart Attack"> Heart Attack<br>
        <input type="checkbox" name="Heart Failure"> Heart Failure<br>
        <input type="checkbox" name="Arrhythmia"> Arrhythmia<br>
        <input type="checkbox" name="Angina"> Angina<br>
      </p> 
      <div class="modal-fotter">
        <button type="button" class="btn btn-danger" data-dismiss="modal">Close</button>
      </div>   
  </div>  
  </div>
  </div>
  </div>
  <div class="col-md-3 col-sm-12 col-lg-3 slideanim">
    <button onclick="myMed3()" class="about">Heart</button>
  </div> 
  <div class="col-md-3 col-sm-12 col-lg-3 slideanim">
    <button onclick="myMed4()" class="about">Sprain</button>
  </div> 
  </div>
  <div class="row">
    <div class="col-md-3 col-sm-12 col-lg-3 slideanim">
    <button onclick="myMed5()" class="about">Eye Drop</button>
  </div> 
    <div class="col-md-3 col-sm-12 col-lg-3 slideanim">
    <button onclick="myMed6()" class="about">Acne</button>
  </div> 
    <div class="col-md-3 col-sm-12 col-lg-3 slideanim">
    <button onclick="myMed7()" class="about">Teeth</button>
  </div> 
    <div class="col-md-3 col-sm-12 col-lg-3 slideanim">
    <button onclick="myMed8()" class="about">Hair</button>
  </div> 
  </div>
  </div>
  <br>
  <br>
                                     <!--Text Slideshow-->
    <h2 style="text-align:center;">What our customers say</h2>
  <div id="myCarousel" class="carousel slide text-center" data-ride="carousel" data-interval="3000">
    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
      <div class="item active">
        <h4>"Always laugh when you can, it is cheap medicine."<br><span>Lord Byron</span></h4>
      </div>
      <div class="item">
        <h4>"Let food be the medicine and medicine be the food."<br><span>Hippocrates</span></h4>
      </div>
      <div class="item">
        <h4>"The art of medicine consists of amusing the patient while nature cures the disease."<br><span>Voltaire</span></h4>
      </div>
    </div>
 <!--********************************************************************************--> 
                                <!--Second image gallery-->

<br>
<div class="container-fluid"id="appoint">
<h2 style="font-size:45px; font-weight:bold; text-align:center; color:black;">OUR TOP SERVICE PROVIDERS</h2>
<br>
<p style="text-align:center; font-size:16px; color:black;>Now you can directly book appointment,with our top doctors for your dear one's.</p>
<br>
  <div class="row">
    <div class="col-md-4">
      <div class="panel panel-default text-center slideanim">
        <div class="panel heading">
          <h2 style="font-size:50px; font-weight:600px; color:black;">AIIMS</h2>
        </div>
        <div class="panel-body">
          <h2></h2>
          <h2 style="color:black;">Fix Your Appoint</h2>
          <br>
          <input type="text" class="form-control" name="username"placeholder="Name">
          <input type="number" class="form-control"  name="age"placeholder="age">       
          <form>
          <div class="input-group">
          <input type="text" class="form-control" placeholder="Disease Name" required>
          <div class="input-group-btn">
          <button onclick="myFun()" type="button"class="btn btn-information">Appoint</button>
          </div>
          </div>
          </form>
        </div>
      </div>
    </div>
  <div class="col-md-4">
      <div class="panel panel-default text-center slideanim">
        <div class="panel heading">
          <h2 style="font-size:50px; font-weight:600px; color:black;">COSMOS</h2>
        </div>
        <div class="panel-body">
          <h2></h2>
       <h2 style="color:black;">Fix Your Appoint</h2>
          <br>
          <input type="text" class="form-control" name="username"placeholder="Name">
          <input type="number" class="form-control"  name="age"placeholder="age">       
          <form>
          <div class="input-group">
          <input type="text" class="form-control" placeholder="Disease Name" required>
          <div class="input-group-btn">
<button onclick="myFun()"type="button"class="btn btn-information">Appoint</button>
          </div>
          </div>
          </form>
        </div>
      </div>
  </div>
    <div class="col-md-4">
      <div class="panel panel-default text-center slideanim">
        <div class="panel heading">
          <h2 style="font-size:50px; font-weight:600px; color:black;">FORTIS</h2>
        </div>
        <div class="panel-body">
          <h2></h2>
       <h2 style="color:black;">Fix Your Appoint</h2>
          <br>
          <input type="text" class="form-control" name="username"placeholder="Name">
          <input type="number" class="form-control"  name="age"placeholder="age">       
         <form>
          <div class="input-group">
          <input type="text" class="form-control" placeholder="Disease Name" required>
          <div class="input-group-btn">
          <button onclick="myFun()" type="button"class="btn btn-information">Appoint</button>
          </div>
          </div> 
         </form>
        </div>
      </div>
      </div>
</div>
 </div>
<br>
 <!--Parallax4-->                                                        
 <div class="parallax3">
                                   
                       
                       
                       </div>                                                                                                     
<!--CONTACT-->
                                                          
<div id="contact" class="container-fluid">
<div class="row">
  <h3 style="text-align:center; color:white;">CONTACT</h3>
  <div class="col-md-5">
  <p>  We are on your service</p>
  <p><span class="glyphicon glyphicon-map-marker"></span> New Delhi</p>
  <p><span class="glyphicon glyphicon-send"></span>  hurtlocker0071@gmail.com</p>
  <p><span class="glyphicon glyphicon-phone"></span> 91+ 9870650397</p>
  <p> <span class="glyphicon glyphicon-tint"></span> 2 Times</p>
    <p><span class="glyphicon glyphicon-globe"></span> 25,000+ vehicles on road</p>
   </div>
  <br>
    <div class="col-sm-5">
      <div class="row">
        <p style="padding-left:18px;">Please,give your valuable Feedback</p>
      <textarea class="form-control" id="comments" name="comments" placeholder="Feedback" rows="5"></textarea><br>
      <div class="row">
        <div class="col-sm-12 form-group">
          <button class="btn btn-default pull-right" type="submit">Send</button>
        </div>
      </div>
    </div>
  </div>
</div>
</div>
</body>
</html>
