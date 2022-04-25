<template>
        <div class="mb-20">
          <div class="container max-w-7xl mx-auto sm:px-6 lg:px-8 pt-5 px-2">
           <nav class="flex justify-end" aria-label="Breadcrumb">
            <ol role="list" class="flex items-center justify-start gap-x-1 text-right">
              <li>
                <div>
                  <a href="#" class="pr-1 font-Flatnormal text-[#A3A3A4]  text-[14px] hover:text-gray-700">
                    <span>طلباتي</span>
                  </a>
                </div>
              </li>

              <li>
                <div class="flex items-center">
                  <!-- Heroicon name: solid/chevron-right -->
                  <svg class="flex-shrink-0 h-5 w-5 text-gray-400 rotate-180" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                    <path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd" />
                  </svg>
                  <a href="#" class="pr-1 font-Flatnormal  text-[14px] hover:text-gray-700">لوحة التحكم</a>
                </div>
              </li>
              <li>
                <div class="flex items-center">
                  <!-- Heroicon name: solid/chevron-right -->
                  <svg class="flex-shrink-0 h-5 w-5 text-gray-400 rotate-180" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                    <path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd" />
                  </svg>
                  <a href="#" class="pr-1 font-Flatnormal  text-[14px] hover:text-gray-700" aria-current="page">الرئيسية</a>
                </div>
              </li>
            </ol>
          </nav>
        <p class="sm:text-right text-center font-FlatBold text-[30px] pt-6">لوحة التحكم</p>
    </div>

       <div class="md:flex md:flex-row-reverse flex flex-col mx-auto px-4 my-4 sm:px-6 lg:max-w-7xl">
       <div class="lg:basis-1/4 min-w-[300px] md:block hidden ">
       <nav class="bg-[#F5F7FF] text-white rounded-md" aria-label="Sidebar">
             <a  href="{{route('user-account')}}" class="flex hover:bg-black  duration-300  justify-between flex-row-reverse pr-5 py-5 text-[16px] font-shamelBold border-b-2 border-[#CACDD8] mx-3" >
                <p class="w-full text-right hover:border-l-2 hover:border-l-[#0156FF] font-FlatBold text-[15px] text-[#212121] hover:text-white">حسابي </p>
             </a>

             <a href="{{route('account-oder') }}" class="flex hover:bg-black  duration-300  justify-between flex-row-reverse px-5 py-5 text-[16px] font-shamelBold border-b-2 border-[#CACDD8] mx-3" >
                <p class="w-full text-right font-FlatBold text-[15px] text-[#212121] hover:text-white hover:border-l-2 hover:border-l-[#0156FF]">طلباتي </p>

             </a>
             <a href="{{route('wishlists')}}" class="flex hover:bg-black  duration-300  justify-between flex-row-reverse px-5 py-5 text-[16px] font-shamelBold border-b-2 border-[#CACDD8] mx-3" >
                <p class="w-full text-right font-FlatBold text-[15px] text-[#212121] hover:text-white hover:border-l-2 hover:border-l-[#0156FF]">تتبع الطلب </p>
             </a>

             <a class="flex hover:bg-black  duration-300  justify-between flex-row-reverse px-5 py-5 text-[16px] font-shamelBold border-b-2 border-[#CACDD8] mx-3" >
                <p class="w-full text-right font-FlatBold text-[15px] text-[#212121] hover:text-white hover:border-l-2 hover:border-l-[#0156FF]">خدمة العملاء  </p>

             </a>
             <a href="{{route('customer.auth.logout')}}" class="flex hover:bg-black  duration-300  justify-between flex-row-reverse px-5 py-5 text-[16px] font-shamelBold border-b-2 border-[#CACDD8] mx-3">
                <p class="w-full text-right font-FlatBold text-[15px] text-[#212121] hover:text-white hover:border-l-2 hover:border-l-[#0156FF]"> تسيجل خروج </p>
             </a>
          </nav>
       </div>
       <div class="lg:basis-3/4">
          <div class="px-4 sm:px-6 lg:px-8 h-full">
             <div class="sm:flex sm:items-center"></div>
             <div class="mt-8 lg:mt-0 flex flex-col h-full ">
                <div class="-mx-4 overflow-x-auto sm:-mx-6 lg:-mx-8 h-full">
                   <div class="inline-block min-w-full align-middle lg:px-8 lg:pl-0 h-full">
                      <div class="overflow-hidden  ring-opacity-0 rounded-md h-full">
                    <p class="font-FlatBold text-[18px] text-right border-b border-b-[#CACDD8] pb-4 ml-8 mr-4">خدمة العملاء</p>
                    <p class="font-FlatBold text-[11px] pt-6 text-right">*ما الذي يدور في ذهنك؟</p>
  <div class="mt-1 flex justify-end">
              <textarea id="message" name="message" rows="8"  cols="72" placeholder="قم بتدوين ملاحظة وسنقوم بالرد عليك في أسرع وقت ممكن" 
              class="py-3 px-4 block text-[14px] lg:min-h-[236px] xl:w-[770px] md:w-[400px] focus:ring-[#9A92CC] placeholder[#A2A6B0] text-right border border-[#A2A6B0] rounded-[4px]" />
            </div>
            <div class="flex flex-row justify-end mt-5">
                   <button type="button" class="inline-flex justify-center items-center px-4 py-2  h-[50px] text-[14px] font-FlatBold rounded-[50px] lg:min-w-[150px] text-white bg-blue-700 hover:bg-black hover:text-blue-700 ">ارسال</button>
                      </div>
                      </div>
                   </div>
                </div>

             </div>
          </div>
       </div>
    </div>



        </div>
</template>