<template>
  <header class="flex justify-between xl:justify-start">
    <img class="small_icon mr-8" src="../assets/images/SmallIcon.png" alt="icon">
    <ul class="list">
      <li class="menu_item mb-4 mr-4 md:mr-6 md:mb-0 lg:mr-10 xl:mr-12">главная</li>
      <li class="menu_item mb-4 mr-4 md:mr-6 md:mb-0 lg:mr-10 xl:mr-12">галерея</li>
      <li class="menu_item mb-4 mr-4 md:mr-6 md:mb-0 lg:mr-10 xl:mr-12">проекты</li>
      <li class="menu_item mb-4 mr-4 md:mr-6 md:mb-0 lg:mr-10 xl:mr-12">сертификаты</li>
      <li class="menu_item mr-4 md:mr-6">котнакты</li>
    </ul>
  </header>
</template>

<style scoped>
header {
  padding-top: 29px;
  padding-bottom: 29px;
  color: #333333;
}

.small_icon {
  width: 70px;
  height: 44px;
}

.menu_item {
  font-family: "TT Hoves-400", system-ui;
  font-size: 12px;
  line-height: 12px;
  text-transform: uppercase;
  text-underline-offset: 4px;
  cursor: pointer;
}

.menu_item:hover {
  text-decoration: overline underline;
}

@media (min-width: 400px) {
  .list {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
  }
}

@media (min-width: 1024px) {
  .small_icon {
    margin-right: 280px;
  }
}

@media (min-width: 1280px) {
  .small_icon {
    margin-right: 330px;
  }
}
</style>