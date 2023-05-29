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

<div class="container">
          <h1>Simple Flat UI CSS Accordion</h1>
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



<h1><span class = "overline">Option #8</span></h1>


