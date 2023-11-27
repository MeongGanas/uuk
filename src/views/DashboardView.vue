<template>
  <HeaderComponent />
  <section>
    <img
      src="img/wave.png"
      alt=""
      class="absolute -z-10 h-[60%] w-full md:w-1/2 lg:h-screen"
    />
    <div class="block md:flex py-20">
      <div class="w-full relative md:w-1/2">
        <img src="img/siswa stelk.png" />
      </div>
      <div
        class="w-full mt-20 px-2 md:mt-0 md:pr-5 md:w-1/2 text-center flex justify-center items-center flex-col"
      >
        <h1 class="uppercase text-2xl lg:text-4xl font-bold">
          the real informatics school
        </h1>
        <p class="text-slate-700 text-sm md:text-lg">
          Pelopor SMK bidang Teknologi Informasi dan Komunikasi di Indonesia
        </p>
      </div>
    </div>
  </section>

  <section class="py-20 mx-5">
    <div class="w-full">
      <h1 class="text-center text-4xl font-bold">Jalur Pendaftaran</h1>
      <p class="text-center mt-2">
        Berikut merupakan jalur pendaftaran yang kami tawarkan kepada calon
        pendaftar
      </p>
      <div
        id="jalur-1"
        class="w-full lg:flex lg:justify-evenly lg:items-center mt-10"
      >
        <div class="max-w-md mx-auto">
          <h1 class="text-4xl font-bold mb-4">Jalur Prestasi Akademik</h1>
          <p class="text-slate-500 text-sm">
            Berikut merupakan persyaratan untuk jalur prestasi:
          </p>
          <ul>
            <li class="mt-3">
              Bidang prestasi meliputi Akademik dan Non Akademik
            </li>
            <li class="mt-3">Nilai Raport Kelas VIII</li>
            <li class="mt-3">Tahap 1: Verifikasi Berkas</li>
            <li class="mt-3">Tahap 2: Psikotes, kesehatan, dan wawancara</li>
            <li class="mt-3">
              Proses tes wawancara diikuti oleh orang tua dan calon siswa
            </li>
          </ul>
        </div>
        <div class="max-w-md mx-auto">
          <img src="img/ilustrasi1.png" alt="" />
        </div>
      </div>
      <div
        id="jalur-2"
        class="w-full lg:flex lg:justify-evenly lg:items-center mt-10"
      >
        <div class="max-w-md mx-auto">
          <h1 class="text-4xl font-bold mb-4">Jalur Reguler</h1>
          <p class="text-slate-500 text-sm mb-3">
            Berikut merupakan persyaratan untuk jalur reguler:
          </p>
          <ul>
            <li class="mt-3">Seleksi Tahap 1 berupa Tes Akademik</li>
            <li class="mt-3">
              Materi tes Akademik: Matematika, Bahasa Inggris, & IPA
            </li>
            <li class="mt-3">Seleksi Tahap 2 berupa tes non akademik</li>
            <li class="mt-3">
              Tes non akademik: Psikotes, kesehatan dan wawancara
            </li>
            <li class="mt-3">
              Proses tes wawancara diikuti oleh orang tua dan calon siswa
            </li>
          </ul>
        </div>
        <div class="max-w-md mx-auto">
          <img src="img/ilustrasi 2.png" alt="" />
        </div>
      </div>
    </div>
  </section>

  <section class="py-20 px-5">
    <div class="w-full">
      <h1 class="text-center text-4xl font-bold">Jadwal PERISAI</h1>
      <p class="text-center mt-2">
        Berikut merupakan jadwal PERISAI STELK untuk calon pendaftar.
      </p>

      <div
        class="w-full flex justify-center flex-col lg:flex-row lg:justify-evenly mt-5"
      >
        <div class="card mx-auto">
          <div>
            <h1>Jalur Prestasi</h1>
            <h3>Rp. 200.000</h3>
          </div>
          <div>
            <h6>Jadwal Pendaftaran</h6>
            <h5>1 Oktober 2022</h5>
            <h3>25 November 2022</h3>
          </div>
          <div>
            <h6>Test / Ujian</h6>
            <h3>26 November 2022</h3>
          </div>
          <div>
            <h6>Pengumuman</h6>
            <h3>29 November 2022</h3>
          </div>
          <button>Daftar</button>
        </div>
        <div class="card mt-14 lg:mt-0 mx-auto">
          <div>
            <h1>Jalur Reguler</h1>
            <h3>Rp. 200.000</h3>
          </div>
          <div>
            <h6>Jadwal Pendaftaran</h6>
            <h5>1 Oktober 2022</h5>
            <h3>27 Januari 2023</h3>
          </div>
          <div>
            <h6>Test / Ujian</h6>
            <h3>6 April 2023</h3>
          </div>
          <div>
            <h6>Pengumuman</h6>
            <h3>10 April 2023</h3>
          </div>
          <button>Daftar</button>
        </div>
        <div class="card mt-14 lg:mt-0 mx-auto">
          <div>
            <h1>Jalur CBT</h1>
            <h3>Rp. 200.000</h3>
          </div>
          <div>
            <h6>Jadwal Pendaftaran</h6>
            <h5>9 Juli 2023</h5>
            <h3>22 Juli 2023</h3>
          </div>
          <div>
            <h6>Test / Ujian</h6>
            <h3>22 Juli 2023</h3>
          </div>
          <div>
            <h6>Pengumuman</h6>
            <h3>26 Juli 2023</h3>
          </div>
          <button>Daftar</button>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="w-full py-10 px-5 lg:flex lg:justify-evenly">
      <div class="w-[300px]">
        <h1 class="font-bold text-xl">Tentang Kami</h1>
        <p>
          <span class="font-bold">SMK Telkom Makassar</span> Lorem ipsum dolor
          sit amet consectetur, adipisicing elit. Alias, adipisci!
        </p>
      </div>
      <div class="w-[300px] mt-10 lg:mt-0">
        <h1 class="font-bold text-xl">Lokasi Kami</h1>
        <p>Lorem ipsum dolor sit amet.</p>
      </div>
      <div class="w-[300px] mt-10 lg:mt-0">
        <h1 class="font-bold text-xl">Sosial Media Kami</h1>
        <div class="flex gap-2">
          <div class="bg-red-700 p-2 rounded-full">
            <svg
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              width="30"
            >
              <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
              <g
                id="SVGRepo_tracerCarrier"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></g>
              <g id="SVGRepo_iconCarrier">
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M12 18C15.3137 18 18 15.3137 18 12C18 8.68629 15.3137 6 12 6C8.68629 6 6 8.68629 6 12C6 15.3137 8.68629 18 12 18ZM12 16C14.2091 16 16 14.2091 16 12C16 9.79086 14.2091 8 12 8C9.79086 8 8 9.79086 8 12C8 14.2091 9.79086 16 12 16Z"
                  fill="#ffffff"
                ></path>
                <path
                  d="M18 5C17.4477 5 17 5.44772 17 6C17 6.55228 17.4477 7 18 7C18.5523 7 19 6.55228 19 6C19 5.44772 18.5523 5 18 5Z"
                  fill="#ffffff"
                ></path>
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M1.65396 4.27606C1 5.55953 1 7.23969 1 10.6V13.4C1 16.7603 1 18.4405 1.65396 19.7239C2.2292 20.8529 3.14708 21.7708 4.27606 22.346C5.55953 23 7.23969 23 10.6 23H13.4C16.7603 23 18.4405 23 19.7239 22.346C20.8529 21.7708 21.7708 20.8529 22.346 19.7239C23 18.4405 23 16.7603 23 13.4V10.6C23 7.23969 23 5.55953 22.346 4.27606C21.7708 3.14708 20.8529 2.2292 19.7239 1.65396C18.4405 1 16.7603 1 13.4 1H10.6C7.23969 1 5.55953 1 4.27606 1.65396C3.14708 2.2292 2.2292 3.14708 1.65396 4.27606ZM13.4 3H10.6C8.88684 3 7.72225 3.00156 6.82208 3.0751C5.94524 3.14674 5.49684 3.27659 5.18404 3.43597C4.43139 3.81947 3.81947 4.43139 3.43597 5.18404C3.27659 5.49684 3.14674 5.94524 3.0751 6.82208C3.00156 7.72225 3 8.88684 3 10.6V13.4C3 15.1132 3.00156 16.2777 3.0751 17.1779C3.14674 18.0548 3.27659 18.5032 3.43597 18.816C3.81947 19.5686 4.43139 20.1805 5.18404 20.564C5.49684 20.7234 5.94524 20.8533 6.82208 20.9249C7.72225 20.9984 8.88684 21 10.6 21H13.4C15.1132 21 16.2777 20.9984 17.1779 20.9249C18.0548 20.8533 18.5032 20.7234 18.816 20.564C19.5686 20.1805 20.1805 19.5686 20.564 18.816C20.7234 18.5032 20.8533 18.0548 20.9249 17.1779C20.9984 16.2777 21 15.1132 21 13.4V10.6C21 8.88684 20.9984 7.72225 20.9249 6.82208C20.8533 5.94524 20.7234 5.49684 20.564 5.18404C20.1805 4.43139 19.5686 3.81947 18.816 3.43597C18.5032 3.27659 18.0548 3.14674 17.1779 3.0751C16.2777 3.00156 15.1132 3 13.4 3Z"
                  fill="#ffffff"
                ></path>
              </g>
            </svg>
          </div>
          <div class="bg-red-700 p-2 rounded-full">
            <svg
              fill="#ffffff"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              stroke="#ffffff"
              width="30"
            >
              <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
              <g
                id="SVGRepo_tracerCarrier"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></g>
              <g id="SVGRepo_iconCarrier">
                <path
                  d="M12 2.03998C6.5 2.03998 2 6.52998 2 12.06C2 17.06 5.66 21.21 10.44 21.96V14.96H7.9V12.06H10.44V9.84998C10.44 7.33998 11.93 5.95998 14.22 5.95998C15.31 5.95998 16.45 6.14998 16.45 6.14998V8.61998H15.19C13.95 8.61998 13.56 9.38998 13.56 10.18V12.06H16.34L15.89 14.96H13.56V21.96C15.9164 21.5878 18.0622 20.3855 19.6099 18.57C21.1576 16.7546 22.0054 14.4456 22 12.06C22 6.52998 17.5 2.03998 12 2.03998Z"
                ></path>
              </g>
            </svg>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-red-700 py-4 flex justify-center">
      <h1 class="text-white">
        Copyright <span style="color: rgba(255, 255, 255, 0.7)">@ 2023 </span
        ><span class="font-bold">SMK Telkom Makassar</span>
      </h1>
    </div>
  </footer>
</template>

<script>
import HeaderComponent from "@/components/HeaderComponent.vue";

export default {
  name: "HomeView",
  components: { HeaderComponent },
};
</script>

<style scoped>
.card {
  @apply w-[334px] px-5 pb-10 border relative;
  border: 1px solid rgba(0, 0, 0, 0.2);
}

.card > div {
  @apply text-center p-5;
  border-bottom: 1px solid rgba(0, 0, 0, 0.2);
}

.card > div > h1 {
  @apply font-bold text-2xl;
}
.card > div > h3 {
  @apply font-bold text-red-700 text-xl;
}
.card > div > h6 {
  @apply text-slate-700 text-lg;
}
.card > div > h5 {
  @apply font-bold text-red-700 text-xl my-5;
}

.card > button {
  @apply rounded-full bg-red-700 text-white px-8 py-2 absolute right-[34%] -bottom-6;
}
</style>
