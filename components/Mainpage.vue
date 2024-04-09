<template class="bg-white">
  <div class="bg-white h-screen">
    <header class="absolute inset-x-0 top-0 z-50">
      <nav class="flex items-center justify-between p-6 lg:px-8" aria-label="Global">
        <div class="flex lg:flex-1">
          <a href="#" class="-m-1.5 p-1.5">
            <span class="sr-only">Icon</span>
            <img src="https://i.ibb.co/6WjvC8B/8146f5db32acfbacf7b5bbfa3953063f-removebg-preview.png" alt=""
              class="h-8 w-auto">
          </a>
        </div>
        <div class="flex lg:hidden">
          <button type="button" class="-m-2.5 inline-flex items-center justify-center rounded-md p-2.5 text-black"
            @click="mobileMenuOpen = true">
            <span class="sr-only">main menu icon </span>
            <img src="https://cdn2.iconfinder.com/data/icons/e-commerce-clean-ui-flat/32/menu-64.png" alt=""
              class="h-8 w-auto">
          </button>
        </div>
        <div class="hidden lg:flex lg:gap-x-12">
          <a v-for="item in navigation" :key="item.name" :href="item.href"
            class="text-sm font-semibold leading-6 text-black">{{ item.name }}</a>
        </div>
      </nav>
      <Dialog as="div" class="lg:hidden" @close="mobileMenuOpen = false" :open="mobileMenuOpen">
        <div class="fixed inset-0 z-50" />
        <DialogPanel
          class="fixed inset-y-0 right-0 z-50 w-full overflow-y-auto bg-white px-6 py-6 sm:max-w-sm sm:ring-1 sm:ring-black-900/10">
          <div class="flex items-center justify-between">
            <a href="#" class="-m-1.5 p-1.5">
              <span class="sr-only">Icon</span>
              <img src="https://i.ibb.co/6WjvC8B/8146f5db32acfbacf7b5bbfa3953063f-removebg-preview.png" alt=""
                class="h-8 w-auto">
            </a>
            <button type="button" class="-m-2.5 rounded-md p-2.5 text-gray-700" @click="mobileMenuOpen = false">
              <span class="sr-only">Close menu</span>
              <xmarkicon aria-hidden="true" class="h-6 w-6"><img
                  src="https://cdn2.iconfinder.com/data/icons/4web-3/139/close-64.png" alt="" class="h-8 w-auto">
              </xmarkicon>
            </button>
          </div>
          <div class="mt-6 flow-root">
            <div class="-my-6 divide-y divide-gray-500/10">
              <div class="space-y-2 py-6">
                <a v-for="item in navigation" :key="item.name" :href="item.href"
                  class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50">{{
              item.name }}</a>
              </div>
            </div>
          </div>
        </DialogPanel>
      </Dialog>
    </header>

    <div class="relative isolate px-6 pt-14 lg:px-8">
    <div class="absolute inset-x-0 -top-40 -z-10 transform-gpu overflow-hidden blur-3xl sm:-top-80" aria-hidden="true">
      <div class="relative left-[calc(50%-11rem)] aspect-[1155/678] w-[36.125rem] -translate-x-1/2 rotate-[30deg] bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30 sm:left-[calc(50%-30rem)] sm:w-[72.1875rem]" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
    </div>
    <div class="mx-auto max-w-2xl py-32 sm:py-48 lg:py-56">
      <div class="sm:mb-8 sm:flex sm:justify-center">
        <div class="relative h-150 w-75">  
      <img class="h-full w-full object-cover" src="https://i.ibb.co/hXvJ1rZ/photo-2021-10-29-08-56-10-removebg-preview-1.png"  alt="myphoto" border="0"/> 
    </div>
      </div>
      <div class="text-center">
        <h2 id="typed-text" class="title-font  mb-4 text-4xl font-extrabold leading-10 tracking-tight sm:text-5xl sm:leading-none md:text-6xl"></h2>
        <p class="mt-6 text-lg leading-8 text-text-Indigo">En tant que passionné de développement  je recherche un poste d'alternant pour suivre la formation MSc Expert en informatique et systèmes d'information de niveau bac +5 chez EPSI à partir d'octobre 2024, avec un rythme de 2 semaines en entreprise/1 semaine en centre</p>
        <div class="mt-10 flex items-center justify-center gap-x-6">
          <a href="https://www.linkedin.com/in/vadim-spac-973656225/" class="text-black mr-4">
      <i class="fab fa-linkedin-in text-xl"></i>
    </a>
    <a href="https://github.com/shvadimm" class="text-black mr-4">
      <i class="fab fa-github text-xl"></i>
    </a>
    <a href="https://x.com/vadimsh33?s=11&t=6fQ-nsEDI8nzIlLmdSbQyQ" class="text-black">
      <i class="fab fa-twitter text-xl"></i>
    </a>
        </div>
      </div>
    </div>

    <div id="Skills" class="max-w-6xl mx-auto px-5 py-32 sm:py-48 lg:py-56">
          <div class="text-center mb-20">
            <h1 class=" title-font  mb-4 text-4xl font-extrabold leading-10 tracking-tight sm:text-5xl sm:leading-none md:text-6xl">Compétences</h1>
            <p class="text-base leading-relaxed xl:w-2/4 lg:w-3/4 mx-auto"></p>
            <div class="flex mt-6 justify-center">
              <div class="w-16 h-1 rounded-full bg-indigo-500 inline-flex"></div>
            </div>
          </div>
          <div class="flex flex-wrap sm:-m-4 -mx-4 -mb-10 -mt-4 ">
            <div class="p-10 md:w-1/3 md:mb-0 mb-6 flex flex-col ">
              <div class="pattern-dots-md gray-light">
                <div class="rounded bg-transparent 0 p-4 transform translate-x-6 -translate-y-6 ">
                    <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-black text-blue-500 mb-5 flex-shrink-0">
                      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path></svg>
                 </div>
                  <div class="flex-grow ">
                    <h2 class=" text-xl title-font font-medium mb-3">Frontend</h2>
                   
                    <p class="leading-relaxed text-sm text-justify">
                   
                    <i class="fa-brands fa-html5"></i> HTML <br>                    
                      <i class="fa-brands fa-css3"></i> CSS<br> 
                      <i class="fa-solid fa-wind"></i> Tailwind CSS<br>
                      <i class="fa-brands fa-angular"></i> Angular<br>
                      <i class="fa-sharp fa-solid fa-n"></i> Nuxt.js<br>
                      <i class="fa-brands fa-vuejs"></i> Vue.js<br>
                      <i class="fa-brands fa-react"></i> React</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="p-10 md:w-1/3 md:mb-0 mb-6 flex flex-col ">
              <div class="pattern-dots-md gray-light">
                <div class="rounded bg-transparent p-4 transform translate-x-6 -translate-y-6 ">
                    <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-black text-indigo-500 mb-5 flex-shrink-0">
                      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4m0 5c0 2.21-3.582 4-8 4s-8-1.79-8-4"></path></svg>
                  </div>
                  <div class="flex-grow">
                    <h2 class=" text-xl title-font font-medium mb-3">Back-end</h2>
                    <p class="leading-relaxed text-sm text-justify">
                      <i class="fa-brands fa-php"></i> PHP(Symfony)<br>
                      <i class="fa-brands fa-python"></i> Python(Flask)<br>
                      <i class="fa-brands fa-node"></i> NodeJs<br>
                      <i class="fa-brands fa-java"></i> Java<br>
                      <i class="fa-brands fa-battle-net"></i> C++<br>
                      <i class="fa-brands fa-battle-net"></i> C#<br>
                      <i class="fa-brands fa-battle-net"></i> MangoDB<br>
                      <i class="fa-brands fa-battle-net"></i> Mysql
                    </p>
                  </div>
                </div>
              </div>
            </div>
            <div class="p-10 md:w-1/3 md:mb-0 mb-6 flex flex-col ">
              <div class="pattern-dots-md gray-light">
                <div class="rounded bg-transparent p-4 transform translate-x-6 -translate-y-6 ">
                  <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-black text-yellow-500 mb-5 flex-shrink-0">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21a4 4 0 01-4-4V5a2 2 0 012-2h4a2 2 0 012 2v12a4 4 0 01-4 4zm0 0h12a2 2 0 002-2v-4a2 2 0 00-2-2h-2.343M11 7.343l1.657-1.657a2 2 0 012.828 0l2.829 2.829a2 2 0 010 2.828l-8.486 8.485M7 17h.01"></path></svg>               
                   </div>
                  <div class="flex-grow">
                    <h2 class=" text-xl title-font font-medium mb-3">Other</h2>
                    <p class="leading-relaxed text-sm text-justify">
                      <i class="fa-solid fa-m"></i> Mamp<br>
                      <i class="fa-brands fa-docker"></i> Docker<br>
                      <i class="fa-brands fa-github"></i> Git<br>
                      <i class="fa-solid fa-a"></i> Adobe XD
                    </p>
                  </div>
                </div>
             </div>
          </div>
        </div>
      </div>


      <div id="Work" class="text-center py-32 sm:py-48 lg:py-56">
            <h1 class=" title-font  mb-4 text-4xl font-extrabold leading-10 tracking-tight sm:text-5xl sm:leading-none md:text-6xl">Work Together</h1>
            <div class="flex mt-6 justify-center">
              <div class="w-16 h-1 rounded-full bg-indigo-500 inline-flex"></div>
            </div>
   </div>      
<div class="flex items-center justify-center p-12">
   
  <div class="mx-auto w-full max-w-[550px]">
    <form action="https://formbold.com/s/9XqDy" method="POST">
      <div class="mb-5">
        <label
          for="name"
          class="mb-3 block text-base font-medium text-[#07074D]"
        >
        Prénom
        </label>
        <input
          type="text"
          name="name"
          id="name"
          placeholder="Prénom"
          class="w-full rounded-md border border-[#e0e0e0] bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-[#6A64F1] focus:shadow-md"
        />
      </div>
      <div class="mb-5">
        <label
          for="email"
          class="mb-3 block text-base font-medium text-[#07074D]"
        >
          Email
        </label>
        <input
          type="email"
          name="email"
          id="email"
          placeholder="toto@toto.com"
          class="w-full rounded-md border border-[#e0e0e0] bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-[#6A64F1] focus:shadow-md"
        />
      </div>
      <div class="mb-5">
        <label
          for="subject"
          class="mb-3 block text-base font-medium text-[#07074D]"
        >
          Sujet
        </label>
        <input
          type="text"
          name="subject"
          id="subject"
          placeholder="Votre Sujet"
          class="w-full rounded-md border border-[#e0e0e0] bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-[#6A64F1] focus:shadow-md"
        />
      </div>
      <div class="mb-5">
        <label
          for="message"
          class="mb-3 block text-base font-medium text-[#07074D]"
        >
          Message
        </label>
        <textarea
          rows="4"
          name="message"
          id="message"
          placeholder="Votre message"
          class="w-full resize-none rounded-md border border-[#e0e0e0] bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-[#6A64F1] focus:shadow-md"
        ></textarea>
      </div>
      <div>
        <button
          class="hover:shadow-form rounded-md bg-[#6A64F1] py-3 px-8 text-base font-semibold text-white outline-none"
        >
          Valider
        </button>
      </div>
    </form>
  </div>
</div>
    <div class="absolute left-1/2 top-0 -z-10 -translate-x-1/2 blur-3xl xl:-top-6" aria-hidden="true">
    <div class="aspect-[1155/678] w-[72.1875rem] bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
  </div>
  </div>
</div>
  
</template>

<script setup>
import { ref, onMounted } from 'vue'
import Typed from 'typed.js';
import '@fortawesome/fontawesome-free/css/all.css';


const navigation = [
  { name: 'Accueille', href: '/' },
  { name: 'Skills', href: '#Skills' },
  { name: 'Work Together', href: '#Work' },
]

const mobileMenuOpen = ref(false)

onMounted(() => {
  var typed = new Typed('#typed-text', {
    strings: ['Vadim Spac Developpeur full stack'],
    typeSpeed: 50,
    showCursor: false
  });
})
</script>

<style>
  @keyframes blink {
    0%, 100% {
      opacity: 1;
    }
    50% {
      opacity: 0;
    }
  }
</style>

