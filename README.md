<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />

    <!-- <link rel="stylesheet" href="style.css"> -->
</head>
<body>
    <style>
        
        .container{
    height: 80vh;
}
/* DEMO-SPECIFIC STYLES */
.typewriter h1 {
color: rgb(14, 13, 13);
font-family: monospace;
width: 80vw;
overflow: hidden; /* Ensures the content is not revealed until the animation */
border-right: .15em solid orange; /* The typwriter cursor */
white-space: nowrap; /* Keeps the content on a single line */
margin: 0 auto; /* Gives that scrolling effect as the typing happens */
letter-spacing: .15em; /* Adjust as needed */
/* bottom:vh; */
animation: 
typing 5s steps(30, end),
blink-caret .5s step-end infinite;
}

/* The typing effect */
@keyframes typing {
from { width: 0 }
to { width: 100% }
}

/* The typewriter cursor effect */
@keyframes blink-caret {
from, to { border-color: transparent }
50% { border-color: orange }
}
.abttext{
width: 80vw;
height: fit-content;
margin: 10vw;
text-align: center;
justify-content: center;
align-items: center;
position: relative;
bottom: 60vh;
color: black;
}
.abtimg{
opacity:0.8;
height: 470px;
width: 100%;
}
.abthd{
position: relative;
bottom:60vh;
text-align: center;
width: 80vw;
}
.btn{
color: rgb(247, 244, 244);
text-decoration: none;
border: 1px solid black;
padding: 5px 5px 5px 5px;
align-items: center;
justify-content: center;
align-content: center;
text-align: center;
/* border-radius: 20px; */
width: fit-content;
height: fit-content ;
position: relative;
right: 10px;
/* background-color: rgb(90, 86, 86); */
}
.btn:hover{
background-color: rgb(82, 79, 79);
}
/* -----------------services css */

.sercont{
width: 80vw;
height: fit-content;
position: relative;
bottom: 33vh;
align-content: center;
justify-content: center;
}
.serhead1{
position: absolute;
width: fit-content;
text-align: center;
/* border-bottom: 2px solid rgb(133, 129, 129); */
justify-content: center;
align-content: center;
margin-top: 20%;
/* margin-left: 45%; */
width: 80vw;
margin-left: 10vw;
font-size: larger;
font-weight: bold;

}
/* ---------services css starts here  */
.serhead {
position: relative;
bottom:170px;
width: fit-content;
height: fit-content;
color: black;
font-size: x-large;
text-align: center;
/* border-bottom: 2px solid red; */

}
div .serh1{
position: relative;
border-bottom: 2px solid red;
padding: 2px 2px 2px 2px;
text-align: center;

width: fit-content;
height: fit-content;
justify-content: center;
align-items: center;
align-content: center;
text-align: center;
margin-left:147%;
top: 130px;
}
.services a{
position:relative;
text-align: center;
left: 32%;
font-size:larger;
text-decoration:none;
font-weight: 900;
color: rgb(0, 0, 0);
bottom:158px;
opacity: 0;
}

.service img:hover {
transition: 0.5s;
opacity: 0.5;
}
.services .service:hover a{
transition: 1.5s;
opacity: 1;
}
.service p{
font-size: large;
font-weight: bold;
}
.album{
    width:fit-content;
    margin-left:43vw;
    height: fit-content;
    text-align:center;
    border-bottom: 2px solid red;
     padding: 2px 2px 2px 2px;
     font-size: large;
     font-weight: bold;
}


/* ------------------------------ */

.services{
                        
    width: 80vw;
    height: fit-content;
    margin-left: 10vw;
    margin-right: 10vw;
    
}
.service p {
    
    justify-content: center;
    align-content: center;
    align-items: center;
    text-align: center;
    border-bottom: 5px solid #ede8e8;
    padding:2px 2px 8px 2px;

}
.service img{
    width: 80vw;
    height:300px;
}
.d-block w-100{
    transition: 2s;
}

    </style>
    <div class="container" data-aos="fade-up"
    data-aos-offset="200"
    data-aos-delay="50"
    data-aos-duration="1000">
        <img class="abtimg" src="abt-img.jpg" alt="" srcset="">
        <div class="typewriter">
            <h1 class="abthd">Hello, I'm Javed</h1>
          </div>
          <div class="abttext">
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis, magnam.</p>
              <a href="#" class="btn">Read More</a>
          </div>
    </div>
                <div class="serhead">
                    <p class="serh1">Services</p>
                </div>    
                <div class="services"  data-aos="fade-up"
                data-aos-offset="200"
                data-aos-delay="50"
                data-aos-duration="1000">
                    <div class="service">
                        <p>Pre-Weeding Photography</p>
                        <img src="pre (7).jpg" alt="">
                        <a href="#" class="viewmore">View Photos</a>
                    </div>
                </div>
                <div class="services" data-aos="fade-up"
                data-aos-offset="200"
                data-aos-delay="50"
                data-aos-duration="1000">
                    <div class="service">
                        <p>Maternity Photography</p>
                        <img src="mat (4).jpg" alt="">
                        <a href="#" class="viewmore">View Photos</a>
                    </div>
                </div>
                <div class="services" data-aos="fade-up"
                data-aos-offset="200"
                data-aos-delay="50"
                data-aos-duration="1000">
                    <div class="service">
                        <p>Engagement Photography</p>
                        <img src="eng (6).jpg" alt="">
                        <a href="#" class="viewmore">View Photos</a>
                    </div>
                </div>
                <div class="services" data-aos="fade-up"
                data-aos-offset="200"
                data-aos-delay="50"
                data-aos-duration="1000"> 
                    <div class="service">
                        <p>Pre-Weeding Photography</p>
                        <img src="pre (7).jpg" alt="">
                        <a href="#" class="viewmore">View Photos</a>
                    </div>
                </div>
                <div class="services" data-aos="fade-up"
                data-aos-offset="200"
                data-aos-delay="50"
                data-aos-duration="1000">
                    <div class="service">
                        <p>Baby Photography</p>
                        <img src="bab (2).jpg" alt="">
                        <a href="#" class="viewmore">View Photos</a>
                    </div>
                </div>
                <div class="services" data-aos="fade-up"
                data-aos-offset="200"
                data-aos-delay="50"
                data-aos-duration="1000">
                    <div class="service">
                        <p>Portfolio Photography</p>
                        <img src="aboutme (1).jpg" alt="">
                        <a href="#" class="viewmore">View Photos</a>
                    </div>
                </div>
<style>
   
    
</style>

                <!-- -------------------latest works--------------- -->
                <div class="album" data-aos="fade-up"
                data-aos-offset="200"
                data-aos-delay="50"
                data-aos-duration="1000"> Albums </div>
                <br>
                <div class="latest">
                    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
                        <div class="carousel-indicators">
                          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
                          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
                        </div>
                        <div class="carousel-inner">
                          <div class="carousel-item active">
                            <img src="eng (10).jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                              <h5>Virat & Anushka</h5>
                              <p>"Some representative placeholder content for the first slide."</p>
                            </div>
                          </div>
                          <div class="carousel-item">
                            <img src="eng (1).jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                              <h5>itika & Rohit</h5>
                              <p>Some representative placeholder content for the second slide.</p>
                            </div>
                          </div>
                          <div class="carousel-item">
                            <img src="pre (3).jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                              <h5>Deepika & Ranveer</h5>
                              <p>Some representative placeholder content for the third slide.</p>
                            </div>
                          </div>
                        </div>
                        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
                          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                          <span class="visually-hidden">Previous</span>
                        </button>
                        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
                          <span class="carousel-control-next-icon" aria-hidden="true"></span>
                          <span class="visually-hidden">Next</span>
                        </button>
                      </div>
                </div>




                <!-- --------------testimonals-------------------   -->


                
                <style>
                  
                </style>
                <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
                <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
                <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
                <script>
                  AOS.init();
                </script>
              
</body>
</html>
