<template>
    <div class="bg-color">
        <div class="app-background mx-auto max-w-3xl xl:max-w-2xl xl:px-18">
            <slot />
        </div>
    </div>
</template>

<style>
.app-background {
  background-image: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.5)), url('/background.webp');  background-size: cover;
  background-position: center;
  background-attachment: fixed;
  min-height: 100vh;
  box-shadow: 0 6px 10px 0 rgba(0, 0, 0, 0.8);
}
.bg-color {
    background-color: #3b4f56;
}
</style>