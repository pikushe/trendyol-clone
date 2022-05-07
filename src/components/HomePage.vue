<template>
  <div class="home">
    <div class="mx-auto mt-[15px] w-[1200px]">
      <div class="mt-[20px]">
        <div class="w-full">
          <div id="slider" class="flex align-center">
            <div v-for="item in 10" :key="item" v-html="items">
            </div>
          </div>
        </div>
      </div>
      <div class="flex flex-row">
      <div>
        <div class="flex flex-1 mb-[30px] relative">
          <div class="w-[750px] grow shrink">
            <div class="mb-[15px]">
              <a href="" class="block rounded-md shadow-7xl">
                <div class="border-x-[rgb(60, 65, 68)] border-t-[rgb(60, 65, 68)] border-b-initial">
                  <img src="https://cdn.dsmcdn.com/ty411/campaign/banners/original/604763/39e0bba2d4_0_new.jpg" alt="Elektrikli Ev ve Kişisel Bakım Aletlerinde Anneler Gününe Özel Fırsatlar" >
                </div>
                <div>
                <span class="w-3/6 overflow-hidden overflow-ellipsis">Elektrikli Ev ve Kişisel Bakım Aletlerinde Anneler Gününe Özel Fırsatlar</span>
                </div>
              </a>
            </div>
          </div>

        </div>
      </div>
      <div class="banner ml-[30px] self-stretch max-h-full overflow-hidden relative">
        <div class="stickybanner">
          <div class="banneritem h-auto mb-[15px]">
            <div class="bannerImage">
              <img src="https://cdn.dsmcdn.com/mrktng/crm/rightBnr/2022/mar/28/imgs/eski.gif" height="auto" class="block">
            </div>
          </div>
        </div>
      </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  data: function () {
    return {
      items: '<a href="" class="flex flex-col align-center text-center cursor-pointer w-[115px]">' +
          '              <img src="https://cdn.dsmcdn.com/mnresize/200/200/marketing/datascience/automation/2022/3/9/Top_Widget_202203091801.png" width="68" height="68" class="m-auto">' +
          '              <span class="mt-2.5">Sana özel</span></a>'
    }

  }
}
</script>

<style scoped>

</style>
