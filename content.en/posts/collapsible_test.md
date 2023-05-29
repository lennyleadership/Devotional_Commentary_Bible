+++
title = "Collapsible test"
description = ""
tags = [

]
date = "2023-05-27"
categories = [
]
menu = "main"
+++


<h1><span class = "overline">Option #1</span></h1>
<button type="button" class="collapsible">Collapsible Demo</button>
<div class="content">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>



<h1><span class = "overline">Option #2</span></h1>

<h1>BJCP Style 26. Trappist Ale</h1>
<section class="accordion">
  <input type="checkbox" name="collapse" id="handle1" checked="checked">
  <h2 class="handle">
    <label for="handle1">26A. Trappist Single</label>
  </h2>
  <div class="content">
    <p><strong>Overall Impression:</strong> A pale, bitter, highly attenuated and well carbonated Trappist ale, showing a fruity-spicy Trappist yeast character, a spicy-floral hop profile, and a soft, supportive grainy-sweet malt palate.</p>
    <p><strong>History:</strong> While Trappist breweries have a tradition of brewing a lower-strength beer as a monk’s daily ration, the bitter, pale beer this style describes is a relatively modern invention reflecting current tastes. Westvleteren first brewed theirs in 1999, but replaced older lower-gravity products.</p>
  </div>
</section>
<section class="accordion">
  <input type="checkbox" name="collapse2" id="handle2">
  <h2 class="handle">
    <label for="handle2">26B. Belgian Dubbel</label>
  </h2>
  <div class="content">
    <p><strong>Overall Impression:</strong> A deep reddish-copper, moderately strong, malty, complex Trappist ale with rich malty flavors, dark or dried fruit esters, and light alcohol blended together in a malty presentation that still finishes fairly dry.</p>
    <p><strong>History:</strong> Originated at monasteries in the Middle Ages, and was revived in the mid-1800s after the Napoleonic era.</p>
  </div>
</section>
<section class="accordion">
  <input type="checkbox" name="collapse2" id="handle3">
  <h2 class="handle">
    <label for="handle3">26C. Belgian Tripel</label>
  </h2>
  <div class="content">
    <p><strong>Overall Impression:</strong> A pale, somewhat spicy, dry, strong Trappist ale with a pleasant rounded malt flavor and firm bitterness. Quite aromatic, with spicy, fruity, and light alcohol notes combining with the supportive clean malt character to produce a surprisingly drinkable beverage considering the high alcohol level.</p>
    <p><strong>History:</strong> Originally popularized by the Trappist monastery at Westmalle.</p>
  </div>
</section>

<p><small>Source: <cite><a href="https://www.bjcp.org/stylecenter.php">BJCP Style Guidelines</a></cite></small></p>

<a href = "https://codepen.io/markcaron/pen/RVvmaz" target="_blank" rel="noopener noreferrer">[Source]</a>


<style>
.accordion > input[type="checkbox"] {
  position: absolute;
  left: -100vw;
}

.accordion .content {
  overflow-y: hidden;
  height: 0;
  transition: height 0.3s ease;
}

.accordion > input[type="checkbox"]:checked ~ .content {
  height: auto;
  overflow: visible;
}

.accordion label {
  display: block;
}

/*
 Styling
*/
body {
  font: 16px/1.5em "Overpass", "Open Sans", Helvetica, sans-serif;
  color: #333;
  font-weight: 300;
}

.accordion {
  margin-bottom: 1em;
}

.accordion > input[type="checkbox"]:checked ~ .content {
  padding: 15px;
  border: 1px solid #e8e8e8;
  border-top: 0;
}

.accordion .handle {
  margin: 0;
  font-size: 1.125em;
  line-height: 1.2em;
}

.accordion label {
  color: #333;
  cursor: pointer;
  font-weight: normal;
  padding: 15px;
  background: #e8e8e8;
}

.accordion label:hover,
.accordion label:focus {
  background: #d8d8d8;
}

.accordion .handle label:before {
  font-family: 'fontawesome';
  content: "\f054";
  display: inline-block;
  margin-right: 10px;
  font-size: .58em;
  line-height: 1.556em;
  vertical-align: middle;
}

.accordion > input[type="checkbox"]:checked ~ .handle label:before {
  content: "\f078";
}


/*
 Demo purposes only
*/
*,
*:before,
*:after {
  box-sizing: border-box;
}

body {
  padding: 40px;
}

a {
  color: #06c;
}

p {
  margin: 0 0 1em;
}

h1 {
  margin: 0 0 1.5em;
  font-weight: 600;
  font-size: 1.5em;
}

.accordion {
  max-width: 65em;
}

.accordion p:last-child {
  margin-bottom: 0;
}
</style>



<h1><span class = "overline">Option #3</span></h1>

<details>
  <summary>
  Click to toggle
  </summary>
  <span>Hello</span>
</details>



<h1><span class = "overline">Option #4</span></h1>
<label for="my_checkbox">Collapsible message <span class = "icon">+</span></label>
<input type="checkbox" id="my_checkbox" style="display:none;">
<div id="hidden">
<p>text</p>
</div>



<style>
#hidden {
  display: none;
  height: fit;
  background: lightblue;
}

:checked + #hidden {
  display: block;
  span.icon {
  transform: rotate(45deg);
}
}
</style>


<h1><span class = "overline">Option #5</span></h1>
<div class="collapsible">
    <label for="checkbox2" class="collapsor-lbl"> Click me </label>
    <div class="focus-capturer" tabindex="0">
        <input id="checkbox2" class="collapsor" type="checkbox" />
        <div class="collapsible-content">
            <p>This is the body of the collapsible.<p>
            <ul>
                <li><a href="">link1</a></li>
                <li><a href="">link2</a></li>
                <li><a href="">link3</a></li>
            </ul>
        </div>
    </div>
</div>

<style>
.collapsible {
  background-color: green;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.collapsor-lbl:hover {
    background-color: orange;
}

.collapsor-lbl {
    display: block;
    text-align: left;
    padding: 0.5rem 1rem;
}

.collapsor-lbl:after {
  content: '\02795'; /* Unicode character for "plus" sign (+) */
  font-size: 13px;
  color: white;
  float: right;
  margin-left: 5px;
}

.collapsor, .active:after {
  content: "\2716"; /* Unicode character for "Heavy multiplication X" sign (X) */
  font-size: 13px;
  color: white;
  float: right;
  margin-left: 30px;
}


.collapsible-content {
    padding: 0.5rem;
    border-top: 1px solid black;
}


.collapsor, .collapsible-content {
    display: none;
}
.collapsor:checked ~ .collapsible-content {
  display: block;
}

.focus-capturer:focus-within .collapsible-content {
    display: block;
}
</style>



<h1><span class = "overline">Option #6</span></h1>
<a href = "https://dev.to/jordanfinners/creating-a-collapsible-section-with-nothing-but-html-4ip9" target="_blank" rel="noopener noreferrer">[source]</a>
 
<br>
<details>
  <summary>
    What is the meaning of life?
    <span class="icon">👇</span>
  </summary>
  <p>
    42 more details
  </p>
</details>

<style>
details {
  user-select: none;
}

details>summary span.icon {
  width: 24px;
  height: 24px;
  transition: all 0.3s;
  margin-left: auto;
}

details[open] summary span.icon {
  transform: rotate(180deg);
}

summary {
  display: flex;
  cursor: pointer;
}

summary::-webkit-details-marker {
  display: none;
}
</style>



<h1><span class = "overline">Option #7</span></h1>
<a href = "https://www.freecodecamp.org/news/build-an-accordion-menu-using-html-css-and-javascript/" target="_blank" rel="noopener noreferrer">[source]</a>


<body>
  <div class="accordion-body">
  <div class="accordion">
    <h1>Frequently Asked Questions</h1>
    <hr>
    <div class="container">
      <div class="label">What is HTML?</div>
      <div class="content">Hypertext Markup Language (HTML) is a computer language that makes up most web pages and online applications. A hypertext is a text that is used to reference other pieces of text, while a markup language is a series of markings that tells web servers the style and structure of a document. HTML is very simple to learn and use.</div>
    </div>
    <hr>
    <div class="container">
      <div class="label">What is CSS?</div>
      <div class="content">CSS stands for Cascading Style Sheets. It is the language for describing the presentation of Web pages, including colours, layout, and fonts, thus making our web pages presentable to the users. CSS is designed to make style sheets for the web. It is independent of HTML and can be used with any XML-based markup language. CSS is popularly called the design language of the web.
</div>
    </div>
    <hr>
    <div class="container">
      <div class="label">What is JavaScript?</div>
      <div class="content">JavaScript is a scripting or programming language that allows you to implement complex features on web pages — every time a web page does more than just sit there and display static information for you to look at — displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc. — you can bet that JavaScript is probably involved. It is the third of the web trio.</div>
    </div>
    <hr>
    <div class="container">
      <div class="label">What is React?</div>
      <div class="content">React is a JavaScript library created for building fast and interactive user interfaces for web and mobile applications. It is an open-source, component-based, front-end library responsible only for the application’s view layer. In Model View Controller (MVC) architecture, the view layer is responsible for how the app looks and feels. React was created by Jordan Walke, a software engineer at Facebook. </div>
    </div>
    <hr>
    <div class="container">
      <div class="label">What is PHP?</div>
      <div class="content">PHP is a server-side and general-purpose scripting language that is especially suited for web development. PHP originally stood for Personal Home Page. However, now, it stands for Hypertext Preprocessor. It’s a recursive acronym because the first word itself is also an acronym.</div>
    </div>
    <hr>
    <div class="container">
      <div class="label">What is Node JS?</div>
      <div class="content">Node.js is an open-source, cross-platform, back-end JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside a web browser. Node.js lets developers use JavaScript to write command line tools and for server-side scripting—running scripts server-side to produce dynamic web page content before the page is sent to the user's web browser. Consequently, Node.js represents a "JavaScript everywhere" paradigm</div>
    </div>
    <hr>
  </div>
  </div>

</body>

<style>
@import url('https://fonts.googleapis.com/css2?family=Rubik:wght@300&display=swap');

/* Sets the background color of the body to blue. Sets font to Rubik */

body {
  font-family: 'rubik', sans-serif;
}

/* Aligns the heading text to the center. */
 
h1 {
  text-align: center;
}

/* Sets the width for the accordion. Sets the margin to 90px on the top and bottom and auto to the left and right */

.accordion {
  width: 800px;
  margin: 90px auto;
  color: black;
  background-color: white;
  padding: 45px 45px;
}


/* Positions the plus sign 5px from the right. Centers it using the transform property. */

.accordion .label::before {
  content: '+';
  color: black;
  position: absolute;
  top: 50%;
  right: -5px;
  font-size: 30px;
  transform: translateY(-50%);
}

/* Hides the content (height: 0), decreases font size, justifies text and adds transition */

.accordion .content {
  position: relative;
  background: white;
  height: 0;
  font-size: 20px;
  text-align: justify;
  width: 780px;
  overflow: hidden;
  transition: 0.5s;
}

/* Adds a horizontal line between the contents */

.accordion hr {
  width: 100;
  margin-left: 0;
  border: 1px solid grey;
}


/* Unhide the content part when active. Sets the height */

.accordion .container.active .content {
  height: 150px;
}

/* Changes from plus sign to negative sign once active */

.accordion .container.active .label::before {
  content: '-';
  font-size: 30px;
}


</style>

<script src="index.js" type="text/javascript">
  const accordion = document.getElementsByClassName('container');

for (i=0; i<accordion.length; i++) {
  accordion[i].addEventListener('click', function () {
    this.classList.toggle('active')
  })
}

  </script>


<h1><span class = "overline">Option #8</span></h1>


<h1>CSS + HTML only Accordion Element</h1>
<ul>
  <li>
    <input type="checkbox" checked>
    <i></i>
    <h2>Languages Used</h2>
    <p>This page was written in HTML and CSS. The CSS was compiled from SASS. I used Normalize as my CSS reset and -prefix-free to save myself some headaches. I haven't quite gotten the hang of Slim for compiling into HTML, but someday I'll use it since its syntax compliments that of SASS. Regardless, this could all be done in plain HTML and CSS.</p>
  </li>
  <li>
    <input type="checkbox" checked>
    <i></i>
    <h2>How it Works</h2>
    <p>Using the sibling and checked selectors, we can determine the styling of sibling elements based on the checked state of the checkbox input element. One use, as demonstrated here, is an entirely CSS and HTML accordion element. Media queries are used to make the element responsive to different screen sizes.</p>
  </li>
  <li>
    <input type="checkbox" checked>
    <i></i>
    <h2>Points of Interest</h2>
    <p>By making the open state default for when :checked isn't detected, we can make this system accessable for browsers that don't recognize :checked. The fallback is simply an open accordion. The accordion can be manipulated with Javascript (if needed) by changing the "checked" property of the input element.</p>
  </li>
</ul>

<style>
  

.transition, ul li i:before, ul li i:after, p {
  transition: all 0.25s ease-in-out;
}

.flipIn, ul li, h1 {
  animation: flipdown 0.5s ease both;
}

.no-select, h2 {
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

html {
  width: 100%;
  height: 100%;
  perspective: 900;
  overflow-y: scroll;
  background-color: #dce7eb;
  font-family: "Titillium Web", sans-serif;
  color: rgba(48, 69, 92, 0.8);
}

body {
  min-height: 0;
  display: inline-block;
  position: relative;
  left: 50%;
  margin: 90px 0;
  transform: translate(-50%, 0);
  box-shadow: 0 10px 0 0 #ff6873 inset;
  background-color: #fefffa;
  max-width: 450px;
  padding: 30px;
}
@media (max-width: 550px) {
  body {
    box-sizing: border-box;
    transform: translate(0, 0);
    max-width: 100%;
    min-height: 100%;
    margin: 0;
    left: 0;
  }
}

h1, h2 {
  color: #ff6873;
}

h1 {
  text-transform: uppercase;
  font-size: 36px;
  line-height: 42px;
  letter-spacing: 3px;
  font-weight: 100;
}

h2 {
  font-size: 26px;
  line-height: 34px;
  font-weight: 300;
  letter-spacing: 1px;
  display: block;
  background-color: #fefffa;
  margin: 0;
  cursor: pointer;
}

p {
  color: rgba(48, 69, 92, 0.8);
  font-size: 17px;
  line-height: 26px;
  letter-spacing: 1px;
  position: relative;
  overflow: hidden;
  max-height: 800px;
  opacity: 1;
  transform: translate(0, 0);
  margin-top: 14px;
  z-index: 2;
}

ul {
  list-style: none;
  perspective: 900;
  padding: 0;
  margin: 0;
}
ul li {
  position: relative;
  padding: 0;
  margin: 0;
  padding-bottom: 4px;
  padding-top: 18px;
  border-top: 1px dotted #dce7eb;
}
ul li:nth-of-type(1) {
  animation-delay: 0.5s;
}
ul li:nth-of-type(2) {
  animation-delay: 0.75s;
}
ul li:nth-of-type(3) {
  animation-delay: 1s;
}
ul li:last-of-type {
  padding-bottom: 0;
}
ul li i {
  position: absolute;
  transform: translate(-6px, 0);
  margin-top: 16px;
  right: 0;
}
ul li i:before, ul li i:after {
  content: "";
  position: absolute;
  background-color: #ff6873;
  width: 3px;
  height: 9px;
}
ul li i:before {
  transform: translate(-2px, 0) rotate(45deg);
}
ul li i:after {
  transform: translate(2px, 0) rotate(-45deg);
}
ul li input[type=checkbox] {
  position: absolute;
  cursor: pointer;
  width: 100%;
  height: 100%;
  z-index: 1;
  opacity: 0;
}
ul li input[type=checkbox]:checked ~ p {
  margin-top: 0;
  max-height: 0;
  opacity: 0;
  transform: translate(0, 50%);
}
ul li input[type=checkbox]:checked ~ i:before {
  transform: translate(2px, 0) rotate(45deg);
}
ul li input[type=checkbox]:checked ~ i:after {
  transform: translate(-2px, 0) rotate(-45deg);
}

@keyframes flipdown {
  0% {
    opacity: 0;
    transform-origin: top center;
    transform: rotateX(-90deg);
  }
  5% {
    opacity: 1;
  }
  80% {
    transform: rotateX(8deg);
  }
  83% {
    transform: rotateX(6deg);
  }
  92% {
    transform: rotateX(-3deg);
  }
  100% {
    transform-origin: top center;
    transform: rotateX(0deg);
  }
}


</style>