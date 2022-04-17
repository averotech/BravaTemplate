<template>
<div class="relative bg-[#020203] overflow-hidden md:max-h-24">

  <div class="relative pt-6 pb-16 sm:pb-24">
      <div class="max-w-7xl mx-auto px-4 sm:px-6">
        <nav class="relative flex items-center justify-between sm:h-10 md:justify-center" aria-label="Global">
          <div class="flex items-center flex-1 md:absolute md:inset-y-0 md:left-0">
            <div class="flex items-center justify-between w-full md:w-auto">
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

    <div class=" space-x-4">
            <a href="#">
              <img class="h-5 w-24" src="../assets/Icons/Logo.svg" alt="Logo" />
            </a>
          </div>



              <div class="-mr-2 flex items-center md:hidden">
                <button type="button" class="bg-gray-50 rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500" aria-expanded="false">
                  <span class="sr-only">Open main menu</span>
                  <!-- Heroicon name: outline/menu -->
                  <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                  </svg>
                </button>
              </div>
            </div>
          </div>
        </nav>
      </div>

      <!--
        Mobile menu, show/hide based on menu open state.

        Entering: "duration-150 ease-out"
          From: "opacity-0 scale-95"
          To: "opacity-100 scale-100"
        Leaving: "duration-100 ease-in"
          From: "opacity-100 scale-100"
          To: "opacity-0 scale-95"
      -->
      <div class="absolute z-10 top-0 inset-x-0 p-2 transition transform origin-top-right md:hidden">
        <div class="rounded-lg shadow-md bg-white ring-1 ring-black ring-opacity-5 overflow-hidden">
          <div class="px-5 pt-4 flex items-center justify-between">
        
            <div class="-mr-2">
              <button type="button" class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500">
                <span class="sr-only">Close menu</span>
                <!-- Heroicon name: outline/x -->
                <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                </svg>
              </button>
            </div>
          </div>
          <div class="px-2 pt-2 pb-3" v-for="item in navigation" :key="item.name">
            <a href="#" class="text-base
                  font-Poppins-SemiBold
                  text-[14px] text-black
                  hover:text-indigo-50">{{item.name}}</a>
          </div>
        </div>
      </div>

    <main class="mt-16 mx-auto max-w-7xl px-4 sm:mt-24">
      <div class="md:h-0 h-[250px]">
      
      </div>
    </main>
  </div>
</div>
</template>

<script>
import { Popover, PopoverButton, PopoverPanel } from '@headlessui/vue'
import { MenuIcon, XIcon } from '@heroicons/vue/outline'

const navigation = [
  { name: 'Trade Up', href: '#' },
  { name: 'Accessories', href: '#' },
  { name: 'Tv', href: '#' },
  { name: 'Watch', href: '#' },
  { name: 'iPhone', href: '#' },
  { name: ' iPad', href: '#' },
  { name: ' Mac', href: '#' },
  { name: 'Trade Up', href: '#' },
  { name: 'Accessories', href: '#' },
  { name: 'Music', href: '#' },
]

export default {
  components: {
    Popover,
    PopoverButton,
    PopoverPanel,
    MenuIcon,
    XIcon,
  },
  setup() {
    return {
      navigation,
    }
  },
}
</script>