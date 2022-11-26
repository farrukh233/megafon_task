<script setup>
import Information from "./components/Infromation.vue";

const list = [
  {
    subTitle: "Ваш тариф",
    title: "Биё! Фаъол бош - Сотрудник",
    info: "Сменить тариф",
  },
  {
    subTitle: "Остатки минут по РТ:",
    title: "102",
    info: "Подключай минуты +",
  },
  {
    subTitle: "Остатки интернет трафика:",
    title: "987 МБ",
    info: "Пополнить мегабайты +",
  },
  {
    subTitle: "Остатки бонусных баллов:",
    title: "150",
    info: "Обменять",
  },
];
</script>

<template>
  <div class="h-screen overflow-x-hidden">
    <header class="w-full h-44 bg-[#00bd49]">
      <div class="max-w-[1200px] flex justify-between w-full m-auto pt-[20px]">
        <img src="./assets/megafon--1-cropped.svg" width="120" alt="logo" />
        <div>
          <div class="flex items-center">
            <p class="text-white">
              <a href="tel:+9929000000">+992 90 000 00</a>
            </p>
            <img src="./assets/icons8-sort-down-30.png" width="20" />
          </div>
          <p class="text-white">Фамилия Имя Отчество</p>
        </div>
      </div>
    </header>
    <main class="w-screen">
      <section
        class="max-w-[1200px] w-full relative -top-8 flex justify-between m-auto"
      >
        <div class="bg-white w-1/3 h-36 rounded-xl">
          <Information
            title="12,00 TJS"
            subTitle="Текущий баланс:"
            info="+ Пополнить"
          />
        </div>
        <ul class="bg-white rounded-xl w-[65%] pb-[40px]">
          <li v-for="item in list" :key="item.title">
            <Information
              :title="item.title"
              :subTitle="item.subTitle"
              :info="item.info"
            />
          </li>
        </ul>
      </section>
    </main>
  </div>
</template>
