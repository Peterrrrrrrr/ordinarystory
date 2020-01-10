<template>
  <div>
    <Header />
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
          <img class="square" src="/img/4a.jpg" alt />
        </li>
        <li>
          <img src="/img/4b.jpg" alt />
        </li>
        <li>
          <img src="/img/5.JPG" alt />
        </li>
        <li>
          <img class="rectangle" src="/img/6b.JPG" alt />
        </li>
        <li>
          <img class="square" src="/img/6a.JPG" alt />
        </li>
        <li>
          <img src="/img/7.jpg" alt />
        </li>
        <li>
          <img src="/img/8.JPG" alt />
        </li>
        <li>
          <img class="square" src="/img/9.JPG" alt />
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
          <img class="square" src="/img/13.JPG" alt />
        </li>
        <li>
          <img src="/img/14.JPG" alt />
        </li>
        <li>
          <img src="/img/15.JPG" alt />
        </li>
        <li>
          <img class="square" src="/img/16.JPG" alt />
        </li>
        <li>
          <img class="square" src="/img/17.JPG" alt />
        </li>
        <li>
          <img class="square" src="/img/18.JPG" alt />
        </li>
        <li>
          <img class="square" src="/img/19.JPG" alt />
        </li>
        <li>
          <img src="/img/20.JPG" alt />
        </li>
        <li>
          <img class="square" src="/img/21.JPG" alt />
        </li>
        <li>
          <img class="rectangle" src="/img/22.JPG" alt />
        </li>
        <li>
          <img src="/img/23.JPG" alt />
        </li>
        <li>
          <img class="rectangle" src="/img/24.JPG" alt />
        </li>
        <li>
          <img class="square" src="/img/25.JPG" alt />
        </li>
        <li>
          <img src="/img/26.JPG" alt />
        </li>
        <li>
          <img class="square" src="/img/27.JPG" alt />
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
          <img class="square" src="/img/31.JPG" alt />
        </li>
        <li>
          <img class="square" src="/img/32.JPG" alt />
        </li>
        <li>
          <img src="/img/34.JPG" alt />
        </li>
        <li>
          <img class="square" src="/img/34a.JPG" alt />
        </li>
        <li>
          <img src="/img/35.JPG" alt />
        </li>
        <li>
          <img src="/img/36.JPG" alt />
        </li>
        <li>
          <img class="rectangle" src="/img/37.JPG" alt />
        </li>
        <li>
          <img  class="square" src="/img/37a.JPG" alt />
        </li>
        <li>
          <img src="/img/38.JPG" alt />
        </li>
        <li>
          <img src="/img/39.JPG" alt />
        </li>
      </ul>
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header";
import Footer from "@/components/Footer";
export default {
  name: "home",
  components: {
    Header,
    Footer
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
.square {
  width: 80%;
}
.rectangle {
  width: 70%;
}
</style>
