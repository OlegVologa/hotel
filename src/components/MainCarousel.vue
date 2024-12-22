<script setup>
import { Carousel } from 'flowbite'
import MainTitle from './MainTitle.vue'
import MainButton from './WhiteButton.vue'
// const carousel = new Carousel(carouselElement, items, options, instanceOptions);
</script>

<template>
  <div id="default-carousel" class="progect_wrapper relative w-full flex" data-carousel="slide">
    <div class="title_wrapper">
      <MainTitle TextThin="project" TextBold="nurtown" />
      <div class="arrows relative">
        <!-- Slider controls -->
        <button
          type="button"
          class="arrow-left absolute top-0 start-0 z-30 flex items-center justify-center cursor-pointer"
          data-carousel-prev
        >
          <img src="../assets/images/arrow-left.svg" alt="arrow-left" />
        </button>
        <button
          type="button"
          class="arrow-right absolute top-0 end-0 z-30 flex items-center justify-center cursor-pointer"
          data-carousel-next
        >
          <img src="../assets/images/arrow-right.svg" alt="arrow-right" />
        </button>
        <p class="line relative z-30"></p>
      </div>
      <div class="pages relative z-30 flex justify-between content-center">
        <!-- Slider indicators -->
        <button
          type="button"
          class="w-8 h-8 rounded-full"
          aria-current="true"
          aria-label="Slide 1"
          data-carousel-slide-to="0"
        >
          01
        </button>
        <img src="../assets/images/slash.png" alt="slash" />
        <button
          type="button"
          class="w-8 h-8 rounded-full"
          aria-current="false"
          aria-label="Slide 2"
          data-carousel-slide-to="1"
        >
          02
        </button>
        <div class="absolute rtl:space-x-reverse"></div>
      </div>
    </div>
    <!-- Carousel wrapper -->
    <div class="curousel_wrapper relative overflow-hidden">
      <!-- Item 1 -->
      <div class="hidden duration-700 ease-in-out" data-carousel-item>
        <img
          src="../assets/images/MainProgect.png"
          class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
          alt="..."
        />
      </div>
      <!-- Item 2 -->
      <div class="hidden duration-700 ease-in-out" data-carousel-item>
        <img
          src="../assets/images/MainProgect.png"
          class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
          alt="..."
        />
      </div>
      <div class="absolute z-40 bottom-0 left-0">
        <MainButton text="взглянуть" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.progect_wrapper {
  width: 1170px;
  margin-bottom: 150px;
}

.title_wrapper {
  width: 400px;
}

.arrows {
  width: 129px;
  height: 53px;
  margin-bottom: 90px;
}

.arrow-left,
.arrow-right {
  width: 53px;
  height: 53px;
  border: 1px solid #f2f2f2;
}

.arrow-left,
.arrow-right:hover {
  background-color: #f9f9f9;
}

.line {
  width: 271px;
  left: 129px;
  bottom: -26.5px;
  border-bottom: 1px solid #f9f9f9;
}
.pages {
  width: 142px;
  height: 31px;
  color: #bdbdbd;
  font-family: 'TTHoles-400';
  font-size: 24px;
  line-height: 24px;
}

.curousel_wrapper {
  width: 770px;
  height: 829px;
}
</style>
