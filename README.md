<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="../Captures/fontawesome-free-6.1.1-web/css/all.min.css">
    <link rel="stylesheet" href="style.css">
    <title>Menz Onyeocha</title>
</head>
<style>
*{
    margin: 0;
    padding: 0%;
    box-sizing: border-box;
}
body{
    width: 100%;
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
    margin-right: 0% !important;
}
/* ---------------header-------------- */
.hero{
    /* width: 100%; */
    font-size: 20px;
    color: white;
}
.header{
    display: flex;
    justify-content: space-around;
    align-items: center;
}
.herobefore{
    background: linear-gradient(to top, rgba(0,0,0,0.6), rgba(0,0,0,.9)), url(hero.jpg) no-repeat;
    height: 100vh;
    left: 0;
    right: 0;
    bottom: 0;
    top: 0;
    background-size: cover;
    position: relative;
    width: 100%;
}
.heroafter{
    left: -5%;
    right: 0;
    height:15vh;
    top: 85%;
    bottom: -0.1%;
    background-color: white;
    position: absolute;
    overflow: hidden;
}
.navbar1{
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding-top: 3rem;
}
.navbar2{
    display: flex;
    list-style: none;
    justify-content: center;
    align-items: center;
}
nav a{
    padding: 20px;
    font-size: 20px;
    color: white;
    text-decoration: none;
}
.nav a:hover{
    color:dodgerblue;
}
.logo{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 40px;
    align-self: center;
    margin-top: 5.8vh;
}
.fa-bars{
    display: none;
}
.log{
    color: yellow;
}
.mynumber a{
    color:black;
    text-decoration: none;
}
.mynumber{
    background:linear-gradient(to right, yellow, white);
    padding: 10px;
    border-radius: 30px;
}
.mynumber:hover{
    box-shadow: 0 4px 8px 0 rgb(0,0,0);
    animation-name: big;
    animation-duration: 1s;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
}
@keyframes big {
    0%{
        transform: none;
    }
    50%{
        transform: scale(1.1);
    }
    100%{
        transform: none;
    }
    
}
.Name{
    margin-top: 13%;
    margin-left: 15%;
    font-size: 25px;
}
.menz{
    font-size: 70px;
}
.Anthony{
    color: yellow;
}
#tel{
    height: 40px;
    width: 300px;
    border-radius: 20px;
    border: 1px solid yellow;
    outline: none;
    position: relative;
}
#chatme{
    height:43px;
    border-radius: 20px;
    width:90px;
    margin-left: -90px;
    position:absolute;
    background-color:yellow;
    color: #010103;
    box-shadow:0, 0, 15px ;
}
#tel,#chatme:hover{
    cursor: pointer;
}
.global{
    padding-bottom: 20px;
}
.mynameis{
    color: rgb(228, 228, 156);
}
.seemebutton{
    bottom: 0;
    top: 90vh;
    left:0 ;
    right: 0;
    text-align: center;
    font-size: 30px;
}
.seemebutton:hover{
    cursor: pointer;
}
@keyframes expanding {
    0%{
        transform: none;
    }
    50%{
        transform: scale(1.4);
    }
    100%{
        transform: none;
        opacity: 0.7;
    }
    
}
.seemebutton img{
    height: 60px;
    width: 100px;
    animation-name:expanding ;
    animation-duration: 1.5s;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    animation-delay: 2.5s;
}
/* --------------header animation------------- */
.herobefore{
    animation-name:move ;
    animation-delay: .2s;
    animation-duration: 1s;
    animation-timing-function: ease-out;
    animation-direction: forwards;
}
@keyframes move {
    0%{
        transform: translateY(-4rem);
    }   
    100%{
        opacity: 1;
        transform: none;
    }
}
body{
    animation-name: pop;
    animation-duration: .7s;
    animation-timing-function: ease-in;
    animation-direction: forwards;
}
@keyframes pop {
    0%{
        opacity: 0;
    }   
    100%{
        opacity: 1;
    }
}
.anima{
    animation-name: popin;
    animation-duration: 1s;
    animation-timing-function: ease-in;
    animation-direction: forwards;
}
.anime{
    animation-name: pop-in;
    animation-duration: 1s;
    animation-timing-function: ease-in;
    animation-direction: forwards;
}
@keyframes popin {
    0%{
        transform:  scale(.6);
    }
    100%{
        transform: none;
    }
}
@keyframes pop-in {
    0%{
        transform: translateY(-2rem) scale(.8);
    }
    100%{
        transform: none;
    }
}
/* ---------------MAIN--------------- */
main{
    
    width: 100%;
    color: white;
}
/* -----------ARTICLE1----------- */
.article1{
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 11vh;
    flex-direction: row;
    flex-wrap: wrap;
    background-color:rgba(0,0,0,0.9);
}
.imageme1{
    height:540px;
    width: 50%;
    background:linear-gradient(to top, rgba(0,0,0,.5),rgba(0,0,0,0.3)), url(j.jpg);
    background-size: cover;
    background-position: center;
}
.about1{
    margin-bottom: 4vh;
    color: lightyellow;
}
.section1{
    width:500px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    padding-top: 2vh;
}
.contact1button{
    background-color: yellow;
    display: inline-block;   
    padding-left:1rem;
    padding-right:1rem;
    padding-top: 0.5rem;
    padding-bottom: 0.5rem;
    border-radius: 20px;
    border: 1px solid transparent;
    outline: none;
    text-decoration: none;
    color: black;
    font-size: 15px;
    transition: 2s;
}
.contact1button:hover{
    background-color: transparent;
    border: 1px solid yellow;
    color: white;
    transform: scale(1.2);
}
.aboutme1{
    font-size: 50px;
    margin-bottom: 2vh;
}
.Philantropist1{
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 20px;
    margin-bottom: 3vh;
}
.Philantropist1 span{
    color:yellow;
}
/* ------------ARTICLE2------------ */
.article2{
    background-color: rgba(0,0,0,1);
    padding: 15vh;

}
.section2{
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 2vh;
    box-sizing: content-box;
}
.card{
    width: 350px;
    height: 320px;
    text-align: center;
    background-color: #191919;
    padding: 20px;
    padding-bottom: 3vh;
}
.aboutfootballer2 span{
    display: none;
}
.myscores2{
    text-align: center;
    font-size: 5rem;
    padding-bottom: 10vh;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-style: italic;
}
.h3scores{
    padding-bottom: 0.5rem;
    font-size: 25px;
}
.readmore{
    padding:8px;
    background-color: yellow;
    color: black;
    display: inline-block;
    text-decoration: none;
    border-radius: 50px;
    font-size: 15px;
    padding-left: 30px;
    padding-right: 30px;
    font-weight: bolder;
    margin-top: 2vh;
    transition: 2s;
}
.readmore:hover{
    transform: scale(1.2);
    background-color: transparent;
    color: white;
    border: 1px solid yellow;
}
.pscores{
    color: lightyellow;
}
.fa2solid{
    font-size: 50px;
    color: yellow;
    animation-name: bounce;
    animation-delay: 1s;
    animation-duration: 2.5s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
    animation-direction: forwards;
}
@keyframes bounce {
    0%{
        transform: none;
    }
    50%{
        transform: scale(1.5) ;
    }
    100%{
        transform: none;
    }
}
.space{
    margin-top: 3vh;
}
/* ----------------ARTICLE3---------------- */
.article3head{
    background:linear-gradient( to bottom ,rgba(0,0,0,.7),rgba(0,0,0,0.9)), url(e.jpg) no-repeat ;
    background-position: center;
    background-size: cover;
    padding-bottom: 15vh;
}
.article3{
    overflow: hidden;
    margin: 0 auto;
    height: 80vh;
    width: 90vh;
    border: 20px solid rgba(0,0,0,.2);
    
}
.article3:hover{
    outline: lightskyblue;
    cursor: pointer;
    box-shadow: 2px 2px 4px 4px lightskyblue;
    animation-name: like;
    animation-duration: 2s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
}
@keyframes like {
    0%{
        transform: none;
    }
    50%{
        transform: scale(1.04);
    }
    100%{
        transform: none;
    }
    
}
.section3{
    position: relative;
    width: 500%;
    margin: 0%;
    left: 0;
    animation-name: slideshow;
    animation-duration: 20s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
}
@keyframes slideshow {
    0%{
        left: 0;
    }
    20%{
        left: 0;
    }
    25%{
        left:-100%;
    }
    40%{
        left:-100%;
    }
    45%{
        left:-200%;
    }
    60%{
        left:-200%;
    }
    65%{
        left:-300%;
    }
    80%{
        left: -300%;
    }
    85%{
        left:-400%;
    }
   99%{
        left:-400%;
    }
    100%{
        left: -500%;
    }
    
}
.article3 section img{
    float: left;
    width: 20%;
}
.h33{
    font-size: 50px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    color: yellow;
    text-align: center;
    padding: 3vh;
}
.space3{
    height: 40rem;
}
/* ---------------FOOTER---------------- */
footer .tech{
    height: 300px;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 2em;
    flex-basis: 60%;
}
footer{
    background-color: #010103;
    color: white;
    display: flex;
    justify-content: space-around;
    align-items: center;
}
.fa3solid{
    font-size: 20px;
    color: #010103;
}
.fa3{
    display: flex;
    flex-direction: row;
    gap: 1rem;
}
.fab{
    background: yellow;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    padding: 10px;

}
.footerh3{
    color: #9b9c8f;
    font-size: 40px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.footlearner span,.techtrademark span, .footerh3 span{
    color: yellow;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.footlearner{
    font-size: 30px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    width: 100%;
    text-align: center;
    flex-basis: 20%;
}
.techtrademark{
    font-size: 30px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    width: 100%;
    text-align: center;
    flex-basis: 20%;
}
@media screen and (max-width: 1116px) {
    .imageme1{
        height: 400px;
        width: 50%;
    }
    .section2{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        gap: 20px;
    }
    .card{
        width: 100%;
        font-size: 1rem;
        padding: 10px;
        height: fit-content;
        box-sizing: border-box;
    }
    footer{
        display: grid;
        grid-template-columns: 1fr 3fr 1fr;
        align-items: center;
        justify-content: center;
    }
    .techtrademark , .footlearner{
        font-size: 1.5rem;
        width: 100%;
        text-align: center;
    }    
    footer .tech{
        width: 100%;
    }
}
@media screen and (max-width: 960px) {
    .techlogo{
        text-align: center;
    }
       footer{
        display: flex;
        flex-direction: column;
        gap: 2vh;
    }
    .techtrademark , .footlearner{
        font-size: 2rem;
    }
    .section2{
        display: flex;
        gap:3%;
        padding: 10px;
    }
    .card{
        width: 100%;
        height: fit-content;
    }
    .aboutfootballer2 span{
        display: block;
    }
    .fa-bars{
        display: block;
        font-size: 2.5rem;
    }
    .header h2{
        margin-top: 7vh;
    }
    .navbar1>ul{
        position: fixed;
        transition: 2s;
        top: -40vh;
        width: 100%;
        right: 0;
        left: 0%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background-color:#010103;
        padding-block: 20px;
        z-index: 20;
        opacity: 0;
    }
    .navbar1:hover ul{
        position: fixed;
        top: 0%;
        opacity: 1;
    }
     .nav{
        margin-bottom: 5vh;
    }
    
}
@media screen and (max-width: 900px) {
    *{
        margin: 0%;
        /* background-color: #010103; */
    }
    body{
        width: 100%;
        overflow-x: hidden;
    }
    .imageme1{
        width: 50%;
        height: 40vh;
    }
    .article1{
        padding: 7vh;
    }
    .article3{
        width: 90%;
        height: 60%;
    }
    .myscores2{
        font-size: 3rem;
        padding-top: 10vh;
    }
    .imageme1{
        width: 80%;
    }
    .heroafter{
        overflow: hidden;
        right: 0%;
    }
    .card{
        width: 70%;
        height: fit-content;
        margin-top: 8vh;
        height: fit-content;
        padding-top: 40px;
        box-sizing: border-box;
    }
    .section2{
        display: flex;
        flex-direction: column;
        width: 100%;
        justify-content: center;
        align-items: center;
        column-gap: 50px;
        height: fit-content;
        padding-top:0 ;
    }
    .article2{
        padding:0;
        margin: 0;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .seemebutton img{
        height: 40px;
        width: 60px;
    }
    .herobefore{
        width: 100%;
        background-size: cover;
        background-position: center;
    }
    .card span{
        display: none;
    }
}
@media screen and (max-width: 700px) {
    .card{
        padding-top: 2vh;
        height:fit-content;
    }
    .card1 span{
        display: none;
        
    }
}
</style>

<body>
   <div class="herobefore">

    <header class="hero animation">
       <div class="header">
        <H2 class="logo anima"><span class="log">Menz</span> Onyeocha</H2>

        <nav class="navbar1" >
           
            <ul class="navbar2 anima">
                <li class="nav"><a href="">Home</a></li>
                <li class="nav"><a href="">About</a></li>
                <li class="nav"><a href="">Contact us</a></li>
                <li class="mynumber anima"><a href="">My Number</a></li>
            </ul>
            <i class="fa-solid fa-bars"></i>
           
        </nav>
       </div>
        

        <section class="Name">
            <p class="mynameis anime" >My name is </p>
            <h1 class="menz anime">Menkiti <span class=" Anthony"> Anthony</span></h1>
            <p class="global anime">I am a Global Philantropist</p>
            <form action="" class="anime">
                <input type="tel" placeholder="Phone Number" id="tel">
                <input type="submit" value="Chat me" id ="chatme">
            </form>
        </section>

        <section>
           <div class="heroafter"> <p class="seemebutton"><a href="#main"><img src="f.jpg" alt=""></a></p></div>
        </section>

    </header>

   </div>

    <main class="main" id="main">
     
       <article class="article1">
        <div class="imageme1"></div>
        <section class="section1">
            <h2 class="aboutme1">About Me</h2>
           <h3 class="Philantropist1">Kidnapper  <span>& Philantropist</span></h3>
           <p class="about1">My name is Menkiti Anthony who is among the four gang Kidnappers terrorising Ekiti State and environs. from the money made from collecting ransoms, I have fed many motherless baby home, fed many poor people on the road and bought alot of bomb to terrorise the city.The only thing stop me from commiting many other bad things is inflation. There is no money in Nigeria. Very soon one grain of rice will be 25,000 naira. The women in Nigeria are now scarce. Chidbearing is reducing. Is Nigeria turning into North Korea. Breaking news from asaba headebridge headquarters.</p>
          <a href="tel:+2349043346739" class="contact1button">Contact</a>
        </section>
       </article>

       <article class="article2">
        <h2 class="myscores2">My Scores</h2>
        <section class="section2">
            <div class="card card1">
                <i class="fa-solid fa-futbol fa2solid"></i>
               <div class="space">
                <h3 class="footballer2 h3scores">Footballer</h3>
                <p class="aboutfootballer2 pscores">He is a world class defender. He can play Defensive-Midfield, Centerback and Rightback. He is the Pepe of Reget College. He is a cultist on the field. He is has his right haand ma n ocha, who was his former cult  member on the field ,also known as Ramos...............</p>
                <a href="" class="readmore">Read more</a>
               </div>
            </div>
            <div class="card card2">
            <i class="fa-solid fa-money-bill fa2solid"></i>
              <div class="space">
                <h3 class="dancer h3scores">Dancer</h3>
                <p class="aboutdancer2 pscores">He has danced all his life but nothing to show for it. Although many people envy him for that he still does it. He has danced all Naira Marley trends and he is even currently waiting for another trend to dance to it. He has also tried American dance but its not for him</p>
                <a href="" class="readmore">Read more</a>
              </div>
            </div>
            <div class="card card3">
                <i class="fa-solid fa-brain fa2solid"></i>
              <div class="space">
                <h3 class="100%IQ h3scores">100% IQ</h3>
                <p class="about100%IQ pscores">He has dominated the world of academics. In so many territories. He has moved many mountains in the file of Mathematics. Menkiti Chiemelie Anthony future Phone designer and Developer has conquered many academic threats all disciplines of the world. </p>
                <a href="" class="readmore">Read more</a>
              </div>
            </div>
        </section>
       </article>

       <article class="article3head">
       <div class="space3">

        <h3 class="h33">GALLERY</h3>

        <div class="article3">
          
        <section class="section3">
          <img src="k.jpg" alt="" class="slier">
          <img src="o.jpg" alt="" class="slier ">
          <img src="t.jpg" alt=""class="slier" >
          <img src="e.jpg" alt="" class="slier" >
          <img src="n.jpg" alt="" class="slier" >
          <img src="k.jpg" alt="" class="slier">
        </section>
        </div>


       </div>
       </article>

    </main>
    <footer>
      <h2 class="footlearner"><span>&copy;learner</span> Games</h2>
      <div class="tech">
        <h3 class="footerh3"><span>Menz</span> Onyeocha</h3>
       <div class="techlogo"> <p>Yesterday is history, Tomorrow is History, Today is a Gift that is why it is called The Present </p></div>
       <div class="fa3"> 
       <div class="fab"> <i class="fa-solid fa-apple-whole fa3solid"></i></div>
       <div class="fab"> <i class="fa-solid fa-basketball fa3solid"></i></div>
       <div class="fab"> <i class="fa-solid fa-phone-flip fa3solid"></i></div>
       </div>
      </div>
     <div class="techtrademark"> 
    <p>  Presentday Tech <span>&trade;</span> </p>
    </div>
    </footer>
</body>
</html>
