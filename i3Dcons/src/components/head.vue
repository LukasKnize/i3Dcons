<template>
  <header>
    <img src="@/assets/logoi3d.png" alt="" />
    <nav>
      <a href="">Icons</a>
      <a href="">About</a>
      <a href="">Contact</a>
    </nav>
  </header>
</template>

<script>
export default {
  name: "head",
};
</script>

<style scoped>
header {
    color: #3C096C;
    width: calc(100% - 100px);
    height: 70px;
    padding-left: 50px;
    padding-right: 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header img{
    height: 50px;
}

header nav{
    display: flex;
    width: 300px;
    justify-content: space-evenly;
}

header nav a{
    text-decoration: none;
    font-weight: 700;
}
</style>