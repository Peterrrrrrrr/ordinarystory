<template>
  <div id="footer">
    <div class="footerwrap">
      <ul>
        <li >
          <i class="icon iconfont icon-shang-copy-copy"></i>
          <i class="icon iconfont icon-shang-copy-copy"></i>
        </li>
      </ul>
      <div class="link">
        <p>
          <a href="https://github.com/Peterrrrrrrr/ordinarystory/tree/dev">@作业本</a>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "footer"
};
</script>

<style>
#footer {
  display: flex;
  justify-content: center;
  bottom: 0;
}
.footerwrap {
  margin-top: 140px;
  margin-bottom: 50px;
}
.footerwrap ul{
    margin-bottom: 80px;
}
#footer i {
  font-size: 50px;
  color: #333333;
  transform: rotate(180deg);
}
.link {
  height: 20px;
  width: 100%;
}
.link p {
  height: 20px;
  text-align: center;
}
#footer a {
  font-size: 15px;
  font-family: "微軟正黑體";
  color: #666666;
  text-decoration: none;
}
</style>