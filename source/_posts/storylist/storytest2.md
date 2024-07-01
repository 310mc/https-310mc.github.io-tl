---
title: "[V0.1] Ryuseitai Story List"
date: 2015-4-10 9:00:00
categories:
- [Uncategorized]
tags:
- Not Translation
description: "Ryuseitai Story Reading List with recommended stories to read."
hidden: true
---

<img src="/img/banner/about.jpg" width="100%" height="100%" class="preview-image">

<!-- more -->

<section>
<!--
    * icons by https://fontawesome.com/
    * filter js by https://magnusthemes.tumblr.com
 -->
<link rel="stylesheet" href="/temp/css/recclist2.css">
<script src="https://kit.fontawesome.com/0993e30c04.js" crossorigin="anonymous"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
<script src="https://unpkg.com/isotope-layout@3/dist/isotope.pkgd.min.js"></script>
<script src="https://static.tumblr.com/p0knose/FpAp5c11c/magnusthemes.combofilters.js"></script>
<script>
$(document).ready(function() {var $container = $(".storylist-grid"); // the container with all the elements to filter inside
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
<em>Welcome</em> to the Ryuseitai story reading list! In here you'll find a list of Ryuseitai stories to get you started on reading about them (or to check what you haven't read so far). I'll start by explaining a few things.
<ul class="list">
<li>Stories are picked based on lore and character relevance. For a full list of every character appearance, please use the filters in the translation masterlist instead: <strong><a href="https://enstarsmasterlist.github.io/scoutevent" target="_blank">EVENT/SCOUT TRANSLATIONS</a> — <a href="https://enstarsmasterlist.github.io/featureidol" target="_blank">IDOL/FEATURE TRANSLATIONS</a></strong>
<ul class="list2"><li>Some stories have been temporarily omitted until there's an accessible translation.</li>
<li>For stories with a long list of character appearances, they have been shortened to only the ones that interact with a Ryuseitai member.</ul>
</li>
<li>This list is sorted in <strong>release order</strong>. For a chronological order of Ryuseitai's stories, <a href="https://citrinesea.github.io/main-sections/essays/timeline.html" target="_blank">please see this list</a> by citrinesea, or <a href="https://ensemble-stars.fandom.com/wiki/Story/Chronological_Story_Order_(!)" target="_blank">the timeline on the Wiki</a>!</li>
<li>For a condensed, <strong>text-only</strong> Ryuseitai story list, please see <a href="/storylist/ryuseitai" target="_blank">here</a>!</li>
<li><strong>Stories are still being added and updated with information!</strong> Please feel free to contact me about the list on <a href="https://retrospring.net/@310mc" target="_blank">retrospring</a> or on <a href="https://twitter.com/310mc1" target="_blank">Twitter</a>. Feedback is always welcome!</li>
</ul>

<div id="Index" class="filters-list">
<ul class="filter option-set exclusive" data-filter-group="weight">
    <li class="filters-title">I want to read…</li>
    <li><a href="#" data-filter-value="" class="selected">All</a></li>
    <li><a href="#" data-filter-value=".lore-focused">Lore Focused</a></li>
    <li><a href="#" data-filter-value=".light-read">Light Read</a></li>
</ul>
<ul class="filter option-set" data-filter-group="recommended">
    <li class="filters-title">Recommended For…</li>
    <li><a href="#" data-filter-value="" class="selected">All</a></li>
    <li><a href="#" data-filter-value=".ryuseitai1"><i class="fa-solid fa-star star-color"></i> Ryuseitai</a></li>
    <li><a href="#" data-filter-value=".tetora1"><i class="fa-solid fa-star" style="color:#8B838E;"></i> </i>Tetora</a></li>
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

<section class="storylist-grid">
<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 chiaki1 unit-only">
    <article class="top-section">
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> First look into how Ryuseitai is like before they debut in a large-scaled performance (ex. learning about heroes or performing hero shows)</li>
        <li><i class="fa-solid fa-star chiaki"></i> Explores Chiaki's feelings and desires about Ryuseitai</li>
        <li><i class="fa-solid fa-star tetora"></i> Explores Tetora's feelings about Ryuseitai in the early days</li>
        <li><i class="fa-solid fa-star chiaki"></i> First story to show how easily sick Chiaki gets</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read midori1 unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Izumi"></span>
                        <span class="charhead" character="Arashi"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        15
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
        <li><i class="fa-solid fa-star tetora"></i> First look into Tetora's potential as a leader when Chiaki isn't around</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read midori1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/morningpractice.jpg"  class="storylist-image">
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
                        2
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
    <article class="top-section">
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
        <li><i class="fa-solid fa-star chiaki"></i> Establishes Chiaki and Kuro's relationship and hints at their history</li>
        <li><i class="fa-solid fa-star chiaki"></i> First hint that Midori is similar to how Chiaki was in the past</li>
        <li><i class="fa-solid fa-star tetora"></i> Shows how Tetora warms up to Ryuseitai eventually</li>
        <li><i class="fa-solid fa-star midori"></i> Shows Midori's resolve to work hard</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 unit-only chiaki1">
    <article class="top-section">
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
                        <span class="charhead" character="Yuta"></span>
                        <span class="charhead" character="Hinata"></span>
                        <span class="charhead" character="Yuzuru"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        16
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Ryuseitai helping people and other units (2wink in this case)</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Establishes 2wink and Ryuseitai's relationship</li>
        <li><i class="fa-solid fa-star tetora"></i> Highlights Tetora's strengths as a hero and a person</li>
        <li><i class="fa-solid fa-star chiaki"></i> Explores Chiaki and Tetora's relationship, especially in regards to the Red position</li>
        <li><i class="fa-solid fa-star shinobu"></i> Showcases Shinobu and Yuuta's friendship. Read Crash Course for how they became friends!</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 shinobu1 midori1 non-unit">
    <article class="top-section">
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
                        10
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
        <li><i class="fa-solid fa-star midori"></i> Story is related to a strawberry-picking job, which becomes relevant in later stories</li>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<!--
<section class="storylist-box unit-only">
    <article class="top-section">
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
<!--
<section class="storylist-box light-read unstarred unit-only">
    <article class="top-section">
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
                        3
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
    <article class="top-section">
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
                        <span class="charhead" character="Kuro"></span>
                        <span class="charhead" character="Eichi"></span>
                        <span class="charhead" character="Yuzuru"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        18
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
        <div class="label">Key Points</div>
        <div class="tl-credit">Scroll for full list!</div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai-color"></i> The live show to kickstart Ryuseitai as idols and heroes</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Explores each unit member's feelings as part of Ryuseitai, their desires, hopes, prospects, etc…</li>
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
<!--
<section class="storylist-box light-read unstarred unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Hinata"></span>
                        <span class="charhead" character="Yuta"></span>
                        <span class="charhead" character="Rei"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        14
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
<section class="storylist-box lore-focused ryuseitai1 shinobu1 unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Souma"></span>
                        <span class="charhead" character="Keito"></span>
                        <span class="charhead" character="Kuro"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        16
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
        <li><i class="fa-solid fa-star shinobu"></i> Spotlight on Shinobu and the ninja association through a ninja-themed performance</li>
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
<!--
<section class="storylist-box light-read unstarred unit-only">
    <article class="top-section">
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
<section class="storylist-box lore-focused tetora1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/fourbeastsoffistfighting.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            The Four Beasts of Fistfighting
        </div>
        <div class="no-tl">Translation on Wayback<div class="tl-credit"><a target="_blank" href="https://healingbonds.dreamwidth.org/98674.html" class="unstyled">Translator has given permission</a></div></div>
    </article>
    <div class="three-wrapper" style="--storyColor:#5ac189;--storyColor-rgb:90,193,137;--storyColor-h:147.4;--storyColor-s:45.4%;--storyColor-l:55.5%;">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="Kuro"></span>
                        <span class="charhead" character="Hinata"></span>
                        <span class="charhead" character="Koga"></span>
                        <span class="charhead" character="Keito"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        10
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
        <li><i class="fa-solid fa-star tetora"></i> Explores Kuro and Tetora's relationship, especially as part of the Karate Club</li>
        <li><i class="fa-solid fa-star tetora"></i> Gives more information on how Tetora was scouted to Ryuseitai</li>
        <li><i class="fa-solid fa-star tetora"></i> Acts as a repayment story from Tetora to Kuro before graduation</li>
        <li><i class="fa-solid fa-star tetora"></i> Shows Tetora's growth since he first entered Yumenosaki</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 midori1 chiaki1 unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Eichi"></span>
                        <span class="charhead" character="Kaoru"></span>
                        <span class="charhead" character="Subaru"></span>
                        <span class="charhead" character="Mao"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        23
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Ryuseitai's Repayment Festival, i.e. story related to the 3rd years' graduation</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Explores the changes in dynamic that Ryuseitai will go through by having two members graduate, such as juniors needing to be independant and make decisions on their own</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Acts as a foundation for future stories set in !! Era</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Explores the confusing feelings each member has knowing their daily life as they know it is coming to an end and changing with graduation</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Shows a huge clash between various Ryuseitai members, and how they navigate clashing with one another because of differences</li>
        <li><i class="fa-solid fa-star midori"></i> An in-depth look into Midori as a character, his fears, lack of motivation up until this point, as well as his relationship with his family</li>
        <li><i class="fa-solid fa-star chiaki"></i> Hints at Chiaki's vulnerabilities and how he's affected by loneliness</li>
        <li><i class="fa-solid fa-star chiaki"></i> Explores Midori and Chiaki's relationship, and how much influence Chiaki has had in Midori's life</li>
        <li><i class="fa-solid fa-star tetora"></i> Exemplifies how different Tetora is from Chiaki, and hints that he'll be a different type of leader from him</li>
        <li><i class="fa-solid fa-star tetora"></i> A look into Tetora's insecurities and perceived weaknesses, and how he navigates them</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 shinobu1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Yuta"></span>
                        <span class="charhead" character="Hinata"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        9
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> A story set extremely early into the year, explaining how Chiaki scouted the Ryuseitai juniors</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> A look into Chiaki's relationship with Shinobu and Midori</li>
        <li><i class="fa-solid fa-star shinobu"></i> How Shinobu forms the ninja association</li>
        <li><i class="fa-solid fa-star shinobu"></i> Shows how Shinobu navigates as a socially anxious person</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused shinobu1 chiaki1 kanata1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Madara"></span>
                        <span class="charhead" character="Souma"></span>
                        <span class="charhead" character="Mitsuru"></span>
                        <span class="charhead" character="Adonis"></span>
                        <span class="charhead" character="Arashi"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        20
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
        <li><i class="fa-solid fa-star kanata"></i> Brief hints of Kanata's vulnerabilities</li>
        <li><i class="fa-solid fa-star kanata"></i> Establishes Madara and Kanata's relationship</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Establishes Madara's relationship with Chiaki and Shinobu</li>
        <li><i class="fa-solid fa-star kanata"></i> Explores Kanata's relationship with Shinobu and Chiaki in the early days of the timeline</li>
        <li><i class="fa-solid fa-star shinobu"></i> Explores Shinobu and Chiaki's relationship, and Shinobu's loyalty to Ryuseitai</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read tetora1 unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Mika"></span>
                        <span class="charhead" character="Shu"></span>
                        <span class="charhead" character="Kuro"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        15
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
        <li><i class="fa-solid fa-star tetora"></i> A look into Tetora leading a performance for Ryuseitai</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused chiaki1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Keito"></span>
                        <span class="charhead" character="Rei"></span>
                        <span class="charhead" character="Kuro"></span>
                        <span class="charhead" character="Kaoru"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        ~4-5 chapters
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
        <li><i class="fa-solid fa-star chiaki"></i> First reveal that Chiaki wears glasses</li>
        <li><i class="fa-solid fa-star chiaki"></i> A look into Kuro and Chiaki's relationship in the past</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 midori1 unit-only">
    <article class="top-section">
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
                        1
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> A look into Ryuseitai in the early days</li>
        <li><i class="fa-solid fa-star midori"></i> Midori trying to understand and make sense of Ryuseitai</li>
        <li><i class="fa-solid fa-star tetora"></i> Shows Tetora's feelings towards how Ryuseitai operates</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused chiaki1 unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Jin"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        1
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> A brief history of Ryuseitai as a unit</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> The first reveal that Jin was involved in Ryuseitai during his school days</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused kanata1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Kaoru"></span>
                        <span class="charhead" character="Souma"></span>
                        <span class="charhead" character="Madara"></span>
                        <span class="charhead" character="Rei"></span>
                        <span class="charhead" character="Wataru"></span>
                        <span class="charhead" character="Hinata"></span>
                        <span class="charhead" character="Sora"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        22
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
        <li><i class="fa-solid fa-star kanata"></i> Explores Kanata's distance from others, his feelings of TBA</li>
        <li><i class="fa-solid fa-star kanata"></i> Explores Kanata's relationship with Kaoru, Souma, and Madara</li>
        <li><i class="fa-solid fa-star kanata"></i> The first reveal that Kanata is a living god to his household is in ADDLINK, and this story further explores that relationship between Kanata and his household</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 midori1 chiaki1 unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Tomoya"></span>
                        <span class="charhead" character="Hajime"></span>
                        <span class="charhead" character="Mitsuru"></span>
                        <span class="charhead" character="Nazuna"></span>
                        <span class="charhead" character="Madara"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        24
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
<section class="storylist-box light-read midori1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Subaru"></span>
                        <span class="charhead" character="Keito"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        3
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
<section class="storylist-box light-read unstarred unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Hinata"></span>
                        <span class="charhead" character="Yuta"></span>
                        <span class="charhead" character="Tsukasa"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        14
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
        <li><i class="fa-solid fa-star chiaki"></i> Chiaki being an attentive senior to a non-Ryuseitai junior, Hinata</li>
        <li><i class="fa-solid fa-star midori"></i> The story has a voice clip for one of Midori's Ryusei Green catchphrase variations</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused tetora1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Arashi"></span>
                        <span class="charhead" character="Madara"></span>
                        <span class="charhead" character="Ritsu"></span>
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
<section class="storylist-box light-read unstarred unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/aprilfools2018.jpg"  class="storylist-image">
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
                        <span class="charhead" character="Mao"></span>
                        <span class="charhead" character="Tori"></span>
                        <span class="charhead" character="Eichi"></span>
                        <span class="charhead" character="Wataru"></span>
                        <span class="charhead" character="Keito"></span>
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
        <li><i class="fa-solid fa-star ryuseitai"></i> Fun "fictional" story where Ryuseitai are actual Meteor Rangers in outer space, protecting the peace of the galaxy!</li>
        <li><i class="fa-solid fa-star ryuseitai"></i> Heroes VS Villains story between Ryuseitai VS Student Council (+ Wataru)</li>
        <li><i class="fa-solid fa-star ryuseitai"></i> Also has a retro shoot 'em up mini-game in Enstars Basic</span></li>
        <li><i class="fa-solid fa-star chiaki"></i> Eichi helping Chiaki making one of his dreams come true</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused chiaki1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Kuro"></span>
                        <span class="charhead" character="Yuzuru"></span>
                        <span class="charhead" character="Mika"></span>
                        <span class="charhead" character="Ibara"></span>
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
        <li><i class="fa-solid fa-star chiaki"></i> Explores Chiaki and Kuro's relationship in their 2nd year and present year</li>
        <li><i class="fa-solid fa-star chiaki"></i> Gives more insight on Chiaki's time when he was bullied, and how Kuro tried to help him</li>
        <li><i class="fa-solid fa-star chiaki"></i> Shows Chiaki's tokusatsu nerdy side and pragmatic outlook within the same chapters</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read unstarred unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Tomoya"></span>
                        <span class="charhead" character="Wataru"></span>
                        <span class="charhead" character="Sora"></span>
                        <span class="charhead" character="Kaoru"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        14
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
        <li><i class="fa-solid fa-star ryuseitai"></i> The ONLY event story Ryuseitai has that's set in Spring (early days)</li>
        <li><i class="fa-solid fa-star tetora"></i> Shows how Tetora ADJUST</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 midori1 shinobu1 unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Mao"></span>
                        <span class="charhead" character="Subaru"></span>
                        <span class="charhead" character="Hokuto"></span>
                        <span class="charhead" character="Makoto"></span>
                        <span class="charhead" character="Wataru"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        21
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
        <li><i class="fa-solid fa-star ryuseitai"></i> Junior-focused story, where they are guided by Trickstar instead</li>
        <li><i class="fa-solid fa-star ryuseitai"></i> Juniors have an eye-opening experience about their dependance, and how that leads them to develop their own independancy</li>
        <li><i class="fa-solid fa-star ryuseitai"></i> Explores Ryuseitai member's feelings as part of the unit and how they're warming up to their place</li>
        <li><i class="fa-solid fa-star shinobu"></i> Displays Shinobu's strengths as a ninja and Ryuseitai member</li>
        <li><i class="fa-solid fa-star shinobu"></i> Explores Shinobu and Mao's relationship</li>
        <li><i class="fa-solid fa-star shinobu"></i> Establishes Midori and Subaru's relationship</li>
        <li><i class="fa-solid fa-star shinobu"></i> Displays Shinobu's strengths as a ninja and Ryuseitai member</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused kanata1 non-unit">
    <article class="top-section">
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
                        9
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
        <li><i class="fa-solid fa-star kanata"></i> Showcases what being a hero means to Kanata during his early days as a third year</li>
        <li><i class="fa-solid fa-star kanata"></i> Explores Keito and Kanata's relationship in relation to the War</li>
        <li><i class="fa-solid fa-star kanata"></i> A display of Kanata's mindset and philosophy about the world, and how he wishes to repay kindness with kindness</li>
        <li><i class="fa-solid fa-star kanata"></i> Rare Kanata interactions with Kuro and Ritsu</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read unstarred non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Madara"></span>
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
                        TBA
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai"></i> A light-hearted, silly story of some Ryuseitai members during summer break</li>
        <li><i class="fa-solid fa-star chiaki"></i> Chiaki learning that he can spend his time with his Ryuseitai juniors if he wants to</li>
        <li><i class="fa-solid fa-star chiaki"></i> A little bit of Chiaki's family mentioned</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused chiaki1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Jin"></span>
                        <span class="charhead" character="Hokuto"></span>
                        <span class="charhead" character="Tori"></span>
                        <span class="charhead" character="Madara"></span>
                        <span class="charhead" character="Akiomi"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        51 TBA
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
<section class="storylist-box light-read midori1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Mao"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        2
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
<section class="storylist-box lore-focused chiaki1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Hokuto"></span>
                        <span class="charhead" character="Tori"></span>
                        <span class="charhead" character="Jin"></span>
                        <span class="charhead" character="Seiya"></span>
                        <span class="charhead" character="Hiyori"></span>
                        <span class="charhead" character="Jun"></span>
                        <span class="charhead" character="Eichi"></span>
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
<section class="storylist-box light-read midori1 unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Shu"></span>
                        <span class="charhead" character="Mika"></span>
                        <span class="charhead" character="Subaru"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        15
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
<section class="storylist-box lore-focused ryuseitai1 chiaki1 kanata1 unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Madara"></span>
                        <span class="charhead" character="Kuro"></span>
                        <span class="charhead" character="Souma"></span>
                        <span class="charhead" character="Keito"></span>
                        <span class="charhead" character="Shu"></span>
                        <span class="charhead" character="Subaru"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        54
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
<section class="storylist-box light-read kanata1 unit-only">
    <article class="top-section">
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
                        8
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
<section class="storylist-box light-read ryuseitai1 unit-only">
    <article class="top-section">
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
                        1
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
<section class="storylist-box light-read ryuseitai1 non-unit">
    <article class="top-section">
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
                        Several 1-chaptered stories
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Recommended because early Spring timeline is rare yet important!</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 unit-only">
    <article class="top-section">
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
                        Ten 1-chaptered stories
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
<section class="storylist-box lore-focused ryuseitai1 non-unit">
    <article class="top-section">
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
<section class="storylist-box lore-focused ryuseitai1 tetora1 unit-only">
    <article class="top-section">
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
                        15
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
<section class="storylist-box light-read unstarred non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/schrmonster.png"  class="storylist-image">
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
                        <span class="charhead" character="Wataru"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        1
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
<section class="storylist-box light-read unstarred non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/emergencysecretmission.png"  class="storylist-image">
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
                        1
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
<section class="storylist-box light-read unstarred non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/alwaysholdaheroicheart.png"  class="storylist-image">
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
                        1
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
<section class="storylist-box lore-focused tetora1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Koga"></span>
                        <span class="charhead" character="Yuta"></span>
                        <span class="charhead" character="Sora"></span>
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
<section class="storylist-box lore-focused ryuseitai1 midori1 chiaki1 kanata1 unit-only">
    <article class="top-section">
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
                        23
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
<section class="storylist-box lore-focused ryuseitai1 chiaki1 kanata1 unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Souma"></span>
                        <span class="charhead" character="Kuro"></span>
                        <span class="charhead" character="Keito"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        32
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
<section class="storylist-box light-read tetora1 midori1 shinobu1 chiaki1 kanata1 non-unit">
    <article class="top-section">
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
                        Ten 2-chaptered stories
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
<section class="storylist-box light-read shinobu1 unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Mao"></span>
                        <span class="charhead" character="Mayoi"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        12
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
<section class="storylist-box lore-focused unstarred non-unit">
    <article class="top-section">
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
<section class="storylist-box lore-focused kanata1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Madara"></span>
                        <span class="charhead" character="Souma"></span>
                        <span class="charhead" character="Mitsuru"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        12
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
<section class="storylist-box lore-focused shinobu1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Yuta"></span>
                        <span class="charhead" character="Hinata"></span>
                        <span class="charhead" character="Koga"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        10
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
<section class="storylist-box lore-focused ryuseitai1 tetora1 midori1 non-unit">
    <article class="top-section">
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
<section class="storylist-box lore-focused ryuseitai1 tetora1 shinobu1 non-unit">
    <article class="top-section">
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
    <article class="top-section">
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
        <li><i class="fa-solid fa-star tetora"></i> Deep dive into Tetora's character, his fears, wishes to grow stronger, backstory, determination as a hero, etc…</li>
        <li><i class="fa-solid fa-star tetora"></i> All of Tetora's efforts coming to fruition, like his former Ryuseitai-N juniors asking for his help, Tetora confidently acting as a leader and executing his own plan, etc…</li>
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
    <article class="top-section">
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
                        <span class="charhead" character="Natsume"></span>
                        <span class="charhead" character="Rei"></span>
                        <span class="charhead" character="Shu"></span>
                        <span class="charhead" character="Wataru"></span>
                        <span class="charhead" character="Eichi"></span>
                        <span class="charhead" character="Hiyori"></span>
                        <span class="charhead" character="Nagisa"></span>
                        <span class="charhead" character="Tsumugi"></span>
                        <span class="charhead" character="Akiomi"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        47 (Appears in 10 chapters)
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
<section class="storylist-box light-read unstarred non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/weddingmarch.png"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Wedding March!
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
                        19
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
<section class="storylist-box light-read ryuseitai1 unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Tomoya"></span>
                        <span class="charhead" character="Hajime"></span>
                        <span class="charhead" character="Mitsuru"></span>
                        <span class="charhead" character="Nazuna"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        1
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> A first, brief look into the potential of all-leaders Ryuseitai</li>
        <li><i class="fa-solid fa-star chiaki"></i> test test <span class="spoiler-text">hellooo</span></li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read ryuseitai1 midori1 unit-only">
    <article class="top-section">
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
                        14
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
<section class="storylist-box lore-focused shinobu1 non-unit">
    <article class="top-section">
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
<section class="storylist-box lore-focused kanata1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Madara"></span>
                        <span class="charhead" character="Souma"></span>
                        <span class="charhead" character="Kaoru"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        16
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
<section class="storylist-box lore-focused shinobu1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Yuta"></span>
                        <span class="charhead" character="Hinata"></span>
                        <span class="charhead" character="Nagisa"></span>
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
<section class="storylist-box light-read unstarred non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/promisetotrain.png"  class="storylist-image">
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
                        1
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
<section class="storylist-box lore-focused ryuseitai1 tetora1 chiaki1 kanata1 unit-only">
    <article class="top-section">
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
                        <span class="charhead" character="Eichi"></span>
                        <span class="charhead" character="Tori"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        30
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
<section class="storylist-box light-read tetora1 non-unit">
    <article class="top-section">
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
                        <span class="charhead" character="Kuro"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        12
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
<section class="storylist-box light-read unstarred non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/testing.jpg"  class="storylist-image">
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
                        Several short stories
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
<section class="storylist-box lore-focused light-read unstarred non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="/img/es/storylist/banner/testing1.jpg"  class="storylist-image">
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
                        Several short stories
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
<section class="storylist-box lore-focused ryuseitai1 unit-only">
    <article class="top-section">
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
                        None
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
<section class="storylist-box light-read ryuseitai1 unit-only">
    <article class="top-section">
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
                        None
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
<section class="storylist-box light-read unstarred non-unit">
    <article class="top-section">
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
                        None
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
    <article class="top-section">
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
<a href="#top" class="top-arrow" title="Back to Top"><i class="fa fa-arrow-up"></i></a>
</div>