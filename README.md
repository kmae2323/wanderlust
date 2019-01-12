# wanderlust
<!DOCTYPE html>
  <html lang="en">
    
    <head> 
      <meta charset="UTF-8">
      <title> Wanderlust </title>
    </head>
    <style>
      body {
        font-size: 20px;
        font-family: Helvetica, Arial, sans-serif;
        margin-left: 20px;
        margin-right: 20px;
      }
      h1{
        font-weight: 100;
        font-size: 8rem;
        text-align: center;
      margin: 0 0 0 0;
        padding: 130px 0px 0px 5px;
        height: 200px;
        text-shadow: 2px 3px white;
      } 
      h1, .quote {
          background-image: url(https://images.pexels.com/photos/671658/pexels-photo-671658.jpeg?auto=compress&cs=tinysrgb&h=650&w=940);
        background-size: 1000px, auto;
        background-attachment: fixed;
        background-position: 50% 50%;
      }
      .quote {
        font-family: cursive;
        text-align: center; 
        margin: 0;
        padding-bottom: 97px;
      }
    
      nav #navlist li {
        font-family: Helvetica, Arial, sans-serif;
        line-height: 1.5em;
        text-align: center;
        list-style: none;
       display: inline-flex;
        margin-right: 0;
        margin-left: 0;
      }
      nav {
        background-color: rgba(30,0,220,0.6);
        background-image: linear-gradient(to right, lightblue, indigo);
          border: 2px solid navy;
      }
      .countrylist li {
        margin-top:.5em;
        margin-bottom:.5em;
        margin-right: 0px;
        margin-left: 0px;
        border: 1px solid;
        padding-left: 20px;
        padding-right: 20px;
        width: 3em;
        padding-top: .5px;
        background: white;
        opacity: .9;
      }
      
      #home, .germ, .italy, .aust {
        color: indigo;
        text-shadow: .8px .5px black;
        border: 1px solid indigo;
      }
      li#home:hover {
        background-color: coral;
      }
      li.germ:hover {
        background-color: coral;
      }
      li.aust:hover {
        background-color: coral;
      }
      .malt, .kam, .long {
        color: rgb(50,20,180);
        text-shadow: .8px .7px black;
        border: 1px solid rgb(50,20,180);
      }
      li.malt:hover {
        background-color: coral;
      }
      li.long:hover {
        background-color: coral;
      }
      #west, .mich, .contact {
        color: rgb(25,75,220);
        text-shadow: .9px .9px indigo;
        border: 1px solid rgb(35,106,150);
      }
      li.mich:hover {
        background-color: coral;
        color: black;
      }
      li.contact{
        padding-left: 10px;
        padding-right: 14px;
        width: 3.8em;
      }
      li.contact:hover {
        background-color: coral;
      }
      li.long{
        padding-left: 17px;
        padding-right: 12px;
          width: 6.3em;
      }
      li.long:hover {
        background-color: coral;
      }
      li.germ{
        width: 4em;
      }
      li.germ:hover {
        background-color: coral;
      }
      li.italy{width: 2em;}
      li.italy:hover {
        background-color: coral;
      }
      li.kam {
        width: 5.1em;
        padding-left: 10px;
        padding-right: 10px; 
      }
      li.kam:hover {
        background-color: coral;
      }
      nav #navlist {
        padding: .5px 0px;
        text-align: center;
        width: 100%;
        margin: 0;
      }
      nav {
        width: 100%;
        text-align: center;
        margin: 0;
        padding-bottom: 0;
      }
      p {
        margin-left: 30px;
        margin-right: 20px;
        line-height: 1.4rem;
        font-size: .9em;
        font-weight: 100;
      }
      #breakhead{
        margin-top: 0;
        display: block;
        border: 2px solid navy;
      }
      footer {
        font-size: .5em;
        text-align: center;
      }
      #bensound {
        font-size: .6em;
        text-align: center;
        margin-right: 80%;
      }
      iframe#bobrossmountain {
        border: 4px solid navy;
      }
      img#mtnmap{
        border: 6px ridge navy;
      }
      figcaption#mountainhype {
    font-size: .8em;
        text-align: center;
        line-height: 2;
        color: navy;
    }
      a:visited {
  color: navy;
}
button#happymtn{
text-align: center;
  margin-left: 45%;
  font-size: 1em;
  background-color: white;
  border: 4px solid steelblue;
  color: navy;
  font-family: 'caveat';
  box-shadow: 3px 3px indigo;
  
}
button#happymtn:hover {
  background-color: coral;
  color: white;
  border: 4px solid navy;
  box-shadow: 3px 3px steelblue;
  cursor: pointer;
}
    </style>
    
    <body>
      <nav><ul class="countrylist" id="navlist">
        <li id="home">Home</li>  
        <li class="germ">Germany</li>  
        <li class="italy">Italy</li>  
        <li class="aust">Austria</li>  
        <li class="malt">Malta</li>  
        <li class="kam">Kamchatka</li>  
        <li class="long">Southern U.S.</li>  
        <li class="long" id="west">Western U.S.</li>  
        <li class="contact">Michigan</li> 
        <li class="contact">Contact</li>           
        </ul></nav>
      <h1 id="bigpicture">Wanderlust</h1>
      <h4 class="quote">I haven't been everywhere, but it's on my list.<br> -Susan Sonntag
        
        </h4>
      <hr id="breakhead">
      <button id="happymtn" onclick="myFunction();">Mountains!</button>
      <br>
      <audio controls loop autoplay preload="auto"> <source src="https://www.bensound.com/bensound-music/bensound-adaytoremember.mp3" type="audio/mpeg"> 
        <source src="bensound-adaytoremember.wav" type="audio/wav">
        <cource src="bensound-adaytoremember.ogg" type="audio/ogg">
        Your browser does not support the audio file.
      </audio>
        <figcaption id=bensound>Music: <a href="www.bensound.com">Bensound</a></figcaption> 
      <br>
      <br>
        <!-- Image Map Generated by http://www.image-map.net/ -->
<img id="mtnmap" src="http://i63.tinypic.com/359bmfa.jpg" alt="Beautiful blue mountains to navigate to pages with mountain range information." usemap="#mountainmap" style="display: block; margin-left: auto; margin-right: auto;" width="850em">

<map name="mountainmap">
    <area target="_blank" alt="Appalachian mountains" title="Click to navigate to the Appalachian Mountains" href="https://en.wikipedia.org/wiki/Appalachian_Mountains" coords="140,232,226,212,266,217,409,293,356,300,233,287,112,299,81,277,107,243,129,239" shape="poly">
    <area target="_blank" alt="Alps" title="Click to navigate to the Alps" href="https://en.wikipedia.org/wiki/Alps" coords="2,130,140,99,350,91,389,145,217,164,89,193,6,186,0,156,8,141" shape="poly">
    <area target="_blank" alt="Himalayas" title="Click to navigate to the Himalayas" href="https://en.wikipedia.org/wiki/Himalayas" coords="391,105,748,109,798,120,773,180,642,178,501,144,475,155" shape="poly">
    <area target="_blank" alt="Rocky Mountains" title="Click to navigate to the Rockies" href="https://en.wikipedia.org/wiki/Rocky_Mountains" coords="483,175,371,201,550,163,217,168,2,211,37,269,274,196,315,237,408,202,544,224,587,247,631,230,691,235,746,208,796,187,576,177,550,165" shape="poly">
    <area target="_blank" alt="Andes" title="Click to navigate to the Andes" href="https://en.wikipedia.org/wiki/Andes" coords="412,290,593,289,616,260,614,259,520,226,464,212,415,205,376,219,342,232,327,237" shape="poly">
</map>
        <figcaption id="mountainhype">Hover over sections of the ridges for information on various popular hikes around the world!</figcaption>
      <br>
      <br>
      <br>
      <br>
        <iframe id="bobrossmountain" style="display: block; margin-left: auto; margin-right: auto;" width="560" height="315" src="https://www.youtube.com/embed/kNZssD9zWlw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <br>
      <br>
      <br>
      <img src="http://i64.tinypic.com/23j6d7k.jpg" border="0" alt="angels landing zion" width="300" title="Angels Landing, Zion National Park, Utah"> <img src="http://i68.tinypic.com/ieq9ae.jpg" border="0" alt="hiker in Austrian Alps" width="300" align="middle" title="Zillertal hike in Austria"> <img src="http://i64.tinypic.com/14t7ypg.jpg" border="0" alt="hiking volcanoes in Russia" width="330" title="Kamchatka volcano hikes, Russia">
      <hr>
      <article id=southus>
        <header>
          <h2 id="pagehead"> Exploring the <a href="https://en.wikipedia.org/wiki/South_Atlantic_states">Southern U.S.</a> </h2>
          <h3> Beauty, Nature & Adventure </h3>
          <h4> <i>Where to Go, What to Do, & How to Not Get Lost</i></h4>
          <p>Sweet tea. Shrimp and grits. Wonderfully warm and kind people. Red clay. Hurricanes. Cotton and palm trees and tobacco.  
All of this comes to mind when thinking of the South, that conglomeration of U.S. states with their own strong identity and culture.
     Prior to moving to South Carolina, all I personally knew was gleaned from books, like Gone With The Wind and To Kill A Mocking Bird, the news, history, and the weather channel. Thus, I was quite pleasantly surprised to discover gorgeous mountains and towns that still possess the ability to thrust one back into the past, into a world where people move more slowly and still rock on porches. This is by no means an exhaustive compilation, but rather a begin, an overview of some of my favorite places with a skew towards activities for the active.        
        </header>
        <section>
      <details>
        <summary class="minitopic"><b><u>Hiking</u></b></summary><br>
          <ul>
            <details>
            <summary>Smoky Mountains</summary>
            <ul>
              <li>Chimney Top</li>
              <li>Mount LeConte, Alum Cave</li>
              <li>Mt. Cammerer</li>
              <li>Newfound Gap</li>
              <li>Clingman's Dome</li>
              <li>The Appalachain Trail</li>
              </ul></details>
            <details><summary>Blue Ridge Mountains</summary>
            <ul>
           <li>Grandfather Rock</li>
         <li>Blue Ridge Parkway</li>
        </ul></details>
            <details>
    <summary>South Carolina</summary>
            <ul>
              <li>Table Rock</li>
              <li>Cesar's Head</li>
              </ul></details>
            <details>
            <summary>Pisgah National Forest</summary>
            <ul>
              <li>Waterfalls</li>
              <li>Mount Mitchell</li>
              </ul> </details>
            </ul> </details>
        </section>
        
        <section>
          <hr>
          <details>
          <summary class="minitopic"><u><b>City Life</b></u></summary><h5>Click the links for more information!</h5>
          <ul>
            <li>Asheville, NC</li>
            <li>Greenville, SC</li>
            <li>Charleston, SC</li>
            <li>Savannah, GA</li>
            <li>Cherokee, NC</li>
            </ul></details>
        </section>
        <hr>
        <footer>
          <pre> Written by: Kelsey Mae Ehnle    2018    Contact: <a href="kmae@umich.edu">kmae@umich.edu</a></pre>
        </footer>
      </article>
        
          
