---
title: "Possible Translation Directory"
date: 2015-4-10 9:00:00
categories:
- [Uncategorized]
tags:
- Not Translation
description: "Possible Translation Directory"
hidden: true
---

<link href="https://necolas.github.io/normalize.css/7.0.0/normalize.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
<script src="https://unpkg.com/isotope-layout@3/dist/isotope.pkgd.min.js"></script>
<script src="https://static.tumblr.com/p0knose/FpAp5c11c/magnusthemes.combofilters.js"></script>
<script>
$(document).ready(function() {var $container = $(".grid"); // the container with all the elements to filter inside
var filters = {}; //should be outside the scope of the filtering function
/* --- read the documentation on isotope.metafizzy.co for more options --- */
var $grid = $container.isotope({
itemSelector: ".tl", // the elements to filter
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
.header {
    display: none;
}

.main {
    width: calc(100% - 20px);
}

.main-inner {
    border-radius: initial;
    box-sizing: border-box;
    width: 100%;
    margin-right: 0;
}

.main-inner .post-block {
    box-shadow: none;
}

.footer-inner {
    padding-left: 0px;
}

body {
    background: var(--content-bg-color);
}

.grid {
    display: flex;
    flex-flow: row wrap;
}

.tl {
    box-sizing: border-box;
    width: 400px;
    height: 360px;
}

.box {
    display: flex;

}

.left {
    height: 101%;
    width: 70%;
    flex: 1 0 100px;
}

.left img {
    max-width: 101%;
    object-fit: cover;
    height: 300px;
}

.right {
    height: 101%;
    width: 100%;
    padding: 15px;
    flex: 3 3 250px;
}

.shift-left {
    object-position: 80%;
}

.shift-right {
    object-position: 20%;
}
</style>

<ul class="filter option-set exclusive" data-filter-group="group1">
    <li><a href="#" data-filter-value="" class="selected">All</a></li>
    <li><a href="#" data-filter-value=".event">Filter 1</a></li>
    <li><a href="#" data-filter-value=".scout">Filter 2</a></li>
</ul>

<ul class="filter option-set" data-filter-group="group2">
    <li><a href="#" data-filter-value="" class="selected">All</a></li>
    <li><a href="#" data-filter-value=".g2f1">Filter 1</a></li>
    <li><a href="#" data-filter-value=".g2f2">Filter 2</a></li>
</ul>

<section class="grid">
    <article class="tl event">
        <article class="box">
            <div class="left">
                <img src="/img/es/eventstory/climax/midoribcgframe_300px.jpg" class="shift-left">
            </div>
            <div class="right">
                <h2>Climax</h2>
                <i>Akira</i>
                <p><b>Characters: </b>Tetora, Tori, Subaru, Hokuto, Makoto, Koga, Mao, Keito, Kuro</p>
                <a class="second" href="https://ensemble-stars.fandom.com/wiki/Hierarchy">Wiki</a>
            </div>
        </article>
    </article>
    <article class="tl scout">
        <article class="box">
            <div class="left">
                <img src="https://f005.backblazeb2.com/file/reitoouji/ro_6756fd83voAESG50.webp?timestamp=1733754251916" class="stories-image">
            </div>
            <div class="right">
                <h2>Climax</h2>
                <i>Akira</i>
                <p><b>Characters: </b>Tetora, Tori, Subaru, Hokuto, Makoto, Koga, Mao, Keito, Kuro</p>
                <a class="second" href="https://ensemble-stars.fandom.com/wiki/Hierarchy">Wiki</a>
            </div>
        </article>
    </article>
    <article class="tl event">
        <article class="box">
            <div class="left">
                <img src="https://f005.backblazeb2.com/file/reitoouji/ro_gkazX67709a61b95.webp?timestamp=1735432807695" class="stories-image">
            </div>
            <div class="right">
                <h2>Climax</h2>
                <i>Akira</i>
                <p><b>Characters: </b>Tetora, Tori, Subaru, Hokuto, Makoto, Koga, Mao, Keito, Kuro</p>
                <a class="second" href="https://ensemble-stars.fandom.com/wiki/Hierarchy">Wiki</a>
            </div>
        </article>
    </article>
    <article class="tl scout">
        <article class="box">
            <div class="left">
                <img src="/img/es/eventstory/cometshow/chiakibcgframe_300px.jpg" class="stories-image">
            </div>
            <div class="right">
                <h2>Climax</h2>
                <i>Akira</i>
                <p><b>Characters: </b>Tetora, Tori, Subaru, Hokuto, Makoto, Koga, Mao, Keito, Kuro</p>
                <a class="second" href="https://ensemble-stars.fandom.com/wiki/Hierarchy">Wiki</a>
            </div>
        </article>
    </article>
    <article class="tl event">
        <article class="box">
            <div class="left">
                <img src="https://f005.backblazeb2.com/file/reitoouji/ro_jY676719895rCIR2.webp?timestamp=1734809998875" class="shift-right">
            </div>
            <div class="right">
                <h2>Climax</h2>
                <i>Akira</i>
                <p><b>Characters: </b>Tetora, Tori, Subaru, Hokuto, Makoto, Koga, Mao, Keito, Kuro</p>
                <a class="second" href="https://ensemble-stars.fandom.com/wiki/Hierarchy">Wiki</a>
            </div>
        </article>
    </article>
</section>

