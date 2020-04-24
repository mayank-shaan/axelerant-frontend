<template>
  <header>
        <div class="container" >

          <a href="#" class="company-logo">
            <img src="@/assets/images/logo.png" alt="company-logo">
          </a>
          <div class="header-right">
            <button class="hamburger" :class="menuOpen ? 'open' : ''" @click="menuOpen = !menuOpen" >
              <span class="lines top"></span>
              <span class="lines middle"></span>
              <span class="lines bottom"></span>
            </button>

            <ul class="menu" :class="menuOpen ? 'right-to-left' : ''">
              <li>
                <a href="#">About</a>
              </li>
              <li>
                <a href="#">Services</a>
              </li>
              <li>
                <a href="#">Solutions</a>
              </li>
              <li>
                <a href="#">Blog</a>
              </li>
              <li><button @click="handleGetInTouch"><i class="icon-btn"></i>Get in Touch</button></li>
            </ul>
          </div>
        </div>

      </header>
</template>

<script>

export default {
  name: 'Header',
  data: () => ({
    menuOpen: false,
  }),
  methods: {
    handleGetInTouch() {
      // console.log('here');
      this.menuOpen = !this.menuOpen;
      document.getElementById('contactUs').scrollIntoView();
    },
  },
};

</script>

<style scoped lang="scss">
</style>
