<script setup>
const items = ref([
  {
    name: "Máy tính & Laptop",
  },
  {
    name: "Phụ kiện máy tính",
  },
  {
    name: "Bộ chia cổng USB & Đọc thẻ nhớ",
  },
]);
</script>

<template>
  <div class="breadcrumb">
    <IconHome />
    <div class="item" v-for="item in items">
      <ArrowRight style="margin-left: 1rem"></ArrowRight>
      <div style="margin-left: 1rem">
        <a href="/">{{ item.name }}</a>
      </div>
    </div>
  </div>
</template>

<style scoped>
.breadcrumb {
  display: flex;
  align-items: center;
  height: 40px;
}

.item {
  display: flex;
  font-weight: 500;
  color: rgb(75, 85, 99);
}

a {
  text-decoration: none;
  color: rgb(75, 85, 99);
}

a:visited {
  color: rgb(75, 85, 99);
}
</style>
