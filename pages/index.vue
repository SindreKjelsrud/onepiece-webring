<template>
    <NuxtLayout name="default">
        <div class="flex flex-col gap-4 pt-4">
            <h1 class="pb-2 text-center text-6xl font-bold text-white">the grand line webring</h1>
            <h2 class="text-3xl font-bold text-white">Ahoy there!</h2>
            <p class="text-l font-semibold text-white">
                Welcome to the Grand Line Webring, where all passionate pirates and fans of One Piece gather to celebrate the epic adventures of Monkey D. Luffy and his crew! Whether you sail the seas or dream of setting sail, this webring is for you. Join our crew and become part of the greatest adventure on the Grand Line!
            </p>
            <h2 class="text-3xl font-bold text-white">How to Join</h2>
            <p class="text-l font-semibold text-white">
                To join the Grand Line Webring, <a href="https://github.com/SindreKjelsrud/onepiece-webring" class="px-1 bg-red-500">submit a pull request</a> to our GitHub repository. Be sure to include your site URL, your alias, and your 88x31 button (optional)!
                We'll review your submission as fast as we can, and remember to include the widget on your site for all to see. Read the <a href="https://github.com/SindreKjelsrud/onepiece-webring/blob/main/README.md" class="px-1 bg-red-500">README.md</a> to make sure you've covered all the criterias to join!
            </p>
            <h2 class="text-3xl font-bold text-white">Webring Widgets</h2>
            <p class="text-l font-semibold text-white">
                You could either use the white or black SVG below (click them to download), or <a href="https://github.com/SindreKjelsrud/onepiece-webring/tree/main/public" class="px-1 bg-red-500">download it from here</a> and change the color yourself!
            </p>
            <div class="flex justify-between">
                <a href="/goingmerry.white.svg" download><img src="/goingmerry.white.svg" alt="The Going Merry SVG in white" class="w-36" /></a>
                <a href="/goingmerry.black.svg" download><img src="/goingmerry.black.svg" alt="The Going Merry SVG in black" class="w-36" /></a>
            </div>
            <h2 class="text-3xl font-bold text-white">Webring Crew</h2>
            <p class="text-l font-semibold text-white">
                Interested in checking out your fellow crewmates? <a href="/crewmates" class="px-1 bg-red-500">Click here</a> to see the full list!
            </p>
        </div>
    </NuxtLayout>
</template>