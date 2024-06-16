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

<section style="font-size:16px;">
<strong>Welcome</strong> to the Ryuseitai story list! In here you'll find a list of Ryuseitai stories to get you started on reading about them (or maybe to check what you haven't read so far!). I'll start by explaining a few things.
<ul class="list">
<li>Stories are picked based on story and character relevance. To see a full list of every character appearance, please use the filters in the translation masterlist: <strong><a href="https://enstarsmasterlist.github.io/scoutevent" target="_blank">EVENT/SCOUT TRANSLATIONS</a> — <a href="https://enstarsmasterlist.github.io/featureidol" target="_blank">IDOL/FEATURE TRANSLATIONS</a></strong>
<ul class="list2"><li>Some stories have been omitted until there's an accessible translation.</li>
<li>For stories with a long list of character appearances, they have been shortened to only the ones that interact with a Ryuseitai member.</ul>
</li>
<li>This list is sorted in <b>release order</b>. For a chronological order of Ryuseitai's stories, <a href="https://citrinesea.github.io/main-sections/essays/timeline.html" target="_blank">please see this list</a> by citrinesea (it also lists Akatsuki's!), or <a href="https://ensemble-stars.fandom.com/wiki/Story/Chronological_Story_Order_(!)" target="_blank">the timeline on the Wiki</a>!</li>
<li>For a <b>text-only Ryuseitai story list</b>, please see <a href="/storylist/ryuseitai" target="_blank">here</a>!</li>
<li>Please feel free to contact me about the list on <a href="https://retrospring.net/@310mc" target="_blank">retrospring</a> or on <a href="https://twitter.com/310mc1" target="_blank">Twitter</a>. Feedback is always welcome!</li>
</ul>

<div id="Index" class="filters-list">
<ul class="filter option-set exclusive" data-filter-group="weight">
    <li class="filters-title">I want to read...</li>
    <li><a href="#" data-filter-value="" class="selected">All</a></li>
    <li><a href="#" data-filter-value=".lore-focused">Lore Focused</a></li>
    <li><a href="#" data-filter-value=".light-read">Light Read</a></li>
</ul>
<ul class="filter option-set" data-filter-group="recommended">
    <li class="filters-title">Recommended For...</li>
    <li><a href="#" data-filter-value="" class="selected">All</a></li>
    <li><a href="#" data-filter-value=".ryuseitai1"><i class="fa-solid fa-star star-color"></i> Ryuseitai</a></li>
    <li><a href="#" data-filter-value=".tetora1"><i class="fa-solid fa-star" style="color:#bba2c4;"></i> </i>Tetora</a></li>
    <li><a href="#" data-filter-value=".midori1"><i class="fa-solid fa-star" style="color:#0d9c7d;"></i> Midori</a></li>
    <li><a href="#" data-filter-value=".shinobu1"><i class="fa-solid fa-star" style="color:#fcee21;"></i> Shinobu</a></li>
    <li><a href="#" data-filter-value=".chiaki1"><i class="fa-solid fa-star" style="color:#BD1F20;"></i> Chiaki</a></li>
    <li><a href="#" data-filter-value=".kanata1"><i class="fa-solid fa-star" style="color:#008db7;"></i> Kanata</a></li>
    <li><a href="#" data-filter-value=".unstarred">Unstarred</a></li>
</ul>
<ul class="filter option-set exclusive" data-filter-group="story">
    <li class="filters-title">Story Type</li>
    <li><a href="#" data-filter-value="" class="selected">All</a></li>
    <li><a href="#" data-filter-value=".unit-only">Unit stories</a></li>
    <li><a href="#" data-filter-value=".non-unit">Non-Unit stories</a></li>
</ul>
</div>
</section>

<section id="mainbox" class="grid">
<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 chiaki1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/heroshow.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Hero Show
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="TetoraRecc"></span>
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
                        ! Era, Summer
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        6/30/2015
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Ryuseitai's very first story of the game</li>
        <li><i class="fa-solid fa-star chiaki"></i> Explores Chiaki's feelings and desires about Ryuseitai</li>
        <li><i class="fa-solid fa-star tetora"></i> Explores Tetora's feelings about Ryuseitai in the early days</li>
        <li><i class="fa-solid fa-star chiaki"></i> First story to show how easily sick Chiaki gets</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read midori1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/piratefestival.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Pirate Festival
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="MidoriRecc"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Rei"></span>
                        <span class="charhead" character="Kaoru"></span>
                        <span class="charhead" character="Adonis"></span>
                        <span class="charhead" character="Koga"></span>
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
                        ! Era, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Ryuseitai's first event story</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Briefly establishes a relationship between UNDEAD and Ryuseitai</li>
        <li><i class="fa-solid fa-star midori"></i> Shows a motivated and hardworking Midori in the early days</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read midori1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/morningpractice.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Morning Practice
        </div>
        <a target="_blank" href="/morning_practice"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="MidoriRecc"></span>
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
                        ! Era, Spring
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star midori"></i> How Midori gets his phone-strap</li>
        <li><i class="fa-solid fa-star midori"></i> Senpai-kouhai bonding for Midori&Kanata, and Midori&Chiaki</li>
        <li><i class="fa-solid fa-star midori"></i> Establishes how and why Chiaki picks Midori up in the morning</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/toughguy.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Tough Guy
        </div>
        <a target="_blank" href="/tough_guy"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Kuro"></span>
                        <span class="charhead" character="Mao"></span>
                        <span class="charhead" character="Subaru"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        11
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        ! Era, Autumn
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star chiaki"></i> Establishes Chiaki and Kuro's relationship</li>
        <li><i class="fa-solid fa-star chiaki"></i> First hint that Midori is similar to how Chiaki was in the past</li>
        <li><i class="fa-solid fa-star tetora"></i> Expresses how Tetora warms up to Ryuseitai eventually</li>
        <li><i class="fa-solid fa-star midori"></i> Midori's resolve to work hard</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 unit-only chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/christmaslive.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Christmas Live
        </div>
        <a target="_blank" href="/christmas_live"><div>Start Reading</div><div class="tl-credit">Translation by 310mc & Mika Enstars</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="TetoraRecc"></span>
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
                        ! Era, Winter
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> Highlights Tetora's strengths as a hero and a person</li>
        <li><i class="fa-solid fa-star chiaki"></i> Explores Chiaki and Tetora's relationship, especially in regards to the Red position</li>
        <li><i class="fa-solid fa-star shinobu"></i> Showcases Shinobu and Yuuta's friendship. Read Crash Course for how they became friends!</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 shinobu1 midori1 non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/strawberrycoloredholiday.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Strawberry Colored Holiday
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="MidoriRecc"></span>
                        <span class="charhead" character="ShinobuRecc"></span>
                        <span class="charhead" character="Hinata"></span>
                        <span class="charhead" character="Yuta"></span>
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
                        ! Era, Spring (Post-graduation)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai-color"></i> First look into Ryuseitai's future post-graduation, such as Tetora being the leader now. (Note: This story was written before Enstars decided to create the agencies)</li>
        <li><i class="fa-solid fa-star shinobu"></i> Explores Shinobu's resolve and determination as a hero</li>
        <li><i class="fa-solid fa-star midori"></i> How Midori switches from "Sengoku-kun" to "Shinobu-kun"</li>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<!--
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/triumphoftheemperor.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Triumph of the Emperor
        </div>
        <div class="no-tl">Translation available, use search terms</div>
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read unstarred unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/hellokittycollab.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Hello Kitty Collab
        </div>
        <div class="no-tl">Translation available, use search terms</div>
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
                        ! Era, TBA
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Cute story with Hello Kitty and Ryuseitai interacting!</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 midori1 shinobu1 chiaki1 kanata1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/supernova.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Supernova
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="KanataRecc"></span>
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="MidoriRecc"></span>
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        ! Era, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;">Scroll for full list!</span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai-color"></i> The live show to kickstart Ryuseitai as idols and heroes</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Explores each unit member's feelings as part of Ryuseitai, their desires, hopes, prospects, etc...</li>
        <li><i class="fa-solid fa-star kanata"></i> First look into Kanata's motivations as part of Ryuseitai</li>
        <li><i class="fa-solid fa-star midori"></i> Explores Midori's feelings about accidentally becoming an idol</li>
        <li><i class="fa-solid fa-star tetora"></i> The moment Tetora starts to reflect on his initial feelings towards Ryuseitai and warm up to them</li>
        <li><i class="fa-solid fa-star shinobu"></i> Shows Shinobu's loyalty and intimacy with Ryuseitai</li>
        <li><i class="fa-solid fa-star chiaki"></i> Establishes Ryuseitai's ideals and goals as a hero unit, as told by Chiaki</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read unstarred unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/beachmatch.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Beach Match
        </div>
        <div class="no-tl">Translation available, use search terms</div>
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
                        ! Era, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star shinobu"></i> Showcases Shinobu's ninja lifestyle and how Chiaki validates it</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/scrolloftheelements.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Scroll of the Elements
        </div>
        <a target="_blank" href="https://citrinesea.github.io/translation/scroll_of_the_elements/"><div>Start Reading</div><div class="tl-credit">Translation by citrinesea</div></a>
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
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        ! Era, Autumn
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star shinobu"></i> Spotlight on Shinobu and the ninja association through a ninja-themed performance.</li>
        <li><i class="fa-solid fa-star shinobu"></i> Exploration of Shinobu's feelings as part of Ryuseitai, his gratitude towards them</li>
        <li><i class="fa-solid fa-star shinobu"></i> Hints about Shinobu's loneliness before meeting Ryuseitai</li>
        <li><i class="fa-solid fa-star kanata"></i> Hints about Keito and Kanata's relationship as a Student Council member and an Eccentric</li>
        <li><i class="fa-solid fa-star chiaki"></i> How Chiaki incorporates other member's interests into Ryuseitai and fosters them</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Discusses the distances between the seniors and juniors within their life (adjust later)</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/holidayparty.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Holiday Party
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
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
                        ! Era, Winter
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box tetora1 non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/fourbeastsoffistfighting.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            The Four Beasts of Fistfighting
        </div>
        <div class="no-tl">Translation only found on Wayback<div class="tl-credit">(Translator has given permission)</div></div>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
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
                        ! Era, Winter
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/climax.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Climax
        </div>
        <a target="_blank" href="/climax"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="MidoriRecc"></span>
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
                        ! Era, Winter (Graduation season)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/sparklyfirstyears.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Sparkly First Years
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        ! Era, Spring
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/purplewisteria.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Purple Wisterias of May
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="KanataRecc"></span>
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        ! Era, Spring
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/shootingstarfestival.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Shooting Star Festival
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="TetoraRecc"></span>
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
                        ! Era, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/crossroad.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Crossroad
        </div>
        <a target="_blank" href="/crossroad"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
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
                        ! Era, past (Spring time, Chiaki's 2nd year)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/herogame.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Hero Game
        </div>
        <a target="_blank" href="/hero_game"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
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
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        ! Era, Spring
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/legendaryhero.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Legendary Hero!
        </div>
        <a target="_blank" href="/legendary_hero"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
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
                        ! Era, Spring
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/aquarium.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Aquarium
        </div>
        <a target="_blank" href="/aquarium"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="KanataRecc"></span>
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
                        ! Era, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/sweethalloween.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Sweet Halloween
        </div>
        <a target="_blank" href="/sweet_halloween"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
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
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        ! Era, Autumn
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/zodiac.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Zodiac: Senpai Turned Into A Dog!?
        </div>
        <a target="_blank" href="/senpai_turned_into_a_dog"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="MidoriRecc"></span>
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
                        ! Era, Winter (New years)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/beasts.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Beasts
        </div>
        <a target="_blank" href="/beasts"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="Midori"></span>
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
                        ! Era, Winter (Graduation season)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/boardinglive.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Boarding Live
        </div>
        <a target="_blank" href="https://otori.neocities.org/tls/enstars/directory"><div>Start Reading</div><div class="tl-credit">Translation by Bella</div></a>
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
                        ! Era, Winter
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/aprilfools2018.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            2018 April Fools Story
        </div>
        <a target="_blank" href="https://distortedheart.dreamwidth.org/4191.html"><div>Start Reading</div><div class="tl-credit">Translation by adriessene</div></a>
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
                        ! Era, Spring
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/gang.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Gang
        </div>
        <a target="_blank" href="/gang"><div>Start Reading</div><div class="tl-credit">Translation by harmonyleaf & 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
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
                        ! Era, Spring
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/schoolfestival.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            School Festival 4
        </div>
        <a target="_blank" href="/school_festival_4"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
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
                        ! Era, Spring
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/orihimeandhikoboshi.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Orihime and Hikoboshi
        </div>
        <a target="_blank" href="/orihime_and_hikoboshi"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="MidoriRecc"></span>
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        ! Era, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/buddy.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Buddy
        </div>
        <a target="_blank" href="/buddy"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
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
                        ! Era, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/comicworld.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Comic World
        </div>
        <a target="_blank" href="/comic_world"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="KanataRecc"></span>
                        <span class="charhead" character="Keito"></span>
                        <span class="charhead" character="Kuro"></span>
                        <span class="charhead" character="Ritsu"></span>
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
                        ! Era, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/rainbow.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Rainbow
        </div>
        <a target="_blank" href="https://kotofucius.github.io/2018/saga1-rainbow/"><div>Start Reading</div><div class="tl-credit">Translation by kotofucius</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
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
                        ! Era, Summer (TBA)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/firstdreams.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            First Dreams: Hurray for a Normal Day!
        </div>
        <a target="_blank" href="/hurray_normal_day"><div>Start Reading</div><div class="tl-credit">Translation by Peace</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="MidoriRecc"></span>
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
                        ! Era, Winter (New years)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/saga.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Saga
        </div>
        <a target="_blank" href="https://hyenahunt.tumblr.com/post/682683575976574976/translation-sagaclashing-rebirth-live"><div>Start Reading</div><div class="tl-credit">Translation by kotofucius</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
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
                        ! Era, Winter
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/chocofes.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Hot & Elegant Chocolat Fes
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
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
                        TBA
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
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/meteorimpact.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Meteor Impact
        </div>
        <a target="_blank" href="/meteor_impact"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="KanataRecc"></span>
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
                        ! Era, Winter (Before New years), past (Chiaki&Kanata's 1st&2nd year)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/toryumon.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Toryumon
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="KanataRecc"></span>
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
                        ! Era, Autumn
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/studyheroes.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Study Heroes
        </div>
        <a target="_blank" href="/study_heroes"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
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
                        ! Era, Autumn
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/managementstories.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Management Stories
        </div>
        <a target="_blank" href="/management_story"><div>Start Reading</div><div class="tl-credit">Translation by 310mc & citrinesea</div></a>
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
                        ! Era, Spring
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai-color"></i> A look into how Ryuseitai interacted with each other in the early days</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/idolstory123.png"  class="storylist-image">
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
                        !! Era Year 1, Spring
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/mainstoryes2.png"  class="storylist-image">
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
                        !! Era Year 1, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/motorshow.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Motor Show
        </div>
        <a target="_blank" href="/motor_show"><div>Start Reading</div><div class="tl-credit">Translation by 310mc & Peace & Whisper</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Hiiro"></span>
                        <span class="charhead" character="Mayoi"></span>
                        <span class="charhead" character="Tatsumi"></span>
                        <span class="charhead" character="Aira"></span>
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
                        !! Era Year 1, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/TBA.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Schrödinger's Monster
        </div>
        <div class="no-tl">Translation available in the English version of Enstars!! music</div>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
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
                        !! Era Year 1, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/TBA.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Emergency! Secret Mission
        </div>
        <div class="no-tl">Translation available in the English version of Enstars!! music</div>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
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
                        !! Era Year 1, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/TBA.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Always Hold a Heroic Heart
        </div>
        <a target="_blank" href="/always_hold_a_heroic_heart"><div>Start Reading</div><div class="tl-credit">Translation by 310mc & TsubasaFL</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
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
                        !! Era Year 1, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/cometshow.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Comet Show
        </div>
        <a target="_blank" href="/comet_show"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="KanataRecc"></span>
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
                        TBA
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        !! Era Year 1, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/centurywars.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Turn of the Century Wars
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
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
                        !! Era Year 1, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/submarine.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Submarine
        </div>
        <a target="_blank" href="/submarine"><div>Start Reading</div><div class="tl-credit">Translation by 310mc & verdantgrove</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="KanataRecc"></span>
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
                        !! Era Year 1, Winter
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/TBA.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Ryuseitai Feature Scout 5* Stories
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="KanataRecc"></span>
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="MidoriRecc"></span>
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        !! Era Year 1
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/ninjaclan.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Ninja Clan
        </div>
        <a target="_blank" href="/ninja_clan"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
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
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        !! Era Year 1, Summer
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/ssfinals.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            SS Finals
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
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
                        !! Era Year 1, Winter
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/myriad.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Myriad of Colored Flowers
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="KanataRecc"></span>
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
                        !! Era Year 1, TBA
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/mirage.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            MIRAGE
        </div>
        <a target="_blank" href="https://twilightmalachite.tumblr.com/mirage"><div>Start Reading</div><div class="tl-credit">Translation by Mika Enstars</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        !! Era Year 1, Winter
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/highandlow.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            High and Low
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="MidoriRecc"></span>
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
                        !! Era Year 1, Autumn
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/blackjack.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Black Jack
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        !! Era Year 1, Winter
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 shinobu1 chiaki1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/supervillain.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Supervillain
        </div>
        <a target="_blank" href="/supervillain"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="ShinobuRecc"></span>
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="Kanata"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        25
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        !! Era, Winter (March)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;">Scroll for full list!</span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai-color"></i> The story to resolve Ryuseitai's tension and complications across the first !! Era year, as well as start a whole new era for them (New unit formation)</li>
        <li><i class="fa-solid fa-star tetora"></i> Deep dive into Tetora's character, his fears, wishes to grow stronger, backstory, determination as a hero, etc...</li>
        <li><i class="fa-solid fa-star tetora"></i> All of Tetora's efforts coming to fruition, like his former Ryuseitai-N juniors asking for his help, Tetora confidently acting as a leader and executing his own plan, etc...</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Explores Ryuseitai's rebellion against their agency, as well as how they resolve to survive as part of ES.</li>
        <li><i class="fa-solid fa-star chiaki"></i> Chiaki opening up to Tetora and telling him about his past in Ryuseitai</li>
        <li><i class="fa-solid fa-star shinobu"></i> Shinobu's ninja expertise coming into use for a real life situation</li>
        <li><i class="fa-solid fa-star shinobu"></i> Ryuseitai's, especially Chiaki's, unwavering trust in Shinobu and his loyalty to Ryuseitai</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused kanata1 non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/altered.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Altered
        </div>
        <a target="_blank" href="https://twilightmalachite.tumblr.com/altered"><div>Start Reading</div><div class="tl-credit">Translation by Mika Enstars</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="KanataRecc"></span>
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
                        !! Era Year 1, Winter
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star kanata"></i> Shows Kanata's thoughts in his 2nd year, regarding his role as a god and in the Yumenosaki war</li>
        <li><i class="fa-solid fa-star kanata"></i> Tells a little bit about his relationship with Madara and Souma</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/weddingmarch.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Wedding March
        </div>
        <a target="_blank" href="/wedding_march"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Midori"></span>
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
                        !! Era Year 1, Autumn
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/parallelworld.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Parallel World
        </div>
        <a target="_blank" href="/parallel_world"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
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
                        !! Era Year 1, Winter (Post-Supervillain)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/tropical.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Tropical
        </div>
        <a target="_blank" href="/tropical"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="MidoriRecc"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
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
                        !! Era Year 2, Spring (April)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/atlantis.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Atlantis
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        !! Era Year 1, Winter (TBA)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/abyss.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            ABYSS
        </div>
        <a target="_blank" href="/abyss"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="KanataRecc"></span>
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
                        !! Era Year 1, Winter + Past, childhood days
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/2x2.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            2x2
        </div>
        <a target="_blank" href="https://twilightmalachite.tumblr.com/2x2"><div>Start Reading</div><div class="tl-credit">Translation by Mika Enstars</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        !! Era Year 1, Winter
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/TBA.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            The Promise To Train
        </div>
        <a target="_blank" href="/the_promise_to_train"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
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
                        !! Era Year 1, Winter
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only chiaki1">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/stellamaris.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Stella Maris
        </div>
        <a target="_blank" href="/stella_maris"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="KanataRecc"></span>
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="ChiakiRecc"></span>
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
                        !! Era Year 2, Spring (May)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/dragonshead.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Dragon's Head
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
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
                        !! Era Year 1, Winter
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/TBA.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Birthday Stories
        </div>
        <a target="_blank" href="/birthday_story"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
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
                        ! Era and !! Era
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/TBA.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Mini Talks
        </div>
        <a target="_blank" href="/minitalk"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
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
                        ! Era and !! Era
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box ryuseitai1 unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/dokisutaryuseitai.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Dokisuta Ryuseitai
        </div>
        <a target="_blank" href="/dokisuta_ryuseitai"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
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
                        !! Era (Post-Supervillain)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box unit-only">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/ryuseitaialbumtrip.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Ryuseitai Album TRIP
        </div>
        <a target="_blank" href="/ryuseitai_album_trip"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
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
                        !! Era (All-leaders formation)
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box non-unit">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/oshiroom.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Oshi Room
        </div>
        <a target="_blank" href="https://citrinesea.github.io/translation/oshi_room_2024/"><div>Start Reading</div><div class="tl-credit">Translation by 310mc & citrinesea</div></a>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
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
                        !! Era
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<!--
<section class="storylist-box">
    <article class="upper-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/TBA.png"  class="storylist-image">
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
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star tetora"></i> test TBA</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
-->
<!-- story box end -->
</section>

<div class="navigation2">
<a href="/" title="Home" target="_blank"><i class="fa fa-home"></i></a>
<a href="#Index" class="top-arrow" title="Back to Top"><i class="fa fa-arrow-up"></i></a>
</div>

<div title="Code Credits! Thank you!" style="position:fixed;bottom:3rem;right:2rem;font-size:.85rem"><a target="_blank" href="https://southcodes.tumblr.com/">SC</a></div>