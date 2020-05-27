# HTML-portfolio
<!DOCTYPE html>
<html>
<head>
<style>

body {
  background-color: white;
}

h1{
  font-size: 28px;
}

/* The navigation bar */
.navbar {
  overflow: hidden;
  background-color: #333;
  position: fixed; /* Set the navbar to fixed position */
  top: 0; /* Position the navbar at the top of the page */
  width: 100%; /* Full width */
}

/* Links inside the navbar */
.navbar a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change background on mouse-over */
.navbar a:hover {
  background: #ddd;
  color: black;
}

.welcome-section{
  height: 100vh;
  background-color: white;
  color: red;
  text-align: center;
  padding: 50px;
}

.project-tile {
  font-size: 40px;
  text-align: center;
  background-color: lightblue;
  padding: 20px;
}
  
  .center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}
</style>

<div class="navbar">
  <a href="#welcome-section">Home</a>
  <a href="#projects">Projects</a>
  <a href="#contact">Contact</a>
</div>

<div class="welcome-section">
  <section id="welcome-section">
   <h1>Farqa's groveste portfolio</h1>
  </section>
</div>
  
<img src="https://i.ytimg.com/vi/tFpA8KWR1NQ/maxresdefault.jpg" alt="This is an image">
</img>

<div id="projects">
  <div class="project-tile">
    <h2>Python</h2>
    <p>Python veteran developer</p>
  </div>
  
  <div class="project-tile">
    <h2>HTML</h2>
    <p>Exquisid html developer</p>
  </div> 
 
  <div class="project-tile"> 
    <h2>Ruby on rails</h2>
    <p>Groveste Ruby developeren ever.</p>
      <a href="https://pure-journey-13452.herokuapp.com/cars?fbclid=IwAR1UrYwzIRRDHL-MrptesFGv9zPgvEZvR8zeC53WBQjHNnEIIUWCyAhuAQ0" target=_blank> Sjekk ut den grove appen jeg lagde. </a> 
    <p>ps hvertall ikke stjålet...</p>
  </div>
</div>

<section id="contact">
  <a href="https://github.com/Farqaleeti"   target="_blank"><button>GitHub  Profile</button></a>
</section>
