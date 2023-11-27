<template lang="">
  <header
    class="fixed top-0 left-0 right-0 md:flex md:justify-between md:items-center px-10 py-4 shadow-md bg-white z-10"
    style="height: 70px"
  >
    <img
      src="img/STELK LOGO.png"
      alt="logo"
      width="200"
      class="absolute -left-10 -top-5 md:relative md:top-0"
    />
    <div>
      <div
        class="hamburger absolute right-4 top-6 cursor-pointer md:hidden"
        id="hamburger"
        @click="click"
      >
        <span class="hamburger-line"></span>
        <span class="hamburger-line mt-2"></span>
        <span class="hamburger-line mt-2"></span>
      </div>
      <nav
        class="bg-white p-5 rounded-md absolute right-4 top-12 hidden md:block md:static md:bg-transparent"
      >
        <ul class="flex flex-col gap-2 md:gap-10 md:flex-row">
          <li><a href="#home">Jalur Pendaftaran</a></li>
          <li><a href="#jalur">Jadwal</a></li>
          <li><a href="#home">Profil Jurusan</a></li>
          <li><a href="#home">Hubungi Kami</a></li>
          <li v-if="logged"><a href="#/login">Keluar</a></li>
          <li v-else><a href="#/login">Login</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
import { ref, watchEffect } from "vue";

export default {
  setup() {
    const logged = ref(false);

    watchEffect(() => {
      let url = window.location.href.split("/");
      let page = url[url.length - 1];
      if (page === "logged") {
        logged.value = true;
      }
    });

    return { logged };
  },
  methods: {
    click() {
      const nav = document.querySelector("nav");

      nav.classList.toggle("hidden");
    },
  },
};
</script>

<style scoped>
.hamburger-line {
  display: block;
  width: 30px;
  height: 2px;
  background-color: black;
}
</style>
