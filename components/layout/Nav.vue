<template>
  <nav id="header" class="fixed w-full z-30 top-0 text-black">
    <div
      class="w-full container mx-auto flex flex-wrap items-center justify-between mt-0 py-2"
    >
      <div class="pl-4 flex items-center">
        <a
          class="toggleColour text-black no-underline hover:no-underline font-bold text-2xl lg:text-4xl"
          href="#"
        >
        <img :src="require('@/assets/imgs/logo.png')" alt="AI Meeting Logo" class="h-[60px] w-[60px] inline">
  <img :src="require('@/assets/imgs/team2.png')" alt="AI Meeting Logo" class="h-[60px] w-[180px] inline">

        </a>
      </div>
      <div class="block lg:hidden pr-4">
        <button
          @click="mobileSidebar = !mobileSidebar"
          id="nav-toggle"
          class="flex items-center p-1 text-pink-800 hover:text-gray-900 focus:outline-none focus:shadow-outline transform transition hover:scale-105 duration-300 ease-in-out"
        >
          <svg
            class="fill-current h-6 w-6"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <title>菜单</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
          </svg>
        </button>
      </div>
      <div
        :class="mobileSidebar ? '' : 'hidden'"
        class="w-full flex-grow lg:flex lg:items-center lg:w-auto mt-2 lg:mt-0 bg-white lg:bg-transparent text-black p-4 lg:p-0 z-20"
        id="nav-content"
      >
        <ul class="list-reset lg:flex justify-end flex-1 items-center">
          <li class="mr-3">
            <a
              class="inline-block uppercase py-2 px-4 font-medium no-underline"
              href="#"
              >首页</a
            >
          </li>
          <li class="mr-3">
            <a
              class="inline-block uppercase no-underline font-medium hover:text-gray-800 hover:text-underline py-2 px-4"
              href="#about"
              >介绍</a
            >
          </li>
          <li class="mr-3">
            <a
              class="inline-block uppercase no-underline font-medium hover:text-gray-800 hover:text-underline py-2 px-4"
              href="#customers"
              >功能特点</a
            >
          </li>
          <li class="mr-3">
            <a
              class="inline-block uppercase no-underline font-medium hover:text-gray-800 hover:text-underline py-2 px-4"
              href="#pricing"
              >产品展示</a
            >
          </li>
          <li class="mr-3">
            <a
              class="inline-block uppercase no-underline font-medium hover:text-gray-800 hover:text-underline py-2 px-4"
              href="#contact"
              >联系我们</a
            >
          </li>
        </ul>
        <button
          id="navAction"
          style="background-color: #409eff;"
          class="mx-auto lg:mx-0 hover:underline bg-white text-gray font-bold rounded-full mt-4 lg:mt-0 py-4 px-8 shadow opacity-75 focus:outline-none focus:shadow-outline transform transition hover:scale-105 duration-300 ease-in-out"
          @click="redirectToUrl"
          >
          登录
        </button>
      </div>
    </div>
    <hr class="border-b border-white opacity-30 my-0 py-0" />
  </nav>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "layout-nav",
  data() {
    return {
      scrollY: 0,
      mobileSidebar: false,
    };
  },
  mounted() {
    this.scrollY = window.scrollY;

    // Listen to the scroll event to update the scrollY property dynamically
    window.addEventListener("scroll", this.handleScroll);
  },

  methods: {
    handleScroll() {
      this.scrollY = window.scrollY;
    },
    redirectToUrl() {
      window.location.href = 'https://ai-meeting.onrender.com';
    }
  },

  watch: {
    scrollY(newValue: number) {
      var navaction = document.getElementById("navAction");
      var header = document.getElementById("header");
      var toToggle = document.querySelector(".toggleColour");
      if (newValue > 10) {
        navaction?.classList.remove("bg-white");
        navaction?.classList.add("bg-blue-500");
        navaction?.classList.remove("text-[#170F4F]");
        navaction?.classList.add("text-white");
        header?.classList.add("bg-white");
        header?.classList.add("navbar-active");
        toToggle?.classList.add("text-gray-800");
        toToggle?.classList.remove("text-white");
      } else {
        // navaction?.classList.add("bg-white");
        navaction?.classList.remove("gradient");
        navaction?.classList.add("text-[#170F4F]");
        navaction?.classList.remove("text-white");
        header?.classList.remove("bg-white");
        header?.classList.remove("navbar-active");
        toToggle?.classList.remove("text-gray-800");
        toToggle?.classList.add("text-white");
      }
    },
  },
});
</script>

<style>
a {
  font-weight: 600;
  font-style: normal !important;
  color: rgb(0, 0, 0);
}

.navbar-active ul li a{
  color: #170F4F;
}
</style>
