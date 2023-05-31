---
weight: 14
title: Bible Study
authors: Lenny
categories: null
tags: [Demo Accordion Table]
description: 
draft: false
date: "2023-03-17"
lastmod: "2023-03-17"
series:
toc: true
---


<!--more-->

<!-- Tab links -->
<div class="tab">
  <button class="tablinks active" onclick="tablabel(event, 'english')">English</button>
  <button class="tablinks" onclick="tablabel(event, 'chinese')">中文</button>
  
</div>

<!-- Tab content -->
<div id="english" class="tabcontent" style="display:block">

<h1><span class = "overline">Chapter 1</span></h1>
The way to start this book is different from modern business writing, with which the author usually put the statement first, then develop the body with providing three evidences.  

The author did not state clearly what God had said to the prophets and his Son in verse 1, 2, and 3, instead the author proclaimed who Jesus was. He is God's Son, is heir of all things, is the creator of the world, is the savior.  



<h1><span class = "overline">Chapter 2</span></h1>
The key word in this chapter is salvation.  
Jesus, angles, and human being 



<h1><span class = "overline">Chapter 3</span></h1>

<div id="toc_container">
<p class="toc_title">Contents</p>
<ul class="toc_list">
  <li><a href="#header_1">Who is Moses from authors perspective?</a></li>
  <li><a href="#header_2">Moses did different things</a></li>
  <li><a href="#header_3">In what ways was Moses like Jesus?</a></li>
  <li><a href="#header_4">Comparison</a></li>
</ul>
</div>


<h2 id = "header_1">Who is Moses from authors perspective?</h2>  

<style>

table {
  margin: 1em 0;
  border-collapse: collapse;
}


th,
td {
  padding: 0.25em 0.5em 0.25em 1em;
  vertical-align: text-top;
  text-align: left;
  text-indent: -0.5em;
}

.row td:nth-of-type(2), .cell td:nth-of-type(3) {
  font-style: italic;
}

.row th:nth-of-type(3),
.row td:nth-of-type(3),
.cell th:nth-of-type(4),
.cell td:nth-of-type(4) {
  text-align: left;
}

td[colspan] {
  /*background-color: #eee;*/
  color: #000;
  font-weight: normal;
  font-style: italic;
  padding: 0;
  text-indent: 0;
}

tr.shown, tr.hidden {
  /*background-color: #eee;*/
  *display: table-row;
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


<table class="row">
  <caption style="text-align:left", align = "top"><b>Bible verses on Moses</b></caption>
  <colgroup>
    <col style="width: 34%" /><col style="width: 33%" /><col style="width: 33%" />
  </colgroup>
  <thead>
    <tr>
      <th><p>ESV</p></th>
      <th><p>KJV</p></th>
      <th><p>和合本</p></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="3" class = "pink subtitle">
        <button type="button" id="btnlife" aria-expanded="false" onclick="toggle(this.id,'#life01,#life02,#life03,#life04,#life05,#life06,#life07,#life08');" aria-controls="life01 life02 life03 life04 life05 life06 life07 life08">
          <svg xmlns="\http://www.w3.org/2000/svg&quot;" viewBox="0 0 80 80" focusable="false"><path d="M70.3 13.8L40 66.3 9.7 13.8z"></path></svg>
          Moses Personal Life 摩西的个人生活
        </button>
      </td>
    </tr> 
    <tr id="life01" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
出埃及记 2:1    
有一个利未家的人娶了一个利未女子为妻。  
<br>出埃及记 6:20  
暗兰娶了他父亲的妹妹约基别为妻，她给他生了亚伦和摩西。暗兰一生的岁数是一百三十七岁。[*摩西和亚伦的族谱]
<br>民数记 26:59
暗兰的妻名叫约基别，是利未女子，生在埃及。她给暗兰生了亚伦、摩西，并他们的姐姐米利暗。
</p></td>
    </tr>
    <tr id="life02" class="hidden">
      <td VALIGN=Middle><p>
      </p></td>
      <td VALIGN=TOP><p>
      </p></td>
      <td VALIGN=TOP><p>
出埃及记 2:10  
孩子渐长，妇人把他带到法老的女儿那里，就作了她的儿子。她给孩子起名叫摩西，<b>意思说：“因我把他从水里拉出来。”</b>[*摩西出生]
</p></td>
    </tr>
    <tr id="life03" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
使徒行传 7:22
摩西学了埃及人一切的学问，说话行事都有才能。
</p></td>
    </tr>
    <tr id="life04" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
‪出埃及记‬2:16
一日，他在井旁坐下。<b>米甸</b>的祭司有七个女儿；她们来打水，打满了槽，要饮父亲的群羊。
<br>出埃及记 18:12
<b>摩西的岳父叶忒罗</b>把燔祭和平安祭献给神。亚伦和以色列的众长老都来了，与摩西的岳父在神面前吃饭。
<br>民数记 10:29
<b>摩西对他岳父米甸人流珥的儿子何巴</b>说：“我们要行路，往耶和华所应许之地去；他曾说：‘我要将这地赐给你们。’现在求你和我们同去，我们必厚待你，因为耶和华指着以色列人已经应许给好处。”
<br>士师记 4:11
<b>摩西岳父何巴</b>的后裔，基尼人希百曾离开基尼族，到靠近基低斯、撒拿音的橡树旁支搭帐棚。
<br>民数记 12:1   
摩西娶了<b>古实</b>女子为妻。米利暗和亚伦因他所娶的古实女子就毁谤他...
<br>参考：<a href = "https://www.ccbiblestudy.org/Old%20Testament/04Num/04GS12.htm" target="_blank" rel="noopener noreferrer">华人基督徒查经资料网站 | 民数记第十二章拾穗</a>
</p></td>
    </tr>
    <tr id="life05" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
申命记 34:6
<b>耶和华将他</b>埋葬在摩押地、伯毗珥对面的谷中，只是到今日没有人知道他[*摩西]的坟墓。
<br>申命记 34:7
摩西死的时候年一百二十岁；眼目没有昏花，精神没有衰败。[*摩西去世]
</p></td>
    </tr>    
    <tr id="life06" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
历代志上 23:14
至于神人摩西，他的子孙名字记在利未支派的册上。
注：尽管摩西娶了外邦女子为妻，他的后代依然属于利未支派。
</p></td>
    </tr>
    <tr id="life07" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
摩西孙子的情况：
<br>1. 摩西后代作了祭司
<br>士师记 18:30
但人就为自己设立那雕刻的像。摩西的孙子、革舜的儿子约拿单，和他的子孙作但支派的祭司，直到那地遭掳掠的日子。
<br>2. 摩西后代掌管府库
<br>历代志上 26:24
摩西的孙子、革舜的儿子细布业掌管府库。
</p></td>
    </tr>
    <tr id="life08" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
    </tr>
    <tr>
    <td colspan="3" class = "pink subtitle">
        <button type="button" id="btntitle" aria-expanded="false" onclick="toggle(this.id,'#title01,#title02,#title03,#title04,#title05,#title06');" aria-controls="title01 title02 title03 title04 title05 title06">
          <svg xmlns="\http://www.w3.org/2000/svg&quot;" viewBox="0 0 80 80" focusable="false"><path d="M70.3 13.8L40 66.3 9.7 13.8z"></path></svg>
          Moses Title 摩西的称谓
        </button>
    </td>
    </tr> 
    <tr id="title01" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
他是祭司
<br>诗篇 99:6
在他的祭司中有摩西和亚伦；在求告他名的人中有撒母耳。他们求告耶和华，他就应允他们。
</p></td>
    </tr>
    <tr id="title02" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
他是仆人
<br>民数记 12:7  
我的仆人摩西不是这样；他是<b>在我全家尽忠</b>的。  
<br>民数记 12:8  
我要与他[*摩西]面对面说话，乃是明说，不用谜语，并且他必见我的形像。你们毁谤我的仆人摩西，为何不惧怕呢？”
</p></td>
    </tr>    
    <tr id="title03" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
他是先知
<br>申命记 34:10-12
<br>以后以色列中再没有兴起<b>先知</b>像摩西的。他是耶和华面对面所认识的。
<br>耶和华打发他[*摩西]在埃及地向法老和他的一切臣仆，并他的全地，行各样神迹奇事，
<br>又在以色列众人眼前显大能的手，行一切大而可畏的事。
</p></td>
    </tr>
    <tr id="title04" class="hidden">
      <td><p>
14 But the sons of Moses <b>the man of God</b> were named among the tribe of Levi.  
1 Chronicles 23:14 (ESV)
</p></td>
      <td><p>
14 Now concerning Moses <b>the man of God</b>, his sons were named of the tribe of Levi.  
1 Chronicles 23:14 (KJV)
</p></td>
      <td><p>
他是神人
<br>历代志上 23:14
至于神人摩西，他的子孙名字记在利未支派的册上。
<br>注：尽管摩西娶了外邦女子为妻，他的后代依然属于利未支派。
</p></td>
    </tr>
    <tr id="title05" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
    </tr>
    <tr id="title06" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
    </tr>
    <tr>
    <td colspan = "3" class = "pink subtitle">
      <button type="button" id="btncharacter" aria-expanded="false" onclick="toggle(this.id,'#character01,#character02,#character03,#character04,#character05,#character06');" aria-controls="character01 character02 character03 character04 character05 character06">
      <svg xmlns="\http://www.w3.org/2000/svg&quot;" viewBox="0 0 80 80" focusable="false"><path d="M70.3 13.8L40 66.3 9.7 13.8z"></path></svg>
          Moses Characters 摩西的品格
    </td>
    </tr>
    <tr id="character01" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
民数记 12:3    
摩西<b>为人极其谦和</b>，胜过世上的众人。  
</p></td>
    </tr>
    <tr  id="character02" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
民数记 12:7  
我的仆人摩西不是这样；他是<b>在我全家尽忠</b>的。
<br>‪希伯来书‬3:2
他为那设立他的尽忠，如同摩西在　神的全家尽忠一样。
</p></td>
    </tr>
    <tr  id="character03" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
民数记 27:18
耶和华对摩西说：“嫩的儿子约书亚是<b>心中有圣灵</b>的；你将他领来，按手在他头上，[*约书亚承继摩西的职位]
</p></td>
    </tr>
    <tr id="character04" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
希伯来书 11:24-28
<br>摩西因着信，长大了就不肯称为法老女儿之子。[*摩西]
<br>他宁可和神的百姓同受苦害，也不愿暂时享受罪中之乐。
<br>他看为基督受的凌辱比埃及的财物更宝贵，因他想望所要得的赏赐。[*摩西看为基督受凌辱胜于埃及的宝贝]
<br>他因着信，就离开埃及，不怕王怒；因为他恒心忍耐，如同看见那不能看见的主。 
<br>他因着信，就守（或作“立”）逾越节，行洒血的礼，免得那灭长子的临近以色列人。
</p></td>
    </tr>    
    <tr id="character05" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
摩西甘愿付上生命的代价
<br>出埃及记 32:31-32  
<br>摩西回到耶和华那里，说：“唉！这百姓犯了大罪，为自己做了金像。  
<br>倘或你肯赦免他们的罪......不然，求你从你所写的册上<b>涂抹</b>我[*摩西]的名。” 
</p></td>
    </tr> 
    <tr id="character06" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
    </tr>    
    <tr>
      <td colspan = "3" class = "pink subtitle">
      <button type="button" id="btnevent" aria-expanded="false" onclick="toggle(this.id,'#event01,#event02,#event03,#event04,#event05,#event06,#event07,#event08,#event09,#event10,#event11,#event12,#event13,#event14,#event15,#event16,#event17,#event18,#event19,#event20,#event21,#event22,#event23,#event24,#event25,#event26,#event27');" aria-controls="event01 event02 event03 event04 event05 event06 event07 event08 event09 event10 event11 event12 event13 event14 event15 event16 event17 event18 event19 event20 event21 event22 event23 event24 event25 event26 event27">
          <svg xmlns="\http://www.w3.org/2000/svg&quot;" viewBox="0 0 80 80" focusable="false"><path d="M70.3 13.8L40 66.3 9.7 13.8z"></path></svg>
          Moses Events 摩西大事件
        </button>
      </td>
    </tr>
    <tr id="event01" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
‪路加福音‬20:38
神原不是死人的　神，乃是活人的　神；因为在他那里（“那里”或作“看来”），人都是活的。”
</p></td>
    </tr>
    <tr id="event02" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
上帝早有预备
<br>弥迦书 6:4
我曾将你从埃及地领出来，从作奴仆之家救赎你；我也差遣摩西、亚伦，和米利暗在你前面行。
<br>使徒行传 7:23
“他将到四十岁，心中起意去看望他[*摩西]的弟兄以色列人；
</p></td>
    </tr>
    <tr id="event03" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
摩西自以为是
<br>在使徒行传第七章，司提反回顾以色列人的历史
<br>使徒行传 7:25
他以为弟兄必明白神是藉他[*摩西]的手搭救他们；他们却不明白。[*拒绝摩西的拯救]
</p></td>
    </tr>    
    <tr id="event04" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
出埃及记 4:20    
摩西就带着妻子和两个儿子，叫他们骑上驴，回埃及地去。摩西手里拿着<b>神的杖</b>。[*上帝赐摩西能力]      
</p></td>
    </tr>
    <tr id="event05" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
出埃及记 4:24-26   
<br>摩西在路上住宿的地方，耶和华遇见他，想要杀他[*摩西]。[*摩西給兒子行割禮]  
<br>西坡拉就拿一块火石，割下他儿子的阳皮，丢在摩西脚前，说：“你[*摩西]真是我的血郎了。”  
<br>这样，耶和华才放了他[*摩西]。西坡拉说：“你因割礼就是血郎了。”
<br>约翰福音 7:22
摩西传割礼给你们（其实不是从摩西起的，乃是从祖先起的），因此你们也在安息日给人行割礼。
</p></td>
    </tr>
    <tr id="event06" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
出埃及记 5:1  
后来摩西、亚伦去对法老说：“耶和华以色列的神这样说：‘容我的百姓去，在旷野向我守节。’”[*摩西和亚伦见法老]
</p></td>
    </tr>
    <tr id="event07" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
出埃及记 15:2
<b>耶和华是</b>我的力量，我的诗歌，也成了我的拯救。这是我的神，我要赞美他，是我[*摩西]父亲的神，我要尊崇他。
</p></td>
    </tr>
    <tr id="event08" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
出埃及记 18:3-4  
<br>又带着西坡拉的两个儿子，一个名叫革舜，因为摩西说：“我在外邦作了寄居的”；[*葉忒羅帶西坡拉和兩個外孫來見摩西]
<br>一个名叫以利以谢，因为他说：“我父亲的神帮助了我，救我[*摩西]脱离法老的刀。”
</p></td>
    </tr>
    <tr id="event09" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
出埃及记 18:16  
他们有事的时候就到我[*摩西]这里来，我便在两造之间施行审判；我又叫他们知道神的律例和法度。”  
<br>出埃及记 18:20  
又要将律例和法度教训他们，指示他们当行的道，当做的事；
</p></td>
    </tr>
    <tr id="event10" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
出埃及记 19:3
摩西到神那里，耶和华从山上呼唤他说：“你要这样告诉雅各家，晓谕以色列人说：
<br>出埃及记 19:6
你们要归我作祭司的国度，为圣洁的国民。’这些话你要告诉以色列人。”
<br>出埃及记 19:7
摩西去召了民间的长老来，将耶和华所吩咐他的话都在他们面前陈明。
</p></td>
    </tr>
    <tr id="event11" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
出埃及记 24:2
<br><b>惟独</b>你可以<b>亲近</b>耶和华；他们却不可亲近；百姓也不可和你一同上来。”
</p></td>
    </tr>
    <tr id="event12" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
出埃及记 32:30
到了第二天，摩西对百姓说：“你们犯了大罪。<b>我</b>如今要<b>上</b>耶和华那里去，或者可以为你们赎罪。”[*摩西代祷]  
<br>注：不是献祭的仪式  
</p></td>
    </tr>
    <tr id="event13" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
出埃及记 33:8-9
<br>当摩西出营到会幕去的时候，百姓就都起来，各人站在自己帐棚的门口，望着摩西，直等到他进了会幕。[*摩西进会幕]    
<br>摩西进会幕的时候，云柱降下来，立在会幕的门前，耶和华便与摩西说话。  
<br>注：摩西是祭司
</p></td>
    </tr>
    <tr id="event14" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
‪出埃及记‬33:12-23 和合本  
<br>12 摩西对耶和华说：“你吩咐我说：‘将这百姓领上去’，却没有叫我知道你要打发谁与我同去，只说：‘我按你的名认识你，你在我眼前也蒙了恩。’   
<br>13 我如今若在你眼前蒙恩，求你将你的道指示我，使我可以认识你，好在你眼前蒙恩。求你想到这民是你的民。”   
<br>14 耶和华说：“我必亲自和你同去，使你得安息。”   
<br>15 摩西说：“你若不亲自和我同去，就不要把我们从这里领上去。   
<br>16 人在何事上得以知道我和你的百姓在你眼前蒙恩呢？岂不是因你与我们同去、使我和你的百姓与地上的万民有分别吗？”  
<br>17 耶和华对摩西说：“你这所求的我也要行；因为你在我眼前蒙了恩，并且我按你的名认识你。”   
<br>18 摩西说：“求你显出你的荣耀给我看。”   
<br>19 耶和华说：“我要显我一切的恩慈，在你面前经过，宣告我的名。我要恩待谁就恩待谁；要怜悯谁就怜悯谁”；   
<br>20 又说：“你不能看见我的面，因为人见我的面不能存活。”   
<br>21 耶和华说：“看哪，在我这里有地方，你要站在磐石上。   
<br>22 我的荣耀经过的时候，我必将你放在磐石穴中，用我的手遮掩你，等我过去，   
<br>23 然后我要将我的手收回，你就得见我的背，却不得见我的面。”
</p></td>
    </tr>
    <tr id="event15" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
出埃及记 34:28  
摩西在耶和华那里四十昼夜，也不吃饭也不喝水。耶和华将<b>这约</b>的话，就是十条诫，写在两块版上。
</p></td>
    </tr>
    <tr id="event16" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
民数记 7:89
摩西进会幕要与耶和华说话的时候，听见法柜的施恩座以上、二基路伯中间有与他说话的声音，就是耶和华与他说话。
<br>注：摩西也是祭司</p></td>
    </tr>
    <tr id="event17" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
民数记 11:25  
<br>耶和华在云中降临，对摩西说话，把降与他[*摩西]身上的灵分赐那七十个长老。灵停在他们身上的时候，他们就受感说话，以后却没有再说。  
<br>民数记 11:29  
<br>摩西对他说：“你为我的缘故嫉妒人吗？惟愿耶和华的百姓都受感说话！<b>愿耶和华把他的灵</b>降在他们身上！”  
</p></td>
    </tr>
    <tr id="event18" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
民数记 16:22
摩西、亚伦就俯伏在地，说：“神，万人之灵的神啊，一人犯罪，你就要向全会众发怒吗？”[*永恆主吩咐摩西亞倫叫他們要跟會眾分別出來]
</p></td>
    </tr>
    <tr id="event19" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
民数记 17:8   
第二天，摩西进法柜的帐幕去。谁知利未族亚伦的杖已经发了芽，生了花苞，开了花，结了熟杏。
</p></td>
    </tr>
    <tr id="event20" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
民数记 21:8  
耶和华对摩西说：“你制造一条火蛇，挂在杆子上；凡被咬的，一望这蛇，就必得活。”
</p></td>
    </tr>
    <tr id="event21" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
申命记 11:13
“你们若留意听从我[*摩西]今日所吩咐的诫命，爱耶和华你们的神，尽心尽性侍奉他，
<br>申命记 11:26
“看哪，我[*摩西]今日将祝福与咒诅的话都陈明在你们面前。
<br>注：摩西是先知，讲祝福的话，也讲咒诅的话。
</p></td>
    </tr>
    <tr id="event22" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
申命记 31:2
说：“我现在一百二十岁了，不能照常出入；耶和华也曾对我[*摩西]说：‘你必不得过这约旦河。’
<br>注：过河
</p></td>
    </tr>
    <tr id="event23" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
申命记 33:2
他说：“耶和华从西奈而来，从西珥向他们显现，从巴兰山发出光辉，从万万圣者中来临，从他右手为百姓传出烈火的律法。
<br>注：上帝来就近人。</p></td>
    </tr>
    <tr id="event24" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
诗篇 90
神人摩西的祈祷。
</p></td>
    </tr>
    <tr id="event25" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
    </tr>
    <tr id="event26" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
    </tr>
    <tr id="event27" class="hidden">
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
    </tr>
  </tbody>
</table>

<div class="scroll-container">
    <a href="#header_1">To Table Header</a>
</div>

<h2 id = "header_2">Moses did different things</h2>

约翰福音 1:17
律法本是藉着摩西传的；恩典和真理都是由耶稣基督来的。

使徒行传 7:37
那曾对以色列人说‘神要从你们弟兄中间给你们兴起一位先知像我’的，就是这[*摩西]位摩西。

‪使徒行传‬13:16-43
<br>‪23 从这人的后裔中，　神已经照着所应许的，为以色列人<b>立了一位救主</b>，就是耶稣。……
<br>26 “弟兄们，亚伯拉罕的子孙和你们中间敬畏　神的人哪，这<b>救世的道</b>是传给我们的。
<br>27 耶路撒冷居住的人和他们的官长，因为不认识基督，也不明白每安息日所读<b>众先知的书</b>，就把基督定了死罪，正应了先知的预言；
‪38 所以，弟兄们，你们当晓得：赦罪的道是由这人传给你们的。
‪39 你们靠摩西的律法，在一切不得称义的事上信靠这人，就都得称义了。
<br>注：旧约书卷里早已提到耶稣

使徒行传 21:21
他们听见人说，你教训一切在外邦的犹太人离弃摩西，对他们说，不要给孩子行割礼，也不要遵行条规。
<br>注：这是保罗对割礼、条规的态度。NLT的译本却说要守摩西的律法。

使徒行传 26:22
然而我蒙神的帮助，直到今日还站得住，对着尊贵、卑贱、老幼作见证；所讲的并不外乎众先知和摩西所说将来必成的事，

使徒行传 28:23
他们和保罗约定了日子，就有许多人到他的寓处来。保罗从早到晚，对他们讲论这事，证明神国的道，引摩西的律法和先知的书，以耶稣的事劝勉他们。

罗马书 5:14
然而从亚当到摩西，死就作了王，连那些不与亚当犯一样罪过的，也在他的权下。亚当乃是那以后要来之人的预像。

罗马书 10:5
摩西写着说：“人若行那出于律法的义，就必因此活着。”

哥林多前书 10:2
都在云里、海里受洗归了摩西；

哥林多后书 3:15
然而直到今日，每逢诵读摩西书的时候，帕子还在他们心上。

希伯来书 9:19-21
<br>因为摩西当日照着律法将各样诫命传给众百姓，就拿朱红色绒和牛膝草，把牛犊山羊的血和水洒在书上，又洒在众百姓身上，说：
<br>“这血就是神与你们立约的凭据。”
<br>他又照样把血洒在帐幕和各样器皿上。

启示录 15:3
唱神仆人摩西的歌和羔羊的歌，说：“主神，全能者啊，你的作为大哉！奇哉！万世之王啊，你的道途义哉！诚哉！[*摩西的歌和羔羊的歌]

God used Moses to reveal His will in future





<h2 id = "header_3">In what ways was Moses like Jesus?</h2>
In one of Moses’ final speeches, he gave this messianic prophecy: “The Lord your God will raise up for you a prophet like me from among you, from your fellow Israelites. You must listen to him” (Deuteronomy 18:15). The prophet whom Moses foretells bears these qualities: He will be raised up by God, He will come from among the Israelites, He will be like Moses, and He will be worthy of being heard and obeyed. The prophet who fulfills these words is Jesus Christ, the prophet like Moses.

On the banks of the Jordan River, the Jews questioned John the Baptist about who he was and why he was baptizing. Their question “Are you the Prophet?” (John 1:21) shows that they were looking for the fulfillment of Moses’ prophecy. John plainly informed them that he was not the Prophet but pointed them to the One who was: “Among you stands one you do not know. He is the one who comes after me, the straps of whose sandals I am not worthy to untie” (verses 26–27). John’s description of the Messiah as one “among you” recalls Moses’ prediction that God would raise up the Prophet “from among you” in Deuteronomy 18:15. The very next day, John specifically identifies Jesus as the One they were waiting for (John 1:29–31).

In his sermon at the temple, Peter affirms that Jesus is the prophet like Moses (Acts 3:22, quoting Deuteronomy 18:15). Stephen, addressing the Sanhedrin in Acts 7:37, also quotes Moses and applies the prophecy to Jesus Christ.

Jesus is like Moses in several ways. Moses was both a prophet and a lawgiver, and Jesus is, too. Jesus was widely recognized as a prophet who spoke the Word of God (Matthew 21:46), and He gave commandments for His followers to obey (John 13:34; 15:12, 17; Galatians 6:2). Both Moses and Jesus mediated a covenant between God and men—Moses the Old Covenant (Exodus 34:27; Acts 7:44), and Jesus the New (Luke 22:20; Hebrews 9:15). Both Moses and Jesus were born during perilous times, and both narrowly escaped a king bent on murdering babies (Exodus 1:22 and Matthew 2:16–18). Both Moses and Jesus had a connection to Egypt (Exodus 2:1–4 and Matthew 2:13–14). Moses was the (adopted) son of a king (Exodus 2:10), and Jesus is the Son of the Most High (Luke 1:32). Moses spent forty years as a shepherd (Exodus 3:1), and Jesus is the Good Shepherd (John 10:11, 14). Both Moses and Jesus were known for their meekness (Numbers 12:3 and Matthew 11:29).

Moses and Jesus were alike in that they both led God’s people out of captivity. With great power, Moses led the Israelites out of physical bondage and slavery in Egypt, and Jesus, with even greater power, led God’s elect out of spiritual bondage and slavery to sin. Moses stood before Pharaoh and said, “'Let my people go” (Exodus 5:1). Jesus came “to proclaim freedom for the prisoners and . . . to set the oppressed free” (Luke 4:18). “In Christ Jesus the law of the Spirit of life has set you free from the law of sin and death” (Romans 8:2).

Moses was also like Jesus in that he performed miracles—not all prophets did. Several of the miracles of Moses bear a resemblance to Jesus’ miracles, most notably the provision of bread in the wilderness (Exodus 16:35), which is comparable to Jesus’ feeding of the 5,000 (John 6:1–13). In fact, after Jesus multiplied the loaves and fishes, the people’s thoughts ran immediately to Moses’ prophecy: “After the people saw the sign Jesus performed, they began to say, ‘Surely this is the Prophet who is to come into the world’” (John 6:14).

Another way that Moses was like Jesus is that <b>he held intimate conversations with God</b>: “The LORD would speak to Moses face to face, as one speaks to a friend” (Exodus 33:11). Jesus also had a special relationship to God: “No one knows the Son except the Father, and no one knows the Father except the Son” (Matthew 11:27); “The Father knows me and I know the Father” (John 10:15). When Moses stood in God’s presence, his face shone with a heavenly glory and had to be covered with a veil (Exodus 34:29–35), and this reminds us of Jesus’ transfiguration, when “His face shone like the sun” (Matthew 17:2).

Another important way that Moses was like Jesus is that <b>he constantly interceded for his people</b>. When the Israelites sinned, Moses was always standing by, ready to petition God on their behalf and plead for their forgiveness. After the blatant idolatry at the foot of Mt. Sinai involving the golden calf, Moses interceded twice for the people (Exodus 32:11–13, 30–32), and his intercession was needed at other times, too (e.g., Numbers 11:2; 12:13; 21:7). Moses’ intercession was temporary, but our Lord’s is everlasting. “If anybody does sin, we have an advocate with the Father—Jesus Christ, the Righteous One” (1 John 2:1). Jesus is right now “at the right hand of God and is also interceding for us” (Romans 8:34). Jesus “always lives to intercede” for us (Hebrews 7:25).

Not only was Moses an intercessor for God’s people but, like Jesus, <b>he was willing to die for them</b>. In Exodus 32:32, Moses offers his life in exchange for sinners. “Greater love has no one than this: to lay down one’s life for one’s friends,” Jesus said (John 15:13), and Jesus proved His love when He “laid down his life for us” (1 John 3:16; cf. John 10:15).

<b>Reference</b>: <a href = "https://www.gotquestions.org/Moses-and-Jesus.html" target="_blank" rel="noopener noreferrer">Got Questions | In what ways was Moses like Jesus?</a>




<h2 id = "header_4">Comparison</h2>
Could we see Jesus in Moses?

performed miracles
Moses was a prophet, priest

<table>
  <caption style="text-align:left", align = "top"><b>Bible verses on Moses</b></caption>
  <colgroup>
    <col style="width: 20%" /><col style="width: 40%" /><col style="width: 40%" />
  </colgroup>
  <thead style="text-align:left">
    <tr>
      <th><p>Comparison</p></th>
      <th><p>Moses</p></th>
      <th><p>Jesus</p></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><p>
God's plan
</p></td>
      <td><p>
yes, Moses was the role in God's plan. <br> God heard Israelites' complains on hard-working, and answered their prayers by preparing Moses.  God did not take a proactive action.
</p></td>
      <td><p>
yes, Jesus was the role in God's plan. <br> Human being do not complain about sin. God voluntarily prepared Jesus.
</p></td>
    </tr>
    <tr>
      <td><p>
Prophet
</p></td>
      <td><p>
Moses was a prophet.
</p></td>
      <td><p>
Jesus was a prophet.[Acts 3:22, Deuteronomy 18:15, Matthew 21:46]
</p></td>
    </tr>    
    <tr>
      <td><p>
Priest      
</p></td>
      <td><p>
Moses was a priest
</p></td>
      <td><p>
Jesus was a High Priest.
</p></td>
    </tr> 
    <tr>
      <td><p>
Savior
</p></td>
      <td><p>
Moses took the Israelites out of Egypt from slavery
</p></td>
      <td><p>
Jesus saved human beings out of sin.
</p></td>
    </tr>
    <tr>
      <td><p>
Sinful Nature
</p></td>
      <td><p>
Moses struck the rock at the desert Zin.  
<br>Moses was a sinner. He can't be the sacrifice.
<br>Reference: Moses offered himself a sacrifice, but he was not qualified. [Exodus 32:31-32]
</p></td>
      <td><p>
Jesus was not a sinner.
He can be the perfect sacrifice.</p></td>
    </tr>
    <tr>
      <td><p>
Messages
</p></td>
      <td><p>
Moses delivered Law.
</p></td>
      <td><p>
Jesus delivered grace and love.
</p></td>
    </tr>
    <tr>
      <td><p>
Meekness
</p></td>
      <td><p>
Numbers 12:3 Moses was very meek, above all the men.
</p></td>
      <td><p>
Matthew 11:29 Jesus was meek and lowly in heart.
</p></td>
    </tr>
    <tr>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
    </tr>
    <tr>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
    </tr>    
    <tr>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
    </tr>    
    <tr>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
    </tr>    
    <tr>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
      <td><p>
      </p></td>
    </tr>    
  </tbody>
</table>
</div>

<div id="chinese" class="tabcontent">

<h1><span class = "overline">第一章</span></h1>

Date: 2023-03-17  

希伯来书重申了信仰的根基。  
‪希伯来书‬6:1-2 和合本
<br>1 所以，我们应当离开基督道理的开端，竭力进到完全的地步，不必再<u class = "red">立根基</u>，就如那懊悔死行、信靠　神、 
<br>2 各样洗礼、按手之礼、死人复活，以及永远审判各等教训。  

起誓。‪希伯来书‬6:16 和合本
<br>16 人都是指着比自己大的起誓，并且以起誓为实据，了结各样的争论。

<table style="width:100%; font-size: 80%">
  <caption style="text-align:left", align = "top"></caption>
  <colgroup>
    <col style="width: 20%"><col style="width: 40%"><col style="width: 40%">
  </colgroup>
  <thead style="text-align:left">
  <tr>
    <th><p>比较因素</p></th><th><p>影儿的事</p></th><th><p>将来的事</p></th>
  </tr>
  </thead>
  <tbody align = "top">
    <tr>
      <th style="text-align:left"><p>
      大祭司
      </p></th>
      <td><p>‪希伯来书‬5:1 和合本
<br>1 凡从人间挑选的大祭司，是奉派替人办理属　神的事，为要献上礼物和赎罪祭（或作“要为罪献上礼物和祭物”）。
      </p></td>
      <td><p>‪希伯来书‬5:4-5,10 和合本  
<br>4 这大祭司的尊荣，没有人自取。惟要蒙　神所召，像亚伦一样。  
<br>5 如此，基督也不是自取荣耀作大祭司，乃是在乎向他说“你是我的儿子，我今日生你”的那一位；  
<br>……  
<br>10 并蒙　神照着麦基洗德的等次称他为大祭司。 
      </p></td>
    </tr>
    <tr>
      <th style="text-align:left"><p>
      除罪
      </p></th>
      <td><p>‪希伯来书‬10:4,11 和合本
<br>4 因为公牛和山羊的血，断不能除罪。<br>……
<br>11 凡祭司天天站着侍奉　神，屡次献上一样的祭物，这祭物永不能除罪。
      </p></td>
      <td><p>‪希伯来书‬10:10,12,14 和合本
<br>10 我们凭这旨意，靠耶稣基督，只一次献上他的身体，就得以成圣。<br>……
<br>12 但基督献了一次永远的赎罪祭，就在　神的右边坐下了。<br>……<br>14 因为他一次献祭，便叫那得以成圣的人永远完全。
      </p></td>
    </tr>
  </tbody>
</table>

</div>

