<script lang="ts" setup>
  import DatePicker from './components/DatePicker.vue';
</script>

<template>
  <DatePicker
    locale="fa"
    :auto-submit="false"
    :clearable="true"
    mode="single"
    type="datetime"
    element="birth"
    click-on="all"
    shortcut
    :column="3"
    color="red"
    placeholder="تاریخ تولد"
  />
</template>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
