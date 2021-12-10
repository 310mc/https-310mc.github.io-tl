<style>

.stories {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 0.5em;
}
.story {
    position: relative;
    border-radius: 0.25em;
    overflow: hidden;
}

.stories a:hover{
    color: white;
}

.story:hover img {
    transform: scale(1.05);
}
.story:hover .storyName {
    transform: translate(0, 0);
}
.story:hover .storyName .read {
    transform: translate(0, 0);
}
.storyName {
    transform: translate(0, 0);
}
.image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: 0.2s ease;
    margin: 0;
}
.storyName {
    font-size: 0.9em;
    font-weight: 700;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    background: linear-gradient(to bottom, transparent 0, #000000a3 90%);
    color: #fff;
    position: absolute;
    padding: 5em 0.75em 0.75em;
    width: 100%;
    bottom: 0;
    left: 0;
    transition: 0.2s ease;
    transform: translate(0, 2.3em);
}
.storyName .read {
       margin-top: 0.25em;
       font-size: 0.85em;
       background: black;
       color: white;
       padding: 0.5em 1.25em;
       height: 2.25em;
       border-radius: 0.25em;
       width: 100%;
       text-align: center;
       transition: 0.2s ease;
       transform: translate(0, 1em);
   }
   .storyName .read:before {
       content: "Read";
   }

   .storyName .read.soon {
       opacity: 0.5;
       pointer-events: none;
       &:before {
           content: "Soon!";
       }
   }

   .storyName .read:not(.soon):hover {
       color: #f1c755;
   }
</style>
<div class="stories">
    <div class="story">
        <div class="image">
            <img
                src="/img/es/eventstory/climax/midoribcgframe.jpg"
                alt="Climax"
            />
        </div>
        <a href="/climax" class="storyName">
            <span>Climax</span>
            <span class="read"></span>
        </a>
    </div>
    <div class="story">
        <div class="image">
            <img
                src="/img/es/eventstory/climax/midoribcgframe.jpg"
                alt="Climax"
            />
        </div>
        <a href="/climax" class="storyName">
            <span>Climax</span>
            <span class="read"></span>
        </a>
    </div>
    <div class="story">
        <div class="image">
            <img
                src="/img/es/eventstory/climax/midoribcgframe.jpg"
                alt="Climax"
            />
        </div>
        <a href="/climax" class="storyName">
            <span>Climax</span>
            <span class="read"></span>
        </a>
    </div>
    <div class="story">
        <div class="image">
            <img
                src="/img/es/eventstory/climax/midoribcgframe.jpg"
                alt="Climax"
            />
        </div>
        <a href="/climax" class="storyName">
            <span>Climax</span>
            <span class="read"></span>
        </a>
    </div>
    <div class="story">
        <div class="image">
            <img
                src="/img/es/eventstory/climax/midoribcgframe.jpg"
                alt="Climax"
            />
        </div>
        <a href="/climax" class="storyName">
            <span>Climax</span>
            <span class="read"></span>
        </a>
    </div>
    <div class="story">
        <div class="image">
            <img
                src="/img/es/eventstory/climax/midoribcgframe.jpg"
                alt="Climax"
            />
        </div>
        <a href="/climax" class="storyName">
            <span>Climax</span>
            <span class="read"></span>
        </a>
    </div>
    <div class="story">
        <div class="image">
            <img
                src="/img/es/eventstory/climax/midoribcgframe.jpg"
                alt="Climax"
            />
        </div>
        <a href="/climax" class="storyName">
            <span>Climax</span>
            <span class="read"></span>
        </a>
    </div>
    <div class="story">
        <div class="image">
            <img
                src="/img/es/eventstory/climax/midoribcgframe.jpg"
                alt="Climax"
            />
        </div>
        <a href="/climax" class="storyName">
            <span>Climax</span>
            <span class="read"></span>
        </a>
    </div>
    <div class="story">
        <div class="image">
            <img
                src="/img/es/eventstory/climax/chiakibcgframe.jpg"
                alt="Climax"
            />
        </div>
        <a href="/climax" class="storyName">
            <span>Climax</span>
            <span class="read soon"></span>
        </a>
    </div>
</div>
