<script>
export default {
  data() {
    return {
      count: 5,
    };
  },
  methods: {
    increment() {
      this.count++;
    },
  },
};
</script>

<template>
  <h1 class="count">{{ count }}</h1>
  <p>vue로 확인하는 웹페이지입니다. 아래버튼을 누르면 값이 1씩 증가합니다.</p>
  <button class="btn" v-on:click="increment">+1</button>
</template>

<style>
.count {
  color: red;
}
.btn {
  border: 2px solid black;
  border-radius: 3px;
}
</style>
