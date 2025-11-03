
  <template>
  <div class="bg-white dark:bg-gray-900">
    <header class="absolute inset-x-0 top-0 z-50">
      <div class="mx-auto max-w-7xl">
        <div class="px-6 pt-6 lg:max-w-2xl lg:pr-0 lg:pl-8">
          <!-- <nav class="flex items-center justify-between lg:justify-start" aria-label="Global">
            <a href="#" class="-m-1.5 p-1.5">
              <span class="sr-only">Your Company</span>
              <img alt="Your Company" class="h-8 w-auto dark:hidden" src="https://tailwindcss.com/plus-assets/img/logos/mark.svg?color=indigo&shade=600" />
              <img alt="Your Company" class="h-8 w-auto not-dark:hidden" src="https://tailwindcss.com/plus-assets/img/logos/mark.svg?color=indigo&shade=500" />
            </a>
            <button type="button" class="-m-2.5 rounded-md p-2.5 text-gray-700 lg:hidden dark:text-gray-200" @click="mobileMenuOpen = true">
              <span class="sr-only">Open main menu</span>
              <Bars3Icon class="size-6" aria-hidden="true" />
            </button>
            <div class="hidden lg:ml-12 lg:flex lg:gap-x-14">
              <a v-for="item in navigation" :key="item.name" :href="item.href" class="text-sm/6 font-semibold text-gray-900 dark:text-white">{{ item.name }}</a>
            </div>
          </nav> -->
        </div>
      </div>
      <!-- <Dialog class="lg:hidden" @close="mobileMenuOpen = false" :open="mobileMenuOpen">
        <div class="fixed inset-0 z-50"></div>
        <DialogPanel class="fixed inset-y-0 right-0 z-50 w-full overflow-y-auto bg-white p-6 sm:max-w-sm sm:ring-1 sm:ring-gray-900/10 dark:bg-gray-900 dark:sm:ring-gray-100/10">
          <div class="flex items-center justify-between">
            <a href="#" class="-m-1.5 p-1.5">
              <span class="sr-only">Your Company</span>
              <img class="h-8 w-auto dark:hidden" src="https://tailwindcss.com/plus-assets/img/logos/mark.svg?color=indigo&shade=600" alt="" />
              <img class="h-8 w-auto not-dark:hidden" src="https://tailwindcss.com/plus-assets/img/logos/mark.svg?color=indigo&shade=500" alt="" />
            </a>
            <button type="button" class="-m-2.5 rounded-md p-2.5 text-gray-700 dark:text-gray-200" @click="mobileMenuOpen = false">
              <span class="sr-only">Close menu</span>
              <XMarkIcon class="size-6" aria-hidden="true" />
            </button>
          </div>
          <div class="mt-6 flow-root">
            <div class="-my-6 divide-y divide-gray-500/10 dark:divide-white/10">
              <div class="space-y-2 py-6">
                <a v-for="item in navigation" :key="item.name" :href="item.href" class="-mx-3 block rounded-lg px-3 py-2 text-base/7 font-semibold text-gray-900 hover:bg-gray-50 dark:text-white dark:hover:bg-white/5">{{ item.name }}</a>
              </div>
              <div class="py-6">
                <a href="#" class="-mx-3 block rounded-lg px-3 py-2.5 text-base/7 font-semibold text-gray-900 hover:bg-gray-50 dark:text-white dark:hover:bg-white/5">Log in</a>
              </div>
            </div>
          </div>
        </DialogPanel>
      </Dialog> -->
    </header>

    <div class="relative">
      <div class="mx-auto max-w-7xl">
        <div class="relative z-10 pt-14 lg:w-full lg:max-w-2xl">
          <svg class="absolute inset-y-0 right-8 hidden h-full w-80 translate-x-1/2 transform fill-white lg:block dark:fill-gray-900" viewBox="0 0 100 100" preserveAspectRatio="none" aria-hidden="true">
            <polygon points="0,0 90,0 50,100 0,100" />
          </svg>

          <div class="relative px-6 py-32 sm:py-40 lg:px-8 lg:py-56 lg:pr-0">
            <div class="mx-auto max-w-2xl lg:mx-0 lg:max-w-xl">
              <div class="hidden sm:mb-10 sm:flex">
                <!-- <div class="relative rounded-full px-3 py-1 text-sm/6 text-gray-500 ring-1 ring-gray-900/10 hover:ring-gray-900/20 dark:text-gray-400 dark:ring-white/10 dark:hover:ring-white/20">
                  Anim aute id magna aliqua ad ad non deserunt sunt. <a href="#" class="font-semibold whitespace-nowrap text-indigo-600 dark:text-indigo-400"><span class="absolute inset-0" aria-hidden="true"></span>Read more <span aria-hidden="true">&rarr;</span></a>
                </div> -->
              </div>
              <h1 class="text-5xl font-semibold tracking-tight text-pretty text-gray-900 sm:text-7xl dark:text-white">莎賓娜的音樂天地</h1>

              <!-- <p class="mt-8 text-lg font-medium text-pretty text-gray-500 sm:text-xl/8 dark:text-gray-400">
                Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat aliqua.
              </p> -->
              <div class="mt-10 flex items-center gap-x-6">
                <a href="https://www.facebook.com/sabrina.chen.427910" class="flex items-center justify-center w-10 h-10 rounded-full bg-blue-600 hover:bg-blue-700 text-white transition-colors">
                  <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/>
                  </svg>
                </a>
                <a href="https://open.spotify.com/artist/40wjyacEHSchuvz1jxTGKI?si=xk5-QHE4QZmZOQSjJ59hQA&nd=1&utm_medium=organic&_branch_referrer=H4sIAAAAAAAAA72N3wqCMByFn2bepaUWFEgI2X8IsatuZM6p07WN37bKLnr2LOgVgnNxOB8fpzFG6YXnaSUNq3oXK%2BVyJjpvqUCWlphIKioc5IeV5Ty3wKPmo6AgRv56yAe7P5vI6zBhMEyboYTje9tjkmwz0tjbc9I%2BzpvDDgVrzVCwenTTUbpNwvRyvZzSrN1P500af68w5wUm3R%2FukD8T5UAnTkWxsUAjCTUWjDgvoBUFYKLOC5B3TSE6MkHfsVFlazEBAAA%3D&product=open&%24full_url=https%3A%2F%2Fopen.spotify.com%2Fartist%2F40wjyacEHSchuvz1jxTGKI%3Fsi%3Dxk5-QHE4QZmZOQSjJ59hQA&feature=organic&_branch_match_id=1485609152473519901" class="flex items-center justify-center w-10 h-10 rounded-full bg-green-500 hover:bg-green-600 text-white transition-colors">
                  <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M12 0C5.4 0 0 5.4 0 12s5.4 12 12 12 12-5.4 12-12S18.66 0 12 0zm5.521 17.34c-.24.359-.66.48-1.021.24-2.82-1.74-6.36-2.101-10.561-1.141-.418.122-.779-.179-.899-.539-.12-.421.18-.78.54-.9 4.56-1.021 8.52-.6 11.64 1.32.42.18.479.659.301 1.02zm1.44-3.3c-.301.42-.841.6-1.262.3-3.239-1.98-8.159-2.58-11.939-1.38-.479.12-1.02-.12-1.14-.6-.12-.48.12-1.021.6-1.141C9.6 9.9 15 10.561 18.72 12.84c.361.181.54.78.241 1.2zm.12-3.36C15.24 8.4 8.82 8.16 5.16 9.301c-.6.179-1.2-.181-1.38-.721-.18-.601.18-1.2.72-1.381 4.26-1.32 11.28-1.08 15.721 1.621.539.3.719 1.02.42 1.56-.299.421-1.02.599-1.559.3z"/>
                  </svg>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="bg-gray-50 lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2 dark:bg-gray-800">
        <img class="aspect-3/2 object-cover lg:aspect-auto lg:size-full" src="~/assets/images/file01.png" alt="" />
      </div>
    </div>
  </div>

  <!-- s2-->
  <div class="bg-white px-6 py-32 lg:px-8 dark:bg-gray-900">
    <div class="mx-auto max-w-3xl text-base/7 text-gray-700 dark:text-gray-300">
      <p class="text-base/7 font-semibold text-indigo-600 dark:text-indigo-400">Self-introduction</p>
      <h1 class="mt-2 text-4xl font-semibold tracking-tight text-pretty text-gray-900 sm:text-5xl dark:text-white">陳文瑜 Wen-Yu Chen</h1>
      <p class="mt-6 text-xl/8">東海大學音樂系畢業。曾就讀草屯國中音樂班主修打擊、副修鋼琴。高中就讀美國加州 Mission San Jose High School，並參與學校行進樂隊前往澳洲巡演。曾於東海大學音樂系主修打擊，師事陳又誠老師。
曾參與 111 學年度全國學生音樂比賽臺中市初賽榮獲打擊（馬林巴）獨奏大專組優等。



本網站提供家教、教學資訊，有意者歡迎洽詢。</p>
      <p>台灣：090-972-4355</p>
      <p>美國：510-320-8016</p>
      <figure class="mt-16">
        <img class="aspect-video rounded-xl bg-gray-50 object-cover dark:bg-gray-800" src="~/assets/images/file02.png" alt="" />

      </figure>
      <!-- <div class="mt-16 max-w-2xl text-gray-600 dark:text-gray-400">
        <h2 class="text-3xl font-semibold tracking-tight text-pretty text-gray-900 dark:text-white">Everything you need to get up and running</h2>
        <p class="mt-6">Purus morbi dignissim senectus mattis adipiscing. Amet, massa quam varius orci dapibus volutpat cras. In amet eu ridiculus leo sodales cursus tristique. Tincidunt sed tempus ut viverra ridiculus non molestie. Gravida quis fringilla amet eget dui tempor dignissim. Facilisis auctor venenatis varius nunc, congue erat ac. Cras fermentum convallis quam.</p>
        <p class="mt-8">Faucibus commodo massa rhoncus, volutpat. Dignissim sed eget risus enim. Mattis mauris semper sed amet vitae sed turpis id. Id dolor praesent donec est. Odio penatibus risus viverra tellus varius sit neque erat velit.</p>
      </div> -->
    </div>
  </div>
  <!-- footer -->
  <footer class="bg-white dark:bg-gray-900">
    <div class="mx-auto px-6 py-12 md:flex md:items-center md:justify-center lg:px-8">
    <p class="mt-8 text-center text-sm/6 text-gray-600 md:order-1 md:mt-0 dark:text-gray-400">&copy; 2025 億辰科技有限公司. All rights reserved.</p>
</div>
  </footer>
</template>

