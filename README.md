<!DOCTYPE html>
<html lang="en">
<head>
<title>Design Styles</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #3b3a30;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Container for flexboxes */
section {
  display: -webkit-flex;
  display: flex;
}

/* Style the navigation menu */
nav {
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  background: #c0ded9;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

/* Style the content */
article {
  -webkit-flex: 3;
  -ms-flex: 3;
  flex: 3;
  background-color: #b2c2bf;
  padding: 10px;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the menu and the content (inside the section) sit on top of each other instead of next to each other */
@media (max-width: 600px) {
  section {
    -webkit-flex-direction: column;
    flex-direction: column;
  }
}
</style>
</head>
<body>


<header>
  <h2>Design Styles</h2>
</header>

<section>
  <nav>
  <h4>Types of Design Styles:</h4>
    <dl>
  <dt><b>Contrast:</b></dt>
  <dd><a href="https://www.webmasterserviceshawaii.com/">Webmaster Services</a></dd>
  <dt><b>Repetition:</b></dt>
  <dd><a href="https://wikiwikiexpress.com/">Wikiwiki Express</a></dd>
  <dt><b>Alignment:</b></dt>
  <dd><a href="https://www.hawaiianbarbecue.com/">L & L Hawai'i</a></dd>
  <dt><b>Proximity:</b></dt>
  <dd><a href="https://www.leonardshawaii.com/home/#">Leonard's Bakery</a></dd>
</dl>
  </nav>
  
  <article>
    <h1>Benefits</h1>
   <ul>
  <li>Color pairs well together</li>
  <li>It's easy to navigate</li>
  <li>Better user experiance</li>
</ul>



  




  <ol>
    <li><h3><a href="https://www.webmasterserviceshawaii.com/">Contrast</h3></li>
  <a href="https://www.webmasterserviceshawaii.com/"><img src= "https://github.com/KhamphouNampong/04---Design-Styles/blob/master/webmaster.PNG"  width="400">

  <li><h3><a href="https://wikiwikiexpress.com/">Repetition</h3></li>
  <a href="https://wikiwikiexpress.com/"><img src= "https://github.com/KhamphouNampong/04---Design-Styles/blob/master/wiki.PNG" width="400">
  
  <li><h3><a href="https://www.hawaiianbarbecue.com/">Alignment</h3></li>
  <a href="https://www.hawaiianbarbecue.com/"><img src= "https://github.com/KhamphouNampong/04---Design-Styles/blob/master/ll.PNG" width="400">
 
  <li><h3><a href="https://www.leonardshawaii.com/home/#">Proximity</h3></li>
  <a href="https://www.leonardshawaii.com/home/#"><img src= "https://github.com/KhamphouNampong/04---Design-Styles/blob/master/leanards.PNG" width="400">
</ol>

  </article>
</section>


</body>
</html>
