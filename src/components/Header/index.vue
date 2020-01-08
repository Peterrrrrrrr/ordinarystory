<template>
  <header id="header">
    <div class="content">
      <ul>
        <li>
          <p>huhuLife</p>
        </li>
        <li>
          <p>|</p>
        </li>
        <li class="backpack">
          <i class="icon iconfont icon-shubao"></i>
        </li>
        <li class="mac">
          <i class="icon iconfont icon-diannao"></i>
        </li>
        <li class="coffe">
          <i class="icon iconfont icon-iconkafei"></i>
        </li>
        <li >
          <i class="icon iconfont icon-jita-liangse-"></i>
        </li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "header"
};
</script>

<style>
#header {
  width: 100%;
  height: 49px;
  position: fixed;
  z-index: 1000;
  top: 0;
  background-color: rgba(255, 255, 255, 0.7);
  border-bottom: 1px solid rgb(238, 238, 238);
}
#header .content {
  display: flex;
  height: 49px;
  align-items: center;
  justify-content: center;
}
#header ul {
  display: flex;
  text-align: center;
  height: 49px;
  width: 60%;
  align-items: center;
}
#header ul li {
  flex: 1;
  height: 40px;
  padding: 0;
}
#header ul .backpack i {
  font-size: 18px;
}
#header ul .mac{
  margin-top: 2px;
}
#header ul .coffe{
  margin-bottom: 5px;
}
#header ul i {
  font-size: 20px;
  color: #666666;
}
#header ul p {
  font-size: 18px;
  font-family:'微軟正黑體';
  color: #666666;
}
</style>