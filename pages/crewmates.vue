<template>
  <NuxtLayout name="default">
    <div class="flex flex-col">
      <div class="flex flex-col pt-4 gap-3">
        <h1 class="pb-2 text-center md:text-6xl text-4xl font-bold text-white">the crewmates</h1>
        <p class="text-l font-medium text-white px-4 md:px-10">
          Here you can find all the crewmates of the Grand Line Webring. Want to go back to the frontpage? <a href="/" class="px-1 font-bold bg-red-500">Click here</a>
        </p>
        <div class="flex justify-center">
          <ul class="grid-cols" id="crew-list">
            <li data-lang="en" id="sid">
              <a href="https://kjelsrud.dev">kjelsrud.dev</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </NuxtLayout>
</template>

<style scoped>
  .grid-cols {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 5rem;
  }
  @media only screen and (max-width: 600px) {
    .grid-cols {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 1rem;
    }
  }
  ul, li a{
    color: white;
    font-weight: 600
  }
  li :hover {
    background-color: #ef4444;
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
</style>
