<template>
    <!--
  This example requires Tailwind CSS v2.0+ 
  
  This example requires some changes to your config:
  
  ```
  // tailwind.config.js
  module.exports = {
    // ...
    plugins: [
      // ...
      require('@tailwindcss/forms'),
    ],
  }
  ```
-->
<footer class="bg-[#020203]" aria-labelledby="footer-heading">
  <h2 id="footer-heading" class="sr-only">Footer</h2>
  <div class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:py-16 lg:px-8">

      <div class="flex md:flex-row-reverse md:py-0 lg:py-6 py-0 mb-9 flex-col items-center justify-between">
          <div class="mt-2 md:mt-0 md:mb-0 mb-4 ">
            <h3 class=" font-FlatBold text-[27px] md:text-[18px] lg:text-[27px] text-white tracking-wider leading-10 text-right">الاشتراك في النشرة الاحبارية.</h3>
        <p class="mt-2 font-Flatnormal text-[14px] text-white text-right leading-5">كن اول من يسمع عن أحدث العروض</p>
      </div>
     <form class="sm:flex sm:flex-row-reverse sm:space-x-3 items-center ">
          <input type="email" name="email-address" id="email-address" autocomplete="email" required 
          class="ml-4 xl:min-w-[390px] min-w-0 w-full text-right bg-transparent text-white border border-white rounded-[4px] text-[14px] py-3 px-4 placeholder-white focus:outline-none  focus:placeholder-gray-400" placeholder="بريدك الالكتروني">
          <div class="mt-3 rounded-md sm:mt-0 ml-6 sm:ml-3 sm:flex-shrink-0">
            <button type="submit" class="w-full bg-[#0156FF] rounded-[50px] border border-transparent py-3 px-12 flex items-center justify-center text-[14px] font-FlatBold text-white hover:bg-indigo-600 ">اشتراك</button>
          </div>
        </form>
      </div>

      <div class="grid grid-cols-2 md:grid-cols-4 gap-8 xl:col-span-1">
          <div class="col-span-2 md:col-span-1 flex flex-col md:block items-center">
            <h3 class="text-[#FFFFFF80] font-Poppins-Bold text-[14px] text-right  ">العنوان</h3>
            <ul role="list" class="mt-4 space-y-4">
              <li >
                <p class="text-white text-[13px] font-Flatnormal text-center md:text-right">
                    Address: 1234 Street Adress City Address, 1234
                </p>
                <p class="text-white text-[13px] font-Flatnormal pt-2 text-center md:text-right">
                Phones: (00) 1234 5678
                </p>
                       <p class="text-white text-[13px] font-Flatnormal pt-2 text-center md:text-right">
                نحن متواجدون: الاثنين - الخميس: 9:00 صباحًا - 5:30 مساءً
                </p>
                <p class="text-white text-[13px] font-Flatnormal pt-2 text-center md:text-right">
                الجمعة: 9:00 ص - 6:00 م   
              </p>
              <p class="text-white text-[13px] font-Flatnormal pt-2 text-center md:text-right">
                السبت: 11:00 ص - 5:00 م     
         </p>
                       <p class="text-white text-[13px] font-Flatnormal pt-2 text-center md:text-right">
                البريد الالكتروني: shop@email.com
         </p>
              </li>
            </ul>
          </div>
          <div class=" md:mt-0 flex flex-col items-center" >
            <h3 class="text-[#FFFFFF80] font-Poppins-Bold text-[14px] ml-10 " >Apple</h3>
            <ul role="list" class="mt-4 space-y-2">
              <li v-for="item in navigation.support" :key="item" class="text-right">
                <a href="#" class="text-white text-[14px] font-Flatnormal  "> {{ item.name }} </a>
              </li>
            </ul>
          </div>
          <div class="flex flex-col items-center ">
            <h3 class="text-[#FFFFFF80] font-Poppins-Bold text-[14px] ml-24">روابط سريعة</h3>
            <ul role="list" class="mt-4 space-y-2">
              <li v-for="item in navigation.company" :key="item" class="text-right">
                <a href="#" class="text-white text-[14px] font-Flatnormal text-justify"> {{ item.name }} </a>
              </li>
            </ul>
          </div>
          <div class="mt-12 md:mt-0 col-span-2 md:col-span-1">
            <div class="flex items-center
             md:justify-end justify-center">
            <img src="../assets/Icons/Logo.svg" class="max-w-[110px] m-5" alt="logo" >
            </div>
            <ul role="list" class="mt-4 space-y-4">
              <li v-for="item in navigation.legal" :key="item" class="text-right">
                <a href="#" class="text-base text-gray-300 hover:text-white text-justify"> {{ item.name }} </a>
              </li>
            </ul>
          </div>
      </div>


    <div class="mt-8 border-t border-gray-700 pt-8 md:flex md:flex-row-reverse md:items-center md:justify-between">
      <div class="flex  md:order-2">
        <a href="#" class="text-gray-400 hover:text-gray-300 px-1">
          <span class="sr-only">Facebook</span>
          <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
            <path fill-rule="evenodd" d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z" clip-rule="evenodd" />
          </svg>
        </a>

        <a href="#" class="text-gray-400 hover:text-gray-300 px-3">
          <span class="sr-only">Instagram</span>
          <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
            <path fill-rule="evenodd" d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z" clip-rule="evenodd" />
          </svg>
        </a>
            <a href="#" class="text-white text-[12px] font-FlatBold pt-1 ">
            BRAVA.IL
        </a>
      </div>
      <p class="mt-8  font-Poppins text-[12px] text-white md:mt-0 md:order-1">Copyright © 2022brava.com</p>
    </div>
  </div>
</footer>
</template>

<script>
const navigation = {
  solutions: [
    { name: 'Marketing', href: '#' },
    { name: 'Analytics', href: '#' },
    { name: 'Commerce', href: '#' },
    { name: 'Insights', href: '#' },
  ],
  support: [
    { name: 'PC Part', href: '#' },
    { name: 'Mac', href: '#' },
    { name: 'iPad', href: '#' },
    { name: 'iPhone', href: '#' },
    { name: 'Apple Watch', href: '#' },
    { name: 'Music', href: '#' },


  ],
  company: [
    { name: 'من نحن', href: '#' },
    { name: 'خدمة الزبائن', href: '#' },
    { name: 'سياسة الطلب والارجاع', href: '#' },
    { name: 'اتصل بنا', href: '#' },
    { name: 'الاشتراك في النشرة الاخبارية', href: '#' },
  ],
  legal: [
    { name: 'هناك حقيقة مثبتة منذ زمن طويل وهي أن المحتوى المقروء لصفحة ما سيلهي القارئ عن التركيز على الشكل الخارجي للنص أو شكل توضع الفقرات في الصفحة التي يقرأها', href: '#' },

  ],}
//   const address = [
// Address: 1234 Street Adress City Address, 1234
// Phones: (00) 1234 5678
// نحن متواجدون: الاثنين - الخميس: 9:00 صباحًا - 5:30 مساءً
// الجمعة: 9:00 ص - 6:00 م
// السبت: 11:00 ص - 5:00 م
// البريد الالكتروني: shop@email.com}
//   ]
export default {
    setup() {
        return{
navigation
        }
    },
}
</script>
