<template>
  <nav class="flex items-center justify-between mx-2 lg:mx-12 my-4 text-sm xl:text-lg">
    <HeaderIcon />
    <div class="hidden lg:block flex items-center justify-center space-x-5">
      <NuxtLink href="/">Результаты</NuxtLink>
      <a href="">Отзывы</a>
      <a href="">Методы</a>
      <a href="">Консултация</a>
      <a href="">Для приезжих</a>
      <a href="/about">О нас</a>
    </div>
    <div class="flex items-center justify-center space-x-2">
      <div class="block sm:hidden ">
        <!-- Phone icon -->
        <svg class="h-8 w-10 " viewBox="0 0 43 43" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect x="0.5" y="0.5" width="42" height="42" rx="9.5" stroke="#DFDFDE" />
          <path
            d="M30.9711 24.9125C30.4806 24.6631 28.0717 23.4917 27.6248 23.329C27.1779 23.1663 26.8509 23.0795 26.5239 23.5785C26.1969 24.0665 25.2596 25.162 24.9762 25.4873C24.6928 25.8127 24.4094 25.8561 23.9189 25.6066C23.4284 25.3572 21.8479 24.8474 19.9731 23.188C18.5125 21.8973 17.5315 20.2921 17.2481 19.8041C16.9647 19.316 17.2154 19.0557 17.4661 18.8063C17.6841 18.5893 17.9566 18.2314 18.1964 17.9494C18.4362 17.6674 18.5234 17.4614 18.6869 17.136C18.8504 16.8106 18.7632 16.5286 18.6433 16.2792C18.5234 16.0297 17.5424 13.6328 17.1282 12.6566C16.7249 11.7022 16.3216 11.8323 16.0273 11.8215C15.7439 11.8106 15.4169 11.7998 15.09 11.7998C14.763 11.7998 14.2289 11.9191 13.782 12.4072C13.3351 12.8952 12.0707 14.0774 12.0707 16.4744C12.0707 18.8713 13.8256 21.1924 14.0763 21.5177C14.3161 21.8431 17.5315 26.7672 22.4583 28.8821C23.6246 29.381 24.5402 29.6847 25.2487 29.9125C26.4258 30.2812 27.494 30.227 28.3333 30.1077C29.2707 29.9667 31.2327 28.9255 31.6469 27.7867C32.0502 26.6479 32.0502 25.6717 31.9303 25.4656C31.7886 25.2813 31.4616 25.162 30.9711 24.9125Z"
            fill="#0EB80E" />
        </svg>

      </div>
      <div class="hidden sm:flex flex items-center  justify-center space-x-4 ">
        <span>
          +992928882699
        </span>
        <button class="bg-white rounded-lg border border-gray-600 px-4 py-2  text-sm " style="color: #0EB80E">
          Заказать звоноки
        </button>
        <div class="hidden lg:block flex flex-wrap items-center justify-center space-x-4">
          <button class="">
            <svg width="37" height="37" viewBox="0 0 37 37" class="lg:w-8 lg:h-8" fill="none"
              xmlns="http://www.w3.org/2000/svg">
              <rect x="0.5" y="0.5" width="36" height="36" rx="9.5" stroke="#DFDFDE" />
              <path
                d="M18.5 9.75C13.6678 9.75 9.75 13.6678 9.75 18.5H12.25C12.25 15.0485 15.0485 12.25 18.5 12.25V9.75ZM9.75 18.5C9.75 23.3322 13.6678 27.25 18.5 27.25V24.75C15.0485 24.75 12.25 21.9515 12.25 18.5H9.75ZM18.5 27.25C23.3322 27.25 27.25 23.3322 27.25 18.5H24.75C24.75 21.9515 21.9515 24.75 18.5 24.75V27.25ZM27.25 18.5C27.25 13.6678 23.3322 9.75 18.5 9.75V12.25C21.9515 12.25 24.75 15.0485 24.75 18.5H27.25Z"
                fill="#0EB80E" />
              <path
                d="M28.75 9C28.75 8.86193 28.8619 8.75 29 8.75V11.25C30.2426 11.25 31.25 10.2426 31.25 9H28.75ZM29 8.75C29.1381 8.75 29.25 8.86193 29.25 9H26.75C26.75 10.2426 27.7574 11.25 29 11.25V8.75ZM29.25 9C29.25 9.13807 29.1381 9.25 29 9.25V6.75C27.7574 6.75 26.75 7.75736 26.75 9H29.25ZM29 9.25C28.8619 9.25 28.75 9.13807 28.75 9H31.25C31.25 7.75736 30.2426 6.75 29 6.75V9.25Z"
                fill="#0EB80E" />
            </svg>
          </button>
          <button><svg width="37" height="37" viewBox="0 0 37 37" class="lg:w-8 lg:h-8" fill="none"
              xmlns="http://www.w3.org/2000/svg">
              <rect width="37" height="37" rx="10" fill="#0EB80E" />
              <path
                d="M19.4379 25C12.263 25 8.17052 20.1201 8 12H11.594C11.7121 17.96 14.3616 20.4845 16.4603 21.005V12H19.8445V17.1401C21.9169 16.9189 24.0943 14.5766 24.8289 12H28.213C27.9362 13.3363 27.3845 14.6015 26.5923 15.7166C25.8001 16.8317 24.7845 17.7726 23.609 18.4805C24.9211 19.1273 26.08 20.0428 27.0093 21.1666C27.9386 22.2904 28.6171 23.597 29 25H25.2748C24.9311 23.7814 24.2324 22.6905 23.2664 21.8641C22.3004 21.0376 21.11 20.5125 19.8445 20.3544V25H19.4379Z"
                fill="white" />
            </svg>
          </button>
          <button><svg width="37" height="37" viewBox="0 0 37 37" fill="none" class="lg:w-8 lg:h-8"
              xmlns="http://www.w3.org/2000/svg">
              <rect x="0.5" y="0.5" width="36" height="36" rx="9.5" stroke="#DFDFDE" />
              <path
                d="M23.4059 19.9125C23.1659 19.7905 21.9878 19.2175 21.7692 19.138C21.5506 19.0584 21.3907 19.016 21.2307 19.26C21.0708 19.4987 20.6123 20.0345 20.4737 20.1936C20.3351 20.3528 20.1965 20.374 19.9566 20.252C19.7167 20.13 18.9437 19.8806 18.0267 19.069C17.3123 18.4377 16.8325 17.6526 16.6939 17.4139C16.5553 17.1752 16.6779 17.0479 16.8005 16.9259C16.9072 16.8198 17.0404 16.6447 17.1577 16.5068C17.275 16.3689 17.3177 16.2681 17.3976 16.109C17.4776 15.9498 17.435 15.8119 17.3763 15.6899C17.3177 15.5679 16.8379 14.3955 16.6353 13.9181C16.438 13.4513 16.2408 13.5149 16.0968 13.5096C15.9582 13.5043 15.7983 13.499 15.6384 13.499C15.4784 13.499 15.2172 13.5574 14.9986 13.7961C14.78 14.0348 14.1616 14.613 14.1616 15.7854C14.1616 16.9577 15.0199 18.0929 15.1426 18.2521C15.2598 18.4112 16.8325 20.8196 19.2422 21.854C19.8126 22.098 20.2605 22.2466 20.607 22.358C21.1828 22.5383 21.7052 22.5118 22.1157 22.4534C22.5742 22.3845 23.5338 21.8752 23.7364 21.3182C23.9336 20.7612 23.9336 20.2838 23.875 20.183C23.8057 20.0928 23.6458 20.0345 23.4059 19.9125Z"
                fill="#0EB80E" />
              <path
                d="M25.3809 11.616C23.688 9.93146 21.4373 9 19.0423 9C14.1029 9 10.0797 13.0033 10.0797 17.9183C10.0797 19.4889 10.4929 21.0248 11.2747 22.3774L10 27L14.7502 25.7614C16.0597 26.4699 17.5336 26.8464 19.0324 26.8464H19.0373C23.9767 26.8464 28 22.8431 28 17.9282C28.005 15.545 27.0738 13.3006 25.3809 11.616Z"
                stroke="#0EB80E" stroke-width="2.04545" />
            </svg></button>
        </div>
      </div>

      <!-- for tablets devices -->

      <div class="block text-sm lg:text-lg lg:hidden">

        <button data-collapse-toggle="navbar-default" @click.prevent="openMenu()" type="button"
          class="inline-flex items-center p-2 ml-3 text-sm text-gray-500 rounded-lg lg:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
          aria-controls="navbar-default" aria-expanded="false">
          <svg width="30" height="22" viewBox="0 0 30 22" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect width="30" height="4" rx="2" fill="#0EB80E" />
            <rect y="9" width="30" height="4" rx="2" fill="#0EB80E" />
            <rect y="18" width="30" height="4" rx="2" fill="#0EB80E" />
          </svg>

        </button>
      </div>
      <div v-show="tablet" style="border-radius: 66px 0; background-color:#0EB80E;"
        class="block lg:hidden fixed flex items-center justify-center z-50 top-0  right-0 w-3/5 h-auto py-12">
        <!-- close X button -->
        <button @click.prevent="(tablet = false)"
          class="text-white absolute hover:bg-white hover:text-red-700 right-0 top-5 rounded-full  text-2xl mr-8">
          <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
          </svg></button>
        <div class=" block flex flex-col text-lg h-auto text-white w-full mx-10 space-y-4 text-center">
          <a href="/"
            class="block py-2 pr-4 pl-3 text-white rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Результаты</a>
          <a href=""
            class="block py-2 pr-4 pl-3 text-white rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Отзывы</a>
          <a href=""
            class="block py-2 pr-4 pl-3 text-white rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Методы</a>
          <a href=""
            class="block py-2 pr-4 pl-3 text-white rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Консултация</a>
          <a href=""
            class="block py-2 pr-4 pl-3 text-white rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Для
            приезжих</a>
          <a href="/about"
            class="block py-2 pr-4 pl-3 text-white rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">О
            нас</a>
          <div class=" items-center text-center justify-center space-x-4">
            <button class=""><svg width="37" height="37" viewBox="0 0 37 37" fill="none"
                xmlns="http://www.w3.org/2000/svg">
                <rect x="0.5" y="0.5" width="36" height="36" rx="9.5" stroke="#DFDFDE" />
                <path
                  d="M18.5 9.75C13.6678 9.75 9.75 13.6678 9.75 18.5H12.25C12.25 15.0485 15.0485 12.25 18.5 12.25V9.75ZM9.75 18.5C9.75 23.3322 13.6678 27.25 18.5 27.25V24.75C15.0485 24.75 12.25 21.9515 12.25 18.5H9.75ZM18.5 27.25C23.3322 27.25 27.25 23.3322 27.25 18.5H24.75C24.75 21.9515 21.9515 24.75 18.5 24.75V27.25ZM27.25 18.5C27.25 13.6678 23.3322 9.75 18.5 9.75V12.25C21.9515 12.25 24.75 15.0485 24.75 18.5H27.25Z"
                  fill="white" />
                <path
                  d="M28.75 9C28.75 8.86193 28.8619 8.75 29 8.75V11.25C30.2426 11.25 31.25 10.2426 31.25 9H28.75ZM29 8.75C29.1381 8.75 29.25 8.86193 29.25 9H26.75C26.75 10.2426 27.7574 11.25 29 11.25V8.75ZM29.25 9C29.25 9.13807 29.1381 9.25 29 9.25V6.75C27.7574 6.75 26.75 7.75736 26.75 9H29.25ZM29 9.25C28.8619 9.25 28.75 9.13807 28.75 9H31.25C31.25 7.75736 30.2426 6.75 29 6.75V9.25Z"
                  fill="white" />
              </svg>
            </button>
            <button class=""><svg width="37" height="37" class="rounded-lg" viewBox="0 0 37 37" fill="none"
                xmlns="http://www.w3.org/2000/svg">
                <rect width="37" height="37" rx="10" fill="" stroke="#DFDFDE" />
                <path
                  d="M19.4379 25C12.263 25 8.17052 20.1201 8 12H11.594C11.7121 17.96 14.3616 20.4845 16.4603 21.005V12H19.8445V17.1401C21.9169 16.9189 24.0943 14.5766 24.8289 12H28.213C27.9362 13.3363 27.3845 14.6015 26.5923 15.7166C25.8001 16.8317 24.7845 17.7726 23.609 18.4805C24.9211 19.1273 26.08 20.0428 27.0093 21.1666C27.9386 22.2904 28.6171 23.597 29 25H25.2748C24.9311 23.7814 24.2324 22.6905 23.2664 21.8641C22.3004 21.0376 21.11 20.5125 19.8445 20.3544V25H19.4379Z"
                  fill="white" />
              </svg>
            </button>
            <button class=""><svg width="37" height="37" viewBox="0 0 37 37" fill="none"
                xmlns="http://www.w3.org/2000/svg">
                <rect x="0.5" y="0.5" width="36" height="36" rx="9.5" stroke="#DFDFDE" />
                <path
                  d="M23.4059 19.9125C23.1659 19.7905 21.9878 19.2175 21.7692 19.138C21.5506 19.0584 21.3907 19.016 21.2307 19.26C21.0708 19.4987 20.6123 20.0345 20.4737 20.1936C20.3351 20.3528 20.1965 20.374 19.9566 20.252C19.7167 20.13 18.9437 19.8806 18.0267 19.069C17.3123 18.4377 16.8325 17.6526 16.6939 17.4139C16.5553 17.1752 16.6779 17.0479 16.8005 16.9259C16.9072 16.8198 17.0404 16.6447 17.1577 16.5068C17.275 16.3689 17.3177 16.2681 17.3976 16.109C17.4776 15.9498 17.435 15.8119 17.3763 15.6899C17.3177 15.5679 16.8379 14.3955 16.6353 13.9181C16.438 13.4513 16.2408 13.5149 16.0968 13.5096C15.9582 13.5043 15.7983 13.499 15.6384 13.499C15.4784 13.499 15.2172 13.5574 14.9986 13.7961C14.78 14.0348 14.1616 14.613 14.1616 15.7854C14.1616 16.9577 15.0199 18.0929 15.1426 18.2521C15.2598 18.4112 16.8325 20.8196 19.2422 21.854C19.8126 22.098 20.2605 22.2466 20.607 22.358C21.1828 22.5383 21.7052 22.5118 22.1157 22.4534C22.5742 22.3845 23.5338 21.8752 23.7364 21.3182C23.9336 20.7612 23.9336 20.2838 23.875 20.183C23.8057 20.0928 23.6458 20.0345 23.4059 19.9125Z"
                  fill="white" />
                <path
                  d="M25.3809 11.616C23.688 9.93146 21.4373 9 19.0423 9C14.1029 9 10.0797 13.0033 10.0797 17.9183C10.0797 19.4889 10.4929 21.0248 11.2747 22.3774L10 27L14.7502 25.7614C16.0597 26.4699 17.5336 26.8464 19.0324 26.8464H19.0373C23.9767 26.8464 28 22.8431 28 17.9282C28.005 15.545 27.0738 13.3006 25.3809 11.616Z"
                  stroke="white" stroke-width="2.04545" />
              </svg></button>
            <p class="text-center">
              +992928882699
            </p>

          </div>
        </div>
      </div>
      <div>

      </div>
    </div>
  </nav>
</template>
<script setup>

const tablet = ref(false);
function openMenu() {
  tablet.value = true
}


</script>
