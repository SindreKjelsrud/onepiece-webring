<template>
    <NuxtLayout name="default">
        <div class="flex flex-col md:gap-4 gap-2 pt-4 pb-2 sm:px-6 xl:px-18 px-4">
            <h1 class="pb-2 text-center md:text-6xl text-4xl font-bold text-white">the grand line webring</h1>
            <!-- INTRO -->
            <div>
                <h2 class="md:text-3xl text-xl font-semibold text-white">Ahoy there!</h2>
                <p class="text-l font-medium text-white">
                    Welcome to the Grand Line Webring, where all passionate pirates and fans of One Piece gather to celebrate the epic adventures of Monkey D. Luffy and his crew! Whether you sail the seas or dream of setting sail, this webring is for you. Join our crew and become part of the greatest adventure on the Grand Line!
                </p>
            </div>
            <!-- HOW TO JOIN -->
            <div>
                <h2 class="md:text-3xl text-xl font-semibold text-white">How to Join</h2>
                <p class="text-l font-medium text-white">
                    To join the Grand Line Webring, <a href="https://github.com/SindreKjelsrud/onepiece-webring" class="px-1 font-bold bg-red-600">submit a pull request</a> to our GitHub repository. Be sure to read the <a href="https://github.com/SindreKjelsrud/onepiece-webring/blob/main/README.md" class="px-1 font-bold bg-red-600">README.md</a> to make sure you've covered all the criterias to join!
                    We'll review your submission as fast as we can, and remember to include the widget on your site for all to see.
                </p>
            </div>
            <!-- WEBRING WIDGETS -->
            <div>
                <h2 class="md:text-3xl text-xl font-semibold text-white">Webring Widgets</h2>
                <p class="text-l font-medium text-white">
                    You could either use the white or black SVG below (click them to download), or <a href="https://github.com/SindreKjelsrud/onepiece-webring/tree/main/public" class="px-1 font-bold bg-red-600">download it from here</a> and change the color yourself!
                </p>
            </div>
            <div class="flex justify-between">
                <a href="/goingmerry.white.svg" download><img src="/goingmerry.white.svg" alt="The Going Merry SVG in white" class="md:w-36 w-20" /></a>
                <a href="/goingmerry.black.svg" download><img src="/goingmerry.black.svg" alt="The Going Merry SVG in black" class="md:w-36 w-20" /></a>
            </div>
            <!-- WEBRING CREW -->
            <h2 class="md:text-3xl text-xl font-semibold text-white">Webring Crew</h2>
            <p class="text-l font-medium text-white">
                Interested in checking out your fellow crewmates? Here you can find all the crewmates of the Grand Line Webring.
            </p>
            <div class="flex justify-center">
                <ul class="grid-cols" id="crew-list">
                    <!-- LIST -->
                    <li data-lang="en" id="sid">
                        <a href="https://kjelsrud.dev">kjelsrud.dev</a>
                    </li> 
                    <li data-lang="en" id="flt">
                        <a href="https://foreverliketh.is/">foreverliketh.is</a>
                    </li> 
                    <li data-lang="en" id="uar">
                        <a href="https://unholyrotten.neocities.org">unholyrotten</a>
                        </li>
                </ul>
            </div>
        </div>
        <img src="/nakama.webp" alt="One Piece Nakama"/>
    </NuxtLayout>
</template>

<style scoped>
.grid-cols {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 3rem;
}
@media only screen and (max-width: 600px) {
    .grid-cols {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 0.5rem;
    }
}
ul, li a{
    color: white;
    font-weight: 600
}
li :hover {
    background-color: #dc2626;
}
#crew-list {
    counter-reset: crew-index;
}
#crew-list > li {
    counter-increment: crew-index;
}
#crew-list > li::before {
    content: counter(crew-index) ". ";
}
#crew-list > li:target {
    background-color: #dc2626;
}
</style>
