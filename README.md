<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WELCOME!
    </title>
    <link rel="icon" href="images/offical glitch.jpg" type="image/jpg" sizes="16x16">
    <meta charset="utf-8">
    <meta name="description" This is from my brainstorm ideas>
    <meta name="keywords" content="HTML, CSS, HTML5, JavaScript">
    <link rel="stylesheet" type="text/css" href="styles.css">
<style>
body {
    font-family: verdana;
    font-size: 20px;
    background-color: lightgreen;
}
</style>
  </head>
  <body>
    <nav class="topnav">
        <a class="active" href="#">Home</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
        <a href="gallery.html">Photo</a>
    </nav>

    <main>
    <Section id="section1">
      <article class="articles">
    <h1>Welcome to the MyWebpage</h1>
     <p style="font-size: 20px">The phenomenon, which can be observed all over the world today, is called Graffiti Art. It all started in Philadelphia, Pennsylvania on the turn of the late 60's with writers like Cornbread and Cool Earl. The movement took on very quickly in New York City and names and nicknames started to appear on buildings, post-boxes, phone boxes, underground tunnels, buses and finally on subway cars. Taki 183, whose name was to be seen all over NY, gave an interview to The New York Times in 1971. Taki’s real name was Zavy, 183 is the number of the street where he lived.
    This young greek boy wrote his name almost everywhere during his work hours as a messenger.
     Other well known writers from that period were: Joe 136, Barbara and Eva 62, Eel 159, Yank 135, Julio 204, Frank 207</p>
      </article>
    </section>
    <section id="section2">
      <article class="articles">
    <h2> This is Expressing My Creativity through works of Art.</h2>
    <p style="font-size: 20px">The interest in showing graffiti on canvas has developed as soon as graffiti sprayed in the city.
      In 1972, Hugo Martinez, sociology major at City College in New York took notice of the legitimate artistic potential of the early graffiti writers generation.
      United Graffiti Artists and Martinez selected top subway artists from all around the city and presented their work in the formal context of an art gallery.</p>
      </article>
    </section>
</main>
<script>
// When the user scrolls down 20px from the top of the document, slide down the navbar
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    document.getElementById("navbar").style.top = "0";
  } else {
    document.getElementById("navbar").style.top = "-50px";
  }
}
</script>
<a href=#mainTitle>Go back to top</a>
  </body>



</html>
