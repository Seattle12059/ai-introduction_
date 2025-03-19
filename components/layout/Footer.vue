<template>
  <footer class="bg-gray-50 border-t border-gray-200">
    <div class="container mx-auto px-8 py-6">
      <div class="flex flex-col md:flex-row items-center justify-between gap-4">
        <!-- 左侧品牌信息 (移动端隐藏) -->
        <div class="hidden md:block">
          <div class="flex items-center">
            <svg class="w-8 h-8 text-indigo-600 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" 
                    d="M8 10h.01M12 10h.01M16 10h.01M9 16H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-5l-5 5v-5z"/>
            </svg>
            <span class="text-xl font-bold text-gray-800">AI Meeting</span>
          </div>
        </div>

        <!-- 居中版权信息 -->
        <div class="text-sm text-gray-500 text-center order-first md:order-none flex-1">
          © 2025 慧议 AI Meeting. 保留所有权利
        </div>

        <!-- 右侧GitHub图标 -->
        <div class="md:ml-4">
          <a 
            title="查看源码" 
            href="https://github.com/skyman1000/AI-meeting-project" 
            target="_blank"
          >
            <img 
              class="h-8 hover:opacity-75 transition-opacity" 
              src="../../assets/imgs/github.svg" 
              alt="GitHub仓库"
            >
          </a>
        </div>
      </div>
    </div>
  </footer>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "LayoutFooter",
});
</script>