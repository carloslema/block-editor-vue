<template>
  <g 
    :class="{'BEV-hover': hover, 'BEV-active': active}">
    <path d=" M 10.5 6 C 10.5 5.6 10.66 5.22 10.94 4.94 C 11.22 4.66 11.6 4.5 12 4.5 C 12.4 4.5 12.78 4.66 13.06 4.94 C 13.34 5.22 13.5 5.6 13.5 6 C 13.5 6.4 13.34 6.78 13.06 7.06 C 12.78 7.34 12.4 7.5 12 7.5 C 11.6 7.5 11.22 7.34 10.94 7.06 C 10.66 6.78 10.5 6.4 10.5 6 Z  M 11.5 6 C 11.5 5.87 11.55 5.74 11.65 5.65 C 11.74 5.55 11.87 5.5 12 5.5 C 12.13 5.5 12.26 5.55 12.35 5.65 C 12.45 5.74 12.5 5.87 12.5 6 C 12.5 6.13 12.45 6.26 12.35 6.35 C 12.26 6.45 12.13 6.5 12 6.5 C 11.87 6.5 11.74 6.45 11.65 6.35 C 11.55 6.26 11.5 6.13 11.5 6 Z " fill-rule="evenodd" fill="rgb(110,117,124)"/><path d=" M 16 12.71 L 16 14 L 13.682 14 L 13.682 14 L 13.37 13.66 L 11.285 11.417 L 11.35 11.35 L 13 9.71 L 15.65 12.35 L 16 12.71 Z  M 16 11.299 L 16 3 L 2 3 L 2 3 L 2 10.336 L 6.53 6.3 L 10.609 10.689 L 10.65 10.65 L 13 8.29 L 16 11.299 Z  M 12.315 14 L 2 14 L 2 11.673 L 2.33 11.37 L 6.47 7.7 L 12.315 14 L 12.315 14 Z  M 1 2 L 17 2 L 17 15 L 1 15 L 1 2 L 1 2 L 1 2 Z " fill-rule="evenodd" fill="rgb(110,117,124)"/>
  </g>
</template>

<script>
export default {
  props: ['hover', 'active'],
}
</script>

<style lang="scss" scoped>
@import '@/styles/valiables.scss';

* {
  transition: opacity .15s;
}

</style>