---
title: "Ryuseitai's Profiles"
date: 2024-6-22 9:00:00
categories:
- [Enstars, 1. Era, ES Era, Year 2]
- [Enstars, Ryuseitai, Ryuseitai POWER UP]
- [Enstars, Tetora]
- [Enstars, Midori]
- [Enstars, Shinobu]
- [Enstars, Chiaki]
- [Enstars, Kanata]
tags:
description: "Ryuseitai's Profiles."
permalink: profiles/
hidden: true
---

<!-- more -->
<!--
<script>
function myFunction() {
var x = document.getElementById("myDIV");
var y = document.getElementById("mynonDIV");
if (x.style.display === "none") {
    x.style.display = "block";
    y.style.display = "none";
    } else {
    x.style.display = "none";
    y.style.display = "block";
}
}
</script>
-->

<script>
function myFunction() {
  var divs = document.querySelectorAll('.myDIV');
  var divss = document.querySelectorAll('.mynonDIV');
for (var i = 0; i < divs.length; i++) {
    divs[i].classList.toggle('hide');
    divss[i].classList.toggle('show');
}
}

function myFunctionen() {
  var divs = document.querySelectorAll('.myDIV');
  var divss = document.querySelectorAll('.mynonDIV');
for (var i = 0; i < divs.length; i++) {
    divs[i].classList.toggle('show');
    divss[i].classList.toggle('hide');
}
}
</script>

<style>
    .mynonDIV {
        display: none;
    }

    .hide {
        display: none !important;
    }

    .show {
        display: block !important;
    }
</style>

<button onclick="myFunction()">JP ←→ ENG</button>

<button onclick="myFunctionen()">English</button>

<div class="myDIV">
  This is my DIV element. in English!
</div>

<div class="myDIV">
  This is my DIV element 2. in English!
</div>

<div class="myDIV">
  This is my DIV element 3. in English!
</div>

<div class="myDIV">
  This is my DIV element 4. in English!
</div>

<div class="myDIV">
  This is my DIV element 5. in English!
</div>

<div class="mynonDIV">
  これは私のDIVエレメント。日本語版！
</div>

<div class="mynonDIV">
  これは私のDIVエレメント 2。日本語版！
</div>

<div class="mynonDIV">
  これは私のDIVエレメント 3。日本語版！
</div>

<div class="mynonDIV">
  これは私のDIVエレメント 4。日本語版！
</div>

<div class="mynonDIV">
  これは私のDIVエレメント 5。日本語版！
</div>
<!--
<script>
    for (let i=0;i<=175;i++) {
function myFunction() {
var x = document.getElementById("english");
var y = document.getElementById("japanese");
if (x.style.display === "none") {
    x.style.display = "block";
    y.style.display = "none";
    }
    else {
    x.style.display = "none";
    y.style.display = "block";
    }
}
    }
</script>
-->

<div id="first">first</div>
<div id="second" style="display:none;">second</div>
<a href="javascript:HideContent(['first']);javascript:ShowContent(['second'])"> ENGLISH</a>

<a href="javascript:HideContent(['japanese']);javascript:ShowContent(['english'])"> ENGLISH1</a>
<a href="javascript:HideContent(['english']);javascript:ShowContent(['japanese'])"> JAPANESE</a>
<script>
  function HideContent(obj) {
    for (var i = 0; i < obj.length; i++) {
      document.getElementById([obj[i]]).style.display = 'none';
    }
  }
  function ShowContent(obj) {
    for (var i = 0; i < obj.length; i++) {
      document.getElementById([obj[i]]).style.display = 'block';
    }
  }
</script>

<style>
    table {
        border-radius: 5px;
    }
    
    th, td {
        border: 1px solid grey;
    }

    th:first-of-type {
        border-top-left-radius: 5px;
    }

    th:last-of-type {
        border-top-right-radius: 5px;
    }

    tr:last-of-type td:first-of-type {
        border-bottom-left-radius: 5px;
    }

    tr:last-of-type td:last-of-type {
        border-bottom-right-radius: 5px;
    }
</style>

<table class="myDIV">
    <tr>
        <th colspan="4" style="text-align:center;">Profile</th>
    </tr>
    <tr>
        <th>Blood Type</th>
        <td colspan="3">O</td>
    </tr>
    <tr>
        <th>Birthday</th>
        <td colspan="3">September 18th</td>
    </tr>
    <tr>
        <th>Family</th>
        <td colspan="3">Parents</td>
    </tr>
    <tr>
        <th>Favorite Food</th>
        <td colspan="3">French Fries</td>
    </tr>
    <tr>
        <th>Likes</th>
        <td colspan="3">Balls signed by famous players[^1]</td>
    </tr>
    <tr>
        <th>Dislikes</th>
        <td colspan="3">Eggplants</td>
    </tr>
    <tr>
        <th>Year-based Details</th>
        <th>Yumenosaki Era</th>
        <th>ES Year 1</th>
        <th>ES Year 2</th>
    </tr>
    <tr>
        <th>Placement</th>
        <td>3rd Year (3-A)</td>
        <td>Graduate</td>
        <td>Graduate</td>
    </tr>
    <tr>
        <th>Height / Weight</th>
        <td colspan="2">175cm / 60kg</td>
        <td>175cm / 61kg</td>
    </tr>
    <tr>
        <th>Age</th>
        <td>17-18</td>
        <td>18-19</td>
        <td>19-20</td>
    </tr>
    <tr>
        <th>Hobby</th>
        <td colspan="2">Watching Tokusatsu shows and films</td>
        <td>Watching Tokusatsu shows and films, collecting figurines, helping others</td>
    </tr>
    <tr>
        <th>Specialty</th>
        <td colspan="2">Performing Stunts</td>
        <td>Stunts, sports taping, energetic greetings</td>
    </tr>
    <tr>
        <th>Club / Circle</th>
        <td>Basketball Club</td>
        <td colspan="2">Martial Artists "SHIN", Sports Survivors</td>
    </tr>
    <tr>
        <th colspan="4" style="text-align:center;">For more details, consider checking Chiaki's <a href="https://ensemble-stars.fandom.com/wiki/Chiaki_Morisawa" target="_blank">Wiki profile</a>.</th>
    </tr>
</table>

## Notes 

[^1]: This is a profile detail from 2015, and can no longer be viewed in his ES Year 1/Year 2 profile, so it may be outdated.