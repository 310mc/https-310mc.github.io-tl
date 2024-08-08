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
 -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="shortcut icon" href="{favicon}">
<meta name="description" content="{MetaDescription}"/>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Karla:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500;1,600;1,700&family=Open+Sans:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">
<link href="https://necolas.github.io/normalize.css/7.0.0/normalize.css" rel="stylesheet">
<link rel="stylesheet" href="/cssfolder/recclist.css">
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

    .filters-list {
    width: 100%;
    position: sticky;
    top: 0px;
    background: var(--content-bg-color);
    z-index: 990;
    padding: 0.01rem 0rem;
    padding-right: 1rem;
    font-size: 13px;
    }

    .filters-list li {
    list-style-type: none;
    display: inline-block;
    }

    .filters-list li a {
    margin: 0 5px;
    }
    
    .filters-title {
        font-weight: 700;
        text-transform: uppercase;
    }

    .selected {
        font-weight: 700;
        color: #E66B6B;
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

<section id="container">
<main id="mainbox">
<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/5/5b/Reverb%E2%98%85Stella_Maris_Crossing_the_Sea%27s_Horizon_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Hero Show</a>
            </div>
        </article>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Pirate Festival</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Morning Practice</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Tough Guy</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Crash Course</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Christmas Live</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Strawberry Colored Holiday</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Triumph of the Emperor</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Hello Kitty Collab</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Supernova</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Beach Match</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Scroll of the Elements</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Holiday Party</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">The Four Beasts of Fistfighting</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Climax</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Sparkly First Years</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Purple Wisterias of May</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Shooting Star Festival</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Crossroad</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Hero Game</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Legendary Hero!</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Aquarium</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Sweet Halloween</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Zodiac – Senpai Turned Into A Dog!?</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Beasts</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Boarding Live</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">2018 April Fools Story</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Gang</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">School Festival 4</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Orihime and Hikoboshi</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Buddy</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Comic World</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Rainbow</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">First Dreams – Hurray for a Normal Day!</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Saga</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Hot & Elegant Chocolat Fes</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Meteor Impact</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Toryumon</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Study Heroes</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box tetora1 midori1 shinobu1 chiaki1 kanata1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Management Stories</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box chiaki1 kanata1 tetora1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Climax</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box chiaki1">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title story-recommend">
                <a target="_blank" href="">Shooting Star Festival</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Midori"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="">Orihime and Hikoboshi</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/6/66/Baton_Pass%21_Repayment_Festival_of_Tears_and_Bonds_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 23 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                    <span class="charhead" character="Kanata"></span>
                    <span class="charhead" character="Tetora"></span>
                    <span class="charhead" character="Chiaki"></span>
                    <span class="charhead" character="Midori"></span>
                    <span class="charhead" character="Shinobu"></span>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!           
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/climax" target="_blank">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box midori1 chiaki1 recommended">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title">
                <a target="_blank" href="/hero_game">Hero Game</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/b/b5/%28Negligent%29_Midori_Takamine_Mini.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Idol Story - 1 Chapter</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                <a href="/categories/Enstars/Chiaki" character="Chiaki"></a>
                <a href="/categories/Enstars/Kanata" character="Kanata"></a>
                <a href="/categories/Enstars/Tetora" character="Tetora"></a>
                <a href="/categories/Enstars/Midori" character="Midori"></a>
                <a href="/categories/Enstars/Shinobu" character="Shinobu"></a>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/hero_game">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->

<!-- box start -->
<section class="fanfic-box unit-only">
    <article class="upper-section">
        <article class="title-top">
            <!-- fanfic title -->
            <div class="title story-recommend">
                <a target="_blank" href="/sweet_halloween">Sweet Halloween</a>
            </div>
        </article>
        <figure class="fanfic-image">
            <!-- fanfic image -->
            <img src="https://static.wikia.nocookie.net/ensemble-stars/images/1/10/Lots_of_Monsters%E2%98%86Sweet_Halloween_Banner.png"  class="fanfic-image">
        </figure>
        <article class="title-author">
            <!-- fanfic author -->
            <div class="author">Event Story - 24 Chapters</div>
        </article>
    </article>    
    <article class="ship-and-fandom">
        <!-- ship -->
        <div class="ship"><div class="characters">
                <div class="value">
                <a href="/categories/Enstars/Chiaki" character="Chiaki"></a>
                <a href="/categories/Enstars/Kanata" character="Kanata"></a>
                <a href="/categories/Enstars/Tetora" character="Tetora"></a>
                <a href="/categories/Enstars/Midori" character="Midori"></a>
                <a href="/categories/Enstars/Shinobu" character="Shinobu"></a>
                </div>
            </div></div>
    </article>
    <article class="fanfic-summary">
        <!-- fanfic summary -->
        PLACEHOLDER TEXT, TO BE ADDED!!         
    </article>
    <article class="fanfic-links">
        <!-- fic links -->
        start reading <a href="/sweet_halloween">here <i class="fa fa-arrow-right"></i></a>
    </article>
    <article class="fanfic-info">
        <!-- details -->
        <li><b>season:</b> ! era, spring</li>
        <li><b>release date:</b> 2017/4/14</li>
    </article>
</section>
<!-- box end -->
</main>
</section>

<div class="navigation2">
<a href="/" title="Home"><i class="fa fa-home"></i></a>
<a href="#top" class="top-arrow" title="Back to Top"><i class="fa fa-arrow-up"></i></a>
</div>

<div title="Code Credits! Thank you!" style="position:fixed;bottom:3rem;right:2rem;font-size:.85rem"><a target="_blank" href="https://southcodes.tumblr.com/">SC</a></div>