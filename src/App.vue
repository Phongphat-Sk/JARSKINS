<template>
  <div id="app">
    <!-- เฮดเดอร์ที่กำหนดเอง -->
    <header class="custom-header">
      <!-- ส่วนเพิ่มเติมเพื่อจัดให้ช่องค้นหาแบบวงลีอยู่กึ่งกลาง -->
      <div class="header-content">
        <!-- ด้านซ้ายมีข้อความว่า JARJOSUDLOR เป็น logo -->
        <div class="logo">JARJOSUDLOR</div>
        <!-- ช่องค้นหาแบบวงลี -->
        <div class="search-box">
          <input class="search-input" type="text" placeholder="ค้นหา..." />
        </div>
        <!-- ทางขวาของช่องสีขาวมีลิงค์ตระกล้าสินค้า -->
        <div class="product-icon">
         <a href="/">
            <img src="/src/assets/pic/product-icon.png" alt="ตระกล้าสินค้า" />
         </a>
       </div>

      </div>
      <!-- สิ้นสุดส่วนเพิ่มเติม -->
    </header>
    
    <!-- เนื้อหาแอปของคุณ -->
    <RouterView />
  </div>
</template>

<script setup>
import { RouterView } from 'vue-router'
</script>
