---
title: "Ryuseitai Story List"
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
itemSelector: ".fanfic-box", // the elements to filter
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

<style>
 .preview-image {
    display: none;
}
</style>
</section>

<div style="display:flex;">
<img src="/img/banner/about.jpg" width="50%" height="50%">
<img src="/img/banner/about.jpg" width="50%" height="50%">
</div>

<div id="Index" style="font-size:16px;margin:0rem 1rem;">
Welcome to the Ryuseitai story list! In here you'll find a list of Ryuseitai stories to get you started on reading about them (or maybe to check what you haven't read so far!). I'll start by explaining a few things.
<ul class="list">
<li>This list is sorted in <b>release order</b>. For a chronological order of Ryuseitai's stories, <a href="https://citrinesea.github.io/main-sections/essays/timeline.html" target="_blank">please see this list</a> by citrinesea (it also lists Akatsuki's!), or <a href="https://ensemble-stars.fandom.com/wiki/Story/Chronological_Story_Order_(!)" target="_blank">the timeline on the Wiki</a>!</li>
<li>For a <b>text-based Ryuseitai story list</b>, please see <a href="/storylist/ryuseitai" target="_blank">here</a>! Text version still includes recommendations!</li>
<li>Please feel free to contact me about the list on <a href="https://retrospring.net/@310mc" target="_blank">retrospring</a> or on <a href="https://twitter.com/310mc1" target="_blank">Twitter</a>.</li>
</ul></div>

<div class="filters-list">
<ul class="filter option-set exclusive" data-filter-group="story">
    <li class="filters-title">Story Type</li>
    <li><a href="#" data-filter-value="" class="selected">All</a></li>
    <li><a href="#" data-filter-value=".recommended">Recommended</a></li>
    <li><a href="#" data-filter-value=".unit-only">Unit stories</a></li>
    <li><a href="#" data-filter-value=".non-unit">Non-Unit stories</a></li>
</ul>
<ul class="filter option-set" data-filter-group="characters">
    <li class="filters-title">Character Appearance</li>
    <li><a href="#" data-filter-value="" class="selected">All</a></li>
    <li><a href="#" data-filter-value=".tetora1">Tetora</a></li>
    <li><a href="#" data-filter-value=".midori1">Midori</a></li>
    <li><a href="#" data-filter-value=".shinobu1">Shinobu</a></li>
    <li><a href="#" data-filter-value=".chiaki1">Chiaki</a></li>
    <li><a href="#" data-filter-value=".kanata1">Kanata</a></li>
</ul>
</div>

<section id="mainbox" class="grid">
<section class="fanfic-box">
    <article class="upper-section">
    <figure class="fanfic-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/b/b5/%28Negligent%29_Midori_Takamine_Mini.png"  class="fanfic-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Climax
        </div>
        <article class="read-button">
            <a target="_blank" href=""><div>Start Reading</div><div class="tl-credit">Translaton by 310mc</div></a>
        </article>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="MidoriRecc"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        8
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        ! Era, Winter
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        2023/2/12
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! 
    </article>
</section>

<section class="fanfic-box recommended">
    <article class="upper-section">
    <figure class="fanfic-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/5/5b/Reverb%E2%98%85Stella_Maris_Crossing_the_Sea%27s_Horizon_Banner.png"  class="fanfic-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Exhibition In A Blink of An Eye
        </div>
        <article class="read-button">
            <a target="_blank" href=""><div>Start Reading<br>(Translaton by 310mc)</div></a>
        </article>
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
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
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
                        8
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        Winter
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                    Release Date
                    </div>
                    <div class="value">                 
                        2023/2/12
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!!
    </article>
</section>

<section class="fanfic-box recommended">
    <article class="upper-section">
    <figure class="fanfic-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/5/5b/Reverb%E2%98%85Stella_Maris_Crossing_the_Sea%27s_Horizon_Banner.png"  class="fanfic-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Exhibition In A Blink of An Eye
        </div>
        <article class="read-button">
            <a target="_blank" href=""><div>Start Reading</div><div class="tl-credit">(Translaton by 310mc)</div></a>
        </article>
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
                        8
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        Winter
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                    Release Date
                    </div>
                    <div class="value">                 
                        2023/2/12
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!!
    </article>
</section>

<section class="fanfic-box recommended">
    <article class="upper-section">
    <figure class="fanfic-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/5/5b/Reverb%E2%98%85Stella_Maris_Crossing_the_Sea%27s_Horizon_Banner.png"  class="fanfic-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Exhibition In A Blink of An Eye
        </div>
        <article class="read-button">
            <a target="_blank" href=""><div>Start Reading<br>(Translaton by 310mc)</div></a>
        </article>
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
                        8
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        Winter
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                    Release Date
                    </div>
                    <div class="value">                 
                        2023/2/12
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!!
    </article>
</section>

<section class="fanfic-box recommended">
    <article class="upper-section">
    <figure class="fanfic-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/5/5b/Reverb%E2%98%85Stella_Maris_Crossing_the_Sea%27s_Horizon_Banner.png"  class="fanfic-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Exhibition In A Blink of An Eye
        </div>
        <article class="read-button">
            <a target="_blank" href=""><div>Start Reading<br>(Translaton by 310mc)</div></a>
        </article>
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
                        8
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        Winter
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                    Release Date
                    </div>
                    <div class="value">                 
                        2023/2/12
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!!
    </article>
</section>

<section class="fanfic-box recommended">
    <article class="upper-section">
    <figure class="fanfic-image">
        <img src="https://static.wikia.nocookie.net/ensemble-stars/images/5/5b/Reverb%E2%98%85Stella_Maris_Crossing_the_Sea%27s_Horizon_Banner.png"  class="fanfic-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Exhibition In A Blink of An Eye
        </div>
        <article class="read-button">
            <a target="_blank" href=""><div>Start Reading<br>(Translaton by 310mc)</div></a>
        </article>
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
                        8
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        Winter
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                    Release Date
                    </div>
                    <div class="value">                 
                        2023/2/12
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">About this story</div>
        PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!! PLACEHOLDER TEXT, TO BE ADDED!!
    </article>
</section>
</section>

<div class="navigation2">
<a href="/" title="Home" target="_blank"><i class="fa fa-home"></i></a>
<a href="#Index" class="top-arrow" title="Back to Top"><i class="fa fa-arrow-up"></i></a>
</div>

<div title="Code Credits! Thank you!" style="position:fixed;bottom:3rem;right:2rem;font-size:.85rem"><a target="_blank" href="https://southcodes.tumblr.com/">SC</a></div>