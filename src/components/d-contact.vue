<template>
  <div class="container">
    <div class="sec_title">
      <h1>Let<span>'</span>s Talk</h1>
    </div>
    <div class="sec_body">
      <div class="contacts">
        <div class="my">
          <img src="../assets/img/phone.png" alt="phone_logo">
          <a href="tel:+7 996 624-93-44" type="phone">+7 9966249344</a>
        </div>
        <div class="my">
          <img src="../assets/img/email.png" alt="email_logo">
          <a  href= "mailto: davlat.azizov.4712@gmail.com">davlat.azizov.4712@gmail.com</a>
        </div>
        <div class="my">
          <img src="../assets/img/location.png" alt="loc_logo">
          <a href="https://www.google.com/maps/place/Samara">Russia, Samara</a>
        </div>
      </div>
      <hr class="contact_secline"/>
      <div class="contactme">
        <form action="https://formsubmit.co/davlat.azizov.4712@gmail.com" method="POST">
          <div>
            <p>Your name</p>
            <input v-model="name" type="text" name="name"/>
          </div>

          <div>
            <p>Your email</p>
            <input v-model="email" type="email" name="email"/>
          </div>

          <div>
            <p>Your message</p>
            <textarea v-model="message" name="message" type="message"></textarea>
          </div>
          <div class="sec_btn">
            <button class = "contactbtn" type="submit">Submit</button>
            <button @click="onReset" class = "contactbtn" type="reset">Reset</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>    
export default {
  name: "Contact",
  props: true,
  data() {
    return {
      name: "",
      email: "",
      message: "",
    };
  },
  methods: {
    onReset() {
      this.name = "";
      this.email = "";
      this.message = "";
    },

  },
};
</script>

<style src="../assets/style/styles.scss" lang="scss">
</style>
