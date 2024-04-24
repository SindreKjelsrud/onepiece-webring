<template>
    <NuxtLayout name="default">
        <div class="flex flex-col md:gap-4 gap-2 pt-4">
            <h1 class="pb-2 text-center md:text-6xl text-3xl font-bold text-white">the grand line webring</h1>
            <div>
                <h2 class="md:text-3xl text-xl font-semibold text-white">Ahoy there!</h2>
                <p class="text-l font-medium text-white">
                    Welcome to the Grand Line Webring, where all passionate pirates and fans of One Piece gather to celebrate the epic adventures of Monkey D. Luffy and his crew! Whether you sail the seas or dream of setting sail, this webring is for you. Join our crew and become part of the greatest adventure on the Grand Line!
                </p>
            </div>
            <div>
                <h2 class="md:text-3xl text-xl font-semibold text-white">How to Join</h2>
                <p class="text-l font-medium text-white">
                    To join the Grand Line Webring, <a href="https://github.com/SindreKjelsrud/onepiece-webring" class="px-1 font-bold bg-red-500">submit a pull request</a> to our GitHub repository. Be sure to read the <a href="https://github.com/SindreKjelsrud/onepiece-webring/blob/main/README.md" class="px-1 font-bold bg-red-500">README.md</a> to make sure you've covered all the criterias to join!
                    We'll review your submission as fast as we can, and remember to include the widget on your site for all to see.
                </p>
            </div>
            <div>
                <h2 class="md:text-3xl text-xl font-semibold text-white">Webring Widgets</h2>
                <p class="text-l font-medium text-white">
                    You could either use the white or black SVG below (click them to download), or <a href="https://github.com/SindreKjelsrud/onepiece-webring/tree/main/public" class="px-1 font-bold bg-red-500">download it from here</a> and change the color yourself!
                </p>
            </div>
            <div class="flex justify-between">
                <a href="/goingmerry.white.svg" download><img src="/goingmerry.white.svg" alt="The Going Merry SVG in white" class="md:w-36 w-20" /></a>
                <a href="/goingmerry.black.svg" download><img src="/goingmerry.black.svg" alt="The Going Merry SVG in black" class="md:w-36 w-20" /></a>
            </div>
            <h2 class="md:text-3xl text-xl font-semibold text-white">Webring Crew</h2>
            <p class="text-l font-medium text-white">
                Interested in checking out your fellow crewmates? <a href="/crewmates" class="px-1 font-bold bg-red-500">Click here</a> to see the full list!
            </p>
        </div>
    </NuxtLayout>
</template>