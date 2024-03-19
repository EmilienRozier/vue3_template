<template>
  <nav>
    <ul>
      <li><a href="/">menu</a></li>
      <li><a href="#">menu</a></li>
      <li><a href="#">menu</a></li>
      <li><a href="#">menu</a></li>
    </ul>
  </nav>
</template>

<style scoped>
nav {
  width: 100%;
  margin: 25px 0;
}

nav>ul {
  display: flex;
  justify-content: space-around;
  width: 50%;
  margin: 0 auto;
}

nav>ul>li {
  list-style: none;
}
</style>