<template>
  <div class="block">
    <div id="headerMain" class="m-0 mx-auto w-120 relative">
      <div class="flex flex-row justify-end list-none pt-5px">
        <ul class="text-tiny float-right block">
          <li><a href="">İndirim Kuponlarım</a></li>
          <li><a href="">Trendyol'da Satış Yap</a></li>
          <li><a href="">Yardım & Destek</a></li>
        </ul>
      </div>
      <div class="flex flex-row justify-between">
        <img src="https://cdn.dsmcdn.com/web/logo/ty-web.svg" width="146px" alt="31">
        <div class="flex flex-row justify-center">
          <div class="flex flex-row w-[598px] relative align-center justify-center">
            <input type="text"
                   class="text-[#333] text-sm w-full outline-none w-full text-sm border-2 border-transparent border-solid rounded-md py-2.5 pl-3.5 pr-10 h-auto"
                   placeholder="Aradığınız ürün, kategori veya markayı yazınız" maxlength="50">
            <span class="m-auto">
              <v-icon color="#FF980"
                      small
              >fa-search</v-icon>
            </span>
          </div>
        </div>
        <div class="flex flex-row justify-center px-15">
          <div class="w-80 flex flex-row justify-between  text-center align-center m-auto">
            <div class="icons">
              <i class="fa-regular fa-user"></i>
              <p class="linkText">Giriş Yap</p></div>
            <div class="icons"><i class="fa-regular fa-heart"></i>
              <p class="linkText">Favorilerim</p></div>
            <div class="icons"><i class="fa-search"></i>
              <p class="linkText">Sepetim</p></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'HeaderTop'
}
</script>

<style scoped>
.icons {
  cursor: pointer;
  display: flex;
  justify-items: center;
  align-items: center;
  position: relative;
  height: 40px;
}
.linkText {
  font-size: 13px;
  padding-left: 5px;
  margin-top: 2px;
}
#headerMain {
  width: 1200px;
}

ul li {
  font-size: 12px;
  line-height: 15px;
  color: #999;
  display: inline-flex;
  margin-left: 40px;
}
</style>
