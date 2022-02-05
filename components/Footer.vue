<template>
  <div>
    <!-- footer top -->
    <div class="footer-top md:px-5 pt-10 pb-20 md:flex space-y-10 text-center">
      <!-- left -->
      <div class="flex-1 space-y-10">
        <img src="https://www.yesdok.com/img/headeryesdok.png" class="w-40 m-auto" />
        <h2 class="text-white font-semibold text-lg">
          YesDok adalah layanan ehealth yang terjangkau dengan platform mobile yang mudah digunakan dan tangguh. Menembus 17.504 pulau dan 260 juta pengguna di Indonesia.
        </h2>
        <img src="https://images.dmca.com/Badges/dmca_protected_sml_120l.png?ID=8a3a3757-4da1-47c3-a8d9-1f84bf10a04b" class="w-40 m-auto"/>
        <div class="flex justify-center space-x-3">
          <a target="_blank" href="https://play.google.com/store/apps/details?id=com.yesdok.mobile.app">
            <img src="https://www.yesdok.com/img/footer_play_store.png" class="w-40"/>
          </a>
          <a target="_blank" href="https://apps.apple.com/id/app/yesdok/id1275373472">
            <img src="https://www.yesdok.com/img/footer_app_store.png"  class="w-40"/>
          </a>
        </div>
      </div>

      <!-- middle -->
      <div class="flex-1 text-left">
        <div class="w-60 m-auto space-y-5">
          <div>
            <h1 class="text-white text-4xl font-semibold uppercase mb-5">Indonesia</h1>
            <div class="flex space-x-3">
              <img src="https://www.yesdok.com/img/indonesia_flag.png" class="h-7 w-7">
              <a target="_blank" href="https://www.google.com/maps/place/Kirana+Boutique+Office/@-6.1741032,106.8940087,21z/data=!4m5!3m4!1s0x2e69f520aed63795:0xd18f4ce7a8259dbb!8m2!3d-6.174088!4d106.8940886">
                <h2 class="text-white font-semibold hover:text-blue-400">
                  PT. Yes Dok Indonesia,<br>
                  Ruko Kirana Boutique <br>
                  Jl. Boulevard Gading Raya Blok F3 <br>
                  No.11 <br>
                  Jakarta 14240
                </h2>
              </a>
            </div>
          </div>
          <div>
            <h1 class="text-white text-4xl font-semibold uppercase mb-5">Singapore</h1>
            <div class="flex space-x-3">
              <img src="https://www.yesdok.com/img/singapore_flag.png" class="h-7 w-7">
                <h2 class="text-white font-semibold">
                  YesDok Pte. Ltd.
                </h2>
            </div>
          </div>
        </div>
      </div>

      <!-- right -->
       <div class="flex-1 text-left space-y-5">
          <div class="w-60 m-auto space-y-10">
            <div class="space-y-2">
              <h1 class="text-white text-4xl font-semibold uppercase mb-5">Kontak</h1>
              <div class="flex space-x-2">
                <font-awesome-icon :icon="['fas','envelope']" class="text-white mt-2"/>
                <div>
                  <h2 class="text-white font-semibold text-lg">Corporate Info :</h2>
                  <a href="mailto:info@yesdok.com">
                    <p class="text-white hover:text-blue-400">info@yesdok.com</p>
                  </a>
                </div>
              </div>
              <div class="flex space-x-2">
                <font-awesome-icon :icon="['fas','envelope']" class="text-white mt-2"/>
                <div>
                  <h2 class="text-white font-semibold text-lg">Customer Service :</h2>
                  <a href="mailto:help@yesdok.com">
                    <p class="text-white hover:text-blue-400">help@yesdok.com</p>
                  </a>
                </div>
              </div>
            </div>
            <div class="space-y-2">
              <h1 class="text-white text-4xl font-semibold uppercase mb-5">Panduan</h1>
              <div class="flex space-x-2">
                <font-awesome-icon :icon="['fas','headphones']" class="text-white mt-1"/>
                <div>
                  <a target="_blank" href="https://www.yesdok.com/id/company/#contact">
                    <p class="text-white hover:text-blue-400">Hubungi Kami</p>
                  </a>
                </div>
              </div>
              <div class="flex space-x-2">
                <font-awesome-icon :icon="['fas','pen-square']" class="text-white mt-1"/>
                <div>
                  <a target="_blank" href="https://www.yesdok.com/id/tnc.html">
                    <p class="text-white hover:text-blue-400">Syarat dan Ketentuan</p>
                  </a>
                </div>
              </div>
              <div class="flex space-x-2">
                <font-awesome-icon :icon="['fas','file-alt']" class="text-white mt-1"/>
                <div>
                  <a target="_blank" href="https://www.yesdok.com/id/privacy.html">
                    <p class="text-white hover:text-blue-400">Kebijakan Privasi</p>
                  </a>
                </div>
              </div>
            </div>
            <div>
              <h1 class="text-white text-4xl font-semibold uppercase mb-5">Follow us</h1>
              <div class="flex space-x-2">
                <a target="_blank" href="https://www.facebook.com/yesdok24jam/">
                  <img src="https://www.yesdok.com/img/facebook.png" class="w-14">
                </a>
                 <a target="_blank" href="https://twitter.com/yesdok_id/">
                  <img src="https://www.yesdok.com/img/twitter.png" class="w-14">
                </a>
                 <a target="_blank" href="https://www.instagram.com/yesdok_id/">
                  <img src="https://www.yesdok.com/img/instagram.png" class="w-14">
                </a>
              </div>
            </div>
          </div>
      </div>
    </div>
    <!-- footer bottom -->
    <div class="footer-bottom p-10">
      <h1 class="text-xl text-white">COPYRIGHT &copy;2022 ALL RIGHTS RESERVED BY YesDok</h1>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>