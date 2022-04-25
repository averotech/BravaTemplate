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
             <div class="mt-8 lg:mt-0 flex flex-col h-full">
                <div class="-mx-4 overflow-x-auto sm:-mx-6 lg:-mx-8 h-full">
                   <div class="inline-block min-w-full align-middle lg:px-8 lg:pl-0 h-full">
                      <div class="overflow-hidden  ring-opacity-0 rounded-md h-full">
                         <table class="min-w-full bg-[#fafafa] px-4 pb-20 h-full" style="border-collapse:separate; border-spacing:0 8px;" cellspacing="0">
                            <thead class="text-right">
                               <tr class="border-b border-[#9A92CC]">
                                  <th scope="col" class="border-b border-[#9A92CC] py-3.5 pl-4 pr-3 text-center text-[17px] sm:pl-6">الحدث</th>
                                  <th scope="col" class="border-b border-[#9A92CC] py-3.5 pl-4 pr-3 text-center text-[17px] sm:pl-6">السعر</th>
                                  <th scope="col" class="border-b border-[#9A92CC] px-3 py-3.5 text-center text-[17px] ">تاريخ الطلب</th>
                                  <th scope="col" class="border-b border-[#9A92CC] px-3 py-3.5 text-center text-[17px] ">الحالة</th>
                                  <th scope="col" class="border-b border-[#9A92CC] px-3 py-3.5 text-center text-[17px] ">الطلب</th>
                               </tr>
                            </thead>
                            <tbody>




                <tr class="">
                  <td class="whitespace-nowrap py-4 pl-4 pr-3 text-sm  font-Flatnormal w-8 h-8  sm:pl-6">
                      <div class="flex flex-row-reverse items-center justify-center w-8 h-8 ">
                      <img src="../../assets/Icons/Eye.svg" class="ml-2"/>
                      <img src="../../assets/Icons/Exit.svg" />
                      </div>
                  </td>
                  <td class="whitespace-nowrap px-3 text-center py-4 text-sm font-Flatnormal ">120₪</td>
                  <td class="whitespace-nowrap px-3 text-center py-4 text-sm font-Flatnormal ">12-02-2022</td>
                  <td class="whitespace-nowrap px-3 text-center py-4 text-sm font-Flatnormal ">مكتمل</td>
                  <td class="whitespace-nowrap px-3 h-full w-full text-center flex items-center justify-center py-4 text-sm text-[#201A3C]">
                      <img class="w-12 h-12 object-fill " src="../../assets/Icons/iphoneProduct.png">
                  </td>
                  <!-- <td class="relative whitespace-nowrap text-center py-4 pl-3 pr-4 text-sm  sm:pr-6">
                    <a href="#" class="text-indigo-600 hover:text-indigo-900"
                      >Edit<span class="sr-only">, {{ person.name }}</span></a
                    >
                  </td> -->
                </tr>

                               <!-- <tr class="bg-white">
                                  <td class="whitespace-nowrap py-4 pl-4 pr-3 text-sm sm:pl-6">
                                     <div class="lg:px-0 px-10 sm:px-0 flex flex-row-reverse items-center justify-center">
                                         src="{{asset('assets/front-end/icons/eye 1.svg')}}"
                                        <img onclick="location.href='{{ route('account-order-details', ['id'=>$order->id]) }}'"
                                        src="../../assets/Icons/Eye.svg"
                                        class="ml-5 cursor-pointer"
                                          alt="" />
                                         src="{{asset('assets/front-end/icons/CartDelete.svg')}}"
                                        <img class="cursor-pointer" onclick="route_alert('{{ route('order-cancel',[$order->id]) }}','{{\App\CPU\translate('want_to_cancel_this_order?')}}')"
                                          src="../../assets/Icons/Exit.svg"
                                          alt="" />
                                     </div>
                                  </td>
                                  <td class="whitespace-nowrap px-3 text-center py-4 text-sm text-[#201A3C]">
                                     <p class="my-2">
                                     </p>
                                  </td>
                                  <td class="whitespace-nowrap px-3 text-center py-4 text-sm text-[#201A3C]">
                                     <p>
                                     </p>
                                  </td>
                                  <td class="whitespace-nowrap px-3 text-center py-4 text-sm text-[#201A3C]"> 
                                      </td>
                                  <td class="whitespace-nowrap px-3 text-center py-4 text-sm text-[#201A3C]">
                                       </td>
                                  <td class="whitespace-nowrap px-3 text-center py-4 text-sm text-[#201A3C]">
                                       </td>
                                  <td class="whitespace-nowrap px-3 text-center py-4 text-sm w-12 h-12 object-fill">
                                     <p class="px-5">
                                     </p>
                                  </td>
                               </tr> -->

                               <!-- <tr class="whitespace-nowrap px-3 text-center text-sm text-[#201A3C]">
                                  <td colspan="5">
                                     <p class="py-10 font-bold">لم يتم العثور على طلب</p>
                                  </td>
                               </tr> -->

                            </tbody>
                         </table>
                      </div>
                   </div>
                </div>

             </div>
          </div>
       </div>
    </div>
    </div>
</template>