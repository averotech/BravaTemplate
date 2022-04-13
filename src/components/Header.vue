<template>
  <!-- This example requires Tailwind CSS v2.0+ -->

  <div>
<TopHeader />
    <header class="bg-[#020203]">
      <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8" aria-label="Top">
        <div
          class="
            w-full
            py-6
            flex
            items-center
            justify-between
            border-b border-indigo-500
            lg:border-none
          "
        >
          <div class="flex items-center">
            <p class="font-Poppins-SemiBold pr-[15px] text-[18px] text-white">
              עִברִית
            </p>
            <a href="#">
              <img
                class="h-4 w-4"
                src="../assets/Icons/Profle.svg"
                alt="Profile"
              />
            </a>
            <a href="#">
              <img
                class="h-5 w-6 mx-3"
                src="../assets/Icons/Favourite.svg"
                alt="Favourite"
              />
            </a>
            <a href="#">
              <img
                class="h-5 w-5 mr-3"
                src="../assets/Icons/Cart.svg"
                alt="Cart"
              />
            </a>
            <a href="#">
              <img
                class="h-5 w-5"
                src="../assets/Icons/Search.svg"
                alt="Search"
              />
            </a>
            <a
              href="#"
              class="
                text-white text-[14px]
                hidden
                sm:inline-flex
                border-2
                px-5
                py-1
                ml-4
                rounded-[25px]
              "
            >
              ارساليات
            </a>
            <div class="hidden ml-10 space-x-12 xl:space-x-8 lg:block">
              <a
                href="#"
                class="
                  text-base
                  hidden
                  xl:inline-flex
                  font-Poppins-SemiBold
                  text-[14px] text-white
                  hover:text-indigo-50
                "
              >
                Dji
              </a>

              <a
                href="#"
                class="
                  text-base
                  hidden
                  xl:inline-flex
                  font-Poppins-SemiBold
                  text-[14px] text-white
                  hover:text-indigo-50
                "
              >
                Trade Up
              </a>

              <a
                href="#"
                class="
                  text-base
                   hidden
                  xl:inline-flex
                  font-Poppins-SemiBold
                  text-[14px] text-white
                  hover:text-indigo-50
                "
              >
                Accessories
              </a>

              <a
                href="#"
                class="
                  text-base
                  font-Poppins-SemiBold
                  text-[14px] text-white
                  hover:text-indigo-50
                "
              >
                Music
              </a>

              <a
                href="#"
                class="
                  text-base
                  font-Poppins-SemiBold
                  text-[14px] text-white
                  hover:text-indigo-50
                "
              >
                Tv
              </a>

              <a
                href="#"
                class="
                  text-base
                  font-Poppins-SemiBold
                  text-[14px] text-white
                  hover:text-indigo-50
                "
              >
                Watch
              </a>

              <a
                href="#"
                class="
                  text-base
                  font-Poppins-SemiBold
                  text-[14px] text-white
                  hover:text-indigo-50
                "
              >
                iPhone
              </a>

              <a
                href="#"
                class="
                  text-base
                  hidden
                  xl:inline-flex
                  font-Poppins-SemiBold
                  text-[14px] text-white
                  hover:text-indigo-50
                "
              >
                iPad
              </a>

              <a
                href="#"
                class="
                  text-base
                  hidden
                  xl:inline-flex
                  font-Poppins-SemiBold
                  text-[14px] text-white
                  hover:text-indigo-50
                "
              >
                Mac
              </a>
            </div>
          </div>
          <div class="ml-10 space-x-4">
            <a href="#">
              <img class="h-5 w-24" src="../assets/Icons/Logo.svg" alt="Logo" />
            </a>
          </div>
        </div>
        <div class="py-4 flex flex-wrap justify-center space-x-6 lg:hidden">
          <a
            href="#"
            class="
              text-base
              font-Poppins-SemiBold
              text-[14px] text-white
              hover:text-indigo-50
            "
          >
            Dji
          </a>

          <a
            href="#"
            class="
              text-base
              font-Poppins-SemiBold
              text-[14px] text-white
              hover:text-indigo-50
            "
          >
            Trade Up
          </a>

          <a
            href="#"
            class="
              text-base
              font-Poppins-SemiBold
              text-[14px] text-white
              hover:text-indigo-50
            "
          >
            Accessories
          </a>

          <a
            href="#"
            class="
              text-base
              font-Poppins-SemiBold
              text-[14px] text-white
              hover:text-indigo-50
            "
          >
            Music
          </a>

          <a
            href="#"
            class="
              text-base
              font-Poppins-SemiBold
              text-[14px] text-white
              hover:text-indigo-50
            "
          >
            Tv
          </a>

          <a
            href="#"
            class="
              text-base
              font-Poppins-SemiBold
              text-[14px] text-white
              hover:text-indigo-50
            "
          >
            Watch
          </a>

          <a
            href="#"
            class="
              text-base
              font-Poppins-SemiBold
              text-[14px] text-white
              hover:text-indigo-50
            "
          >
            iPhone
          </a>

          <a
            href="#"
            class="
              text-base
              font-Poppins-SemiBold
              text-[14px] text-white
              hover:text-indigo-50
            "
          >
            iPad
          </a>

          <a
            href="#"
            class="
              text-base
              font-Poppins-SemiBold
              text-[14px] text-white
              hover:text-indigo-50
            "
          >
            Mac
          </a>
        </div>
      </nav>
    </header>
  </div>
</template>
<script>
import TopHeader from '../components/TopHeader.vue'
export default {
    setup() {
        return{

        }
    },components:{TopHeader}
    
}
</script>
