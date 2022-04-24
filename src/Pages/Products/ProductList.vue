<template>
  <!-- heder -->
  <div class="container max-w-7xl mx-auto sm:px-6 lg:px-8 mt-10 px-2">
    <div class="flex flex-row-reverse">
      <ul
        class="list-reset breadcrumbs flex flex-row-reverse font-Flatnormal "
      >
        <li class="ltr:mr-2 rtl:ml-2 ml-2 font-Flatnormal text-[14px]">
          <a>الرئيسية</a>
        </li>
        <li class="ltr:mr-2 rtl:ml-2 ml-2 text-blue-600">&lt;</li>
        <li class="ltr:mr-2 rtl:ml-2 ml-2 font-Flatnormal text-[14px]">
          منتجات متشابهة
        </li>
        <li class="ltr:mr-2 rtl:ml-2 ml-2 text-blue-600">&lt;</li>
        <li class="ltr:mr-2 rtl:ml-2 ml-2 opacity-25 font-FlatBold text-[14px]">
          جميع المنتجات
        </li>
      </ul>
    </div>
  </div>
  <!-- nav bar  -->

  <div
    class="flex flex-col-reverse md:flex-row container max-w-7xl mx-auto sm:px-6 lg:px-8 sm:my-10 sm:space-x-4 mb-4 p-2">
    <!-- products show -->
    <div class="basis-3/4">
        <div class="md:hidden flex flex-row justify-end items-center  md:justify-start mr-4 ">
          <select
            class="text-[13px] my-4 form-select appearance-none block pl-4 py-1.5 text-base font-FlatBold bg-clip-padding bg-no-repeat rounded transition ease-in-out m-0 focus:border-blue-600 focus:outline-none"
          >
            <option class="font-FlatBold" selected>الفلاتر</option>
            <option value="1">التصنيفات </option>
            <option value="2">السعر</option>
            <option value="3">الالوان</option>
          </select>
         <svg
                    
                      width="8"
                      height="8"
                      viewBox="0 0 6 5"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        d="M5 4L3 2L1 4"
                        stroke="black"
                        stroke-width="1.6"
                        stroke-linecap="round"
                      />
                    </svg>
        
        </div>
      <div class="flex justify-between text-[18px] w-full">

        <div class="hidden md:flex flex-row justify-center  md:justify-start mr-10 md:min-w-[230px] min-w-full border">

          <select
            class="text-[13px] my-4 form-select appearance-none block px-3 py-1.5 text-base font-FlatBold bg-clip-padding bg-no-repeat rounded transition ease-in-out m-0 focus:border-blue-600 focus:outline-none"
            aria-label="Default select example"
          >
            <option class="font-FlatBold" selected>تمت اضافتها حديثا</option>
            <option value="1">One</option>
            <option value="2">Two</option>
            <option value="3">Three</option>
          </select>
          <span class="mb-4 mt-5 font-FlatBold opacity-25"> صنف ب </span>
        
        </div>
       
        <div
          class="opacity-25 hidden md:grid grid-cols-1 md:w-52 font-FlatBold text-[13px] pt-2 min-w-[170px]"
        >
          15من 61 العناصر
        </div>
      </div>
      <div class="flex justify-end w-full mb-4">
        <ul
          class="flex Poppins-SemiBold  flex-row-reverse text-[13px] "
        >
          <li class="ltr:mr-2 rtl:ml-2 ml-2 border flex p-2 min-w-[120px]">
            <svg
              class="ltr:mr-2 rtl:ml-2 mr-2"
              width="20"
              height="20"
              viewBox="0 0 20 20"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <circle cx="10" cy="10" r="10" fill="#A71A1A" />
              <path d="M7 7L13.5 13.5" stroke="white" stroke-linecap="round" />
              <path d="M13.5 7L7 13.5" stroke="white" stroke-linecap="round" />
            </svg>

            <span class="font-Poppins-SemiBold text-[13px]">
              Iphone
              <span class="opacity-25 font-Poppins-SemiBold text-[13px]"> (24) </span>
            </span>
          </li>
          <li class="ltr:mr-2 rtl:ml-2 ml-2 border flex p-2 min-w-[120px]">
            <svg
              class="ltr:mr-2 rtl:ml-2 mr-2"
              width="20"
              height="20"
              viewBox="0 0 20 20"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <circle cx="10" cy="10" r="10" fill="#A71A1A" />
              <path d="M7 7L13.5 13.5" stroke="white" stroke-linecap="round" />
              <path d="M13.5 7L7 13.5" stroke="white" stroke-linecap="round" />
            </svg>

            <span class="font-Poppins-SemiBold text-[13px]">
              Iphone
              <span class="opacity-25 font-Poppins-SemiBold text-[13px]"> (24) </span>
            </span>
          </li>
          <li class="border flex items-center justify-center p-2 font-FlatBold min-w-[90px] ">
            <span class="text-center"> محو الكل</span>
          </li>
        </ul>
      </div>

<!-- Products -->
        <div class="mt-8 relative">
          <div class="relative w-full pb-6  ">
            <ul
              role="list"
              class="mx-4  gap-x-8 gap-y-8 sm:mx-6 xl:mx-0 xl:grid xl:grid-cols-3 xl:gap-x-8  flex flex-wrap-reverse sm:flex-wrap justify-center items-center ">
              <li class="min-w-[290px] max-w-[300px] flex flex-col text-center xl:w-auto drop-shadow-xl rounded-[10px] border-[1.5px] border-[#F9F8F8] m-10 lg:m-0">
                <div class="group relative">
                  <div
                    class="
                      flex flex-row-reverse items-start justify-between w-full px-4  py-4">
                    <p class="text-[#29A71A] text-[12px] font-FlatBold">متوفر</p>
                     <!-- src="{{asset('assets/front-end/img/AppelCharger.png')}}" -->
                    <img
                    src="../../assets/Icons/AppelCharger.png"
                      alt="iphone" class="h-[150px] w-[150px]"/>
                    <!-- src="{{asset('assets/front-end/img/FavouriteIcon.svg')}}" -->
                    <img 
                    src="../../assets/Icons/FavouriteIcon.svg"
                     alt="favourite"/>
                  </div>
                  <div
                    class="flex flex-row-reverse items-center justify-start mt-7 px-4">
                    <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
                    <img
                    src="../../assets/Icons/star.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
                    <img
                    src="../../assets/Icons/star.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
                    <img
                    src="../../assets/Icons/star.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
                    <img
                    src="../../assets/Icons/star.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <!-- src="{{asset('assets/front-end/img/UnColorStar.svg')}}" -->
                    <img
                    src="../../assets/Icons/UnColorStar.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <p dir="rtl" class="text-[#A2A6B0] font-Flatnormal text-[12px]">
                      التقيمات(4)
                    </p>
                  </div>
                  <p class="font-Poppins text-[13px] mt-2 text-right px-4">iPhone 13 Pro & iPhone 13 Pro Max </p>
                  <p
                    dir="rtl"
                    class=" font-Flatnormal text-[#171515] text-right text-[12px] mt-2 px-4">
                    اكبر ترقية على الأطلاق يشهدها نظام كاميرات 6.1 انش ليساهم في
                    superRatio XDR شاشة 6.1انش
                  </p>
                  <p
                    class="font-Poppins text-[14px] text-[#666666] mt-2 text-right relative mx-4" >
                    ₪499.00
                    <span
                      class="absolute border-b w-10 border-[#666666] top-2.5 right-0.5 px-4"
                    ></span>
                  </p>
                  <p
                    class="
                      font-FlatBold text-[16px] text-[#171515] text-right relative px-4">
                    ₪499.00
                  </p>
                  <div
                    class="flex flex-row-reverse items-center justify-start my-2"
                  >
                    <button
                      type="button"
                      class=" inline-flex items-center px-7 py-3 mt-2 text-[14px] font-FlatBold rounded-[30px] text-white bg-[#0156FF] hover:bg-black hover:text-white "
                    >
                      اشتري الأن
                    </button>
                    <button
                      type="button"
                      class="inline-flex items-center px-4 mx-1 py-3 mt-2 border border-[#0156FF] text-[14px] font-FlatBold rounded-[30px] text-[#0156FF] bg-white hover:text-white hover:bg- addtoCart" >
                      أضف الى الحقيبة
                    </button>
                  </div>
                </div>
              </li>
<!-- {{-- second Products --}} -->
<li class="min-w-[290px] max-w-[300px] inline-flex flex-col text-center xl:w-auto drop-shadow-xl rounded-[10px] border-[1.5px] border-[#F9F8F8] m-10 lg:m-0">
  <div class="group relative">
    <div
      class="
        flex flex-row-reverse items-start justify-between w-full px-4  py-4">
      <p class="text-[#29A71A] text-[12px] font-FlatBold">متوفر</p>
       <!-- src="{{asset('assets/front-end/img/OurProductMac2.png')  }}" -->
      <img
      src="../../assets/Icons/OurProductMac2.png"
        alt="iphone" class="h-[150px] w-[150px]"/>
      <!-- src="{{asset('assets/front-end/img/FavouriteIcon.svg')}}" -->
      <img 
      src="../../assets/Icons/FavouriteIcon.svg"
       alt="favourite"/>
    </div>
    <div
      class="flex flex-row-reverse items-center justify-start mt-7 px-4">
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star"
       class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star"
       class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star"
       class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star"
       class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/UnColorStar.svg')}}" -->
      <img
      src="../../assets/Icons/UnColorStar.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <p dir="rtl" class="text-[#A2A6B0] font-Flatnormal text-[12px]">
        التقيمات(4)
      </p>
    </div>
    <p class="font-Poppins text-[13px] mt-2 text-right px-4">iPhone 13 Pro & iPhone 13 Pro Max </p>
    <p
      dir="rtl"
      class=" font-Flatnormal text-[#171515] text-right text-[12px] mt-2 px-4">
      اكبر ترقية على الأطلاق يشهدها نظام كاميرات 6.1 انش ليساهم في
      superRatio XDR شاشة 6.1انش
    </p>
    <p
      class="font-Poppins text-[14px] text-[#666666] mt-2 text-right relative mx-4" >
      ₪499.00
      <span
        class="absolute border-b w-10 border-[#666666] top-2.5 right-0.5 px-4"
      ></span>
    </p>
    <p
      class="
        font-FlatBold text-[16px] text-[#171515] text-right relative px-4">
      ₪499.00
    </p>
    <div
      class="flex flex-row-reverse items-center justify-start my-2"
    >
      <button
        type="button"
        class=" inline-flex items-center px-7 py-3 mt-2 text-[14px] font-FlatBold rounded-[30px] text-white bg-[#0156FF] hover:bg-black hover:text-white "
      >
        اشتري الأن
      </button>
      <button
        type="button"
        class="inline-flex items-center px-4 mx-1 py-3 mt-2 border border-[#0156FF] text-[14px] font-FlatBold rounded-[30px] text-[#0156FF] bg-white hover:text-white hover:bg- addtoCart" >
        أضف الى الحقيبة
      </button>
    </div>
  </div>
</li>

<!-- {{-- third Product --}} -->

<li class="min-w-[290px] max-w-[300px] inline-flex flex-col text-center xl:w-auto drop-shadow-xl rounded-[10px] border-[1.5px] border-[#F9F8F8] m-10 lg:m-0">
  <div class="group relative">
    <div
      class="
        flex flex-row-reverse items-start justify-between w-full px-4  py-4">
      <p class="text-[#29A71A] text-[12px] font-FlatBold">متوفر</p>
      <!-- src="{{asset('assets/front-end/img/AirBod.png')}}" -->
      <img 
      src="../../assets/Icons/AirBod.png"
       alt="iphone" class="h-[150px] w-[150px]"/>
       <!-- src="{{asset('assets/front-end/img/FavouriteIcon.svg')}}" -->
      <img
      src="../../assets/Icons/FavouriteIcon.svg"
        alt="favourite"/>
    </div>
    <div
      class="flex flex-row-reverse items-center justify-start mt-7 px-4">
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/UnColorStar.svg')}}"  -->
      <img
      src="../../assets/Icons/UnColorStar.svg"
      alt="star" class="h-[13px] w-[13px]"/>
      <p dir="rtl" class="text-[#A2A6B0] font-Flatnormal text-[12px]">
        التقيمات(4)
      </p>
    </div>
    <p class="font-Poppins text-[13px] mt-2 text-right px-4">iPhone 13 Pro & iPhone 13 Pro Max </p>
    <p
      dir="rtl"
      class=" font-Flatnormal text-[#171515] text-right text-[12px] mt-2 px-4">
      اكبر ترقية على الأطلاق يشهدها نظام كاميرات 6.1 انش ليساهم في
      superRatio XDR شاشة 6.1انش
    </p>
    <p
      class="font-Poppins text-[14px] text-[#666666] mt-2 text-right relative mx-4" >
      ₪499.00
      <span
        class="absolute border-b w-10 border-[#666666] top-2.5 right-0.5 px-4"
      ></span>
    </p>
    <p
      class="
        font-FlatBold text-[16px] text-[#171515] text-right relative px-4">
      ₪499.00
    </p>
    <div
      class="flex flex-row-reverse items-center justify-start my-2"
    >
      <button
        type="button"
        class=" inline-flex items-center px-7 py-3 mt-2 text-[14px] font-FlatBold rounded-[30px] text-white bg-[#0156FF] hover:bg-black hover:text-white "
      >
        اشتري الأن
      </button>
      <button
        type="button"
        class="inline-flex items-center px-4 mx-1 py-3 mt-2 border border-[#0156FF] text-[14px] font-FlatBold rounded-[30px] text-[#0156FF] bg-white hover:text-white hover:bg- addtoCart" >
        أضف الى الحقيبة
      </button>
    </div>
  </div>
</li>

<!-- {{-- fourth Products --}} -->
<li class="min-w-[290px] max-w-[300px] flex flex-col text-center xl:w-auto drop-shadow-xl rounded-[10px] border-[1.5px] border-[#F9F8F8] m-10 lg:m-0">
                <div class="group relative">
                  <div
                    class="
                      flex flex-row-reverse items-start justify-between w-full px-4  py-4">
                    <p class="text-[#29A71A] text-[12px] font-FlatBold">متوفر</p>
                     <!-- src="{{asset('assets/front-end/img/AppelCharger.png')}}" -->
                    <img
                    src="../../assets/Icons/AppelCharger.png"
                      alt="iphone" class="h-[150px] w-[150px]"/>
                    <!-- src="{{asset('assets/front-end/img/FavouriteIcon.svg')}}" -->
                    <img 
                    src="../../assets/Icons/FavouriteIcon.svg"
                     alt="favourite"/>
                  </div>
                  <div
                    class="flex flex-row-reverse items-center justify-start mt-7 px-4">
                    <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
                    <img
                    src="../../assets/Icons/star.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
                    <img
                    src="../../assets/Icons/star.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
                    <img
                    src="../../assets/Icons/star.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
                    <img
                    src="../../assets/Icons/star.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <!-- src="{{asset('assets/front-end/img/UnColorStar.svg')}}" -->
                    <img
                    src="../../assets/Icons/UnColorStar.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <p dir="rtl" class="text-[#A2A6B0] font-Flatnormal text-[12px]">
                      التقيمات(4)
                    </p>
                  </div>
                  <p class="font-Poppins text-[13px] mt-2 text-right px-4">iPhone 13 Pro & iPhone 13 Pro Max </p>
                  <p
                    dir="rtl"
                    class=" font-Flatnormal text-[#171515] text-right text-[12px] mt-2 px-4">
                    اكبر ترقية على الأطلاق يشهدها نظام كاميرات 6.1 انش ليساهم في
                    superRatio XDR شاشة 6.1انش
                  </p>
                  <p
                    class="font-Poppins text-[14px] text-[#666666] mt-2 text-right relative mx-4" >
                    ₪499.00
                    <span
                      class="absolute border-b w-10 border-[#666666] top-2.5 right-0.5 px-4"
                    ></span>
                  </p>
                  <p
                    class="
                      font-FlatBold text-[16px] text-[#171515] text-right relative px-4">
                    ₪499.00
                  </p>
                  <div
                    class="flex flex-row-reverse items-center justify-start my-2"
                  >
                    <button
                      type="button"
                      class=" inline-flex items-center px-7 py-3 mt-2 text-[14px] font-FlatBold rounded-[30px] text-white bg-[#0156FF] hover:bg-black hover:text-white "
                    >
                      اشتري الأن
                    </button>
                    <button
                      type="button"
                      class="inline-flex items-center px-4 mx-1 py-3 mt-2 border border-[#0156FF] text-[14px] font-FlatBold rounded-[30px] text-[#0156FF] bg-white hover:text-white hover:bg- addtoCart" >
                      أضف الى الحقيبة
                    </button>
                  </div>
                </div>
              </li>
    <!--fifth products -->
<li class="min-w-[290px] max-w-[300px] inline-flex flex-col text-center xl:w-auto drop-shadow-xl rounded-[10px] border-[1.5px] border-[#F9F8F8] m-10 lg:m-0">
  <div class="group relative">
    <div
      class="
        flex flex-row-reverse items-start justify-between w-full px-4  py-4">
      <p class="text-[#29A71A] text-[12px] font-FlatBold">متوفر</p>
       <!-- src="{{asset('assets/front-end/img/OurProductMac2.png')  }}" -->
      <img
      src="../../assets/Icons/OurProductMac2.png"
        alt="iphone" class="h-[150px] w-[150px]"/>
      <!-- src="{{asset('assets/front-end/img/FavouriteIcon.svg')}}" -->
      <img 
      src="../../assets/Icons/FavouriteIcon.svg"
       alt="favourite"/>
    </div>
    <div
      class="flex flex-row-reverse items-center justify-start mt-7 px-4">
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star"
       class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star"
       class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star"
       class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star"
       class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/UnColorStar.svg')}}" -->
      <img
      src="../../assets/Icons/UnColorStar.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <p dir="rtl" class="text-[#A2A6B0] font-Flatnormal text-[12px]">
        التقيمات(4)
      </p>
    </div>
    <p class="font-Poppins text-[13px] mt-2 text-right px-4">iPhone 13 Pro & iPhone 13 Pro Max </p>
    <p
      dir="rtl"
      class=" font-Flatnormal text-[#171515] text-right text-[12px] mt-2 px-4">
      اكبر ترقية على الأطلاق يشهدها نظام كاميرات 6.1 انش ليساهم في
      superRatio XDR شاشة 6.1انش
    </p>
    <p
      class="font-Poppins text-[14px] text-[#666666] mt-2 text-right relative mx-4" >
      ₪499.00
      <span
        class="absolute border-b w-10 border-[#666666] top-2.5 right-0.5 px-4"
      ></span>
    </p>
    <p
      class="
        font-FlatBold text-[16px] text-[#171515] text-right relative px-4">
      ₪499.00
    </p>
    <div
      class="flex flex-row-reverse items-center justify-start my-2"
    >
      <button
        type="button"
        class=" inline-flex items-center px-7 py-3 mt-2 text-[14px] font-FlatBold rounded-[30px] text-white bg-[#0156FF] hover:bg-black hover:text-white "
      >
        اشتري الأن
      </button>
      <button
        type="button"
        class="inline-flex items-center px-4 mx-1 py-3 mt-2 border border-[#0156FF] text-[14px] font-FlatBold rounded-[30px] text-[#0156FF] bg-white hover:text-white hover:bg- addtoCart" >
        أضف الى الحقيبة
      </button>
    </div>
  </div>
</li>
<!-- six Products -->
<li class="min-w-[290px] max-w-[300px] inline-flex flex-col text-center xl:w-auto drop-shadow-xl rounded-[10px] border-[1.5px] border-[#F9F8F8] m-10 lg:m-0">
  <div class="group relative">
    <div
      class="
        flex flex-row-reverse items-start justify-between w-full px-4  py-4">
      <p class="text-[#29A71A] text-[12px] font-FlatBold">متوفر</p>
      <!-- src="{{asset('assets/front-end/img/AirBod.png')}}" -->
      <img 
      src="../../assets/Icons/AirBod.png"
       alt="iphone" class="h-[150px] w-[150px]"/>
       <!-- src="{{asset('assets/front-end/img/FavouriteIcon.svg')}}" -->
      <img
      src="../../assets/Icons/FavouriteIcon.svg"
        alt="favourite"/>
    </div>
    <div
      class="flex flex-row-reverse items-center justify-start mt-7 px-4">
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/UnColorStar.svg')}}"  -->
      <img
      src="../../assets/Icons/UnColorStar.svg"
      alt="star" class="h-[13px] w-[13px]"/>
      <p dir="rtl" class="text-[#A2A6B0] font-Flatnormal text-[12px]">
        التقيمات(4)
      </p>
    </div>
    <p class="font-Poppins text-[13px] mt-2 text-right px-4">iPhone 13 Pro & iPhone 13 Pro Max </p>
    <p
      dir="rtl"
      class=" font-Flatnormal text-[#171515] text-right text-[12px] mt-2 px-4">
      اكبر ترقية على الأطلاق يشهدها نظام كاميرات 6.1 انش ليساهم في
      superRatio XDR شاشة 6.1انش
    </p>
    <p
      class="font-Poppins text-[14px] text-[#666666] mt-2 text-right relative mx-4" >
      ₪499.00
      <span
        class="absolute border-b w-10 border-[#666666] top-2.5 right-0.5 px-4"
      ></span>
    </p>
    <p
      class="
        font-FlatBold text-[16px] text-[#171515] text-right relative px-4">
      ₪499.00
    </p>
    <div
      class="flex flex-row-reverse items-center justify-start my-2"
    >
      <button
        type="button"
        class=" inline-flex items-center px-7 py-3 mt-2 text-[14px] font-FlatBold rounded-[30px] text-white bg-[#0156FF] hover:bg-black hover:text-white "
      >
        اشتري الأن
      </button>
      <button
        type="button"
        class="inline-flex items-center px-4 mx-1 py-3 mt-2 border border-[#0156FF] text-[14px] font-FlatBold rounded-[30px] text-[#0156FF] bg-white hover:text-white hover:bg- addtoCart" >
        أضف الى الحقيبة
      </button>
    </div>
  </div>
</li>
<!-- {{-- third Product --}} -->

<li class="min-w-[290px] max-w-[300px] inline-flex flex-col text-center xl:w-auto drop-shadow-xl rounded-[10px] border-[1.5px] border-[#F9F8F8] m-10 lg:m-0">
  <div class="group relative">
    <div
      class="
        flex flex-row-reverse items-start justify-between w-full px-4  py-4">
      <p class="text-[#29A71A] text-[12px] font-FlatBold">متوفر</p>
      <!-- src="{{asset('assets/front-end/img/AirBod.png')}}" -->
      <img 
      src="../../assets/Icons/AirBod.png"
       alt="iphone" class="h-[150px] w-[150px]"/>
       <!-- src="{{asset('assets/front-end/img/FavouriteIcon.svg')}}" -->
      <img
      src="../../assets/Icons/FavouriteIcon.svg"
        alt="favourite"/>
    </div>
    <div
      class="flex flex-row-reverse items-center justify-start mt-7 px-4">
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/UnColorStar.svg')}}"  -->
      <img
      src="../../assets/Icons/UnColorStar.svg"
      alt="star" class="h-[13px] w-[13px]"/>
      <p dir="rtl" class="text-[#A2A6B0] font-Flatnormal text-[12px]">
        التقيمات(4)
      </p>
    </div>
    <p class="font-Poppins text-[13px] mt-2 text-right px-4">iPhone 13 Pro & iPhone 13 Pro Max </p>
    <p
      dir="rtl"
      class=" font-Flatnormal text-[#171515] text-right text-[12px] mt-2 px-4">
      اكبر ترقية على الأطلاق يشهدها نظام كاميرات 6.1 انش ليساهم في
      superRatio XDR شاشة 6.1انش
    </p>
    <p
      class="font-Poppins text-[14px] text-[#666666] mt-2 text-right relative mx-4" >
      ₪499.00
      <span
        class="absolute border-b w-10 border-[#666666] top-2.5 right-0.5 px-4"
      ></span>
    </p>
    <p
      class="
        font-FlatBold text-[16px] text-[#171515] text-right relative px-4">
      ₪499.00
    </p>
    <div
      class="flex flex-row-reverse items-center justify-start my-2"
    >
      <button
        type="button"
        class=" inline-flex items-center px-7 py-3 mt-2 text-[14px] font-FlatBold rounded-[30px] text-white bg-[#0156FF] hover:bg-black hover:text-white "
      >
        اشتري الأن
      </button>
      <button
        type="button"
        class="inline-flex items-center px-4 mx-1 py-3 mt-2 border border-[#0156FF] text-[14px] font-FlatBold rounded-[30px] text-[#0156FF] bg-white hover:text-white hover:bg- addtoCart" >
        أضف الى الحقيبة
      </button>
    </div>
  </div>
</li>

<!-- {{-- fourth Products --}} -->
<li class="min-w-[290px] max-w-[300px] flex flex-col text-center xl:w-auto drop-shadow-xl rounded-[10px] border-[1.5px] border-[#F9F8F8] m-10 lg:m-0">
                <div class="group relative">
                  <div
                    class="
                      flex flex-row-reverse items-start justify-between w-full px-4  py-4">
                    <p class="text-[#29A71A] text-[12px] font-FlatBold">متوفر</p>
                     <!-- src="{{asset('assets/front-end/img/AppelCharger.png')}}" -->
                    <img
                    src="../../assets/Icons/AppelCharger.png"
                      alt="iphone" class="h-[150px] w-[150px]"/>
                    <!-- src="{{asset('assets/front-end/img/FavouriteIcon.svg')}}" -->
                    <img 
                    src="../../assets/Icons/FavouriteIcon.svg"
                     alt="favourite"/>
                  </div>
                  <div
                    class="flex flex-row-reverse items-center justify-start mt-7 px-4">
                    <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
                    <img
                    src="../../assets/Icons/star.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
                    <img
                    src="../../assets/Icons/star.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
                    <img
                    src="../../assets/Icons/star.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
                    <img
                    src="../../assets/Icons/star.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <!-- src="{{asset('assets/front-end/img/UnColorStar.svg')}}" -->
                    <img
                    src="../../assets/Icons/UnColorStar.svg"
                     alt="star" class="h-[13px] w-[13px]"/>
                    <p dir="rtl" class="text-[#A2A6B0] font-Flatnormal text-[12px]">
                      التقيمات(4)
                    </p>
                  </div>
                  <p class="font-Poppins text-[13px] mt-2 text-right px-4">iPhone 13 Pro & iPhone 13 Pro Max </p>
                  <p
                    dir="rtl"
                    class=" font-Flatnormal text-[#171515] text-right text-[12px] mt-2 px-4">
                    اكبر ترقية على الأطلاق يشهدها نظام كاميرات 6.1 انش ليساهم في
                    superRatio XDR شاشة 6.1انش
                  </p>
                  <p
                    class="font-Poppins text-[14px] text-[#666666] mt-2 text-right relative mx-4" >
                    ₪499.00
                    <span
                      class="absolute border-b w-10 border-[#666666] top-2.5 right-0.5 px-4"
                    ></span>
                  </p>
                  <p
                    class="
                      font-FlatBold text-[16px] text-[#171515] text-right relative px-4">
                    ₪499.00
                  </p>
                  <div
                    class="flex flex-row-reverse items-center justify-start my-2"
                  >
                    <button
                      type="button"
                      class=" inline-flex items-center px-7 py-3 mt-2 text-[14px] font-FlatBold rounded-[30px] text-white bg-[#0156FF] hover:bg-black hover:text-white "
                    >
                      اشتري الأن
                    </button>
                    <button
                      type="button"
                      class="inline-flex items-center px-4 mx-1 py-3 mt-2 border border-[#0156FF] text-[14px] font-FlatBold rounded-[30px] text-[#0156FF] bg-white hover:text-white hover:bg- addtoCart" >
                      أضف الى الحقيبة
                    </button>
                  </div>
                </div>
              </li>
    <!--fifth products -->
<li class="min-w-[290px] max-w-[300px] inline-flex flex-col text-center xl:w-auto drop-shadow-xl rounded-[10px] border-[1.5px] border-[#F9F8F8] m-10 lg:m-0">
  <div class="group relative">
    <div
      class="
        flex flex-row-reverse items-start justify-between w-full px-4  py-4">
      <p class="text-[#29A71A] text-[12px] font-FlatBold">متوفر</p>
       <!-- src="{{asset('assets/front-end/img/OurProductMac2.png')  }}" -->
      <img
      src="../../assets/Icons/OurProductMac2.png"
        alt="iphone" class="h-[150px] w-[150px]"/>
      <!-- src="{{asset('assets/front-end/img/FavouriteIcon.svg')}}" -->
      <img 
      src="../../assets/Icons/FavouriteIcon.svg"
       alt="favourite"/>
    </div>
    <div
      class="flex flex-row-reverse items-center justify-start mt-7 px-4">
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star"
       class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star"
       class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star"
       class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/star.svg')}}" -->
      <img
      src="../../assets/Icons/star.svg"
       alt="star"
       class="h-[13px] w-[13px]"/>
      <!-- src="{{asset('assets/front-end/img/UnColorStar.svg')}}" -->
      <img
      src="../../assets/Icons/UnColorStar.svg"
       alt="star" class="h-[13px] w-[13px]"/>
      <p dir="rtl" class="text-[#A2A6B0] font-Flatnormal text-[12px]">
        التقيمات(4)
      </p>
    </div>
    <p class="font-Poppins text-[13px] mt-2 text-right px-4">iPhone 13 Pro & iPhone 13 Pro Max </p>
    <p
      dir="rtl"
      class=" font-Flatnormal text-[#171515] text-right text-[12px] mt-2 px-4">
      اكبر ترقية على الأطلاق يشهدها نظام كاميرات 6.1 انش ليساهم في
      superRatio XDR شاشة 6.1انش
    </p>
    <p
      class="font-Poppins text-[14px] text-[#666666] mt-2 text-right relative mx-4" >
      ₪499.00
      <span
        class="absolute border-b w-10 border-[#666666] top-2.5 right-0.5 px-4"
      ></span>
    </p>
    <p
      class="
        font-FlatBold text-[16px] text-[#171515] text-right relative px-4">
      ₪499.00
    </p>
    <div
      class="flex flex-row-reverse items-center justify-start my-2"
    >
      <button
        type="button"
        class=" inline-flex items-center px-7 py-3 mt-2 text-[14px] font-FlatBold rounded-[30px] text-white bg-[#0156FF] hover:bg-black hover:text-white "
      >
        اشتري الأن
      </button>
      <button
        type="button"
        class="inline-flex items-center px-4 mx-1 py-3 mt-2 border border-[#0156FF] text-[14px] font-FlatBold rounded-[30px] text-[#0156FF] bg-white hover:text-white hover:bg- addtoCart" >
        أضف الى الحقيبة
      </button>
    </div>
  </div>
</li>
</ul>
          </div>
        </div>



    </div>
    <!-- filter -->
    <div>
     <button type="button" 
     class=" hidden md:flex justify-center w-full items-center px-4 py-2 text-[14px] font-FlatBold text-center
     text-black bg-transparent"> &lt; عودة</button>

      <div
        class="hidden md:flex flex-row-reverse justify-between md:justify-start md:flex-col my-5 bg-[#F5F7FF] p-2 rounded-[5px]"
      >
        <!--search -->

        <div class="hidden lg:block mb-4 p-2">
          <p class="text-center font-FlatBold mb-3 pr-3 text-black text[16px]">التصفية</p>
            <input
              type="text"
              name="name"
              id="name"
              class="rounded-[50px] px-2 font-FlatBold text-center w-full h-12 border p-0 text-gray-900 placeholder-[#A2A6B0] focus:ring-0 sm:text-sm"
              placeholder="محو التصفية"
            />
        </div>
        <div class="flex justify-center w-full b-2 pt-3 mx-auto">
            <div class="w-full max-w-md  rounded-2xl b-2 pb-3">
              <!--  -->
              <ul class="font-FlatBold text-[14px] px-2 mb-4">
                  <li>
            <input
              type="text"
              name="name"
              id="name"
              class="md:hidden block mb-4 rounded-[50px] px-2 font-FlatBold text-center w-full h-12 border p-0 text-gray-900 placeholder-[#A2A6B0] focus:ring-0 sm:text-sm"
              placeholder="محو التصفية"
            />
                  </li>
                <li
                  class="flex flex-row-reverse justify-between items-center font-FlatBold text-[14px]"
                >
                  <span>التصنيفات </span>

                  <span
                    ><svg
                    class="ml-2"
                      width="8"
                      height="8"
                      viewBox="0 0 6 5"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        d="M5 4L3 2L1 4"
                        stroke="black"
                        stroke-width="1.6"
                        stroke-linecap="round"
                      />
                    </svg>
                  </span>
                </li>
                <li
                  class="flex flex-row justify-between items-center pt-3 ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600"
                >
                  <span> 10</span>
                  <span>PC Parts </span>

                </li>
                <li
                  class="flex flex-row justify-between items-center text-justify ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600"
                >
                  <span> 20</span>
                  <span>Mac </span>

                </li>
                <li
                  class="flex flex-row justify-between items-center text-justify ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600">
                  <span> 30</span>
                  <span>iPad </span>

                </li>
                <li
                  class="flex flex-row justify-between items-center text-justify ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600">
                  <span> 55</span>
                  <span>iPhone </span>
                </li>
                <li
                  class="flex flex-row justify-between items-center text-justify ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600">
                  <span> 22</span>
                  <span>Apple Watch </span>
                </li>
                <li
                  class="flex flex-row justify-between items-center text-justify ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600">
                  <span>10</span>
                  <span>Music </span>
                </li>
              </ul>
              <!--  -->
           <ul
                class="grid grid-cols-1 gap-4 list-reset breadcrumbs font-shamelnormal px-2 mb-8"
              >

                <li
                  class="flex flex-row-reverse justify-between items-center font-FlatBold text-[14px]"
                >
                  <span>السعر </span>

                  <span
                    ><svg
                    class="ml-2"
                      width="8"
                      height="8"
                      viewBox="0 0 6 5"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        d="M5 4L3 2L1 4"
                        stroke="black"
                        stroke-width="1.6"
                        stroke-linecap="round"
                      />
                    </svg>
                  </span>
                </li>
                <li
                  class="flex flex-row-reverse justify-between items-center text-justify ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600"
                >
                  <span> ₪ 0.00 - ₪ 1,000.00 </span>

                  <span> 19</span>
                </li>
                <li
                  class="flex flex-row-reverse justify-between items-center text-justify ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600"
                >
                  <span>₪ 1,000.00-₪ 2,000.00 </span>
                  <span> 21</span>
                </li>
                <li
                  class="flex flex-row-reverse justify-between items-center text-justify ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600"
                >
                  <span>₪ 2,000.00-₪ 3,000.00 </span>
                  <span> 9</span>
                </li>
                <li
                  class="flex flex-row-reverse justify-between items-center text-justify ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600"
                >
                  <span>₪ 3,000.00-₪ 4,000.00 </span>
                  <span> 6</span>
                </li>
                <li
                  class="flex flex-row-reverse justify-between items-center text-justify ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600"
                >
                  <span>₪ 4,000.00-₪ 5,000.00 </span>
                  <span> 3</span>
                </li>
                <li
                  class="flex flex-row-reverse justify-between items-center text-justify ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600"
                >
                  <span>₪ 5,000.00-₪ 6,000.00 </span>
                  <span>1</span>
                </li>
                  <li
                  class="flex flex-row-reverse justify-between items-center text-justify ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600"
                >
                  <span>₪ 6,000.00-₪ 7,000.00 </span>
                  <span>1</span>
                </li>
                  <li
                  class="flex flex-row-reverse justify-between items-center text-justify ml-2 font-Poppins text-[14px] text-[#171515] hover:text-blue-600"
                >
                  <span>₪ 7,000.00  اكثر من </span>
                  <span>1</span>
                </li>
              </ul>
              <!--  -->

        <ul class="font-FlatBold text-[14px] px-2 mb-9">
         <li
                  class="flex flex-row-reverse justify-between items-center font-FlatBold text-[14px]"
                >
                  <span>الالوان </span>

                  <span
                  class="ml-2"
                    ><svg
                      width="8"
                      height="8"
                      viewBox="0 0 6 5"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        d="M5 4L3 2L1 4"
                        stroke="black"
                        stroke-width="1.6"
                        stroke-linecap="round"
                      />
                    </svg>
                  </span>
                </li>
        <li class="flex justify-end  ltr:mr-2 rtl:ml-2 ml-2  font-Flatnormal text-[12px]">
        <div>
              <fieldset class="mt-2">
                <legend class="sr-only">Choose a color</legend>
                <div class="flex items-center space-x-3">
                  <!--
                    Active and Checked: "ring ring-offset-1"
                    Not Active and Checked: "ring-2"
                  -->
                  <label class="-m-0.5 relative p-0.5 rounded-full flex items-center justify-center cursor-pointer focus:outline-none ring-gray-400">
                    <input type="radio" name="color-choice" value="Heather Grey" class="sr-only" aria-labelledby="color-choice-1-label">
                    <p id="color-choice-1-label" class="sr-only">Heather Grey</p>
                    <span aria-hidden="true" class="h-8 w-8 bg-[#DB0000] border border-black border-opacity-10 rounded-full"></span>
                  </label>
                  <!--
                    Active and Checked: "ring ring-offset-1"
                    Not Active and Checked: "ring-2"
                  -->
                  <label class="-m-0.5 relative p-0.5 rounded-full flex items-center justify-center cursor-pointer focus:outline-none ring-gray-900">
                    <input type="radio" name="color-choice" value="Black" class="sr-only" aria-labelledby="color-choice-0-label">
                    <p id="color-choice-0-label" class="sr-only">Black</p>
                    <span aria-hidden="true" class="h-8 w-8 bg-gray-900 border border-black border-opacity-10 rounded-full"></span>
                  </label>
                </div>
              </fieldset>
            </div>
              
        </li>
      </ul>
              <button type="button"
               class="flex justify-center items-center w-full  px-3 py-2 border border-transparent text-[14px] font-FlatBold rounded-[50px] text-white
                bg-[#0156FF] hover:bg-black 
                ">تطبيق التصفية </button>
            </div>
        </div>

      
      </div>
        <div class="hidden md:flex top-0">
<img src="../../assets/Icons/Productoffers.svg" class="min-w-[234px] min-h-[370px]" />
        </div>
    </div>
  </div>
<!-- PAGINATION -->
<nav aria-label="Page navigation example">
  <ul class="flex justify-center items-center gap-x-3 mb-2">
    <li>
      <a href="#" class="block h-8 w-8 py-1.5 pl-1 rounded-full  text-gray-500 bg-white  border border-gray-300 hover:bg-gray-100 hover:text-gray-700 dark:bg-gray-800 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white">
        <span class="sr-only">Previous</span>
        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M12.707 5.293a1 1 0 010 1.414L9.414 10l3.293 3.293a1 1 0 01-1.414 1.414l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
      </a>
    </li>
    <li>
      <a href="#" class="flex items-center justify-center h-8 w-8 text-center py-1.5 rounded-full leading-tight text-gray-500 bg-white border border-gray-300 hover:bg-gray-100 hover:text-gray-700 dark:bg-gray-800 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white">1</a>
    </li>
    <li>
      <a href="#" class="flex items-center justify-center h-8 w-8 text-center  rounded-full align-middle text-gray-500 bg-white border border-gray-300 hover:bg-gray-100 hover:text-gray-700 dark:bg-gray-800 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white">2</a>
    </li>
    <li>
      <a href="#" aria-current="page" class="z-10 flex items-center justify-center h-8 w-8 text-center  rounded-full align-middle text-blue-600 bg-blue-50 border border-blue-300 hover:bg-blue-100 hover:text-blue-700 dark:border-gray-700 dark:bg-gray-700 dark:text-white">3</a>
    </li>
    <li>
      <a href="#" class="flex items-center justify-center h-8 w-8 text-center  rounded-full align-middle text-gray-500 bg-white border border-gray-300 hover:bg-gray-100 hover:text-gray-700 dark:bg-gray-800 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white">...</a>
    </li>
    <li>
      <a href="#" class="flex items-center justify-center h-8 w-8 text-center  rounded-full align-middle text-gray-500 bg-white border border-gray-300 hover:bg-gray-100 hover:text-gray-700 dark:bg-gray-800 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white">15</a>
    </li>
    <li>
      <a href="#" class="flex items-center justify-center h-8 w-8 py-1.5 px-1 rounded-full leading-tight  text-gray-500 bg-white  border border-gray-300 hover:bg-gray-100 hover:text-gray-700 dark:bg-gray-800 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white">
        <span class="sr-only">Next</span>
        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"></path></svg>
      </a>
    </li>
  </ul>
</nav>
</template>
