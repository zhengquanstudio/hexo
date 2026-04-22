---
title: 壁纸
date: 2026-04-20
---

<!-- 引入 Fancybox -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fancyapps/fancybox@3.5.7/dist/jquery.fancybox.min.css">
<script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@fancyapps/fancybox@3.5.7/dist/jquery.fancybox.min.js"></script>

<!-- 核心：一行3个图片的网格布局 -->
<style>
.photo-grid {
  display: grid;
  /* 一行3个，自动换行，自适应宽度 */
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 15px; /* 图片之间的间距 */
  margin: 15px 0;
}
.photo-grid img {
  width: 100%;
  border-radius: 8px; /* 圆角，可选 */
}
</style>

<div class="photo-grid">
  <a href="https://img.langya.org.cn/images/2026/04/1776845493" data-fancybox="gallery" data-caption="壁纸">
    <img src="https://img.langya.org.cn/images/2026/04/1776845493">
  </a>
  <a href="https://img.langya.org.cn/images/2026/04/1776845495" data-fancybox="gallery" data-caption="壁纸">
    <img src="https://img.langya.org.cn/images/2026/04/1776845495">
  </a>
  <a href="https://img.langya.org.cn/images/2026/04/1776845496" data-fancybox="gallery" data-caption="壁纸">
    <img src="https://img.langya.org.cn/images/2026/04/1776845496">
  </a>
  <a href="https://img.langya.org.cn/images/2026/04/1776845500" data-fancybox="gallery" data-caption="壁纸">
    <img src="https://img.langya.org.cn/images/2026/04/1776845500">
  </a>
  <a href="https://img.langya.org.cn/images/2026/04/1776845501" data-fancybox="gallery" data-caption="壁纸">
    <img src="https://img.langya.org.cn/images/2026/04/1776845501">
  </a>

</div>