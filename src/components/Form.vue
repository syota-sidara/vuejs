<template>
  <div class="container">
    <div class="item">
      <input type="text" name="title" v-model="inputTitle" />
    </div>
    <div class="item">
      <input type="text" name="period" v-model="inputPeriod" />
    </div>
    <div class="item">
      <textarea name="detaile" v-model="inputDetile"></textarea>
    </div>
    <div class="item">
      <button @click="createTask">作成</button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      // フォームに入れられたデータを入れるものを作る
      inputTitle: "",
      inputPeriod: "",
      inputDetile: ""
    };
  },
  methods: {
    // 作成をされたら実行される動きを作る
    createTask() {}
  }
};
</script>
