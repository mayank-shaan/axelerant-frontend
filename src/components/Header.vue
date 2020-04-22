<template>
  <header>
        <div class="container" >

          <a href="#" class="logo"><img src="@/assets/images/logo.png" alt="Payoo-logo" width="174" height="51"></a>
          <div class="header-right">
            <button class="hamburger">
              <span class="lines top">hamburger</span>
              <span class="lines middle">hamburger</span>
              <span class="lines bottom">hamburger</span>
            </button>

            <ul class="menu">
              <li><a href="#">About</a></li>
              <li><a href="#">Services</a></li>
              <li> <a href="#">Solutions</a></li>
              <li><a href="#">Blog</a></li>
              <li><button class="log-in-button"><i class="icon-btn"></i>Get in Touch</button></li>
            </ul>
          </div>
        </div>

      </header>
</template>

<script>

export default {
  name: 'Header',
};

</script>

<style scoped lang="scss">
</style>
