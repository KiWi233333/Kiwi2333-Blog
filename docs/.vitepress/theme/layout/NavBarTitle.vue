<script setup>
</script>

<template>
  <svg width="40%" height="4rem" version="1.0" xmlns="http://www.w3.org/2000/svg" id="logo-anim" stroke-linecap="round"
    stroke-linejoin="round" viewBox="0 0 509.000000 117.000000" preserveAspectRatio="xMidYMid meet">
    <g transform="translate(0.000000,117.000000) scale(0.100000,-0.100000)">
      <path stroke="var(--vp-c-text-1)" stroke-linecap="round" stroke-linejoin="round" stroke-width="1em" d="M368 1153 c-26 -31 -37 -56 -139 -351 -192 -556 -242 -745 -207 -780
  36 -36 100 7 384 265 l91 83 5 -75 c7 -103 52 -195 115 -235 115 -73 253 -44
  468 98 l90 60 7 -44 c10 -67 37 -106 93 -134 45 -23 61 -25 170 -24 176 0 347
  45 787 205 119 43 219 79 222 79 3 0 13 -26 21 -57 79 -284 124 -297 351 -95
  51 45 94 78 98 75 3 -4 6 -15 6 -27 0 -32 39 -103 66 -121 65 -42 183 -2 377
  129 l99 66 72 0 c40 0 98 5 130 11 32 6 59 9 61 7 1 -2 -2 -31 -8 -64 -10 -56
  -8 -65 14 -110 19 -39 34 -54 74 -74 45 -23 62 -25 170 -25 105 1 138 5 265
  38 241 61 792 255 822 289 13 15 15 25 8 38 -18 34 -41 31 -152 -20 -390 -182
  -833 -304 -1013 -279 -83 11 -109 33 -113 96 -2 41 3 61 33 116 41 79 43 94
  12 108 -18 8 -35 6 -77 -12 -90 -36 -151 -49 -228 -49 -79 0 -99 -7 -195 -72
  -78 -53 -217 -119 -264 -125 -29 -4 -42 -1 -55 14 -21 23 -38 86 -38 140 0 29
  -5 45 -17 52 -14 7 -36 -9 -117 -86 -112 -107 -220 -188 -239 -180 -19 7 -54
  120 -69 222 -17 117 -22 119 -146 61 -309 -143 -677 -261 -887 -284 -97 -11
  -189 0 -224 26 -40 30 -41 101 -1 176 16 32 30 71 30 87 0 25 -4 29 -29 29
  -22 0 -50 -18 -111 -70 -113 -98 -194 -154 -286 -197 -68 -33 -89 -38 -149
  -38 -54 0 -76 5 -97 20 -38 27 -76 108 -84 177 l-7 57 104 97 c141 132 364
  361 395 406 31 44 27 88 -8 88 -28 0 -123 -78 -293 -241 -287 -274 -459 -430
  -648 -588 -9 -8 -20 -12 -23 -9 -13 14 97 347 258 776 79 211 90 246 80 267
  -14 29 -33 32 -54 8z" />
      <path stroke="var(--vp-c-text-1)" stroke-linecap="round" stroke-linejoin="round" stroke-width="1em" d="M1770 790 c-14 -4 -114 -8 -222 -9 -164 -1 -199 -4 -212 -17 -33 -32
  -6 -74 47 -74 18 0 68 4 112 10 44 5 133 14 197 19 131 11 161 21 156 54 -3
  24 -35 31 -78 17z" />
      <path stroke="var(--vp-c-text-1)" stroke-linecap="round" stroke-linejoin="round" stroke-width="1em" d="M4310 790 c-14 -4 -114 -8 -222 -9 -164 -1 -199 -4 -212 -17 -33 -32
  -6 -74 47 -74 18 0 68 4 112 10 44 5 133 14 197 19 131 11 161 21 156 54 -3
  24 -35 31 -78 17z" />
    </g>
  </svg>
</template>

<style scoped>
@keyframes logo-anim {
  0% {
    stroke-dashoffset: 1px;
    stroke-dasharray: 0 3000%;
    opacity: 0;
  }

  10% {
    opacity: 1;
  }

  35% {
    stroke-dasharray: 3000% 0;
    fill: transparent;
  }

  /* Moving back */
  50% {
    stroke-dasharray: 3000% 0;
    fill: var(--vp-c-text-1);
  }

  75% {
    fill: transparent;
  }

  95%,
  100% {
    stroke-dasharray: 0 3000%;
  }
}

#logo-anim,
#logo-anim path {
  fill: transparent;
  transition: all 0.4s ease-in-out;
  stroke-dashoffset: 1px;
  stroke-dasharray: 3000% 0;
  animation: logo-anim 10s ease forwards infinite;
  transform-origin: center;
  stroke: var(--vp-c-text-1);
  animation-delay: 0s;
}
</style>

