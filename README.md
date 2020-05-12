<!DOCTYPE html> 
<html>
<head>
<div>
    <h1>Welcome to maxwells deals</h1>
	</div>
	
	<style>body {
  background-color:white;
}

h1 {
  color: grey;
  text-align: center;
}
h2 {
   color: green;
   text-align: centre;
}
p {
  font-family: verdana;
  font-size: 30px;
}
</style>
</head>
<h1><em>Maxwellsdeals.com</em></h1>
<body>
<div>
     <ol>
	 <li><a href="https://www.google.nl/">google</a></li>
	 <li><a href="">discounts</a></li>
	 <li><a href="">top deals</a></li>
	 </ol>
	 </div>
    </body>
	     <input type="text" id="mySearch" onkeyup="myFunction()" placeholder="Search.." title="Type in a category">

         <ol id="myMenu">
                        <li><a href="#">HTML</a></li>
                        <li><a href="#">CSS</a></li>
                        <li><a href="#">JavaScript</a></li>
                        <li><a href="#">PHP</a></li>
                        <li><a href="#">Python</a></li>
                        <li><a href="#">jQuery</a></li>
                        <li><a href="#">SQL</a></li>
                        <li><a href="#">Bootstrap</a></li>
                        <li><a href="#">Node.js</a></li>
                        </ol>
						<button class="tablink" onclick="openPage('Home', this, 'red')">Home</button>
<button class="tablink" onclick="openPage('News', this, 'green')" id="defaultOpen"><a href="https://www.google.nl">Search the internet</button>
<button class="tablink" onclick="openPage('Contact', this, 'blue')">Contact</button>
<button class="tablink" onclick="openPage('About', this, 'orange')">About</button>

<div id="Home" class="tabcontent">
  <h3>Home</h3>
  <p>Home is where the heart is..</p>
</div>

<div id="News" class="tabcontent">
  <h3>Search the internet</h3>
  <p><h4>Some news this fine day!</h4></p>
</div>

<div id="Contact" class="tabcontent">
  <h3>Contact</h3>
  <p>Get in touch, or swing by for a cup of coffee.</p>
</div>

<div id="About" class="tabcontent">
  <h3>About</h3>
  <p>Who we are and what we do.</p>
</div>
	</body>
	     
</html> 
