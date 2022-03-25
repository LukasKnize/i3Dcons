<template>
  <div class="iconContainer">
    <p class="cost">FREE</p>
    <img src="@/assets/perspective_matte.png" alt="" />
    <p class="name">MEDIA</p>
  </div>
</template>

<style scoped>
.iconContainer {
  width: 200px;
  height: 200px;
  border-radius: 50px;
  background: linear-gradient(225deg, #f0f0f0, #cacaca);
  box-shadow: -29px 29px 58px #929292, 29px -29px 58px #ffffff;
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  justify-content: space-around;
  align-items: center;
}

.iconContainer:hover {
  border-radius: 50px;
  background: linear-gradient(225deg, #cacaca, #f0f0f0);
  box-shadow: -29px 29px 58px #929292, 29px -29px 58px #ffffff;
}

.iconContainer .cost {
  width: 155px;
  text-align: right;
}

.iconContainer img {
  height: 50px;
}

.iconContainer name {
  width: 100%;
  text-align: center;
}
</style>