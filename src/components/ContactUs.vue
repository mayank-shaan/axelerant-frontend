<template>
  <section class="contact-wrapper" id="contactUs">
      <div class="container">
        <div class="contact-sec">
          <h2>Conviced to work with us?</h2>
          <p>Company has helped agencies keep their promises to clients 2005.</p>
          <form>
            <div class="form-container">
              <div class="input-fields">
                <input type="text" id="name" name="name" placeholder="Fullname">
              </div>
              <div class="input-fields">
                <input type="email" id="email" name="email" placeholder="Email Address">
              </div>
              <div class="input-fields">
                <input type="number" id="number" name="number" placeholder="Phone Number">
              </div>
            </div>
            <div class="text-wrap">
              <textarea placeholder="Message in breif">
              </textarea>
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
.form-container {
  margin-bottom: 15px;

  .input-fields {
    margin-bottom: 15px;
  }

  input {
    width: 100%;
    padding: 9px 15px;
    border: none;
    // @include transition(all 0.3s ease-in-out);
    outline: none;
    border-radius: 5px;
    border: 2px solid transparent;
    // font-size: $base-font * 1.4;

    &:focus {
      border: 2px solid #bdbaba;
    }
  }
}

@media (min-width: 768px) {
  .contact-sec {
    form {
      margin: 0 100px;
    }
  }
  .form-container {
    display: flex;
    // align-items: center;
    justify-content: space-between;
    .input-fields {
      width: 30%;
      margin-bottom: 0;
    }
  }
}
</style>
