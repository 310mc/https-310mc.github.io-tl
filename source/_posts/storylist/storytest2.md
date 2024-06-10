---
title: "[V0.1] Ryuseitai Story List"
date: 2015-4-10 9:00:00
categories:
- [Uncategorized]
tags:
- Not Translation
description: "Ryuseitai Story List with recommended stories to read."
hidden: true
---

<img src="/img/banner/about.jpg" width="100%" height="100%" class="preview-image">

<!-- more -->

<section>
<!-- 
    - page 'decay' by skye southcodes.tumblr.com
    - modify as you please but please do not touch the credit
    - any errors? need help? have questions? let me know!
    southcodes.tumblr.com/inbox
    - normalize css by https://github.com/necolas
    - fonts by google
    - icon font by https://fontawesome.com/
    - slide in by https://stackoverflow.com/a/62432099
    - filter js by https://magnusthemes.tumblr.com
 -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Karla:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500;1,600;1,700&family=Open+Sans:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">
<link href="https://necolas.github.io/normalize.css/7.0.0/normalize.css" rel="stylesheet">
<link rel="stylesheet" href="/css/recclist2.css">
<script src="https://kit.fontawesome.com/0993e30c04.js" crossorigin="anonymous"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
<script src="https://unpkg.com/isotope-layout@3/dist/isotope.pkgd.min.js"></script>
<script src="https://static.tumblr.com/p0knose/FpAp5c11c/magnusthemes.combofilters.js"></script>
<script>
$(document).ready(function() {var $container = $("#mainbox"); // the container with all the elements to filter inside
var filters = {}; //should be outside the scope of the filtering function
/* --- read the documentation on isotope.metafizzy.co for more options --- */
var $grid = $container.isotope({
itemSelector: ".storylist-box", // the elements to filter
percentPosition: true // put true if you use percentage widths, otherwise put false
});
$(".option-set a").click(function(e) {
var $this = $(this); // cache the clicked link
var filterAttr = "data-filter-value";
var filterValue = $this.attr(filterAttr); // cache the filter
var $optionSet = $this.parents(".option-set"); // cache the parent element
var group = $optionSet.attr("data-filter-group"); // cache the parent filter group
var filterGroup = filters[group];
if (!filterGroup) {
filterGroup = filters[group] = [];
}
var $selectAll = $optionSet.find('a['+filterAttr+'=""]'); // the 'select all' button in the current group
var activeClass = "selected", // the class for active links
exclClass = "exclusive"; // the class for exclusive groups
comboFiltering($this,filters,filterAttr,filterValue,$optionSet,group,$selectAll,activeClass,exclClass);
var comboFilter = getComboFilter(filters);
$grid.isotope({
filter: comboFilter
});
$this.toggleClass(activeClass);
e.preventDefault();
});
});
</script>

<!--
<style>
 .preview-image {
    display: none;
}
</style>
-->
</section>

<!--
<div style="display:flex;">
<img src="/img/banner/about.jpg" width="50%" height="50%">
<img src="/img/banner/about.jpg" width="50%" height="50%">
</div>
-->

<div id="Index" style="font-size:16px;margin:0rem 1rem;">
<strong>Welcome</strong> to the Ryuseitai story list! In here you'll find a list of Ryuseitai stories to get you started on reading about them (or maybe to check what you haven't read so far!). I'll start by explaining a few things.
<ul class="list">
<li>This list is sorted in <b>release order</b>. For a chronological order of Ryuseitai's stories, <a href="https://citrinesea.github.io/main-sections/essays/timeline.html" target="_blank">please see this list</a> by citrinesea (it also lists Akatsuki's!), or <a href="https://ensemble-stars.fandom.com/wiki/Story/Chronological_Story_Order_(!)" target="_blank">the timeline on the Wiki</a>!</li>
<li>For a <b>text-based Ryuseitai story list</b>, please see <a href="/storylist/ryuseitai" target="_blank">here</a>! Text version still includes recommendations!</li>
<li>Please feel free to contact me about the list on <a href="https://retrospring.net/@310mc" target="_blank">retrospring</a> or on <a href="https://twitter.com/310mc1" target="_blank">Twitter</a>. Feedback is always welcome!</li>
</ul></div>

<div class="filters-list">
<ul class="filter option-set" data-filter-group="recommended">
    <li class="filters-title"><i class="fa fa-star star-color"></i> Recommended For</li>
    <li><a href="#" data-filter-value="" class="selected">All</a></li>
    <li><a href="#" data-filter-value=".ryuseitai1">Ryuseitai</a></li>
    <li><a href="#" data-filter-value=".tetora1">Tetora</a></li>
    <li><a href="#" data-filter-value=".midori1">Midori</a></li>
    <li><a href="#" data-filter-value=".shinobu1">Shinobu</a></li>
    <li><a href="#" data-filter-value=".chiaki1">Chiaki</a></li>
    <li><a href="#" data-filter-value=".kanata1">Kanata</a></li>
</ul>
<ul class="filter option-set exclusive" data-filter-group="story">
    <li class="filters-title">Story Type</li>
    <li><a href="#" data-filter-value="" class="selected">All</a></li>
    <li><a href="#" data-filter-value=".unit-only">Unit stories</a></li>
    <li><a href="#" data-filter-value=".non-unit">Non-Unit stories</a></li>
</ul>
<!--<ul class="filter option-set" data-filter-group="characters">
    <li class="filters-title">Character Appearance</li>
    <li><a href="#" data-filter-value="" class="selected">All</a></li>
    <li><a href="#" data-filter-value=".tetora1">Tetora</a></li>
    <li><a href="#" data-filter-value=".midori1">Midori</a></li>
    <li><a href="#" data-filter-value=".shinobu1">Shinobu</a></li>
    <li><a href="#" data-filter-value=".chiaki1">Chiaki</a></li>
    <li><a href="#" data-filter-value=".kanata1">Kanata</a></li>
</ul>-->
</div>

<section id="mainbox" class="grid">
<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Hero Show
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Pirate Festival
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Morning Practice
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Tough Guy
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Crash Course
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Christmas Live
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Strawberry Colored Holiday
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Triumph of the Emperor
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Hello Kitty Collab
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Supernova
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Beach Match
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Scroll of the Elements
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Holiday Party
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box tetora1 non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            The Four Beasts of Fistfighting
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Climax
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Sparkly First Years
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Purple Wisterias of May
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Shooting Star Festival
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Crossroad
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Hero Game
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Legendary Hero!
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Aquarium
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Sweet Halloween
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Zodiac – Senpai Turned Into A Dog!?
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Beasts
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Boarding Live
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            2018 April Fools Story
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Gang
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            School Festival 4
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Orihime and Hikoboshi
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Buddy
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Comic World
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Rainbow
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            First Dreams – Hurray for a Normal Day!
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Saga
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Hot & Elegant Chocolat Fes
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Meteor Impact
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Toryumon
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Study Heroes
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Management Stories
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Idol Story (1, 2, and 3)
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            !! Era 1st Main Story
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Motor Show
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Schrödinger's Monster
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Emergency! Secret Mission
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Always Hold a Heroic Heart
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Comet Show
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Turn of the Century Wars
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Submarine
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Ryuseitai Feature Scout 5* Stories
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Ninja Clan
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            SS Finals
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Myriad of Colored Flowers
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            MIRAGE
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            High and Low
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Blackjack
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Supervillain
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Graduation
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Altered
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Wedding March
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Parallel World
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Tropical
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Atlantis
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            ABYSS
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            2x2
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            The Promise To Train
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Stella Maris
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Dragon's Head
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Birthday Stories
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Mini Talks
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Dokisuta Ryuseitai
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Ryuseitai Album TRIP
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Oshi Room
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/d/d9/Hero_Show_Banner.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            TBA
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        TBA
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        TBA
    </article>
</section>
<!-- story box end -->
</section>

<div class="navigation2">
<a href="/" title="Home" target="_blank"><i class="fa fa-home"></i></a>
<a href="#Index" class="top-arrow" title="Back to Top"><i class="fa fa-arrow-up"></i></a>
</div>

<div title="Code Credits! Thank you!" style="position:fixed;bottom:3rem;right:2rem;font-size:.85rem"><a target="_blank" href="https://southcodes.tumblr.com/">SC</a></div>