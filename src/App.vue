<template>
  <div id="app">
    <!-- เฮดเดอร์ที่กำหนดเอง -->
    <header class="custom-header">
      <!-- ส่วนเพิ่มเติมเพื่อจัดให้ช่องค้นหาแบบวงลีอยู่กึ่งกลาง -->
      <div class="header-content">
        <!-- ด้านซ้ายมีข้อความว่า JARJOSUDLOR เป็น logo -->
        <div class="logo">JARJOSUDLOR</div>
        
        <!-- ทางขวาของช่องสีขาวมีลิงค์ตระกล้าสินค้า -->
        <div class="product-icon">
          <a href="/">
            <img src="/src/assets/pic/product-icon.png" alt="ตระกล้าสินค้า"/>
          </a>
        </div>
        
      </div>
    </header>

    <div class="subhead">
      <div class="alltag">
        <div class="tags">
          <button><a>Lucky Card</a></button>
        </div>
        <div class="tags">
        <button><a>Lucky CardPlus</a></button>
      </div>
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
      <button class="login">เข้าสู่ระบบ</button>
  </div>
  
  <div class="nav">
    <figure>  
      <img src="src\assets\pic\chevron-arrow-up.png" alt="" width="25px" height="25px">
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
      <img src="" alt="">
      <img src="" alt="">
      <img src="" alt="">
      <img src="" alt="">
    </figure>
    <figure>
      <img src="" alt="">
      <img src="" alt="">
      <img src="" alt="">
      <img src="" alt="">
    </figure>
  </div>

  <div class="contai3">
    <h2>Explore millions of offerings tailored to your business needs</h2>
    <div class="bigfig">
      <figure>
        <div class="ball"></div>
      <div class="ball"></div>
      <div class="ball"></div>
      <div class="ball"></div>
      <div class="ball"></div>
    </figure>
    <figure>
      <div class="ball"></div>
      <div class="ball"></div>
      <div class="ball"></div>
      <div class="ball"></div>
      <div class="ball"></div>
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
        <button>ไปตลาด</button>
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
          <button>รายการ</button>
      </div>
    </div>
  </div>






    <!-- เนื้อหาแอปของคุณ -->
    <RouterView />
  </div>
</template>

<script setup>
import { RouterView } from 'vue-router'
</script>
