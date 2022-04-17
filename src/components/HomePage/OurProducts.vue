<template>
<div class="bg-white">
  <div class="py-16 sm:py-24 lg:max-w-7xl lg:mx-auto lg:px-8">
      <div class="flex flex-row-reverse justify-between items-center">
        <a href="#" class="text-[30px] font-FlatBold text-[#000000]"
          >منتجاتنا لهذا اليوم</a
        >
        <a
          href="#"
          class="text-[#0156FF] text-[16px] font-Flatnormal underline"
        >
          شاهد جميع المنتجات
        </a>
      </div>

    <div class="mt-8 relative">
      <div class="relative w-full pb-6 -mb-6 overflow-x-auto">
        <ul role="list" class="mx-4 inline-flex space-x-8 sm:mx-6 lg:mx-0 lg:space-x-0 lg:grid lg:grid-cols-4 lg:gap-x-8">
          <li class="w-64 inline-flex flex-col text-center lg:w-auto" v-for="item in data" :key="item.id">
            <div class="group relative">
              <div class="flex flex-row-reverse items-start  justify-between w-full px-4 ">
            <p class="text-[#29A71A] text-[12px] font-FlatBold"> متوفر</p>
            <img
              src="../../assets/Icons/iphoneProduct.png"
              alt="iphone"
              class="h-[150px] w-[150px]"
            />
            <img src="../../assets/Icons/FavouriteIcon.svg" alt="favourite">
            </div>
        <div class="flex flex-row-reverse items-center justify-start mt-7 px-4 ">
            <img
              src="../../assets/Icons/star.svg"
              alt="star"
              class="h-[13px] w-[13px]"
            />
            <img
              src="../../assets/Icons/star.svg"
              alt="star"
              class="h-[13px] w-[13px]"
            />
            <img
              src="../../assets/Icons/star.svg"
              alt="star"
              class="h-[13px] w-[13px]"
            />
                   <img
              src="../../assets/Icons/star.svg"
              alt="star"
              class="h-[13px] w-[13px]"
            />
            <img
              src="../../assets/Icons/UnColorStar.svg"
              alt="star"
              class="h-[13px] w-[13px]"
            />
            <p dir="rtl" class="text-[#A2A6B0] font-Flatnormal text-[12px] ">التقيمات(4)</p>
          </div>
 <p class="font-Poppins text-[13px] mt-2 text-right px-4 ">iPhone 13 Pro & iPhone 13 Pro Max</p>
          <p dir="rtl" class="font-Flatnormal text-[#171515] text-right text-[12px] mt-2 px-4 ">اكبر ترقية على الأطلاق يشهدها نظام كاميرات 6.1 انش ليساهم في superRatio XDR شاشة 6.1انش</p>
          <p class="font-Poppins text-[14px] text-[#666666] mt-2 text-right relative mx-4 ">₪499
              <span class="absolute border-b w-10 border-[#666666] top-2.5 right-0.5 px-4 "></span> </p>
          <p  class="font-FlatBold text-[16px] text-[#171515]  text-right relative px-4 ">₪499</p>
         <div class="flex flex-row-reverse items-center justify-start my-2">
           <button
          type="button"
          class="
            inline-flex
            items-center
            px-8
            py-3
            mt-2
            border border-black
            text-[14px]
            font-FlatBold
            rounded-[30px]
            text-white
            bg-[#0156FF]
            hover:bg-transparent hover:text-black
          "
        >
          اشتري الأن
        </button>
           <button
          type="button"
          class="
            inline-flex
            items-center
            px-4
            mx-1
            py-3
            mt-2
            border border-[#0156FF]
            text-[14px]
            font-FlatBold
            rounded-[30px]
            text-[#0156FF]
            bg-white
            hover:bg-[#0156FF] hover:text-whiet
          "
        >
           أضف الى الحقيبة
        </button>
        </div>
            </div>

          </li>


          <!-- More products... -->
        </ul>
      </div>
    </div>

    <div class="mt-12 flex px-4 sm:hidden">
      <a href="#" class="text-sm font-semibold text-indigo-600 hover:text-indigo-500">See everything<span aria-hidden="true"> &rarr;</span></a>
    </div>
  </div>
</div>
</template>

<script>
const data = [
    {
        id:1
    },
    {
        id:2
    },
    {
        id:3
    },
    {
        id:4
    }
]
export default {
    setup() {
    return {
data
    }
    },
}
</script>
