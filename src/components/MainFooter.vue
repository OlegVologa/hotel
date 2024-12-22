<template>
  <footer>
    <div class="wrapper_footer-top container relative flex justify-evenly flex-wrap gap-6 mt-14">
      <img class="big_icon" src="../assets/images/BigIcon.png" alt="icon" />
      <ul class="information capitalize mb-14">
        <li class="list_main">информация</li>
        <li class="list_information mb-4 cursor-pointer">главная</li>
        <li class="list_information mb-4 cursor-pointer">галерея</li>
        <li class="list_information mb-4 cursor-pointer">проекты</li>
        <li class="list_information mb-4 cursor-pointer">сертификаты</li>
        <li class="list_information cursor-pointer">контакты</li>
      </ul>
      <ul class="contacts mb-14">
        <li class="list_main capitalize">контакты</li>
        <li class="list_map mb-14">
          <a href="https://maps.app.goo.gl/XaPdYqyvrJPeETSA6">
            <p>100000, Республика Казахстан,</p>
            <p>г. Караганда, ул. Телевизионная 10</p>
          </a>
        </li>
        <li class="list_phone mb-8">
          <a href="tel:77017776811">+7 (701) 77 76 811</a>
        </li>
        <li class="list_mail">
          <a href="mailto:Galym.sultanov@mail.ru">Galym.sultanov@mail.ru</a>
        </li>
      </ul>
      <div class="social-media mb-14">
        <p class="list_main"><span class="capitalize">социальные </span>сети</p>

        <div class="icons flex">
          <a href="#"
            ><img
              class="mr-10 cursor-pointer"
              src="../assets/images/facebook.png"
              alt="icon-facebook"
          /></a>
          <a href="#"
            ><img
              class="mr-10 cursor-pointer"
              src="../assets/images/twitter.png"
              alt="icon-twitter"
          /></a>
          <a href="#"
            ><img
              class="mr-10 cursor-pointer"
              src="../assets/images/Linked In.png"
              alt="icon-linked_in"
          /></a>
          <a href="#"
            ><img
              class="cursor-pointer"
              src="../assets/images/pininterest.png"
              alt="icon-pininterest"
          /></a>
        </div>
      </div>
    </div>
    <div class="line"></div>
    <div class="wrapper_footer-bottom text-center pt-6 pb-6">
      © 2019 Digital Project. Все права защищены.
    </div>
  </footer>
</template>

<style scoped>
footer {
  background-color: #2c2c2c;
  color: #fff;
  font-family: 'TTHoles-500';
  font-size: 14px;
  line-height: 24px;
}

.big_icon {
  width: 145px;
  height: 94px;
  margin-top: 60px;
}

.information {
  width: 110px;
}

.contacts {
  width: 260px;
}

.social-media {
  width: 193px;
}

.list_main {
  margin-top: 60px;
  margin-bottom: 25px;
  font-family: 'TTHoves-700', system-ui;
  font-size: 16px;
  line-height: 19.92px;
}

.list_map,
.list_phone,
.list_mail {
  position: relative;
  padding-left: 30px;
}

.list_map::before {
  position: absolute;
  content: '';
  width: 11px;
  height: 16px;
  background-image: url('../assets/images/map.png');
  left: 0;
}

.list_phone::before {
  position: absolute;
  content: '';
  width: 16.01px;
  height: 16px;
  background-image: url('../assets/images/phone.png');
  left: 0;
  bottom: 7px;
}

.list_mail::before {
  position: absolute;
  content: '';
  width: 16px;
  height: 11px;
  background-image: url('../assets/images/mail.png');
  left: 0;
  bottom: 7px;
}

.line {
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
}

.wrapper_footer-bottom {
  font-family: 'OpenSans-Light';
  font-size: 12px;
  line-height: 22px;
  color: #c8c8c8;
  opacity: 50%;
  font-weight: 400;
}

.container {
  margin: 0 auto;
  padding: 0 10px;
}

@media (min-width: 640px) {
  .container {
    padding: 0 20px;
  }
}

@media (min-width: 1280px) {
  .wrapper_footer-top {
    justify-content: flex-start;
  }
  .big_icon {
    margin-right: 99px;
  }
  .information {
    margin-right: 150px;
  }
  .contacts {
    margin-right: 80px;
  }
}

@media (min-width: 1440px) {
  .container {
    padding: 0 135px;
  }
}
</style>
