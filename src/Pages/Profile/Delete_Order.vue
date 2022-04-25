<template>
      <div
    class="fixed z-10 inset-0 overflow-y-auto"
    aria-labelledby="modal-title"
    role="dialog"
    aria-modal="true"
  >
    <div
      class="flex items-end justify-center min-h-screen pt-4 px-4 pb-20 text-center sm:block sm:p-0">
      <div
        class="fixed inset-0 bg-gray-500 bg-opacity-75 transition-opacity"
        aria-hidden="true">
      </div>
      <span
        class="hidden sm:inline-block sm:align-middle sm:h-screen"
        aria-hidden="true"
        >&#8203;</span
      >
      <div
        class="relative inline-block align-bottom bg-white rounded-lg px-4 pt-5 pb-4 text-left overflow-hidden
         shadow-xl transform transition-all sm:my-8 sm:align-baseline sm:max-w-md sm:w-full sm:p-6">
        <div>
 
          <div class="mt-3 text-center sm:mt-5">
            <h3 class="text-lg leading-6 text-[30px] text-[#171515] font-FlatBold" id="modal-title">
           هل تريد حذف هذا الطلب؟
            </h3>
            <div class="mt-2"></div>
          </div>
        </div>
        <div
          class="mt-5 sm:mt-6 sm:grid sm:grid-cols-2  sm:grid-flow-row-dense">
          <button
            type="button"
            class="inline-flex justify-center items-center rounded-[50px] border font-FlatBold border-transparent hover:bg-black hover-text-white bg-[#0156FF] max-w-[150px]
              text-[14px] text-white sm:col-start-2 ">
            الغاء
          </button>
          <button
            type="button"
            class="mt-3 ml-10 flex items-center justify-center rounded-[50px] font-FlatBold border border-[#0156FF] max-w-[150px] h-12
             shadow-sm  bg-transparent text-[14px] font-medium text-[#0156FF] hover:bg-[#0156FF]
              hover:text-white sm:mt-0 
              sm:col-start-1 sm:text-sm">
            تأكيد
          </button>
        </div>
      </div>
    </div>
  </div>
</template>