<template>
  <div class="h-[36px] border-b border-[#e8e8e8] m-auto" >
    <nav class="flex flex-row m-auto w-[1200px]">
      <ul class="list-none flex flex-grow justify-between">
        <li class="listItems"><a href="/" class="listLink">KADIN</a></li>
        <li class="listItems"><a href="/" class="listLink">ERKEK</a></li>
        <li class="listItems"><a href="/" class="listLink">ÇOCUK</a></li>
        <li class="listItems"><a href="/" class="listLink">EV & MOBİLYA</a></li>
        <li class="listItems"><a href="/" class="listLink">SÜPERMARKET</a></li>
        <li class="listItems"><a href="/" class="listLink">KOZMETİK</a></li>
        <li class="listItems"><a href="/" class="listLink">AYAKKABI & ÇANTA</a></li>
        <li class="listItems"><a href="/" class="listLink">SAAT & AKSESUAR</a></li>
        <li class="listItems"><a href="/" class="listLink">ELEKTRONİK</a></li>
        <li class="listItems"><a href="/" class="listLink">SPOR & OUTDOOR</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Navigation"
}
</script>

<style scoped>
.listItems {
  flex-shrink: 0;
  flex-grow: 1;
}

.listLink {
  padding: 0;
  font-weight: 600;
  font-family: "Source Sans Pro", sans-serif;
  color: #333;
  font-size: 13px;
  line-height: 34px;
  text-align: center;
  display: block;
  box-sizing: border-box;
  text-decoration: none;
  border-bottom: 2px solid transparent;
}
.listLink:hover {
  color: rgb(186 88 11);
  border-bottom-color: rgb(186 88 11);
}
</style>
