<script setup lang="ts"></script>

<template>
  <nav class="fixed top-0 w-full border-b">
    <div class="container flex h-20 items-center justify-between px-5">
      <h3 class="text-xl font-medium text-darkBlack">Mughees Ahmad</h3>
      <ul class="flex items-center justify-between gap-7">
        <li
          class="cursor-pointer font-medium transition-transform hover:scale-105"
          :class="[true ? 'text-primary' : 'text-darkBlack']"
        >
          Home
        </li>
        <li
          class="cursor-pointer font-medium transition-transform hover:scale-105"
          :class="[false ? 'text-primary' : 'text-darkBlack']"
        >
          About
        </li>
        <li
          class="cursor-pointer font-medium transition-transform hover:scale-105"
          :class="[false ? 'text-primary' : 'text-darkBlack']"
        >
          Works
        </li>
        <li>
          <button
            class="flex items-center gap-1 rounded-full border px-4 py-2 font-medium transition-colors duration-300"
            :class="[
              false
                ? 'border-primary text-primary hover:bg-primary hover:text-white'
                : 'border-darkBlack text-darkBlack hover:bg-darkBlack hover:text-white',
            ]"
          >
            Let's Talk
            <Icon name="material-symbols:arrow-right-alt-rounded"></Icon>
          </button>
        </li>
      </ul>
    </div>
  </nav>
</template>
