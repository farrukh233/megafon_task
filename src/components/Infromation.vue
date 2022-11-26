<template>
  <section>
    <p class="text-gray-400 pt-6 pl-6">{{ subTitle }}</p>
    <h2 class="pt-2 pl-6 text-3xl">
      <strong>{{ title }}</strong>
    </h2>
    <a class="pt-1 pl-6 text-blue-400" href=""
      ><strong>{{ info }}</strong></a
    >
  </section>
</template>

<script>
export default {
  name: "Information",
  props: {
    subTitle: String,
    title: String,
    info: String,
  },
  setup(props) {
    console.log(props.title);
  },
};
</script>
