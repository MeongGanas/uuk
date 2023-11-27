<template>
  <div class="login">
    <img
      src="img/wave.png"
      alt=""
      class="absolute left-0 h-screen"
      width="800"
    />
    <img
      src="img/stelk logo.png"
      alt=""
      class="absolute top-0 right-0"
      width="200"
    />
    <div
      class="w-full h-screen lg:flex p-5 lg:justify-end lg:items-center md:px-10"
    >
      <div class="relative w-full lg:w-1/2">
        <img
          src="img/Siswa stelk.png"
          alt=""
          class="relative bottom-0 max-w-full"
        />
      </div>
      <div class="w-full flex justify-center mt-20 lg:mt-0 lg:w-1/2">
        <div
          class="w-full mt-20 p-5 shadow-md max-w-md rounded-md relative bg-white"
        >
          <div class="absolute -top-10 right-[40%]">
            <img src="img/Sehati.png" alt="logo" width="100" />
          </div>
          <div>
            <input
              type="text"
              name="username"
              id="username"
              placeholder="Username"
              class="w-full px-4 py-3 mb-6 mt-16 border-b border-b-black focus:outline-none"
            />

            <input
              type="password"
              name="password"
              id="password"
              placeholder="Password"
              class="w-full px-4 py-3 border-b border-b-black focus:outline-none"
            />
          </div>
          <button
            class="w-full bg-red-600 text-white py-2 rounded-md mb-2 mt-7 uppercase"
            @click="login"
          >
            Masuk
          </button>
          <p class="text-slate-500 w-full text-center text-sm">
            Powered by Sistelk Project
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  setup() {
    function login() {
      window.location.href = "#/logged";
    }

    return { login };
  },
};
</script>
