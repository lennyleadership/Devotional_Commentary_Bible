+++
title = "Accordion / Collapsible test"
description = ""
tags = ["Demo Accordion Table", "Demo Accordion Text"]
date = "2023-05-29"
categories = []
menu = "main"
+++

<style>
body{
  /*height: calc(100% - 20px);*/
  /*width: calc(100% - 20px);*/
  /*margin: 0;*/
  /*padding: 10px;*/
  /*display: flex;*/
  /*background: #f2f2f2;*/
  /*color: rgba(0,0,0,.87);*/
  /*font-family: 'Roboto', sans-serif;*/
}

</style>



<h1><span class = "overline">Option #1</span></h1>

<div id="faq">

  <ul>
    <li>
      <input type="checkbox" checked>
      <i></i>
      <h2>Question #1..?</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestiae debitis iusto voluptatum doloribus rem, qui nesciunt labore tempore fugit iste deserunt incidunt error provident repudiandae laudantium quo ipsa unde perspiciatis, nihil autem distinctio! Deserunt, aspernatur.</p>
    </li>
    <li>
      <input type="checkbox" checked>
      <i></i>
      <h2>Question #2..?</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente quasi, quia provident facere recusandae itaque assumenda fuga veniam dicta earum dolorem architecto facilis nisi pariatur.</p>
    </li>
    <li>
      <input type="checkbox" checked>
      <i></i>
      <h2>Question #3..?</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nam quas placeat assumenda mollitia magni consequatur dolorum, quod nihil distinctio aperiam officia alias! Voluptate dolore ex officiis sit, magnam non a, eligendi pariatur aut, earum dolores tenetur ipsam id illo deleniti. Laudantium deserunt eaque ipsam voluptatum consequuntur voluptatibus sed minima ad accusamus debitis eos similique laboriosam, molestiae? Consequatur neque tempore quis. Eligendi, in ut aspernatur esse nesciunt libero.</p>
    </li>
  </ul>
</div>


<style>

#faq {
  max-width: 700px;
  margin: auto;
  padding: 0 15px;
  text-align: center;
}

section.faq {
  padding-top: 2em;
  padding-bottom: 3em;
}

#faq ul {
  text-align: left;
}
.transition, p, ul li i:before, ul li i:after {
  transition: all 0.3s;
}

#faq .no-select, #faq h2 {
  -webkit-tap-highlight-color: transparent;
  -webkit-touch-callout: none;
  user-select: none;
}

#faq h1 {
  color: #000;
  margin-bottom: 30px;
  margin-top: 0;
}

#faq h2 {
  color: #cc071e;
  font-size: 20px;
  line-height: 34px;
  text-align: left;
  padding: 15px 15px 0;
  text-transform: none;
  font-weight: 300;
  display: block;
  margin: 0;
  cursor: pointer;
  transition: .2s;
}

#faq p {
  color: #333;
  text-align: left;
  font-size: 14px;
  line-height: 1.45;
  position: relative;
  overflow: hidden;
  max-height: 250px;
  will-change: max-height;
  contain: layout;
  display: inline-block;
  opacity: 1;
  transform: translate(0, 0);
  margin-top: 5px;
  margin-bottom: 15px;
  padding: 0 50px 0 15px;
  transition: .3s opacity, .6s max-height;
  hyphens: auto;
  z-index: 2;
}

#faq ul {
  list-style: none;
  perspective: 900;
  padding: 0;
  margin: 0;
}
#faq ul li {
  position: relative;
  overflow: hidden;
  padding: 0;
  margin: 0;
  /*padding-bottom: 4px;*/
  /*padding-top: 18px;*/
  background: #fff;
  box-shadow: 0 3px 10px -2px rgba(0,0,0,0.1);
  -webkit-tap-highlight-color: transparent;
}
#faq ul li + li {
  margin-top: 15px;
}
#faq ul li:last-of-type {
  padding-bottom: 0;
}
#faq ul li i {
  position: absolute;
  transform: translate(-6px, 0);
  margin-top: 28px;
  right: 15px;
}
#faq ul li i:before, ul li i:after {
  content: "";
  position: absolute;
  background-color: #cc071e;
  width: 3px;
  height: 9px;
}
#faq ul li i:before {
  transform: translate(-2px, 0) rotate(45deg);
}
#faq ul li i:after {
  transform: translate(2px, 0) rotate(-45deg);
}
#faq ul li input[type=checkbox] {
  position: absolute;
  cursor: pointer;
  width: 100%;
  height: 100%;
  z-index: 1;
  opacity: 0;
  touch-action: manipulation;
}
#faq ul li input[type=checkbox]:checked ~ h2 {
  color: #000;
}
#faq ul li input[type=checkbox]:checked ~ p {
  /*margin-top: 0;*/
  max-height: 0;
  transition: .3s;
  opacity: 0;
  /*transform: translate(0, 50%);*/
}
#faq ul li input[type=checkbox]:checked ~ i:before {
  transform: translate(2px, 0) rotate(45deg);
}
#faq ul li input[type=checkbox]:checked ~ i:after {
  transform: translate(-2px, 0) rotate(-45deg);
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html, body {
  /*height: 100%;*/
}

a,
a:visited,
a:focus,
a:active,
a:link {
  text-decoration: none;
  outline: 0;
}

a {
  color: currentColor;
  transition: .2s ease-in-out;
}

h1, h2, h3, h4 {
  margin: .3em 0;
}

ul {
  padding: 0;
  list-style: none;
}

img {
  vertical-align: middle;
  height: auto;
  width: 100%;
}


</style>



<h1><span class = "overline">Option #2</span></h1>



<div class="container">
          <b>Simple Flat UI CSS Accordion</b>  
          <br>case#5: https://alvarotrigo.com/blog/css-accordion/
          <div class="accordion">
            <dl>
              <dt><a class="accordionTitle" href="#">Test Simple Flat UI CSS Accordion 1</a></dt>
              <dd class="accordionItem accordionItemCollapsed">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
              </dd>
              <dt><a href="#" class="accordionTitle">Test Simple Flat UI CSS Accordion 2</a></dt>
              <dd class="accordionItem accordionItemCollapsed">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
              </dd>
              <dt><a href="#" class="accordionTitle">Test Simple Flat UI CSS Accordion 3</a></dt>
              <dd class="accordionItem accordionItemCollapsed">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
              </dd>
            </dl>
          </div>
</div>


<style>
@import url(https://fonts.googleapis.com/css?family=Lato:400,700);
* {
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}

body {
  font-family: 'Lato';
}

h1 {
  font-size: 2em;
  padding: 2em;
  /*text-align: center;*/
}

.accordion dl {
}

.accordion dt > a {
  text-align: center;
  font-weight: 700;
  padding: 2em;
  display: block;
  text-decoration: none;
  color: #fff;
  -webkit-transition: background-color 0.5s ease-in-out;
}
.accordion dd {
  background-color: #1abc9c;
  color:#fafafa;
  font-size: 1em;
  line-height: 1.5em;
}
.accordion dd > p {
  padding: 1em 2em 1em 2em;
}

.accordion {
  position: relative;
  background-color: #16a085;
}

.container {
  max-width: 960px;
  margin: 0 auto;
  padding: 2em 0 2em 0;
}

.accordionTitle {
  background-color: #22313F;
  border-bottom: 1px solid #2c3e50;
}
.accordionTitle:before {
  content: "+";
  font-size: 1.5em;
  line-height: 0.5em;
  float: left;
  -moz-transition: -moz-transform 0.3s ease-in-out;
  -o-transition: -o-transform 0.3s ease-in-out;
  -webkit-transition: -webkit-transform 0.3s ease-in-out;
  transition: transform 0.3s ease-in-out;
}
.accordionTitle:hover {
  background-color: #2c3e50;
}

.accordionTitleActive {
  background-color:#34495e;
}
.accordionTitleActive:before {
  -webkit-transform: rotate(-225deg);
  -moz-transform: rotate(-225deg);
  transform: rotate(-225deg);
}

.accordionItem {
  height: auto;
  overflow: hidden;
}
@media all {
  .accordionItem {
    max-height: 50em;
    -moz-transition: max-height 1s;
    -o-transition: max-height 1s;
    -webkit-transition: max-height 1s;
    transition: max-height 1s;
  }
}
@media screen and (min-width: 48em) {
  .accordionItem {
    max-height: 15em;
    -moz-transition: max-height 0.5s;
    -o-transition: max-height 0.5s;
    -webkit-transition: max-height 0.5s;
    transition: max-height 0.5s;
  }
}

.accordionItemCollapsed {
  max-height: 0;
}

.animateIn {
  -webkit-animation-name: accordionIn;
  -webkit-animation-duration: 0.65s;
  -webkit-animation-iteration-count: 1;
  -webkit-animation-direction: normal;
  -webkit-animation-timing-function: ease-in-out;
  -webkit-animation-fill-mode: both;
  -webkit-animation-delay: 0s;
  -moz-animation-name: normal;
  -moz-animation-duration: 0.65s;
  -moz-animation-iteration-count: 1;
  -moz-animation-direction: alternate;
  -moz-animation-timing-function: ease-in-out;
  -moz-animation-fill-mode: both;
  -moz-animation-delay: 0s;
  animation-name: accordionIn;
  animation-duration: 0.65s;
  animation-iteration-count: 1;
  animation-direction: normal;
  animation-timing-function: ease-in-out;
  animation-fill-mode: both;
  animation-delay: 0s;
}

.animateOut {
  -webkit-animation-name: accordionOut;
  -webkit-animation-duration: 0.75s;
  -webkit-animation-iteration-count: 1;
  -webkit-animation-direction: alternate;
  -webkit-animation-timing-function: ease-in-out;
  -webkit-animation-fill-mode: both;
  -webkit-animation-delay: 0s;
  -moz-animation-name: accordionOut;
  -moz-animation-duration: 0.75s;
  -moz-animation-iteration-count: 1;
  -moz-animation-direction: alternate;
  -moz-animation-timing-function: ease-in-out;
  -moz-animation-fill-mode: both;
  -moz-animation-delay: 0s;
  animation-name: accordionOut;
  animation-duration: 0.75s;
  animation-iteration-count: 1;
  animation-direction: alternate;
  animation-timing-function: ease-in-out;
  animation-fill-mode: both;
  animation-delay: 0s;
}

@-webkit-keyframes accordionIn {
  0% {
    opacity: 0;
    -webkit-transform: scale(0.8);
  }
  100% {
    opacity: 1;
    -webkit-transform: scale(1);
  }
}
@-moz-keyframes accordionIn {
  0% {
    opacity: 0;
    -moz-transform: scale(0.8);
  }
  100% {
    opacity: 1;
    -moz-transform: scale(1);
  }
}
@keyframes accordionIn {
  0% {
    opacity: 0;
    transform: scale(0.8);
  }
  100% {
    opacity: 1;
    transform: scale(1);
  }
}
@-webkit-keyframes accordionOut {
  0% {
    opacity: 1;
    -webkit-transform: scale(1);
  }
  100% {
    opacity: 0;
    -webkit-transform: scale(0.8);
  }
}
@-moz-keyframes accordionOut {
  0% {
    opacity: 1;
    -moz-transform: scale(1);
  }
  100% {
    opacity: 0;
    -moz-transform: scale(0.8);
  }
}
@keyframes accordionOut {
  0% {
    opacity: 1;
    transform: scale(1);
  }
  100% {
    opacity: 0;
    transform: scale(0.8);
  }
}
</style>

<script>
/*!
 * classie - class helper functions
 * from bonzo https://github.com/ded/bonzo
/*!
 * classie - class helper functions
 * from bonzo https://github.com/ded/bonzo
 * 
 * classie.has( elem, 'my-class' ) -> true/false
 * classie.add( elem, 'my-new-class' )
 * classie.remove( elem, 'my-unwanted-class' )
 * classie.toggle( elem, 'my-class' )
 */

/*jshint browser: true, strict: true, undef: true */
/*global define: false */
( function( window ) {
'use strict';
function classReg( className ) {
  return new RegExp("(^|\\s+)" + className + "(\\s+|$)");
}
var hasClass, addClass, removeClass;

if ( 'classList' in document.documentElement ) {
  hasClass = function( elem, c ) {
    return elem.classList.contains( c );
  };
  addClass = function( elem, c ) {
    elem.classList.add( c );
  };
  removeClass = function( elem, c ) {
    elem.classList.remove( c );
  };
}
else {
  hasClass = function( elem, c ) {
    return classReg( c ).test( elem.className );
  };
  addClass = function( elem, c ) {
    if ( !hasClass( elem, c ) ) {
      elem.className = elem.className + ' ' + c;
    }
  };
  removeClass = function( elem, c ) {
    elem.className = elem.className.replace( classReg( c ), ' ' );
  };
}

function toggleClass( elem, c ) {
  var fn = hasClass( elem, c ) ? removeClass : addClass;
  fn( elem, c );
}
var classie = {
  hasClass: hasClass,
  addClass: addClass,
  removeClass: removeClass,
  toggleClass: toggleClass,
  has: hasClass,
  add: addClass,
  remove: removeClass,
  toggle: toggleClass
};
if ( typeof define === 'function' && define.amd ) {
  define( classie );
} else {
  window.classie = classie;
}
})( window );
var $ = function(selector){
  return document.querySelector(selector);
}
var accordion = $('.accordion');
accordion.addEventListener("click",function(e) {
  e.stopPropagation();
  e.preventDefault();
  if(e.target && e.target.nodeName == "A") {
    var classes = e.target.className.split(" ");
    if(classes) {
      for(var x = 0; x < classes.length; x++) {
        if(classes[x] == "accordionTitle") {
          var title = e.target;
          var content = e.target.parentNode.nextElementSibling;
          classie.toggle(title, 'accordionTitleActive');
          if(classie.has(content, 'accordionItemCollapsed')) {
            if(classie.has(content, 'animateOut')){
              classie.remove(content, 'animateOut');
            }
            classie.add(content, 'animateIn');
          }else{
             classie.remove(content, 'animateIn');
             classie.add(content, 'animateOut');
          }
          classie.toggle(content, 'accordionItemCollapsed');      
        }
      }
    }  
  }
});
</script>




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

<div class="acc-wraper">
  <div class="accordion">
    <div>
      <img src="https://image.freepik.com/free-photo/lake-mountains_1204-507.jpg" alt="">
    </div>
    <div>
      <img src="https://image.freepik.com/free-photo/sunlight-forest_1004-9.jpg" alt="">
    </div>
    <div>
      <img src="https://image.freepik.com/free-photo/beautiful-green-park_1417-1443.jpg" alt="">
    </div>
    <div>
      <img src="https://image.freepik.com/free-photo/waterfall-that-is-layer-thailand_1150-15650.jpg" alt="">
    </div>
    <div>
      <img src="https://image.freepik.com/free-photo/sunrise-bali-jungle_1385-1644.jpg" alt="">
    </div>
    <div>
      <img src="https://image.freepik.com/free-photo/grass-with-sunlight-countryside-suburban_53876-42989.jpg" alt="">
    </div>
  </div>
</div>


<style>
.acc-wraper{
  margin: 30px auto;
  width:100%;
}

.accordion{
  display:flex;
  flex-wrap:nowrap;
  overflow:hidden;
  width:100%;
  height:350px
}

.accordion > div{
  width:70%;
  flex-grow:1;
  flex-shrink:1;
  overflow:hidden;
  transition: all .5s ease;
  border:5px solid aliceblue;
  border-radius:50px;
  position:relative
}

.accordion > div:hover{
  flex-shrink:0
}

.accordion div img{
  width:100%;
  height:100%;
  object-fit: cover;
}  
</style>


<h1><span class = "overline">Option #8</span></h1>

<div class="collapsible">
  <p>This is the first paragraph of text that will always be visible. A clickable element will be appended to the bottom of the container to show/hide more content. Alternatively, you could make the entire container clickable, but for now we're gone with the toggler.</p>
  <p>The second and subsequent paragraphs (or lists or other elements) will remain in the HTML, but hidden until requested.</p>
  <p>When the toggler is clicked, JavaScript toggles an open class on the parent container, which in turn shows and hides the additional content.</p>
  <p>Again, the only gotcha is that the first child of the container must be a P.</p>
</div>

<style>
  .collapsible {
    position: relative;
    padding-bottom: 0.5em;
  }
  .collapsible:not(.open) > * {
    display: none;
  }
  .collapsible:not(.open) > p:first-child {
    display: block;
  }

  .collapsible > .toggler {
    position: absolute;
    left: 0;
    bottom: 0;
    display: block;
    width: 100%;
    background: #fff;
    text-align: center;
    cursor: pointer;
  }
  .collapsible > .toggler::after {
    content: "\25bc";
    color: black;
  }
  .collapsible.open > .toggler::after {
    content: "\25b2";
    color: black;
  }

</style>

<script>
  document.querySelectorAll(".collapsible").forEach(function(current) {

    let toggler = document.createElement("div");
    toggler.className = "toggler";
    current.appendChild(toggler);

    toggler.addEventListener("click", function(e) {
      current.classList.toggle("open");
    }, false);

  });
</script>




<h1><span class = "overline">Table with Expando Rows</span></h1>

<p>
  For a detailed explanation of what is going on here, read my post <a href="http://adrianroselli.com/2019/09/table-with-expando-rows.html"><cite>Table with Expando Rows</cite></a>.
</p>


<h2>Disclosure Control in Cell</h2>

<p>
  The disclosure control lives in its own cell/column.
</p>

<table class="cell">
  <caption>Books I May or May Not Have Read</caption>
  <thead>
    <tr>
      <th><span class="visually-hidden">Toggle</span></th>
      <th>Author</th>
      <th>Title</th>
      <th>Year</th>
      <th>ISBN-13</th>
      <th>ISBN-10</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td></td>
      <td>Miguel De Cervantes</td>
      <td>The Ingenious Gentleman Don Quixote of La Mancha</td>
      <td>1605</td>
      <td>9783125798502</td>
      <td>3125798507</td>
    </tr>
    <tr>
      <td>
        <button type="button" id="btnMSb" aria-expanded="false" onclick="toggle(this.id,'#MS01b,#MS02b,#MS03b');" aria-controls="MS01b MS02b MS03b" aria-label="3 more from" aria-labelledby="btnMSb lblMSb">
          <svg xmlns="\http://www.w3.org/2000/svg&quot;" viewBox="0 0 80 80" focusable="false"><path d="M70.3 13.8L40 66.3 9.7 13.8z"></path></svg>
        </button>
      </td>
      <td id="lblMSb">Mary Shelley</td>
      <td>Frankenstein; or, The Modern Prometheus</td>
      <td>1818</td>
      <td>9781530278442</td>
      <td>1530278449</td>
    </tr>
    <tr id="MS01b" class="hidden">
      <td></td>
      <td>Mary Shelley</td>
      <td>Valperga: Or, the Life and Adventures of Castruccio, Prince of Lucca</td>
      <td>1823</td>
      <td></td>
      <td></td>
    </tr>
    <tr id="MS02b" class="hidden">
      <td></td>
      <td>Mary Shelley</td>
      <td>The Last Man</td>
      <td>1826</td>
      <td></td>
      <td></td>
    </tr>
    <tr id="MS03b" class="hidden">
      <td></td>
      <td>Mary Shelley</td>
      <td>The Fortunes of Perkin Warbeck, A Romance</td>
      <td>1830</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>Herman Melville</td>
      <td>Moby-Dick; or, The Whale</td>
      <td>1851</td>
      <td>9781530697908</td>
      <td>1530697905</td>
    </tr>
    <tr>
      <td>
        <button type="button" id="btnEDENSb" aria-expanded="false" onclick="toggle(this.id,'#EDENS01b,#EDENS02b,#EDENS03b,#EDENS04b,#EDENS05b');" aria-controls="EDENS01b EDENS02b EDENS03b EDENS04b EDENS05b" aria-label="5 more from" aria-labelledby="btnEDENSb lblEDENSb">
          <svg xmlns="\http://www.w3.org/2000/svg&quot;" viewBox="0 0 80 80" focusable="false"><path d="M70.3 13.8L40 66.3 9.7 13.8z"></path></svg>
        </button>
      </td>
      <td id="lblEDENSb">Emma Dorothy Eliza Nevitte Southworth</td>
      <td>The Hidden Hand</td>
      <td>1888</td>
      <td>9780813512969</td>
      <td>0813512964</td>
    </tr>
    <tr id="EDENS01b" class="hidden">
      <td></td>
      <td>Emma Dorothy Eliza Nevitte Southworth</td>
      <td>A Leap in the Dark: A Novel</td>
      <td>1889</td>
      <td></td>
      <td></td>
    </tr>
    <tr id="EDENS02b" class="hidden">
      <td></td>
      <td>Emma Dorothy Eliza Nevitte Southworth</td>
      <td>Unknown; or the Mystery of Raven Rocks</td>
      <td>1889</td>
      <td></td>
      <td></td>
    </tr>
    <tr id="EDENS03b" class="hidden">
      <td></td>
      <td>Emma Dorothy Eliza Nevitte Southworth</td>
      <td>The Lost Lady of Lone</td>
      <td>1890</td>
      <td></td>
      <td></td>
    </tr>
    <tr id="EDENS04b" class="hidden">
      <td></td>
      <td>Emma Dorothy Eliza Nevitte Southworth</td>
      <td>The Rejected Bride</td>
      <td>1894</td>
      <td></td>
      <td></td>
    </tr>
    <tr id="EDENS05b" class="hidden">
      <td></td>
      <td>Emma Dorothy Eliza Nevitte Southworth</td>
      <td>Gertrude Haddon</td>
      <td>1894</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>F. Scott Fitzgerald</td>
      <td>The Great Gatsby</td>
      <td>1925</td>
      <td>9780743273565</td>
      <td>0743273567</td>
    </tr>
    <tr>
      <td></td>
      <td>George Orwell</td>
      <td>Nineteen Eighty-Four</td>
      <td>1948</td>
      <td>9780451524935</td>
      <td>0451524934</td>
    </tr>
  </tbody>
</table>


<h2>Disclosure Control as Entire Row</h2>

<p>
  The disclosure control lives in a cell spanning all columns, taking up an entire row.
</p>


<table class="row">
  <caption>Books I May or May Not Have Read</caption>
  <thead>
    <tr>
      <th>Author</th>
      <th>Title</th>
      <th>Year</th>
      <th>ISBN-13</th>
      <th>ISBN-10</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Miguel De Cervantes</td>
      <td>The Ingenious Gentleman Don Quixote of La Mancha</td>
      <td>1605</td>
      <td>9783125798502</td>
      <td>3125798507</td>
    </tr>
    <tr>
      <td>Mary Shelley</td>
      <td>Frankenstein; or, The Modern Prometheus</td>
      <td>1818</td>
      <td>9781530278442</td>
      <td>1530278449</td>
    </tr>
    <tr>
      <td colspan="5">
        <button type="button" id="btnMSa" aria-expanded="false" onclick="toggle(this.id,'#MS01a,#MS02a,#MS03a');" aria-controls="MS01a MS02a MS03a">
          <svg xmlns="\http://www.w3.org/2000/svg&quot;" viewBox="0 0 80 80" focusable="false"><path d="M70.3 13.8L40 66.3 9.7 13.8z"></path></svg>
          3 more from Mary Shelley…
        </button>
      </td>
    </tr>
    <tr id="MS01a" class="hidden">
      <td>Mary Shelley</td>
      <td>Valperga: Or, the Life and Adventures of Castruccio, Prince of Lucca</td>
      <td>1823</td>
      <td></td>
      <td></td>
    </tr>
    <tr id="MS02a" class="hidden">
      <td>Mary Shelley</td>
      <td>The Last Man</td>
      <td>1826</td>
      <td></td>
      <td></td>
    </tr>
    <tr id="MS03a" class="hidden">
      <td>Mary Shelley</td>
      <td>The Fortunes of Perkin Warbeck, A Romance</td>
      <td>1830</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Herman Melville</td>
      <td>Moby-Dick; or, The Whale</td>
      <td>1851</td>
      <td>9781530697908</td>
      <td>1530697905</td>
    </tr>
    <tr>
      <td>Emma Dorothy Eliza Nevitte Southworth</td>
      <td>The Hidden Hand</td>
      <td>1888</td>
      <td>9780813512969</td>
      <td>0813512964</td>
    </tr>
    <tr>
      <td colspan="5">
        <button type="button" id="btnEDENSa" aria-expanded="false" onclick="toggle(this.id,'#EDENS01a,#EDENS02a,#EDENS03a,#EDENS04a,#EDENS05a');" aria-controls="EDENS01a EDENS02a EDENS03a EDENS04a EDENS05a">
          <svg xmlns="\http://www.w3.org/2000/svg&quot;" viewBox="0 0 80 80" focusable="false"><path d="M70.3 13.8L40 66.3 9.7 13.8z"></path></svg>
          5 more from Emma Dorothy Eliza Nevitte Southworth…
        </button>
      </td>
    </tr>
    <tr id="EDENS01a" class="hidden">
      <td>Emma Dorothy Eliza Nevitte Southworth</td>
      <td>A Leap in the Dark: A Novel</td>
      <td>1889</td>
      <td></td>
      <td></td>
    </tr>
    <tr id="EDENS02a" class="hidden">
      <td>Emma Dorothy Eliza Nevitte Southworth</td>
      <td>Unknown; or the Mystery of Raven Rocks</td>
      <td>1889</td>
      <td></td>
      <td></td>
    </tr>
    <tr id="EDENS03a" class="hidden">
      <td>Emma Dorothy Eliza Nevitte Southworth</td>
      <td>The Lost Lady of Lone</td>
      <td>1890</td>
      <td></td>
      <td></td>
    </tr>
    <tr id="EDENS04a" class="hidden">
      <td>Emma Dorothy Eliza Nevitte Southworth</td>
      <td>The Rejected Bride</td>
      <td>1894</td>
      <td></td>
      <td></td>
    </tr>
    <tr id="EDENS05a" class="hidden">
      <td>Emma Dorothy Eliza Nevitte Southworth</td>
      <td>Gertrude Haddon</td>
      <td>1894</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>F. Scott Fitzgerald</td>
      <td>The Great Gatsby</td>
      <td>1925</td>
      <td>9780743273565</td>
      <td>0743273567</td>
    </tr>
    <tr>
      <td>George Orwell</td>
      <td>Nineteen Eighty-Four</td>
      <td>1948</td>
      <td>9780451524935</td>
      <td>0451524934</td>
    </tr>
  </tbody>
</table>

<style>
  body {
  /*font-family: "Segoe UI", -apple-system, BlinkMacSystemFont, Roboto,
    Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;*/
  /*line-height: 1.4;*/
  /*background: #fefefe;*/
  /*color: #333;*/
  /*margin: 0 1em;*/
}

table {
  margin: 1em 0;
  border-collapse: collapse;
}

caption {
  text-align: left;
  font-style: italic;
  padding: 0.25em 0.5em 0.5em 0.5em;
}

th,
td {
  padding: 0.25em 0.5em 0.25em 1em;
  vertical-align: text-top;
  text-align: left;
  text-indent: -0.5em;
}

th {
  vertical-align: bottom;
  background-color: rgba(0, 0, 0, 0.75);
  color: #fff;
  font-weight: bold;
}

.row td:nth-of-type(2), .cell td:nth-of-type(3) {
  font-style: italic;
}

.row th:nth-of-type(3),
.row td:nth-of-type(3),
.cell th:nth-of-type(4),
.cell td:nth-of-type(4) {
  text-align: right;
}

td[colspan] {
  background-color: #eee;
  color: #000;
  font-weight: normal;
  font-style: italic;
  padding: 0;
  text-indent: 0;
}

tr.shown, tr.hidden {
  background-color: #eee;
  display: table-row;
}

tr.hidden {
  display: none;
}

.row button {
  background-color: transparent;
  border: .1em solid transparent;
  font: inherit;
  padding: 0.25em 0.5em 0.25em .25em;
  width: 100%;
  text-align: left;
}

.row button:focus, .row button:hover {
  background-color: #ddd;
  outline: .2em solid #00f;
}

.row button svg {
  width: .8em;
  height: .8em;
  margin: 0 0 -.05em 0;
  fill: #66f;
  transition: transform 0.25s ease-in;
  transform-origin: center 45%;
}

.row button:hover svg,
.row button:focus svg {
  fill: #00c;
}

/* Lean on programmatic state for styling */
.row button[aria-expanded="true"] svg {
  transform: rotate(180deg);
}

.cell button {
  font-size: 60%;
  color: #000;
  background-color: #00f;
  padding: 0.3em 0.2em 0 0.2em;
  border: 0.2em solid #00f;
  border-radius: 50%;
  line-height: 1;
  text-align: center;
  text-indent: 0;
  transform: rotate(270deg);
}

.cell button svg {
  width: 1.25em;
  height: 1.25em;
  fill: #fff;
  transition: transform 0.25s ease-in;
  transform-origin: center 45%;
}

.cell button:hover,
.cell button:focus {
  background-color: #fff;
  outline: none;
}

.cell button:hover svg,
.cell button:focus svg {
  fill: #00f;
}

/* Lean on programmatic state for styling */
.cell button[aria-expanded="true"] svg {
  transform: rotate(90deg);
}

/* Proven method to visually hide something but */
/* still make it available to assistive technology */
.visually-hidden {
  position: absolute;
  top: auto;
  overflow: hidden;
  clip: rect(1px 1px 1px 1px); /* IE 6/7 */
  clip: rect(1px, 1px, 1px, 1px);
  width: 1px;
  height: 1px;
  white-space: nowrap;
}
</style>

<script>
  function toggle(btnID, eIDs) {
  // Feed the list of ids as a selector
  var theRows = document.querySelectorAll(eIDs);
  // Get the button that triggered this
  var theButton = document.getElementById(btnID);
  // If the button is not expanded...
  if (theButton.getAttribute("aria-expanded") == "false") {
    // Loop through the rows and show them
    for (var i = 0; i < theRows.length; i++) {
      theRows[i].classList.add("shown");
      theRows[i].classList.remove("hidden");
    }
    // Now set the button to expanded
    theButton.setAttribute("aria-expanded", "true");
  // Otherwise button is not expanded...
  } else {
    // Loop through the rows and hide them
    for (var i = 0; i < theRows.length; i++) {
      theRows[i].classList.add("hidden");
      theRows[i].classList.remove("shown");
    }
    // Now set the button to collapsed
    theButton.setAttribute("aria-expanded", "false");
  }
}
</script>
