<script setup lang="ts">
import SearchButton from "./search-button.vue";
</script>

<template>
  <div class="wrapper">
    <input placeholder="Dán link hoặc tìm sản phẩm" />
    <div class="search-button-container">
      <SearchButton></SearchButton>
    </div>
  </div>
</template>

<style scoped>
input {
  box-sizing: border-box;
  border-radius: 9999px;
  padding-left: 1.25rem;
  padding-right: 80px;
  border: 1px solid rgb(209, 213, 219);
  height: 40px;
  width: 100%;
}

input:focus {
  outline-width: 0;
}

.search-button-container {
  position: absolute;
  height: 100%;
  top: 0;
  right: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 48px;
  align-items: center;
}

.wrapper {
  position: relative;
  flex-grow: 1;
  align-content: center;
}
</style>
