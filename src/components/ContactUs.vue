<script setup>
import BlackButton from './BlackButton.vue';
</script>
<template>
  <div class="flex flex-col">
    <h3 class="title-h3"><span class="capitalize">связаться</span> с нами</h3>
    <div class="flex">
      <form class="form">
        <input type="text" id="name" class="form_fild" placeholder="Имя" />
        <input type="tel" id="phone" class="form_fild" placeholder="Номер телефона*" required />
        <input type="email" id="email" class="form_fild" placeholder="E-mail*" required />
        <input
          type="text"
          id="product of interest"
          class="form_fild"
          placeholder="Интересующий товар/услуга"
        />
          required
        <textarea id="message" rows="4" class="form_area" placeholder="Сообщение*" required></textarea>
        <label for="message" class="check-mark">
          <svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <rect y="0.686768" width="24" height="23.2625" rx="4" fill="#F3F3F3" />
            <path
              d="M7.17224 12.1173C6.7984 11.7691 6.1923 11.7691 5.81846 12.1173C5.44463 12.4654 5.44463 13.0299 5.81846 13.3781L9.20291 16.5301C9.57792 16.8794 10.1863 16.8781 10.5597 16.5273L18.1838 9.36338C18.556 9.01367 18.5533 8.44918 18.1778 8.10257C17.8023 7.75595 17.1962 7.75846 16.824 8.10817L9.87678 14.6361L7.17224 12.1173Z"
              fill="#333333"
            />
          </svg>
        </label>
        <p class="p-label"><span class="s-label">О</span>тправляя заявку <span class="s-label">В</span>ы соглашаетесь с политикой конфиденциальности</p>
        <button type="submit">
          <BlackButton text="отправить" />
        </button>
      </form>
      <img class="contactUs" src="../assets/images/contactUs.png" alt="men" />
    </div>
  </div>
</template>

<style scoped>
.title-h3 {
  margin-bottom: 22px;
}

.form {
  width: 391px;
  margin-right: 30px;
  margin-bottom: 120px;
}

.form_fild,
.form_area {
  background-color: #f3f3f3;
  color: #333333;
  font-size: 22px;
  padding-left: 21px;
  padding-right: 21px;
  outline: none;
  margin-bottom: 10px;
}

.form_fild {
  width: 391px;
  height: 46px;
}

.form_area {
  width: 391px;
  height: 147px;
  padding-top: 14px;
  padding-bottom: 14px;
}

::placeholder {
  font-family: 'TTHoves-400';
  font-size: 14px;
  line-height: 17.43px;
  color: #8d8d8d;
}

.check-mark {
  position: relative;
  width: 24px;
  height: 24px;
  top: -100px;
}

.p-label {
  padding-left: 40px;
  font-family: 'TTHoves-400';
  font-size: 14px;
  line-height: 17.43px;
  color: #333333;
  margin-bottom: 21px;
}

.s-label {
  text-transform: uppercase;
}

.contactUs {
  align-self: start;
}
</style>
