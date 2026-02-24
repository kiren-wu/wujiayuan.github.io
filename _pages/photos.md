---
title: "Photos"
permalink: /photos/
author_profile: true
---

## Moments

<div class="photo-grid">

  <div class="photo-item">
    <img src="/images/Friends.JPG" alt="">
  </div>

  <div class="photo-item">
    <img src="/images/Friends2.JPG" alt="">
  </div>

  <div class="photo-item">
    <img src="/images/IMG_2804.JPG" alt="">
  </div>

  <div class="photo-item">
    <img src="/images/IMG_2805.JPG" alt="">
  </div>

  <div class="photo-item">
    <img src="/images/IMG_2806.JPG" alt="">
  </div>

  <div class="photo-item">
    <img src="/images/IMG_2807.JPG" alt="">
  </div>

</div>

<style>
.photo-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
  gap: 18px;
  margin-top: 20px;
}

.photo-item {
  overflow: hidden;
  border-radius: 14px;
  box-shadow: 0 6px 18px rgba(0,0,0,0.08);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.photo-item img {
  width: 100%;
  height: 220px;        /* 统一显示高度 */
  object-fit: cover;    /* 自动裁剪居中 */
  transition: transform 0.4s ease;
}

.photo-item:hover {
  transform: translateY(-6px);
  box-shadow: 0 12px 30px rgba(0,0,0,0.15);
}

.photo-item:hover img {
  transform: scale(1.08);
}
</style>
