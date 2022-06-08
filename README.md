<head>
  <style>
    @media(minimum width: 500px;){}
p{
  font-size: 25px;
}
.navbar-list{
  display: flex;
  justify-content: space-around;
  top: 0;
  left: 0;
  width: 100%;
  position: fixed;
  height: 50px;
  background-color: red;
  font-size: 25px;
  z-index: 5;
}


#welcome-section{
  height: 250px;
  background: grey;
  color: white;
  text-align: center;
  width: 100%;
  padding: 60px 0px 20px 0px; 
  
}


#projects{
  display: flex;
  flex-direction: column;
}
h3{
  color: white;
  background-color: black;
  height: 40px;
  width: 90%;
  padding-top: 10px;
  padding-bottom: 10px;
}

#about{
  height: 500px;
  background-color: green;
  width: 100%;
  padding: 30px 0px 30px 0px;
  text-align: center;
}
#work{
  background-color: cyan;
  height: 6000px;
  width: 100%;
  padding-top: 20px;
  text-align: center;
}

#contact{
    background-color: orange;
    height: 250px;
    padding-top: 20px;  
}
.img{
  width: 80%;
}

#contact-info{
  display: flex;
  justify-content: space-around;
  font-size: 50px;
}

footer{
  color: black;
  padding-top: 30px;
  height: 60px;
  font-size: 20px;
  text-align: center;
  line-height: 1.4;
}

body{
  border-style: block;
  border-width: 5px;
  border-color: black;
}

h1{
  font-size: 25px;
  line-height: 1.4;
}
  </style>
</head>

<nav id="navbar">
  <div class ="navbar-list">
    <a class="nav-link" href="#about">About</a>
    <a class="nav-link" href="#work">Work</a>
    <a class="nav-link" href="#contact">Contact</a>
  </div>
</navbar-list>

<section id="welcome-section">
  <h1><strong>Hey Surfer, you are welcome<br>This is my portifolio,<br>My story.</strong></h1>   
</section>
  
  <main id="projects">
    
    <section id="about">
      <article><p><em>I'm Mirimu Disan Mathison<br>I am currently staying in Jomayi Estates, Nalumunye,Kampala<br>Uganda......a place like no other.<br>I'm a web developer and designer from<a href="#"> Freecode Camps</a>.<br>Computer programming and coding is my hobby, <br>.....true story!!!</em></p>
      </article> 
    </section>
  
  <section id="work">
    <article>
      <p style="color: white; font-size: 30px; background-color: blue;">Below are my<br> projects <hr></p>
      <div class="project-tile">
        <img src="https://lh3.googleusercontent.com/qnqxlQ_pfvQfxA5pAoTeEakQ16pB-lfQt1HIiptmb4ljCJkgVFE62BaMhnS_VQ-Zh5OJJ0EC6EwvdFpjZECNQKeh76dShvwTyRvNLDJ0pV1Ks4uXHxVcRBgOg9tWEfbQzZlAq6ZXRQ=w2400" class="img"> <br><h3>Tribute Page</h3><hr>
      </div><br><br>
      
      <div id="survey-form">
        <img src="https://lh3.googleusercontent.com/ItASri6sb-ckFmskMgrP61pAzVXt0prXOPnOzs4XELjmBhCMR-Bmvo4uuTMJoATIXHY5wKU5XhY6_Fj6tTxa8MXC6T0Fqm1TnmlkQT-VDBoILVzYJG5fV5QS5UGas68I5HMeZFMyUQ=w2400" class="img"><br><h3>Survey Form</h3><hr>
      </div><br>
      
      <div id="product-landing-page">
        <img src="https://lh3.googleusercontent.com/mPoIyU7h1qti3GMDrnFkrrNV98yvpq3aWoOQoFZo2-vUHa_nnjU3j5U2Y1GrfuF-QEGZKrb1cQKB5bmF5J3d6U0hUVBlfgNaTwas1WNnBGz436gfSSi6JHwC37QxHXgiBCiBSnpNsQ=w2400" class="img"><br><h3>Product Landing Page</h3><hr>
      </div><br>
      
      <div id=documentation-page>
        <img src="https://lh3.googleusercontent.com/wxtux1qSCa3CRuuOZZfnkNK-H5p1mMhWkyKmW4gCLtR7GqNfndLJEJH_IpwFMQCSHoRJdVK7TTyP-qQgk9yB2oy9_qhCVdFU6GdRqaVLrZrqScmk2KmFtMVVEeRD4RbFnf_Of9MTdQ=w2400" class="img"><br><h3>Documentation Page</h3><hr>
      </div><br>
      <div>
        <a style="color: white; background-color: black; height: 20px;" id="profile-link" href="https://codepen.io/disanm" target="_blank">Access all projects ></a>
      </div>
    </article>
  </section>
    
  <section id ="contact">
    <p style="text-align: center;"><strong>Are you interested in any kind of website?<br>I can develop and design it for you.<br>Reach me on</strong></p><br>
    
    <!-- Add icon library -->
    <link rel ="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    
    <!-- Add font awesome icons -->
    <div id="contact-info">
    <a class="fa fa-facebook" href="https://www.facebook.com/disanmathison" target="_blank"> </a>
    <a  class="fa fa-twitter" href="https://twitter.com/DisanMirimu?s=09" target="_blank"></a>
    <a class="fa fa-phone" href="tel: 070-839-7151" target="_blank"></a>
    <a class="fa fa-codepen" href="https://codepen.io/disanm" taget="_blank"></a>
    <a class="fa fa-whatsapp" href="https://wa.link/4ggorf" target="_blank"></a></div>
    
    </section>
  
 <footer>&copy; Disan Mathison's portfolio, FreeCode Camps, 2022</footer>
    
</main>
  
    
