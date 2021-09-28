<template>
  <div class="footer-container">
    <div class="container">
      <div class="logo">
        <NuxtLink to="/">
          <img src="../../../assets/images/logo.svg" alt="logo">
        </NuxtLink>
      </div>
      <div class="links">
        <ul class="list-unstyled">
              <li>
                <NuxtLink to="/">Home</NuxtLink>
              </li>
              <li>
                <NuxtLink to="/about-us">About US</NuxtLink>
              </li>
              <li>
                <NuxtLink to="/services">Service</NuxtLink>
              </li>
              <li>
                <NuxtLink to="/contact-us">Contact US</NuxtLink>
              </li>
        </ul>
      </div>
      <div class="social">
        <a href="https://www.facebook.com/WeFlyPlus" target="_blank" rel="FaceBook">
          <i class="fab fa-facebook-f"></i>
        </a>
        <a href="https://www.instagram.com/weflyplus/" target="_blank" rel="instagram">
          <i class="fab fa-instagram"></i>
        </a>
        <a href="#" rel="twitter">
          <i class="fab fa-twitter"></i>
        </a>
        <a href="#" rel="linkedin">
          <i class="fab fa-linkedin-in"></i>
        </a>
      </div>
      <hr class="border"/>
      <div class="copy">
      <p>Copyright @ We Fly. All Right Reserved</p>
      </div>
    </div>
  </div>
</template>
