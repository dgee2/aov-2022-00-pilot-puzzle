<template>
  <div class="w-full h-full flex justify-center items-center">
    <div class="grid grid-cols-3 place-items-stretch">
      <div class="flex items-center justify-center border-r-2 border-b-2 text-9xl">{{ topLeft }}</div>
      <div class="flex items-center justify-center border-x-2 border-b-2 text-9xl"></div>
      <div class="flex items-center justify-center border-l-2 border-b-2 text-9xl"></div>
      <div class="flex items-center justify-center border-r-2 border-y-2 text-9xl"></div>
      <div class="flex items-center justify-center border-2 text-9xl">5</div>
      <div class="flex items-center justify-center border-l-2 border-y-2 text-9xl">6</div>
      <div class="flex items-center justify-center border-r-2 border-t-2 text-9xl">7</div>
      <div class="flex items-center justify-center border-x-2 border-t-2 text-9xl">8</div>
      <div class="flex items-center justify-center border-l-2 border-t-2 text-9xl">9</div>
    </div>
  </div>
</template>

<script>
const defaultGame = {
  topLeft: 'topLeft',//&nbsp;,
  topMiddle: &nbsp;,
  topRight: &nbsp;,
  middleLeft: &nbsp;,
  middleMiddle: &nbsp;,
  middleRight: &nbsp;,
  bottomLeft: &nbsp;,
  bottomMiddle: &nbsp;,
  bottomRight: &nbsp;,
}
export default {
  data() {return JSON.parse(JSON.stringify(defaultGame)}
}
</script>
