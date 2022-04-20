<template>
  <div class="bg-white">
    <div class="py-16 sm:py-20 xl:max-w-7xl xl:mx-auto xl:px-8">
      <div class="flex flex-row-reverse justify-between items-center">
        <a href="#" class="text-[18px] sm:text-[30px] font-FlatBold text-[#000000]"
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
          <ul
            role="list"
            class="
              mx-4
              inline-flex
              space-x-8
              sm:mx-6
              xl:mx-0 xl:space-x-0 xl:grid xl:grid-cols-4 xl:gap-x-8
            "
          >
            <li
              class="min-w-[280px] inline-flex flex-col text-center xl:w-auto"
              v-for="item in data"
              :key="item.id"
            >
              <div class="group relative">
                <div
                  class="
                    flex flex-row-reverse
                    items-start
                    justify-between
                    w-full
                    px-4
                  "
                >
                  <p class="text-[#29A71A] text-[12px] font-FlatBold">متوفر</p>
                  <img
                    src="../../assets/Icons/iphoneProduct.png"
                    alt="iphone"
                    class="h-[150px] w-[150px]"
                  />
                  <img
                    src="../../assets/Icons/FavouriteIcon.svg"
                    alt="favourite"
                  />
                </div>
                <div
                  class="
                    flex flex-row-reverse
                    items-center
                    justify-start
                    mt-7
                    px-4
                  "
                >
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
                  <p
                    dir="rtl"
                    class="text-[#A2A6B0] font-Flatnormal text-[12px]"
                  >
                    التقيمات(4)
                  </p>
                </div>
                <p class="font-Poppins text-[13px] mt-2 text-right px-4">
                  iPhone 13 Pro & iPhone 13 Pro Max
                </p>
                <p
                  dir="rtl"
                  class="
                    font-Flatnormal
                    text-[#171515] text-right text-[12px]
                    mt-2
                    px-4
                  "
                >
                  اكبر ترقية على الأطلاق يشهدها نظام كاميرات 6.1 انش ليساهم في
                  superRatio XDR شاشة 6.1انش
                </p>
                <p
                  class="
                    font-Poppins
                    text-[14px] text-[#666666]
                    mt-2
                    text-right
                    relative
                    mx-4
                  "
                >
                  ₪499
                  <span
                    class="
                      absolute
                      border-b
                      w-10
                      border-[#666666]
                      top-2.5
                      right-0.5
                      px-4
                    "
                  ></span>
                </p>
                <p
                  class="
                    font-FlatBold
                    text-[16px] text-[#171515] text-right
                    relative
                    px-4
                  "
                >
                  ₪499
                </p>
                <div
                  class="flex flex-row-reverse items-center justify-start my-2"
                >
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

  <!-- last section Slider -->
  <div class="min-h-[310px] bg-[#F5F7FF] flex flex-col justify-start items-end pr-[30px] mt-[170px]">
    <div class="flex flex-row-reverse ">
      <p class="hidden sm:block text-[96px] font-Poppins pt-5  ">‘’</p>
      <p class=" pt-14 text-[14px] sm:text-[18px] font-Flatnormal  text-right max-w-[850px] pr-4">وصل طلبي الأول اليوم في حالة ممتازة. من الوقت الذي أرسلت فيه سؤالاً حول العنصر إلى إجراء الشراء ، إلى الشحن والآن التسليم ، بقيت شركتك على اتصال هذه خدمة رائعة إنني أتطلع إلى التسوق على موقعك في المستقبل وسأوصي به بشدة.</p>
      </div>
      <p class=" font-Flatnormal text-[14px] mt-4 sm:mt-0 pr-[17px] sm:pr-16">ايمان عبد</p>
      <div class="flex flex-row-reverse items-center justify-between pt-5  pr-[17px] sm:pr-12  w-full pl-9">
                  <button
                    type="button"
                    class="inline-flex items-center px-4 mx-1 py-2 mt-2 mb-4 sm:mb-0  border border-[#0156FF] text-[14px] font-Flatnormal rounded-[30px] text-[#0156FF] bg-white hover:bg-[#0156FF] hover:text-whiet"
                  >
                    اترك لنا مراجعة
                  </button>
                  <div class="flex flex-row-reverse items-center justify-start space-x-1">
          <span class="h-[12px] w-[12px] rounded-[50%]  bg-[#0156FF] ml-1"></span>
            <span class="h-[12px] w-[12px] rounded-[50%]  bg-[#CACDD8] "></span>
              <span class="h-[12px] w-[12px] rounded-[50%]  bg-[#CACDD8] "></span>
              <span class="h-[12px] w-[12px] rounded-[50%]  bg-[#CACDD8] "></span>
              <span class="h-[12px] w-[12px] rounded-[50%]  bg-[#CACDD8] "></span>
                  </div>
      </div>
  </div>
    </div>
  </div>
</template>

<script>
const data = [
  {
    id: 1,
  },
  {
    id: 2,
  },
  {
    id: 3,
  },
  {
    id: 4,
  },
];
const offer = [
  // {
  //     id:1,
  //     type:'iPhone',
  //     src1:"../../assets/Icons/iPhone-13@4x.svg"
  // },
  // {
  //     id:2,
  //     type:'watch',
  //     src1:'../../assets/Icons/watch.svg'
  // },
  // {
  //     id:3,
  //      type:'AirPoad',
  //      src1:"../../assets/Icons/AirPods.svg"
  // }
];
export default {
  setup() {
    return {
      data,
      offer,
    };
  },
};
</script>
