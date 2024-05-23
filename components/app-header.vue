<template>
  <header>
    <div class="header-content">
      <img
        class="logo"
        src="https://lh3.googleusercontent.com/pw/ADCreHd5PMvwKUSbjtSRpUfeyDaazAbdXF1H0arvHtS62AyfivDEAN6hRSq-GTJ6wKiyn-9IEr63aaiNtFq6J2fP_I6VtpGAIwqAQu4B2mL64M2h2HHkPY4VhRWoDpag5VXN3Dxtwb277ZDkXPa0mnDxTTGL=w512"
      />
      <SearchTextBox></SearchTextBox>
      <div class="links">
        <div style="margin-left: 1rem">
          <CategoryButton></CategoryButton>
          <a href="#" style="margin-left: 0.5rem">DANH MỤC</a>
        </div>
        <div style="margin-left: 1rem">
          <a href="#/blog">BLOG</a>
        </div>
      </div>
    </div>
  </header>
</template>

<style scoped>
.logo {
  height: 3rem;
  margin-right: 1.5rem;
}

header {
  border-bottom: 1px solid #e8eaed;
  padding-top: 1rem;
  padding-bottom: 1rem;
  display: flex;
  justify-content: center;
}

.header-content {
  width: 840px;
  height: calc(100% - 1px);
  display: flex;
}

a {
  color: black;
  text-decoration: none;
}

a:visited {
  color: black;
}

.links {
  display: flex;
  align-items: center;
}
</style>
