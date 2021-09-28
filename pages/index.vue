<template>
  <div class="bg-black min-h-screen flex">
    <div class="flex flex-col w-full min-h-screen divide-y divide-gray-700 divide-dotted">
      <div class="flex flex-row divide-x divide-gray-700 divide-dotted">
        <div class="w-2/12 h-24"></div>
        <div class="h-24 flex-1"></div>
      </div>
      <div class="flex flex-row divide-x divide-gray-700 divide-dotted">
        <div class="w-2/12"></div>
        <div class="flex flex-col px-4 py-8 space-y-2"> 
          <h1 class="text-4xl text-blue-200 font-semibold">Chew Tzi Hwee</h1>
          <h2 class="text-xl text-gray-200 font-normal">Full Stack Dev, Electronics</h2>
        </div>
      </div>
      <div class="flex flex-row divide-x divide-gray-700 divide-dotted">
        <div class="w-2/12"></div>
        <div class="flex flex-col px-4 py-8 space-y-6"> 
          <div>
            <h3 class="text-xl text-white font-semibold pb-2">Knowledgable in</h3>
            <ul class="list-inside list-disc space-y-1 text-gray-400">
              <li>Arduino</li>
              <li>Javascript</li>
              <li>Next.Js</li>
              <li>React</li>
              <li>Java</li>
              <li>Preact</li>
            </ul>
          </div>
          <div>
            <h3 class="text-xl text-white font-semibold pb-2">Experiences</h3>
            <ul class="list-inside space-y-1 text-gray-400">
              <li>CLPHS CEC (2019 & 2020) <span class="text-purple-300">[PRESIDENT]</span></li>
              <li>Speer Education <span class="text-purple-300">[LEAD WEB DEV]</span></li>
            </ul>
          </div>
          <div>
            <h3 class="text-xl text-white font-semibold pb-2">Socials</h3>
            <ul class="list-inside space-y-1 text-gray-400">
              <li><span class="text-green-400">[GITHUB]</span> <a href="https://github.com/ImJustChew">https://github.com/ImJustChew</a></li>
              <li><span class="text-green-400">[LINKEDIN]</span> <a href="https://www.linkedin.com/in/imjustchew">https://www.linkedin.com/in/imjustchew/</a></li>
            </ul>
          </div>
        </div>
      </div>
      <div class="flex flex-row divide-x divide-gray-700 divide-dotted flex-1">
        <div class="w-2/12"></div>
        <div class="flex flex-col px-4 py-8"> 
          <h3 class="text-xl text-white font-semibold pb-2">Contact</h3>
          <ul class="list-inside space-y-1 text-gray-400">
            <li><span class="text-blue-300">[EMAIL]</span> chewtzihwee@gmail.com </li>
            <li><span class="text-blue-300">[DISCORD]</span> Chew#9392 </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  head() {
    return {
      title: 'Chew Tzi Hwee',
      meta: [
        { charset: 'utf-8' },
        { name: 'viewport', content: 'width=device-width, initial-scale=1' },
        { hid: 'description', name: 'description', content: 'Chew Tzi Hwee' }
      ],
    }
  }
})
</script>

<style>
html, body {
    font-family: "Roboto Mono";
}
</style>