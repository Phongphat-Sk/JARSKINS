<template>
  <div id="app">
    <!-- เฮดเดอร์ที่กำหนดเอง -->
    <header class="custom-header">
      <!-- ส่วนเพิ่มเติมเพื่อจัดให้ช่องค้นหาแบบวงลีอยู่กึ่งกลาง -->
      <div class="header-content">
        <!-- ด้านซ้ายมีข้อความว่า JARJOSUDLOR เป็น logo -->
        <div class="logo"><a href="">JARJOSUDLOR</a></div>  
        <div class="into">
          <div class="wallet">
            <div class="input-container">
              <span class="currency-icon">B</span> 
                  <input class="wallet-input" type="text" value=" 0.00" readonly/>
                  <button class="add-money-button">+</button>
                </div>
          </div> 
                <div class="product-icon">
                    <a href="/src/item/item_knife.html">ตลาด</a>
                    <a href="/src/headder/inventory.html">คลังสินค้า</a>
                    <a href="/src/headder/buy_order.html">การซื้อ</a>
                    <a href="/src/headder/sell_order.html">การขาย</a>
                    <a href="">เข้าสู่ระบบ</a>
                </div> 
          </div>
                

      </div>
    </header>

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
      <a href="">
        <img src="src\assets\pic\chevron-arrow-up.png" alt="" width="25px" height="25px">
      </a>
      <img src="src\assets\pic\clipart1589423.png" alt="" width="25px" height="25px">
    </figure>
  </div>


  
  <div class="contai1">
    <p>ค้นหาบ่อย : </p>
    <div class="alltag">
      <div class="tags">
        <button>ค้นหาบ่อย</button>
      </div>
      <div class="tags">
        <button>ค้นหาบ่อย</button>
      </div>
      <div class="tags">
        <button>ค้นหาบ่อย</button>
      </div>
      <div class="tags">
        <button>ค้นหาบ่อย</button>
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
    <h2>เลือกหมวดหมู่สินค้า</h2>
    <div class="bigfig">
      <figure>
        <div class="ball">
          <a href="/src/item/item_knife.html">
            <img src="/src/assets/pic/Rectangle 19.png">
          </a>
        </div>
        <div class="ball">
          <a href="/src/item/item_pistol.html">
            <img src="/src/assets/pic/Rectangle 20.png">
          </a>
        </div>
        <div class="ball">
          <a href="/src/item/item_submach.html">
            <img src="/src/assets/pic/Rectangle 21.png">
          </a> 
        </div>
        <div class="ball">
          <a href="/src/item/item_rifle.html">
            <img src="/src/assets/pic/Rectangle 22.png">
          </a> 
        </div>
        <div class="ball">
          <a href="/src/item/item_heavymach.html">
            <img src="/src/assets/pic/Rectangle 23.png">
          </a> 
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
      <a href="src/item/item_knife.html">
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
        <a href="src/item/item_knife.html">
          <button>รายการ</button>
        </a>
      </div>
    </div>
  </div>

  
  <footer class="site-footer">
      <div class="f1">
        <h3>JARJOSUDLOR</h3>
        <p>Powered by Steam. Not affiliated with Valve Corp.</p>
        <p>
          &copy; 2023 JARJOSUDLOR | 
          <a>นโยบายความเป็นส่วนตัว</a> | 
          <a>ข้อกำหนดการให้บริการ</a> | 
          <a>นโยบายคุกกี้</a>
        </p>
      </div>
      <div class="f2">
        <div class="f21">

          <h3>Introduction</h3>
          <p>Privacy Statement</p>
          <p>Terms of Service</p>
          <p>Cookie policy</p>
        </div>
        <div class="f22">
          <h3>Payment methods</h3>
          <p>prompt pay</p>
          <p>true money</p>
        </div>
      </div>


    </footer>
  </div>
</template>

<style>


</style>

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
