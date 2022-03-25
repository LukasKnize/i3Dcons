<template>
  <div class="topAreaContainer">
    <div class="leftContainer">
      <h2>Lorem ipsum dolor sit amet, consectetur adipiscing elit</h2>
      <h3>Quis enim lobortis scelerisque fermentum.</h3>
      <div class="search">
        <input type="text" name="" class="searchInput" placeholder="Search" />
        <i class="fas fa-search"></i>
      </div>
    </div>
    <div class="rightContainer">
      <img src="@/assets/perspective_matte.png" alt="" />
    </div>
  </div>
</template>

<style scoped>
.topAreaContainer {
  width: 100%;
  height: calc(100vh - 70px);
  display: flex;
}

.topAreaContainer .leftContainer {
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 100%;
  width: 50%;
  color: #3c096c;
}

.topAreaContainer .leftContainer h2 {
  margin-left: 50px;
  font-size: 1.3em;
  margin-bottom: 15px;
  font-weight: 700;
}

.topAreaContainer .leftContainer h3 {
  margin-left: 50px;
  font-size: 1.1em;
  margin-bottom: 35px;
  font-weight: 700;
}

.topAreaContainer .leftContainer .search {
  position: relative;
}

.topAreaContainer .leftContainer .search .searchInput {
  width: 330px;
  height: 58px;
  border-radius: 50px;
  margin-left: 50px;
  padding-left: 20px;
  border: none;
  background: #e0e0e0;
  box-shadow: -29px 29px 58px #929292, 29px -29px 58px #ffffff;
}

.topAreaContainer .leftContainer .search .fa-search {
  position: absolute;
  top: calc(50% - 8px);
  left: 364px;
  height: 20px;
}

.topAreaContainer .leftContainer .search .searchInput:focus-visible {
  background: linear-gradient(225deg, #f0f0f0, #cacaca);
box-shadow:  -29px 29px 58px #929292,
             29px -29px 58px #ffffff;
  border: none;
  outline: none;
}

.topAreaContainer .rightContainer {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 50%;
}

.topAreaContainer .rightContainer img {
  width: 85%;
}
</style>