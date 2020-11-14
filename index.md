## Welcome to Tyfoon be Ayushman Sinha
<html>
  <body bgcolor="blue">
  <div class="topnav">
  <a class="active" href="#home">Home</a>
  <a href="#news">News</a>
  <a href="#contact">Contact</a>
  <a href="#about">About</a>
</div>
<h1>Typewriter</h1>

<button onclick="typeWriter()">Click me</button>

<p id="demo"></p>

<script>
var i = 0;
var txt = 'Lorem ipsum dummy text blabla.';
var speed = 50;

function typeWriter() {
  if (i < txt.length) {
    document.getElementById("demo").innerHTML += txt.charAt(i);
    i++;
    setTimeout(typeWriter, speed);
  }
}
</script>

    
  </body>

