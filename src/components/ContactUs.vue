<template>
  <section class="contact-wrapper">
      <div class="container">
        <div class="contact-sec">
          <h2>Conviced to work with us?</h2>
          <p>Company has helped agencies keep their promises to clients 2005.</p>
          <form>
            <div class="fields-wrapper">
              <div class="input-fields">
                <input type="text" id="fname" name="fname" placeholder="Fullname"
                  onfocus="this.placeholder = ''" onblur="this.placeholder = 'Fullname'">
              </div>
              <div class="input-fields">
                <input type="text" id="fname" name="fname" placeholder="Email Address"
                  onfocus="this.placeholder = ''" onblur="this.placeholder = 'Email Address'">
              </div>
              <div class="input-fields">
                <input type="text" id="fname" name="fname" placeholder="Phone Number"
                  onfocus="this.placeholder = ''" onblur="this.placeholder = 'Phone Number'">
              </div>
            </div>
            <div class="text-wrap">
              <textarea>Message in brief</textarea>
            </div>
          </form>
          <button type="button">Submit</button>
        </div>
      </div>
      <!-- container -->
    </section>
</template>

<script>

export default {
  name: 'Contact-us',
};

</script>

<style scoped lang="scss">
</style>
