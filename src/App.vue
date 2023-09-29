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
    
    <!-- เนื้อหาแอปของคุณ -->
    <RouterView />
  </div>
</template>

<script setup>
import { RouterView } from 'vue-router'
</script>
