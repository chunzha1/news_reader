<template>
  <div class="image-container">
    <img
      src="https://gw.alicdn.com/imgextra/O1CN01rOGq191KlTe1YyiZM_!!6000000001204-2-yinhe.png_.webp"
      alt="Decorative"
    />
  </div>
</template>

<style scoped>
img {
  --s: 300px;

  width: var(--s);
  aspect-ratio: 1;
  padding: calc(0.09 * var(--s)) calc(var(--s) / 2 - var(--_p));
  box-sizing: border-box;
  object-fit: cover;
  border-image: radial-gradient(#e5414e 69%, #0000 70%) 84.5% /
    calc(var(--s) / 2) / 0 var(--_p);
  clip-path: polygon(
    calc(-41% - var(--_p)) 0,
    calc(50% - var(--_p)) 91%,
    calc(50% + var(--_p)) 91%,
    calc(141% + var(--_p)) 0
  );
  transition: 0.5s;
  cursor: pointer;
  --_p: 0px;
}
img:hover {
  --_p: calc(var(--s) / 2);
}

.image-container {
  display: grid;
  place-content: center;
  background: #f9ffb4;
  filter: drop-shadow(0 0 10px #cc333f);
}
</style>
