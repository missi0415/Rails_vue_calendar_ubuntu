<template>
  <div>
    <button @click="clickEvent()">ボタンだよ</button>
  </div>
</template>

  <script>
  export default {
    name: "HelloWorld",
    methods: {
      clickEvent() {
        console.log("ボタンが押されました");
      },
    },
  };
  </script>
