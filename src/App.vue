<template>
  <div id="app">
    <!-- เฮดเดอร์ที่กำหนดเอง -->
    <header class="custom-header">
      <!-- ส่วนเพิ่มเติมเพื่อจัดให้ช่องค้นหาแบบวงลีอยู่กึ่งกลาง -->
      <div class="header-content">
        <!-- ด้านซ้ายมีข้อความว่า JARJOSUDLOR เป็น logo -->
        <div class="logo">JARJOSUDLOR</div>
        
        <!-- ทางขวาของช่องสีขาวมีลิงค์ตระกล้าสินค้า -->
        <div class="product-icon1">
          <a href="/src/sell_order.html">
            <img src="/src/assets/pic/icon product.png" >
          </a>
        </div>
        
      </div>
    </header>

    <div class="subhead">
      <div class="alltag">
      <div class="tags">
        <button><a>Give away</a></button>
      </div>
      <div class="tags">
        <button><a>Market</a></button>
      </div>
      </div>

      <div class="search-box">
        <input class="search-input" type="text" placeholder="คุณกำลังมองหาอะไรอยู่"/>
        <button class="serch-button" >ค้นหา</button>
      </div>
      <a href="src\login.vue">
        <button class="login">เข้าสู่ระบบ</button>
      </a>
  </div>

  <div class="carousel" data-flickity='{ "wrapAround": true, "autoPlay": true, "imagesLoaded": true }'>
  <div class="carousel-cell">
    <img class="w3-image carousel-img" src="/src/assets/pic/carousel1.webp">
  </div>
  <div class="carousel-cell">
    <img class="w3-image carousel-img" src="/src/assets/pic/carousel2.webp">
  </div>
  <div class="carousel-cell">
    <img class="w3-image carousel-img" src="/src/assets/pic/carousel3.webp">
  </div>
</div>


  




  <div class="nav">
    <figure> 
      <a href="#">
        <img src="src\assets\pic\chevron-arrow-up.png" alt="" width="25px" height="25px">
      </a>
      <img src="src\assets\pic\clipart1589423.png" alt="" width="25px" height="25px">
      <img src="src\assets\pic\playerLeft.png" alt="" width="25px" height="25px">
    </figure>
  </div>


  
  <div class="contai1">
    <p>ค้นหาบ่อย : </p>
    <div class="alltag">
      <div class="tags">
        <button><a>ค้นหาบ่อย</a></button>
      </div>
      <div class="tags">
        <button><a>ค้นหาบ่อย</a></button>
      </div>
      <div class="tags">
        <button><a>ค้นหาบ่อย</a></button>
      </div>
      <div class="tags">
        <button><a>ค้นหาบ่อย</a></button>
      </div>
    </div>
  </div>

  <div class="contai2">
    <figure>
      <a href="#">
         <img src="/src/assets/pic/Rectangle 11.png" alt="">
      </a>
      <a href="#">
        <img src="/src/assets/pic/Rectangle 12.png" alt="">
      </a>
      <a href="#">
        <img src="/src/assets/pic/Rectangle 13.png" alt="">
      </a>
      <a href="#">
        <img src="/src/assets/pic/Rectangle 14.png" alt="">
      </a>
    </figure>
    <figure>
      <a href="#">
        <img src="/src/assets/pic/Rectangle 15.png" alt="">
      </a>
      <a href="#">
        <img src="/src/assets/pic/Rectangle 16.png" alt="">
      </a>
      <a href="#">
        <img src="/src/assets/pic/Rectangle 17.png" alt="">
      </a>
      <a href="#">
        <img src="/src/assets/pic/Rectangle 18.png" alt="">
      </a>
    </figure>
  </div>

  <div class="contai3">
    <h2>Explore millions of offerings tailored to your business needs</h2>
    <div class="bigfig">
      <figure>
        <div class="ball">
           <img src="/src/assets/pic/Rectangle 19.png">
        </div>
        <div class="ball">
           <img src="/src/assets/pic/Rectangle 20.png">
        </div>
        <div class="ball">
           <img src="/src/assets/pic/Rectangle 21.png">
        </div>
        <div class="ball">
           <img src="/src/assets/pic/Rectangle 22.png">
        </div>
        <div class="ball">
           <img src="/src/assets/pic/Rectangle 23.png">
        </div>
      
    </figure>
  
    </div>
  </div>

  <div class="contai4">
    <h2>CS2GO : จุดหมายปลายทางชั้นนำของคุณสำหรับตลาดสกินที่ดีที่สุด</h2>
    <div class="bigmarket">
      <div class="market">
        <div class="marketflex">
          <div class="mtex">
            <h3>I'm the buyer</h3>
            <b>รับมากขึ้นในราคาที่ถูกลง</b>
          <p>เพลิดเพลินกับราคาที่ต่ำกว่า steam Marketplace ถึง 100%</p>
        </div>
        <img src="src\assets\pic\trolley-cart.png" alt="">
      </div>
      <a href="https://pencil05.github.io/market/">
          <button>ไปตลาด</button>
        </a>
      </div>
      <div class="market">
        <div class="marketflex">
          <div class="mtex">
            <h3>I'm the seller</h3>
            <b>2% commission</b>
            <p>Enjoy the Lowest Commission in the Market</p>
          </div>
          <img src="src\assets\pic\shop.png" alt="">
        </div>
        <a href="https://pencil05.github.io/market/">
          <button>รายการ</button>
        </a>
      </div>
    </div>


  </div>



  
    <RouterView />
  </div>
</template>

<script setup>
import { RouterView } from 'vue-router'
import { onMounted } from 'vue'
import Flickity from 'flickity'

const flickity = new Flickity('.carousel', {
  wrapAround: true,
  autoPlay: true,
  imagesLoaded: true
});

flickity.on('change', function(index) {
  // ซ่อนรูปภาพทั้งหมด
  const images = document.querySelectorAll('.carousel-img');
  images.forEach(image => {
    image.style.display = 'none';
  });

  // แสดงรูปภาพที่เกี่ยวข้องกับหน้าลูกศรปัจจุบัน
  images[index].style.display = 'block';
});


</script>
