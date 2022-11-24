<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div class="overflow-x-hidden">
    <div class="w-full h-44 bg-[#00bd49] flex justify-between">
      <img class="pl-24 pb-14" src="./assets/megafon--1.svg" alt="logo" />
      <div>
        <div class="relative">
          <p class="text-white pr-10 pt-7">+992 90 000 00</p>
          <img
            class="absolute left-32 top-6"
            src="./assets/icons8-sort-down-30.png"
            width="20"
          />
        </div>
        <p class="text-white pr-10">Фамилия Имя Отчество</p>
      </div>
    </div>
    <div class="bg-[#ececec] w-screen h-screen relative">
      <div class="bg-white w-96 h-36 rounded-xl absolute left-28 -top-8">
        <p class="text-gray-400 pt-6 pl-6">Текущий баланс:</p>
        <h4 class="pt-2 pl-6 text-3xl"><strong>12,00 TJS</strong></h4>
        <p class="pt-1 pl-6 text-blue-400"><strong>+ Пополнить</strong></p>
      </div>
      <div class="bg-white w-[600px] rounded-xl absolute left-[510px] -top-8">
        <div>
          <p class="text-gray-400 pt-6 pl-6">Ваш тариф:</p>
          <h4 class="pt-2 pl-6 text-3xl">
            <strong>Биё! Фаъол бош - Сотрудник</strong>
          </h4>
          <p class="pt-1 pl-6 text-blue-400"><strong>Сменить тариф</strong></p>
        </div>
        <div>
          <p class="text-gray-400 pt-6 pl-6">Остатки минут по РТ:</p>
          <h4 class="pt-2 pl-6 text-3xl">
            <strong>102 минуты</strong>
          </h4>
          <p class="pt-1 pl-6 text-blue-400">
            <strong>Подключай минуты +</strong>
          </p>
        </div>
        <div>
          <p class="text-gray-400 pt-6 pl-6">Остатки интернет трафика:</p>
          <h4 class="pt-2 pl-6 text-3xl">
            <strong>987 МБ</strong>
          </h4>
          <p class="pt-1 pl-6 text-blue-400">
            <strong>Подключай мегабайты +</strong>
          </p>
        </div>
        <div>
          <p class="text-gray-400 pt-6 pl-6">Остатки бонусных баллов:</p>
          <h4 class="pt-2 pl-6 text-3xl">
            <strong>150</strong>
          </h4>
          <p class="pt-1 pl-6 text-blue-400"><strong>Обменять</strong></p>
        </div>
      </div>
    </div>
  </div>
</template>
