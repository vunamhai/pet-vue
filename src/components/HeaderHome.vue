<template>
<body>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<nav class="navbar navbar-expand-lg navbar-light bg-light"  >
  <div class="container-fluid">
     <a class="navbar-brand" href="/HomePage">
      <img  src="src\assets\logo.png" alt="" width="150" height="70">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" ali aria-current="page" href="/HomePage  ">Home</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            About
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">About Us</a></li>
            <li><a class="dropdown-item" href="#">The Diffirence</a></li>
            <li><a class="dropdown-item" href="#">Our Team </a></li>
            <li><a class="dropdown-item" href="#">VIPET Program </a></li>
          </ul>
        </li>
        
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Veterinary
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Surgery</a></li>
            <li><a class="dropdown-item" href="#">Diagnostics</a></li>
            <li><a class="dropdown-item" href="#">Dental Care</a></li>
            <li><a class="dropdown-item" href="#">Health Check</a></li>
            <li><a class="dropdown-item" href="#">Parasite Control</a></li>
            <li><a class="dropdown-item" href="#">Pet Travel </a></li>
            <li><a class="dropdown-item" href="#">Grooming </a></li>
            <li><a class="dropdown-item" href="#">Boarding </a></li>
          </ul>
        </li>
        
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dog Traning
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Mark Singer </a></li>
            <li><a class="dropdown-item" href="#">Private Lessons</a></li>
            <li><a class="dropdown-item" href="#">In-home Behavioral Consultations </a></li>
            <li><a class="dropdown-item" href="#">Puppy Classes</a></li>
            <li><a class="dropdown-item" href="#">Group Obedience Services</a></li>
            <li><a class="dropdown-item" href="#">Specialist Services</a></li>
            <li><a class="dropdown-item" href="#">Seminar & Workshop </a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Blog
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Blog</a></li>
            <li><a class="dropdown-item" href="#">Events</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link active" ali aria-current="page" href="#">Contact</a>
        </li>
      </ul>
      <form class="d-flex">
        <button type="button" style="width:200x ;" class="btn btn-outline-danger">Book Appointment</button>
      
      </form>
    </div>
  </div>
</nav>
</body>
    
</template>
<script>

export default {
  name: 'HeaderHome',
  props: {
    msg: String
  }
}

</script>
<style>


.nav-item {
margin-left: 70px;
}
.btn {
  margin-right: 80px;
}
.navbar{
  border:1px solid #000000;
  background-image: url(F:\pet\pet-vue\src\assets\homepage.png);
  padding-top: 0px ;
}
body {
  --wp--preset--color--black: #000000;
    --wp--preset--color--cyan-bluish-gray: #abb8c3;
    --wp--preset--color--white: #ffffff;
    --wp--preset--color--pale-pink: #f78da7;
    --wp--preset--color--vivid-red: #cf2e2e;
    --wp--preset--color--luminous-vivid-orange: #ff6900;
    --wp--preset--color--luminous-vivid-amber: #fcb900;
    --wp--preset--color--light-green-cyan: #7bdcb5;
    --wp--preset--color--vivid-green-cyan: #00d084;
    --wp--preset--color--pale-cyan-blue: #8ed1fc;
    --wp--preset--color--vivid-cyan-blue: #0693e3;
    --wp--preset--color--vivid-purple: #9b51e0;
    --wp--preset--gradient--vivid-cyan-blue-to-vivid-purple: linear-gradient(135deg,rgba(6,147,227,1) 0%,rgb(155,81,224) 100%);
    --wp--preset--gradient--light-green-cyan-to-vivid-green-cyan: linear-gradient(135deg,rgb(122,220,180) 0%,rgb(0,208,130) 100%);
    --wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange: linear-gradient(135deg,rgba(252,185,0,1) 0%,rgba(255,105,0,1) 100%);
    --wp--preset--gradient--luminous-vivid-orange-to-vivid-red: linear-gradient(135deg,rgba(255,105,0,1) 0%,rgb(207,46,46) 100%);
    --wp--preset--gradient--very-light-gray-to-cyan-bluish-gray: linear-gradient(135deg,rgb(238,238,238) 0%,rgb(169,184,195) 100%);
    --wp--preset--gradient--cool-to-warm-spectrum: linear-gradient(135deg,rgb(74,234,220) 0%,rgb(151,120,209) 20%,rgb(207,42,186) 40%,rgb(238,44,130) 60%,rgb(251,105,98) 80%,rgb(254,248,76) 100%);
    --wp--preset--gradient--blush-light-purple: linear-gradient(135deg,rgb(255,206,236) 0%,rgb(152,150,240) 100%);
    --wp--preset--gradient--blush-bordeaux: linear-gradient(135deg,rgb(254,205,165) 0%,rgb(254,45,45) 50%,rgb(107,0,62) 100%);
    --wp--preset--gradient--luminous-dusk: linear-gradient(135deg,rgb(255,203,112) 0%,rgb(199,81,192) 50%,rgb(65,88,208) 100%);
    --wp--preset--gradient--pale-ocean: linear-gradient(135deg,rgb(255,245,203) 0%,rgb(182,227,212) 50%,rgb(51,167,181) 100%);
    --wp--preset--gradient--electric-grass: linear-gradient(135deg,rgb(202,248,128) 0%,rgb(113,206,126) 100%);
    --wp--preset--gradient--midnight: linear-gradient(135deg,rgb(2,3,129) 0%,rgb(40,116,252) 100%);
    --wp--preset--duotone--dark-grayscale: url(#wp-duotone-dark-grayscale);
    --wp--preset--duotone--grayscale: url(#wp-duotone-grayscale);
    --wp--preset--duotone--purple-yellow: url(#wp-duotone-purple-yellow);
    --wp--preset--duotone--blue-red: url(#wp-duotone-blue-red);
    --wp--preset--duotone--midnight: url(#wp-duotone-midnight);
    --wp--preset--duotone--magenta-yellow: url(#wp-duotone-magenta-yellow);
    --wp--preset--duotone--purple-green: url(#wp-duotone-purple-green);
    --wp--preset--duotone--blue-orange: url(#wp-duotone-blue-orange);
    --wp--preset--font-size--small: 13px;
    --wp--preset--font-size--medium: 20px;
    --wp--preset--font-size--large: 36px;
    --wp--preset--font-size--x-large: 42px;
}
body{
  display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -ms-flex-direction: column;
    -webkit-flex-direction: column;
    flex-direction: column;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
}
body{
  font-family: "proxima-nova",sans-serif;
    font-size: 16px;
    font-weight: 400;
    line-height: 1.36;
    letter-spacing: -.2px;
    color: #2c231c;
    background-repeat: repeat;
    background-position: left top;
    text-rendering: optimizeLegibility;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
@import url(https://fonts.googleapis.com/css?family=Lato);

*, *:before, *:after{
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  font-family: 'Lato', sans-serif;
}

/*| Navigation |*/

nav{
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background: #fff;
  box-shadow: 0 3px 10px -2px rgba(0,0,0,.1);
  border: 1px solid rgba(0,0,0,.1);
}
  nav ul{
    list-style: none;
    position: relative;
    float: right;
    margin-right: 100px;
    display: inline-table;
  }
    nav ul li{
      float: left;
      -webkit-transition: all .2s ease-in-out;
      -moz-transition: all .2s ease-in-out;
      transition: all .2s ease-in-out;
    }

    nav ul li:hover{background: rgba(0,0,0,.15);}
    nav ul li:hover > ul{display: block;}
    nav ul li{
      float: left;
      -webkit-transition: all .2s ease-in-out;
      -moz-transition: all .2s ease-in-out;
      transition: all .2s ease-in-out;
    }
      nav ul li a{
        display: block; 
        padding: 30px 20px;
        color: #222; 
        font-size: .9em;
        letter-spacing: 1px;
        text-decoration: none;
        text-transform: uppercase;
      }
      nav ul ul{
        display: none;
        background: #fff;
        position: absolute; 
        top: 100%;
        box-shadow: -3px 3px 10px -2px rgba(0,0,0,.1);
        border: 1px solid rgba(0,0,0,.1);
      }
        nav ul ul li{float: none; position: relative;}
          nav ul ul li a {
            padding: 15px 30px; 
            border-bottom: 1px solid rgba(0,0,0,.05);
          }
          nav ul ul ul {
            position: absolute; 
            left: 100%; 
            top:0;
          }
</style>
