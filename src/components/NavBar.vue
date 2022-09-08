<template>
  <div class="nav-container">
    <section class="left-nav">
      <img src="@/assets/images/logo.svg" alt="Sneakers" id="logo" />
      <ul class="selection-menu">
        <li class="selection-item">Collections</li>
        <li class="selection-item">Men</li>
        <li class="selection-item">Women</li>
        <li class="selection-item">About</li>
        <li class="selection-item">Contact</li>
      </ul>
    </section>
    <section class="right-nav">
      <div>
        <img src="@/assets/images/icon-cart.svg" alt="cart" />
        <img src="@/assets/images/image-avatar.png" />
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style>
  .nav-container {
    display: flex;
    justify-content: space-between;
  }

  .left-nav {
    display: flex;
    
  }

  #logo {
    max-height: 1.8rem;
  }

  .selection-menu {
    display: flex;
    list-style-type: none;
  }
</style>
