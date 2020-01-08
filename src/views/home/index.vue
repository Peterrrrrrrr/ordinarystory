<template>
  <div>
    <Header />
    <!-- <div class="begin">
      <i class="icon iconfont icon-shang-copy-copy"></i>
      <i class="icon iconfont icon-shang-copy-copy"></i>
      <i class="icon iconfont icon-shang-copy-copy"></i>
    </div> -->
    <div>
      <ul class="wrap">
        <li class="begin">
          <i class="icon iconfont icon-shang-copy-copy"></i>
          <i class="icon iconfont icon-shang-copy-copy"></i>
          <i class="icon iconfont icon-shang-copy-copy"></i>
        </li>
        <li>
          <img src="/img/1.JPG" alt />
        </li>
        <li>
          <img src="/img/2.JPG" alt />
        </li>
        <li>
          <img src="/img/3.jpg" alt />
        </li>
        <li>
          <img src="/img/4.jpg" alt />
        </li>
        <li>
          <img src="/img/5.JPG" alt />
        </li>
        <li>
          <img src="/img/6.JPG" alt />
        </li>
        <li>
          <img src="/img/7.jpg" alt class="test" />
        </li>
        <li>
          <img src="/img/8.JPG" alt />
        </li>
        <li>
          <img src="/img/9.JPG" alt />
        </li>
        <li>
          <img src="/img/10.jpg" alt />
        </li>
        <li>
          <img src="/img/11.jpg" alt />
        </li>
        <li>
          <img src="/img/12.JPG" alt />
        </li>
        <li>
          <img src="/img/13.JPG" alt />
        </li>
        <li>
          <img src="/img/14.JPG" alt />
        </li>
        <li>
          <img src="/img/15.JPG" alt />
        </li>
        <li>
          <img src="/img/16.JPG" alt />
        </li>
        <li>
          <img src="/img/18.JPG" alt />
        </li>
        <li>
          <img src="/img/19.JPG" alt />
        </li>
        <li>
          <img src="/img/20.JPG" alt />
        </li>
        <li>
          <img src="/img/21.JPG" alt />
        </li>
        <li>
          <img src="/img/22.JPG" alt />
        </li>
        <li>
          <img src="/img/23.JPG" alt />
        </li>
        <li>
          <img src="/img/24.JPG" alt />
        </li>
        <li>
          <img src="/img/25.JPG" alt />
        </li>
        <li>
          <img src="/img/26.JPG" alt />
        </li>
        <li>
          <img src="/img/27.JPG" alt />
        </li>
        <li>
          <img src="/img/28.JPG" alt />
        </li>
        <li>
          <img src="/img/29.JPG" alt />
        </li>
        <li>
          <img src="/img/30.JPG" alt />
        </li>
        <li>
          <img src="/img/31.JPG" alt />
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import Header from "@/components/Header";
export default {
  name: "home",
  components: {
    Header
  }
};
</script>

<style>
.begin {
  margin-top: 300px;
  margin-bottom: 150px;
}
.begin i {
  font-size: 50px;
  color: #333333;
}
.wrap {
  padding-left: 0;
}
li {
  margin: 0 auto;
  padding-bottom: 200px;
  display: flex;
  width: 80%;
  /* height: 80%; */
  justify-content: center;
  align-items: center;
}

img {
  width: 90%;
}
.test {
  width: 70%;
}
</style>
