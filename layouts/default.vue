<template>
    <div class="bg-slate-900">
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
}
</style>