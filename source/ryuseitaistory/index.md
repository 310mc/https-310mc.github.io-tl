---
title: (Version 0.1) Ryuseitai Story List
description: Ryuseitai Story Reading List with recommended stories to read.
---

<p style="text-align:center;"><big><a href="/" target="_blank">Click here to go back to the homepage!</a></big></p>

<img src="https://f005.backblazeb2.com/file/reitoouji/ro_jpU3m675717a3355.webp?timestamp=1733760934009" width="100%" height="100%" class="preview-image">

<section>
<!--
    * icons by https://fontawesome.com/
    * filter js by https://magnusthemes.tumblr.com
 -->
<link rel="stylesheet" href="/cssfolder/recclist.css">
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
<img src="https://f005.backblazeb2.com/file/reitoouji/ro_jpU3m675717a3355.webp?timestamp=1733760934009" width="50%" height="50%">
<img src="https://f005.backblazeb2.com/file/reitoouji/ro_jpU3m675717a3355.webp?timestamp=1733760934009" width="50%" height="50%">
</div>
-->

<section style="font-size:16px;">
<em>Welcome</em> to the Ryuseitai story reading list! In here you'll find a list of Ryuseitai stories to get you started on reading about them (or to check what you haven't read so far). I'll start by explaining a few things.
<ul class="list">
<li>
Stories are picked based on lore and character relevance. For a full list of every character appearance, please use the filters in the translation masterlist instead: <big><strong><a href="https://enstarsmasterlist.github.io/scoutevent" target="_blank">EVENT/SCOUT TRANSLATIONS</a> — <a href="https://enstarsmasterlist.github.io/featureidol" target="_blank">IDOL/FEATURE TRANSLATIONS</a></strong></big>
<ul class="list2">
<li>Some stories have been temporarily omitted until there's an accessible translation.</li>
<li>For stories with a long list of character appearances, they have been shortened to only the ones that interact with a Ryuseitai member.</li>
</ul>
</li>
<li>This list is sorted in <strong>release order</strong>. For a chronological order of Ryuseitai's stories, <a href="/ryuseitaitimeline" target="_blank">please check the story timeline</a>!</li>
<li>For an extremely condensed, <strong>text-only</strong> Ryuseitai story list, please see <a href="/ryuseitailist" target="_blank">here</a>!</li>
<li><strong>Stories are still being added and updated with information!</strong> Please feel free to contact me about the list on <a href="https://retrospring.net/@310mc" target="_blank">retrospring</a> or on <a href="https://twitter.com/310mc1" target="_blank">Twitter</a>. Feedback is always welcome!</li>
<li><strong>Last Updated:</strong> 14 January 2025, Version 0.1</li>
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
<section class="storylist-box lore-focused light-read ryuseitai1 tetora1 chiaki1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_DDkxDA676739b3w6.webp?timestamp=1734818231697"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Hero Show
        </div>
        <a target="_blank" href="https://enstars-translates.dreamwidth.org/1179.html"><div>Start Reading</div><div class="tl-credit">Translation by enstars-translates</div></a>
    </article>
    <div class="three-wrapper">
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
                    <div class="synopsis-border"></div>
                    <div class="small-synopsis">
                        Getting sick of Ryuseitai's activities, Tetora dashes out of the AV room. Chiaki goes to look for him in the rain, only to suddenly collapse...!
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
                        Yumenosaki Era, Summer (June)
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
        <!--<li><i class="fa-solid fa-star ryuseitai-color"></i> First look into how Ryuseitai is like before they debut in a large-scaled performance (ex. learning about heroes or performing hero shows)</li>
        <li><i class="fa-solid fa-star chiaki"></i> Explores Chiaki's feelings and desires about Ryuseitai</li>
        <li><i class="fa-solid fa-star tetora"></i> Explores Tetora's feelings about Ryuseitai in the early days</li>
        <li><i class="fa-solid fa-star tetora"></i> Explores Tetora's feelings about Ryuseitai in the early days</li>
        <li><i class="fa-solid fa-star chiaki"></i> First story to show how easily sick Chiaki gets</li>-->
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read midori1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_Sg6786a464VOheJ2.webp?timestamp=1736877159309"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Pirate Festival
        </div>
        <a target="_blank" href="https://enstars-translates.dreamwidth.org/4610.html"><div>Start Reading</div><div class="tl-credit">Translation by enstars-translates</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Summer (July)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read midori1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_fBKoN26786a2dfb6.webp?timestamp=1736876773612"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Morning Practice
        </div>
        <a target="_blank" href="/morning_practice"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Spring
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
<section class="storylist-box light-read unstarred non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_D20Zol67673a59l6.webp?timestamp=1734818398300"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Tough Guy
        </div>
        <a target="_blank" href="/tough_guy"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Autumn (November)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused light-read ryuseitai1 chiaki1 tetora1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_ap8vv676738dcHd5.webp?timestamp=1734818019866"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Christmas Live
        </div>
        <a target="_blank" href="/christmas_live"><div>Start Reading</div><div class="tl-credit">Translation by 310mc & Mika Enstars</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Winter (December)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused light-read ryuseitai1 shinobu1 midori1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_x4967673a59Zfh33.webp?timestamp=1734818397696"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Strawberry Colored Holiday
        </div>
        <a target="_blank" href="https://enstars-translates.dreamwidth.org/20906.html"><div>Start Reading</div><div class="tl-credit">Translation by enstars-translates</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Spring (Post-graduation)
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
        <!--<li><i class="fa-solid fa-star midori"></i> Story is related to a strawberry-picking job, which becomes relevant in later stories</li>-->
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<!--
<section class="storylist-box unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_HnU3n67673b14Nr5.webp?timestamp=1734818583577"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Triumph of the Emperor
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper">
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<!--
<section class="storylist-box light-read unstarred unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_7N676739b3Efn4z2.webp?timestamp=1734818233642"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Hello Kitty Collab
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, TBA
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 midori1 shinobu1 chiaki1 kanata1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_5267673a59Jt8D82.webp?timestamp=1734818398868"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Supernova
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Summer (June)
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
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai-color"></i> The live show to kickstart Ryuseitai as idols and heroes</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Explores each unit member's feelings as part of Ryuseitai, their desires, hopes, prospects, etc…</li>
        <li><i class="fa-solid fa-star kanata"></i> First look into Kanata's motivations as part of Ryuseitai</li>
        <li><i class="fa-solid fa-star midori"></i> Explores Midori's feelings about accidentally becoming an idol</li>
        <li><i class="fa-solid fa-star tetora"></i> The moment Tetora starts to reflect on his initial feelings towards Ryuseitai and warm up to them</li>
        <li><i class="fa-solid fa-star shinobu"></i> Shows Shinobu's loyalty and intimacy with Ryuseitai</li>
        <li><i class="fa-solid fa-star chiaki"></i> Establishes Ryuseitai's ideals and goals as a hero unit, as told by Chiaki</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<!--
<section class="storylist-box light-read unstarred unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_iIWQ676738dcFuw4.webp?timestamp=1734818018783"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Beach Match
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Summer
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
        <li><i class="fa-solid fa-star shinobu"></i> Showcases Shinobu's ninja lifestyle and how Chiaki validates it</li> TBA
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused light-read ryuseitai1 shinobu1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_TN67673a59tKkqP2.webp?timestamp=1734818398768"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Scroll of the Elements
        </div>
        <a target="_blank" href="https://citrinesea.github.io/translation/scroll_of_the_elements/"><div>Start Reading</div><div class="tl-credit">Translation by citrinesea</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Autumn (September)
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
        <!--<li><i class="fa-solid fa-star ryuseitai-color"></i> Discusses the distances between the seniors and juniors within their life (adjust later)</li>-->
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read midori1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_9hB3n677e3bb4295.webp?timestamp=1736326069647"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Colorful Autumn
        </div>
        <a target="_blank" href="/colorful_autumn"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="MidoriRecc"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Souma"></span>
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
                        Yumenosaki Era, Autumn
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read chiaki1 midori1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_ik2k676739b34z44.webp?timestamp=1734818232185"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Holiday Party
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#Holiday%20Party"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="MidoriRecc"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Kaoru"></span>
                        <span class="charhead" character="Koga"></span>
                        <span class="charhead" character="Rei"></span>
                        <span class="charhead" character="Adonis"></span>
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
                        Yumenosaki Era, Winter (Before New Year)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused tetora1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_sMcQc3676739b306.webp?timestamp=1734818231751"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            The Four Beasts of Fistfighting
        </div>
        <div class="no-tl">Translation on Wayback<div class="tl-credit"><a target="_blank" href="https://healingbonds.dreamwidth.org/98674.html" class="unstyled">Translator has given permission</a></div></div>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Winter (February)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 midori1 chiaki1 shinobu1 kanata1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_djhmTg676738dc36.webp?timestamp=1734818020253"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Climax
        </div>
        <a target="_blank" href="/climax"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="KanataRecc"></span>
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="MidoriRecc"></span>
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        Yumenosaki Era, Winter (March, Graduation season)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Acts as a foundation for future stories set in ES!! Era</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Explores the confusing feelings each member has knowing their daily life as they know it is coming to an end and changing with graduation</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Shows a huge clash between various Ryuseitai members, and how they navigate clashing with one another because of differences</li>
        <li><i class="fa-solid fa-star midori"></i> An in-depth look into Midori as a character, his fears, lack of motivation up until this point, as well as his relationship with his family</li>
        <li><i class="fa-solid fa-star chiaki"></i> Hints at Chiaki's vulnerabilities and how he's affected by loneliness</li>
        <li><i class="fa-solid fa-star chiaki"></i> Explores Midori and Chiaki's relationship, and how much influence Chiaki has had in Midori's life</li>
        <li><i class="fa-solid fa-star tetora"></i> Exemplifies how different Tetora is from Chiaki, and hints that he'll be a different type of leader from him</li>
        <li><i class="fa-solid fa-star tetora"></i> A look into Tetora's insecurities and perceived weaknesses, and how he navigates them</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused light-read ryuseitai1 shinobu1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_U67673a597yYMUN1.webp?timestamp=1734818398124"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Sparkly First Years
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Spring (April)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused shinobu1 chiaki1 kanata1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_tpNUs6t676739b37.webp?timestamp=1734818232014"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Purple Wisterias of May
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Spring (May)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read tetora1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_xUR67673a59AW5v3.webp?timestamp=1734818398919"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Shooting Star Festival
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#Shooting%20Star%20Festival"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Summer
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused chiaki1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_F676738dc3kon871.webp?timestamp=1734818019862"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Crossroad
        </div>
        <a target="_blank" href="/crossroad"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        27 (Appears in 4 chapters)
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        Yumenosaki Era, Past (Spring, Chiaki's 2nd year)
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
        <li><i class="fa-solid fa-star chiaki"></i> A first look into Kuro and Chiaki's relationship in the past</li>
        <li><i class="fa-solid fa-star chiaki"></i> One of Chiaki's first acts as a hero</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read ryuseitai1 midori1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_cxn676739b3X4pD3.webp?timestamp=1734818230829"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Hero Game
        </div>
        <a target="_blank" href="/hero_game"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Spring
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused light-read chiaki1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_Ans4676739b3wm14.webp?timestamp=1734818229942"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Legendary Hero!
        </div>
        <a target="_blank" href="/legendary_hero"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Summer
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused kanata1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_bi676738dcUtLoR2.webp?timestamp=1734818020192"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Aquarium
        </div>
        <a target="_blank" href="/aquarium"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Summer
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
        <li><i class="fa-solid fa-star kanata"></i> Explores Kanata's relationship with Kaoru, Souma, and Madara</li>
        <li><i class="fa-solid fa-star kanata"></i> The first reveal that Kanata is a living god to his household is in his idol story, <a target="_blank" href="/when_i_drifted_ashore">When I Drifted Ashor</a>, and this story further explores that relationship between Kanata and his household</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused light-read ryuseitai1 midori1 chiaki1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_EFe67673a59H9kS3.webp?timestamp=1734818397065"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Sweet Halloween
        </div>
        <a target="_blank" href="/sweet_halloween"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Autumn (October)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read midori1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_HvtlBFr67673b147.webp?timestamp=1734818584275"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Zodiac: Senpai Turned Into A Dog!?
        </div>
        <a target="_blank" href="/senpai_turned_into_a_dog"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Winter (New Years)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read kanata1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_A5nhjAa677ec2887.webp?timestamp=1736360588788"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Zodiac 2: Sleeping Beauty
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#Zodiac%202"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="KanataRecc"></span>
                        <span class="charhead" character="Kaoru"></span>
                        <span class="charhead" character="Souma"></span>
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
                        Yumenosaki Era, Winter (New Years)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read chiaki1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_4v676738dcYzbsY2.webp?timestamp=1734818019755"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Boarding Live
        </div>
        <a target="_blank" href="https://otori.neocities.org/tls/enstars/directory"><div>Start Reading</div><div class="tl-credit">Translation by Bella</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
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
                        Yumenosaki Era, Winter
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused tetora1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_676738dcyOYrfDQ0.webp?timestamp=1734818019783"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Beasts
        </div>
        <a target="_blank" href="/beasts"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="Arashi"></span>
                        <span class="charhead" character="Madara"></span>
                        <span class="charhead" character="Ritsu"></span>
                        <span class="charhead" character="Midori"></span>
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
                        Yumenosaki Era, Winter (Early March, Graduation season)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read unstarred unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_ZaH7YF6786a2dfW6.webp?timestamp=1736876773059"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Hero Sentai Meteoranger
        </div>
        <a target="_blank" href="https://distortedheart.dreamwidth.org/4191.html"><div>Start Reading</div><div class="tl-credit">Translation by adriessene</div></a>
    </article>
    <div class="three-wrapper">
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
                        5
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        Yumenosaki Era, Spring
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Fun "fictional" story where Ryuseitai are actual Meteor Rangers in outer space, protecting the peace of the galaxy!</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Heroes VS Villains story between Ryuseitai VS Student Council (+ Wataru)</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Also has a retro shoot 'em up mini-game in Enstars Basic</span></li>
        <li><i class="fa-solid fa-star chiaki"></i> Eichi helping Chiaki make one of his dreams come true</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused chiaki1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_S676739b3PC8Hy01.webp?timestamp=1734818231949"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Gang
        </div>
        <a target="_blank" href="/gang"><div>Start Reading</div><div class="tl-credit">Translation by harmonyleaf & 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        7
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        Yumenosaki Era, Spring
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read midori1 tetora1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_Ly67673a59C3s6C2.webp?timestamp=1734818398146"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            School Festival 4
        </div>
        <a target="_blank" href="/school_festival_4"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="MidoriRecc"></span>
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
                        Yumenosaki Era, Spring (May)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> The ONLY event story Ryuseitai has that's set in Spring (early days)</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 midori1 shinobu1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_E676739b33Lwi811.webp?timestamp=1734818232473"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Orihime and Hikoboshi
        </div>
        <a target="_blank" href="/orihime_and_hikoboshi"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Summer (July)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Junior-focused story, where they are guided by Trickstar instead</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Juniors have an eye-opening experience about their dependance, and how that leads them to develop their own independancy</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Explores Ryuseitai member's feelings as part of the unit and how they're warming up to their place</li>
        <li><i class="fa-solid fa-star shinobu"></i> Displays Shinobu's strengths as a ninja and Ryuseitai member</li>
        <li><i class="fa-solid fa-star shinobu"></i> Explores Shinobu and Mao's relationship</li>
        <li><i class="fa-solid fa-star midori"></i> Establishes Midori and Subaru's relationship</li>
        <li><i class="fa-solid fa-star shinobu"></i> Gives insight about the Ninja Association</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused kanata1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_zN8he676738dcDC5.webp?timestamp=1734818019663"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Comic World
        </div>
        <a target="_blank" href="/comic_world"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Summer
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
        <li><i class="fa-solid fa-star kanata"></i> Showcases what being a hero means to Kanata during his early days in his third year</li>
        <li><i class="fa-solid fa-star kanata"></i> Explores Keito and Kanata's relationship in relation to the War</li>
        <li><i class="fa-solid fa-star kanata"></i> A display of Kanata's mindset and philosophy about the world, and how he wishes to repay kindness with kindness</li>
        <li><i class="fa-solid fa-star kanata"></i> Rare Kanata interactions with Kuro and Ritsu</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read chiaki1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_Nx676738dcva1c52.webp?timestamp=1734818020603"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Buddy
        </div>
        <a target="_blank" href="/buddy"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
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
                        Yumenosaki Era, Summer
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> A light-hearted, silly story of some Ryuseitai members during summer break</li>
        <li><i class="fa-solid fa-star chiaki"></i> Chiaki learning that he can spend his time with his Ryuseitai juniors if he wants to</li>
        <li><i class="fa-solid fa-star chiaki"></i> A little bit of Chiaki's family mentioned</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused chiaki1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_67673a597GMVaYH0.webp?timestamp=1734818398067"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Rainbow
        </div>
        <a target="_blank" href="https://kotofucius.github.io/2018/saga1-rainbow/"><div>Start Reading</div><div class="tl-credit">Translation by kotofucius</div></a>
    </article>
    <div class="three-wrapper">
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
                        51<!--TBA-->
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        Yumenosaki Era, Spring & Summer
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read shinobu1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_xfO3c677e4600LH5.webp?timestamp=1736328705080"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Autumn Forest
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#Autumn%20Forest"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ShinobuRecc"></span>
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Nazuna"></span>
                        <span class="charhead" character="Yuta"></span>
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
                        Yumenosaki Era, Autumn
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read midori1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_uY676739b3eYjAj2.webp?timestamp=1734818231866"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            <small>First Dreams:</small> Hurray for a Normal Day!
        </div>
        <a target="_blank" href="/hurray_normal_day"><div>Start Reading</div><div class="tl-credit">Translation by Peace</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Winter (January)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused chiaki1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_fCJr67673a597V44.webp?timestamp=1734818398940"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Saga
        </div>
        <a target="_blank" href="https://hyenahunt.tumblr.com/post/682683575976574976/translation-sagaclashing-rebirth-live"><div>Start Reading</div><div class="tl-credit">Translation by kotofucius</div></a>
    </article>
    <div class="three-wrapper">
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
                        51
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        Yumenosaki Era, Winter
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read midori1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_Iv9RaX676738dcw6.webp?timestamp=1734818019609"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Hot & Elegant Chocolat Fes
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#Hot%20&%20Elegant%20Chocolat%20Fes"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Winter (February)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read shinobu1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_kfYw677e85ec7Od4.webp?timestamp=1736345069702"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Chuunibyou
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#Chuunibyou"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ShinobuRecc"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Nazuna"></span>
                        <span class="charhead" character="Kaoru"></span>
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
                        Yumenosaki Era, Winter
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 chiaki1 kanata1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_bcBJiw676739b3A6.webp?timestamp=1734818231785"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Meteor Impact
        </div>
        <a target="_blank" href="/meteor_impact"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                    <div class="synopsis-border"></div>
                    <div class="small-synopsis">
                        During his first year in school, Chiaki goes to clean the pool at night after Ryuseitai caused problems once again. There, he meets Kanata for the first time...
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
                        Yumenosaki Era, Present (Winter) — Past (Chiaki&Kanata's 1st/2nd year)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<!--
<section class="storylist-box light-read kanata1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_TLN0U67673a59bz5.webp?timestamp=1734818398797"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Toryumon
        </div>
        <div class="no-tl">Translation available, use search terms</div>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Autumn
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read ryuseitai1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_48XvO67673a590f5.webp?timestamp=1734818396609"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Study Heroes
        </div>
        <a target="_blank" href="/study_heroes"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Autumn
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read ryuseitai1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_nOy6786bec4KJOk3.webp?timestamp=1736883915156"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Management Stories
        </div>
        <a target="_blank" href="/management_story"><div>Start Reading</div><div class="tl-credit">Translation by 310mc & citrinesea</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era, Spring
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Recommended because early Spring timeline stories for Ryuseitai are rare yet important!</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused light-read ryuseitai1 chiaki1 kanata1 tetora1 midori1 shinobu1 unit-only non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_3CuiY6780e062lC5.webp?timestamp=1736499302115"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Idol Story (1, 2, and 3)
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/featureidol"><div>Start Reading</div><div class="tl-credit">Translations on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
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
                        Ten 1-chaptered stories
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        ES!! Era Year 1, Spring
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_3CuiY6780e062lC5.webp?timestamp=1736499302115"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            ES!! Era 1st Main Story
        </div>
        <div class="no-tl">Translation available in the English version of Enstars!! music</div>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Rinne"></span>
                        <span class="charhead" character="Niki"></span>
                        <span class="charhead" character="Kohaku"></span>
                        <span class="charhead" character="HiMERU"></span>
                        <span class="charhead" character="Hiiro"></span>
                        <span class="charhead" character="Aira"></span>
                        <span class="charhead" character="Mayoi"></span>
                        <span class="charhead" character="Tatsumi"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        228 (Appears in 14 chapters only)
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        ES!! Era Year 1, Summer (July-August)
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        2020/4/11 - 2020/5/11
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai-color"></i> <b>Full translation is only available in the English version of Ensemble Stars!!</b></li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> A translation of <a href="/es2_mainstory/ch123_124" target="_blank">a few chapters some appear in</a>.</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 shinobu1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_676739b3CwB2Nml0.webp?timestamp=1734818231415"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Motor Show
        </div>
        <a target="_blank" href="/motor_show"><div>Start Reading</div><div class="tl-credit">Translation by 310mc & Peace & Whisper</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        ES!! Era Year 1, Summer (Early September)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<!--
<section class="storylist-box light-read tetora1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_U5BbAt67673a59L6.webp?timestamp=1734818397169"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Schrödinger's Monster
        </div>
        <div class="no-tl">Translation available in the English version of Enstars!! music</div>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
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
                        ES!! Era Year 1, Summer
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<!--
<section class="storylist-box light-read shinobu1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_OPxGAd676738dcJ6.webp?timestamp=1734818019706"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Emergency! Secret Mission
        </div>
        <div class="no-tl">Translation available in the English version of Enstars!! music</div>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="ShinobuRecc"></span>
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
                        ES!! Era Year 1, Summer
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read midori1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_tax676738dcuVde3.webp?timestamp=1734818020657"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Dollhouse
        </div>
        <a target="_blank" href="/dollhouse"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="MidoriRecc"></span>
                        <span class="charhead" character="Mika"></span>
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Tsumugi"></span>
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
                        ES!! Era Year 1, Summer
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read kanata1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_5L0b667673a59RW5.webp?timestamp=1734818398743"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Summer Snow
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#Summer%20Snow"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="KanataRecc"></span>
                        <span class="charhead" character="Ibara"></span>
                        <span class="charhead" character="Rei"></span>
                        <span class="charhead" character="Hinata"></span>
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
                        ES!! Era Year 1, Summer
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        2020/8/14
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read unstarred non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_4Hf676738dcuJmb3.webp?timestamp=1734818020006"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Always Hold a Heroic Heart
        </div>
        <a target="_blank" href="/always_hold_a_heroic_heart"><div>Start Reading</div><div class="tl-credit">Translation by 310mc & TsubasaFL</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 1, Summer
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused light-read tetora1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_H676738dc2Uf6wy1.webp?timestamp=1734818020748"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Turn of the Century Wars
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#Turn%20of%20the%20Century%20Wars"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 1, Summer (Early August)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 midori1 chiaki1 kanata1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_uj8d676738dcsGU4.webp?timestamp=1734818020668"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Comet Show
        </div>
        <a target="_blank" href="/comet_show"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 1, Summer (Late September)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read tetora1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_gKmY6gu67673a597.webp?timestamp=1734818398833"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Spring Bed
        </div>
        <a target="_blank" href="/spring_bed"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="Subaru"></span>
                        <span class="charhead" character="Hajime"></span>
                        <span class="charhead" character="Natsume"></span>
                        <span class="charhead" character="Jin"></span>
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
                        ES!! Era Year 1, Spring
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 chiaki1 kanata1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_S367673a59lb8Zl2.webp?timestamp=1734818398750"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Submarine
        </div>
        <a target="_blank" href="/submarine"><div>Start Reading</div><div class="tl-credit">Translation by 310mc & verdantgrove</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 1, Winter (Mid November)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read shinobu1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_C6d676739b34kxj3.webp?timestamp=1734818232554"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Ninja Clan
        </div>
        <a target="_blank" href="/ninja_clan"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 1, Summer (Early September)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused unstarred non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_dJS67673a59shwa3.webp?timestamp=1734818398664"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            SS Finals
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#SS%20Finals"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Eichi"></span>
                        <span class="charhead" character="Wataru"></span>
                        <span class="charhead" character="Hokuto"></span>
                        <span class="charhead" character="Subaru"></span>
                        <span class="charhead" character="Madara"></span>
                        <span class="charhead" character="Rinne"></span>
                        <span class="charhead" character="Keito"></span>
                        <span class="charhead" character="Natsume"></span>
                        <span class="charhead" character="Tomoya"></span>
                        <span class="charhead" character="Hiiro"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        64 (Appears in 11 chapters)
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        ES!! Era Year 1, Winter (Mid December-End of Year)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused kanata1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_u17j676739b3erX4.webp?timestamp=1734818232365"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Myriad of Colors and Flowers
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#Myriad%20of%20Colors%20and%20Flowers"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 1, Autumn (End of October)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused shinobu1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_7sOO676739b32cd4.webp?timestamp=1734818230604"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            MIRAGE
        </div>
        <a target="_blank" href="https://twilightmalachite.tumblr.com/mirage"><div>Start Reading</div><div class="tl-credit">Translation by Mika Enstars</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 1, Winter (Early January)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 midori1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_cAc88hr676739b37.webp?timestamp=1734818232218"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            High and Low
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#High%20and%20Low"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="MidoriRecc"></span>
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="Mitsuru"></span>
                        <span class="charhead" character="Hajime"></span>
                        <span class="charhead" character="Hitsugi"></span>
                        <span class="charhead" character="NEGI"></span>
                        <span class="charhead" character="Tomoya"></span>
                        <span class="charhead" character="Hinata"></span>
                        <span class="charhead" character="Tori"></span>
                        <span class="charhead" character="Sora"></span>
                        <span class="charhead" character="Yuta"></span>
                        <span class="charhead" character="Hiiro"></span>
                        <span class="charhead" character="Tsukasa"></span>
                        <span class="charhead" character="Shinobu"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        36
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        ES!! Era Year 1, Autumn (Late October)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 shinobu1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_AAgyjgq676738dc7.webp?timestamp=1734818020676"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Black Jack
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#Black%20Jack"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ShinobuRecc"></span>
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="Mayoi"></span>
                        <span class="charhead" character="Natsume"></span>
                        <span class="charhead" character="Souma"></span>
                        <span class="charhead" character="Hitsugi"></span>
                        <span class="charhead" character="NEGI"></span>
                        <span class="charhead" character="Arashi"></span>
                        <span class="charhead" character="Mika"></span>
                        <span class="charhead" character="Tori"></span>
                        <span class="charhead" character="Mao"></span>
                        <span class="charhead" character="Yuzuru"></span>
                        <span class="charhead" character="Madara"></span>
                        <span class="charhead" character="Gatekeeper"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        38
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        ES!! Era Year 1, Winter (Early-Late December)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 shinobu1 chiaki1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_PU67673a59bf4L42.webp?timestamp=1734818398080"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Supervillain
        </div>
        <a target="_blank" href="/supervillain"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 1, Winter (Mid March)
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
        <div class="label">Key Points <!--<span class="tl-credit" style="padding-left:0.3rem;">Scroll for full list!</span>--></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai-color"></i> The story to resolve Ryuseitai's tension and complications across the 1st ES!! Era year, as well as start a whole new era for them (New unit formation and direction)</li>
        <li><i class="fa-solid fa-star tetora"></i> Deep dive into Tetora's character, his fears, wishes to grow stronger, backstory, determination as a hero, etc…</li>
        <li><i class="fa-solid fa-star tetora"></i> All of Tetora's efforts coming to fruition, like his former Ryuseitai-N juniors asking for his help, Tetora confidently acting as a leader and executing his own plan, etc…</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Explores Ryuseitai's rebellion against their agency, as well as how they resolve to survive as part of ES.</li>
        <li><i class="fa-solid fa-star chiaki"></i> Chiaki opening up to Tetora and telling him about his past in Ryuseitai</li>
        <li><i class="fa-solid fa-star shinobu"></i> Shinobu's ninja expertise coming into use in a real life situation</li>
        <li><i class="fa-solid fa-star shinobu"></i> Ryuseitai's, especially Chiaki's, unwavering trust in Shinobu — as well as Shinobu's loyalty to Ryuseitai</li>
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read tetora1 midori1 shinobu1 chiaki1 kanata1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_ertqT6786b0dcn05.webp?timestamp=1736880354879"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Ryuseitai Feature Scout 5* Stories
        </div>
        <a target="_blank" href="/featurescout"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 1
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused kanata1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_SaWUvt676738dcQ6.webp?timestamp=1734818021141"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Altered
        </div>
        <a target="_blank" href="https://twilightmalachite.tumblr.com/altered"><div>Start Reading</div><div class="tl-credit">Translation by Mika Enstars</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 1, Winter (Mid March)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read chiaki1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_N52Do67673b143r5.webp?timestamp=1734818583835"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Wedding March!
        </div>
        <a target="_blank" href="/wedding_march"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="Jun"></span>
                        <span class="charhead" character="Nagisa"></span>
                        <span class="charhead" character="Tatsumi"></span>
                        <span class="charhead" character="Makoto"></span>
                        <span class="charhead" character="Shu"></span>
                        <span class="charhead" character="Yuzuru"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Adonis"></span>
                        <span class="charhead" character="Izumi"></span>
                        <span class="charhead" character="Eichi"></span>
                        <span class="charhead" character="Akiomi"></span>
                        <span class="charhead" character="Jin"></span>
                        <span class="charhead" character="Hajime"></span>
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
                        ES!! Era Year 1, Autumn (Early November)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused light-read ryuseitai1 unit-only non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_uXT674676739b356.webp?timestamp=1734818232353"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Parallel World
        </div>
        <a target="_blank" href="/parallel_world"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 2, Spring (Post-Supervillain)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> More coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read ryuseitai1 midori1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_ksStxbr67673b147.webp?timestamp=1734818583622"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Tropical
        </div>
        <a target="_blank" href="/tropical"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 2, Spring (April)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused shinobu1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_3K676738dcZTVRA2.webp?timestamp=1734818020452"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Atlantis
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#Atlantis"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ShinobuRecc"></span>
                        <span class="charhead" character="Tori"></span>
                        <span class="charhead" character="Wataru"></span>
                        <span class="charhead" character="Eichi"></span>
                        <span class="charhead" character="Yuzuru"></span>
                        <span class="charhead" character="Mao"></span>
                        <span class="charhead" character="Souma"></span>
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
                        ES!! Era Year 1, Winter (February-March)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused kanata1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_FXoM676738dcpbD4.webp?timestamp=1734818021024"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            ABYSS
        </div>
        <a target="_blank" href="/abyss"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 1, Winter (February) + Past, childhood days
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused shinobu1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_hb676738dcvtYzp2.webp?timestamp=1734818020544"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            2x2
        </div>
        <a target="_blank" href="https://twilightmalachite.tumblr.com/2x2"><div>Start Reading</div><div class="tl-credit">Translation by Mika Enstars</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ShinobuRecc"></span>
                        <span class="charhead" character="Yuta"></span>
                        <span class="charhead" character="Hinata"></span>
                        <span class="charhead" character="Nagisa"></span>
                        <span class="charhead" character="Ibara"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        27
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        ES!! Era Year 1, Winter-Early Spring
                    </div>
                </div>
                <div class="info-item three">
                    <div class="label">
                        Release Date
                    </div>
                    <div class="value">                 
                        2023/9/30
                    </div>
                </div>
            </div>
        </div>
    </div>
    <article class="story-summary">
        <div class="label">Key Points <span class="tl-credit" style="padding-left:0.3rem;"></span></div>
        <ul class="key-points">
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read kanata1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_Vyi678043ab1HQt3.webp?timestamp=1736459186386"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Banquet Beneath the Clouded Moon
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#Banquet%20Beneath%20the%20Clouded%20Moon"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="KanataRecc"></span>
                        <span class="charhead" character="Rinne"></span>
                        <span class="charhead" character="Yuta"></span>
                        <span class="charhead" character="Hiyori"></span>
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="Niki"></span>
                        <span class="charhead" character="Jun"></span>
                        <span class="charhead" character="Sora"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        6
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        ES!! Era Year 1, Autumn (October)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read unstarred non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_X676739b3pFTgOY1.webp?timestamp=1734818231098"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            The Promise To Train
        </div>
        <a target="_blank" href="/the_promise_to_train"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="TetoraRecc"></span>
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
                        ES!! Era Year 1, Winter
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused ryuseitai1 tetora1 chiaki1 kanata1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_Bou67673a59kIg93.webp?timestamp=1734818398999"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Stella Maris
        </div>
        <a target="_blank" href="/stella_maris"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era Year 2, Spring (May)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read ryuseitai1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_0vdHE677d9c77Xc5.webp?timestamp=1736285306001"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Ryuseitai Album TRIP
        </div>
        <a target="_blank" href="/ryuseitai_album_trip"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era (All-leaders formation)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read tetora1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_gjesmX676738dc96.webp?timestamp=1734818020533"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Dragon's Head
        </div>
        <a target="_blank" href="https://enstarsmasterlist.github.io/scoutevent#Dragon's%20Head"><div>Start Reading</div><div class="tl-credit">Translation on the masterlist</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="Kuro"></span>
                        <span class="charhead" character="Tomoya"></span>
                        <span class="charhead" character="Eichi"></span>
                        <span class="charhead" character="Hiiro"></span>
                        <span class="charhead" character="Koga"></span>
                        <span class="charhead" character="Adonis"></span>
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
                        ES!! Era Year 1, Winter (March)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused chiaki1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_n67804781lQXTJo1.webp?timestamp=1736460163821"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            VS★GOURMET
        </div>
        <a target="_blank" href="/vs_gourmet"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="ChiakiRecc"></span>
                        <span class="charhead" character="Mitsuru"></span>
                        <span class="charhead" character="Hiyori"></span>
                        <span class="charhead" character="Raika"></span>
                        <span class="charhead" character="Ritsu"></span>
                        <span class="charhead" character="Tetora"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="Shinobu"></span>
                        <span class="charhead" character="Kanata"></span>
                        <span class="charhead" character="Mayoi"></span>
                        <span class="charhead" character="Aira"></span>
                        <span class="charhead" character="Tatsumi"></span>
                        <span class="charhead" character="Akiomi"></span>
                        <span class="charhead" character="Jin"></span>
                        <span class="charhead" character="Nice"></span>
                        <span class="charhead" character="Seiya"></span>
                        <span class="charhead" character="Jun"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        29
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        ES!! Era Year 2, Spring (Late May)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read tetora1 non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_s677e84b2ld7nwN1.webp?timestamp=1736344758994"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Dominant
        </div>
        <a target="_blank" href="https://citrinesea.github.io/translation/dominant/"><div>Start Reading</div><div class="tl-credit">Translation by citrinesea</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="Keito"></span>
                        <span class="charhead" character="Madara"></span>
                        <span class="charhead" character="Leo"></span>
                        <span class="charhead" character="Adonis"></span>
                        <span class="charhead" character="Natsume"></span>
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
                        ES!! Era Year 2, Spring (April)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read lore-focused tetora1 ryuseitai1 kanata1 shinobu1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_eoam677e7f3csbW4.webp?timestamp=1736343361776"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            WILDLAND
        </div>
        <a target="_blank" href="/wildland"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
        <div class="info-area">
            <div class="info">
                <div class="info-item characters">
                    <div class="value">
                        <span class="charhead" character="TetoraRecc"></span>
                        <span class="charhead" character="Midori"></span>
                        <span class="charhead" character="ShinobuRecc"></span>
                        <span class="charhead" character="Chiaki"></span>
                        <span class="charhead" character="KanataRecc"></span>
                        <span class="charhead" character="Hiiro"></span>
                    </div>
                </div>
                <div class="info-item one">
                    <div class="label">
                        Chapters
                    </div>
                    <div class="value">
                        13
                    </div>
                </div>
                <div class="info-item two">
                    <div class="label">
                        Season
                    </div>
                    <div class="value">
                        ES!! Era Year 2, Spring & Summer (May-June)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read unstarred non-unit">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_l6786c2854WfggD1.webp?timestamp=1736884874976"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Birthday Stories
        </div>
        <a target="_blank" href="/birthday_story"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era and ES!! Era (Year 1 & 2)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused light-read unstarred non-unit unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_l6786c2854WfggD1.webp?timestamp=1736884874976"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Mini Talks
        </div>
        <a target="_blank" href="/minitalk"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        Yumenosaki Era and ES!! Era
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box lore-focused light-read ryuseitai1 unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_DaekmJ6786a81996.webp?timestamp=1736878111823"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Dokisuta Ryuseitai
        </div>
        <a target="_blank" href="/dokisuta_ryuseitai"><div>Start Reading</div><div class="tl-credit">Translation by 310mc</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era (Post-Supervillain & Ryuseitai Power Up)
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<section class="storylist-box light-read unstarred non-unit unit-only">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="https://f005.backblazeb2.com/file/reitoouji/ro_DdAdYO6786b0dcb6.webp?timestamp=1736880355348"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            Oshi Room
        </div>
        <a target="_blank" href="https://citrinesea.github.io/translation/oshi_room_2024/"><div>Start Reading</div><div class="tl-credit">Translation by 310mc & citrinesea</div></a>
    </article>
    <div class="three-wrapper">
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
                        ES!! Era
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
<!-- story box end -->

<!-- story box start -->
<!--
<section class="storylist-box">
    <article class="top-section">
    <figure class="storylist-image">
        <img src="TBA"  class="storylist-image">
    </figure>
    </article>
    <article class="second-section">
        <div class="title">
            TBA
        </div>
        <a target="_blank" href="TBA"><div>Start Reading</div><div class="tl-credit">TBA</div></a>
    </article>
    <div class="three-wrapper">
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
        <li><i class="fa-solid fa-star ryuseitai-color"></i> Coming soon! List is currently still in its initial release</li>
        </ul>
    </article>
</section>
-->
<!-- story box end -->
</section>

<div class="navigation2">
<a href="/" title="Home" class="home-button" target="_blank"><i class="fa fa-home"></i></a>
<a href="/ryuseitaitimeline" title="Story Timeline" target="_blank"><i class="fa-regular fa-clock"></i></a>
<a href="#top" class="top-arrow" title="Back to Top"><i class="fa fa-arrow-up"></i></a>
</div>