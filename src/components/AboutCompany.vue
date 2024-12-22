<script setup>
import MainButton from './WhiteButton.vue';
</script>

<template>
  <div class="about-company_wrapper relative">
    <div class="gray_fon absolute z-0"></div>
    <img
      class="about-company1 z-10 col-span-1"
      src="../assets/images/about-company1.png"
      alt="building"
    />
    <img
      class="about-company2 z-10 col-span-1 row-span-2"
      src="../assets/images/about-company2.png"
      alt="building"
    />
    <div class="about-company_text z-10 col-span-1 row-span-2">
      <h3 class="title-h3 mb-5"><span class="capitalize">о</span> компании</h3>
      <p class="about-compaty_lorem mb-5">
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
        been the industry's standard dummy text ever since the 1500s, when an unknown printer took a
        galley of type and scrambled it to make a type specimen book. It has survived not only five
        centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
      </p>
      <MainButton text="читать"/>
    </div>
    <img
      class="about-company3 z-10 col-span-1 row-span-1"
      src="../assets/images/about-company3.png"
      alt="building"
    />
  </div>
</template>

<style scoped>
.gray_fon {
  width: 1170px;
  height: 435px;
  background-color: #fbfbfb;
  top: -20px;
  left: -100px;
}
.about-company_wrapper {
  max-width: 1000px;
  margin: 0 auto 120px auto;
  display: grid;
  grid-template-columns: auto auto auto;
  grid-template-rows: auto auto;
  gap: 30px;
}

.about-company2 {
  position: relative;
  top: 30px;
}

.about-company_text {
  width: 400px;
}

.about-compaty_lorem {
  font-family: 'TTHoves-300';
  font-size: 16px;
  line-height: 25px;
}

</style>
