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
<button type="button" class="collapsible">Collapsible Demo [not working right now]</button>
<div class="content">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>



<h1><span class = "overline">Option #2</span></h1>
<div class="accordion">
  <input type="checkbox" name="collapse" id="handle1" checked="checked">
  <h2 class="handle">
    <label for="handle1">26A. Trappist Single</label>
  </h2>
  <div class="content">
    <p><strong>Overall Impression:</strong> A pale, bitter, highly attenuated and well carbonated Trappist ale, showing a fruity-spicy Trappist yeast character, a spicy-floral hop profile, and a soft, supportive grainy-sweet malt palate.</p>
  </div>
</div>



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