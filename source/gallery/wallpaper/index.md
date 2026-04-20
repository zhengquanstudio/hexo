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
  <a href="/img/gallery/photo/1.png" data-fancybox="gallery" data-caption="图1">
    <img src="/img/gallery/photo/1.png">
  </a>
  <a href="/img/gallery/photo/2.png" data-fancybox="gallery" data-caption="图2">
    <img src="/img/gallery/photo/2.png">
  </a>
  <a href="/img/gallery/photo/3.png" data-fancybox="gallery" data-caption="图3">
    <img src="/img/gallery/photo/3.png">
  </a>
  <a href="/img/gallery/photo/4.png" data-fancybox="gallery" data-caption="图4">
    <img src="/img/gallery/photo/4.png">
  </a>
  <a href="/img/gallery/photo/5.png" data-fancybox="gallery" data-caption="图5">
    <img src="/img/gallery/photo/5.png">
  </a>

</div>