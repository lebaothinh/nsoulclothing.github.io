<template>
  <div>
    <!-- Title page -->
    <section
      class="bg-img1 txt-center p-lr-15 p-tb-92"
      style="background-image: url('/images/bg-01.jpg')"
    >
      <h2 class="ltext-105 cl0 txt-center">Liên Hệ</h2>
    </section>

    <!-- Content page -->
    <section class="bg0 p-t-104 p-b-116">
      <div class="container">
        <div class="flex-w flex-tr">
          <div
            class="size-210 bor10 p-lr-70 p-t-55 p-b-70 p-lr-15-lg w-full-md"
          >
            <form>
              <h4 class="mtext-105 cl2 txt-center p-b-30">Để lại lời nhắn!</h4>

              <div class="p-t-27 text-center">
                <a
                  href="https://www.facebook.com/nsoulclothing"
                  class="fs-50 cl7 hov-cl1 trans-04 m-r-16 m-r-30"
                >
                  <i class="fa fa-facebook"></i>
                </a>

                <a
                  href="https://www.instagram.com/nsoulclothing/"
                  class="fs-50 cl7 hov-cl1 trans-04 m-r-16"
                >
                  <i class="fa fa-instagram"></i>
                </a>
              </div>
            </form>
          </div>

          <div
            class="size-210 bor10 flex-w flex-col-m p-lr-93 p-tb-30 p-lr-15-lg w-full-md"
          >
            <div class="flex-w w-full p-b-42">
              <span class="fs-18 cl5 txt-center size-211">
                <span class="lnr lnr-map-marker"></span>
              </span>

              <div class="size-212 p-t-2">
                <span class="mtext-110 cl2"> Địa chỉ </span>
                <p class="stext-115 cl6 size-213 p-t-18">
                  Số 10, đường số 1, khu phố 5, phường Hiệp Bình Chánh, quận Thủ
                  Đức, Hồ Chí Minh, Việt Nam
                </p>
              </div>
            </div>

            <div class="flex-w w-full p-b-42">
              <span class="fs-18 cl5 txt-center size-211">
                <span class="lnr lnr-phone-handset"></span>
              </span>

              <div class="size-212 p-t-2">
                <span class="mtext-110 cl2"> Liên hệ </span>

                <p class="stext-115 cl1 size-213 p-t-18">0979224170</p>
              </div>
            </div>

            <div class="flex-w w-full">
              <span class="fs-18 cl5 txt-center size-211">
                <span class="lnr lnr-envelope"></span>
              </span>

              <div class="size-212 p-t-2">
                <span class="mtext-110 cl2"> Hỗ trợ </span>

                <p class="stext-115 cl1 size-213 p-t-18">
                  nsoulclothing@gmail.com
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Map -->
    <div class="map">
      <div
        class="size-303"
        id="google_map"
        data-map-x="40.691446"
        data-map-y="-73.886787"
        data-pin="images/icons/pin.png"
        data-scrollwhell="0"
        data-draggable="1"
        data-zoom="11"
      ></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>