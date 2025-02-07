<template>
    <img alt="Vue header" class="header" src="@/assets/HeaderSide.png"/>
    <img alt="Vue banner" class="banner" src="@/assets/Herobanner.png"/>
</template>

<style scoped>
header {
  position: relative;
}

img.header {
  width: 100%;
  height: auto;
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1;
}

img.banner {
  width: 100%;
}
</style>