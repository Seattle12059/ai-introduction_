<template>
  <div class="leading-normal tracking-normal text-balck gradient">
    <LayoutNav />

    <div data-aos="fade-up" class="pt-24">
      <div
        class="container px-3 mx-auto flex flex-wrap flex-col md:flex-row items-center"
      >
        <div
          class="flex flex-col w-full md:w-2/5 justify-center items-start text-center md:text-left"
        >
          <h1 class="my-4 text-5xl font-bold leading-tight text-black">
            慧议 AI Meeting
          </h1>
          <p class="leading-normal text-2xl mb-8 text-black">
            智能 AI 会议平台，打造智能高效的沟通新生态
          </p>
          <button
            style="background-color: #409eff"
            class="mx-auto lg:mx-0 hover:underline text-white font-bold rounded-full my-6 py-4 px-8 shadow-lg focus:outline-none focus:shadow-outline transform transition hover:scale-105 duration-300 ease-in-out"
            @click="redirectToUrl"
          >
            立即体验
          </button>
        </div>
        <div class="w-full md:w-3/5 py-6 text-center">
          <img
            class="w-full md:w-4/5 z-50"
            src="../assets/imgs/feature/usage_scene1.png"
          />
        </div>
      </div>
    </div>
    <div class="relative -mt-12 lg:-mt-24">
      <svg
        viewBox="0 0 1428 174"
        version="1.1"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
      >
        <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
          <g
            transform="translate(-2.000000, 44.000000)"
            fill="#409eff"
            fill-rule="nonzero"
          >
            <path
              d="M0,0 C90.7283404,0.927527913 147.912752,27.187927 291.910178,59.9119003 C387.908462,81.7278826 543.605069,89.334785 759,82.7326078 C469.336065,156.254352 216.336065,153.6679 0,74.9732496"
              opacity="0.12001"
            ></path>
            <path
              d="M100,104.708498 C277.413333,72.2345949 426.147877,52.5246657 546.203633,45.5787101 C666.259389,38.6327546 810.524845,41.7979068 979,55.0741668 C931.069965,56.122511 810.303266,74.8455141 616.699903,111.243176 C423.096539,147.640838 250.863238,145.462612 100,104.708498 Z"
              opacity="0.10001"
            ></path>
            <path
              d="M1046,51.6521276 C1130.83045,29.328812 1279.08318,17.607883 1439,40.1656806 L1439,120 C1271.17211,77.9435312 1140.17211,55.1609071 1046,51.6521276 Z"
              id="Path-4"
              opacity="0.250000003"
            ></path>
          </g>
          <g
            transform="translate(-4.000000, 76.000000)"
            fill="#FFFFFF"
            fill-rule="nonzero"
          >
            <path
              d="M0.457,34.035 C57.086,53.198 98.208,65.809 123.822,71.865 C181.454,85.495 234.295,90.29 272.033,93.459 C311.355,96.759 396.635,95.801 461.025,91.663 C486.76,90.01 518.727,86.372 556.926,80.752 C595.747,74.596 622.372,70.008 636.799,66.991 C663.913,61.324 712.501,49.503 727.605,46.128 C780.47,34.317 818.839,22.532 856.324,15.904 C922.689,4.169 955.676,2.522 1011.185,0.432 C1060.705,1.477 1097.39,3.129 1121.236,5.387 C1161.703,9.219 1208.621,17.821 1235.4,22.304 C1285.855,30.748 1354.351,47.432 1440.886,72.354 L1441.191,104.352 L1.121,104.031 L0.457,34.035 Z"
            ></path>
          </g>
        </g>
      </svg>
    </div>

    <section id="about" class="bg-white border-b py-8">
  <div class="container max-w-9xl mx-auto m-8">
    <h2
      data-aos="fade-up"
      class="w-full my-2 text-5xl font-bold leading-tight text-center text-gray-800"
    >
      介绍
    </h2>
    <div data-aos="fade-up" class="w-full mb-4">
      <div
        class="h-1 mx-auto gradientbutton w-64 opacity-25 my-0 py-0 rounded-t"
      ></div>
    </div>
    <!-- 痛点解决和核心优势部分 -->
    <div class="flex flex-wrap">
      <!-- 左侧：痛点解决和核心优势 -->
      <div class="w-full sm:w-1/2 p-6">
        <div data-aos="fade-up-right">
          <h3 class="text-3xl font-semibold text-gray-900 leading-none mb-6">
            痛点解决
          </h3>
          <p
            class="text-lg text-gray-700 leading-relaxed mb-8 p-4 rounded-xl hover:shadow-lg hover:-translate-y-1 transition-all duration-300"
          >
            针对传统会议软件协作低效、记录繁琐、跨语言障碍等问题，提供 AI
            驱动的智能会议系统，实现高效调度、实时分析与跨语言协作。
          </p>
        </div>
        <div data-aos="fade-up-right">
          <h3 class="text-3xl font-semibold text-gray-900 leading-none mb-6">
            核心优势
          </h3>
          <p
            class="text-lg text-gray-700 leading-relaxed mb-8 p-4 rounded-xl hover:shadow-lg hover:-translate-y-1 transition-all duration-300"
          >
            集成 AI 智能创建会议、实时语音转写翻译、多维度参与度分析功能，
            解决会议组织难、信息沉淀弱、国际沟通不畅等痛点。
          </p>
        </div>
        <!-- 新增的一段介绍 -->
        <div data-aos="fade-up-right">
          <h3 class="text-3xl font-semibold text-gray-900 leading-none mb-6">
            适用人群
          </h3>
          <p
            class="text-lg text-gray-700 leading-relaxed mb-8 p-4 rounded-xl hover:shadow-lg hover:-translate-y-1 transition-all duration-300"
          >
          本项目面向社会各界人士，涵盖了不同职业、不同年龄段、不同地域的广大群体，旨在满足各类人群在不同场景下的会议需求。
          </p>
        </div>
      </div>
      <!-- 右侧：图片 -->
      <div class="w-full sm:w-1/2 p-6 flex items-center justify-center">
        <img
          data-aos="fade-up-left"
          src="../assets/imgs/meeting.png"
          alt="会议系统示意图"
          class="rounded-lg shadow-lg w-full h-full object-cover"
        />
      </div>
    </div>
  </div>
</section>

<section id="customers" class="bg-white border-b py-4">
  <div class="container mx-auto flex flex-wrap pt-4 pb-12">
    <h2
      data-aos="fade-up"
      class="w-full my-2 text-5xl font-bold leading-tight text-center text-gray-800"
    >
      功能特点
    </h2>
    <div data-aos="fade-up" class="w-full mb-4">
      <div
        class="h-1 mx-auto gradientbutton w-64 opacity-25 my-0 py-0 rounded-t"
      ></div>
    </div>
    <div class="w-full flex flex-wrap">
      <!-- 卡片1 -->
      <div data-aos="zoom-in-down" class="w-full md:w-1/2 p-4">
        <div
          class="bg-white-50 rounded-xl border-2 border-purple-200 hover:border-purple-300 transition-all duration-300 h-full flex flex-col shadow-lg hover:shadow-xl transition-shadow"
        >
          <div class="p-6 flex-1">
            <div class="text-purple-600 text-sm mb-2">AI Innovation</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-4">AI 智能会议</h3>
            <p class="text-gray-600 leading-relaxed">
              输入简单指令即可自动生成会议名称、密码等，同时用户可以与AI进行聊天互动，文档解析等
            </p>
          </div>
          <div class="px-4 pb-4 min-h-[300px]">
            <img
              src="../assets/imgs/AI.gif"
              alt="AI Innovation"
              class="w-full h-96 md:h-120 object-cover rounded-xl hover:scale-105 transition-transform duration-300 border-2 border-purple-100/50 hover:border-purple-200"
            />
          </div>
        </div>
      </div>

      <!-- 卡片2 -->
      <div data-aos="zoom-in-down" class="w-full md:w-1/2 p-4">
        <div
          class="bg-white-50 rounded-xl border-2 border-blue-200 hover:border-blue-300 transition-all duration-300 h-full flex flex-col shadow-lg hover:shadow-xl transition-shadow"
        >
          <div class="p-6 flex-1">
            <div class="text-blue-600 text-sm mb-2">Language Processing</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-4">实时语音转录与翻译</h3>
            <p class="text-gray-600 leading-relaxed">
              支持多语言实时转写并生成字幕，打破语言 barriers，提升国际会议沟通效率
            </p>
          </div>
          <div class="px-4 pb-4 min-h-[300px]">
            <img
              src="../assets/imgs/转录和翻译.gif"
              alt="Language Processing"
              class="w-full h-96 md:h-120 object-cover rounded-xl hover:scale-105 transition-transform duration-300 border-2 border-blue-100/50 hover:border-purple-200"
            />
          </div>
        </div>
      </div>

      <!-- 卡片3 -->
      <div data-aos="zoom-in-down" class="w-full md:w-1/2 p-4">
        <div
          class="bg-white-50 rounded-xl border-2 border-yellow-200 hover:border-yellow-300 transition-all duration-300 h-full flex flex-col shadow-lg hover:shadow-xl transition-shadow"
        >
          <div class="p-6 flex-1">
            <div class="text-yellow-600 text-sm mb-2">AI Summarization</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-4">智能会议笔记生成</h3>
            <p class="text-gray-600 leading-relaxed">
              根据会议内容自动提取关键信息并生成结构化总结，替代人工整理，提升会议信息利用率
            </p>
          </div>
          <div class="px-4 pb-4 min-h-[300px]">
            <img
              src="../assets/imgs/picture6.gif"
              alt="AI interface demo"
              class="w-full h-96 md:h-120 object-cover rounded-xl hover:scale-105 transition-transform duration-300 border-2 border-yellow-100/50 hover:border-purple-200"
            />
          </div>
        </div>
      </div>

      <!-- 卡片4 -->
      <div data-aos="zoom-in-down" class="w-full md:w-1/2 p-4">
        <div
          class="bg-white-50 rounded-xl border-2 border-pink-200 hover:border-pink-300 transition-all duration-300 h-full flex flex-col shadow-lg hover:shadow-xl transition-shadow"
        >
          <div class="p-6 flex-1">
            <div class="text-pink-600 text-sm mb-2">Engagement Analytics</div>
            <h3 class="text-2xl font-bold mb-4">多维度参与度分析</h3>
            <p class="opacity-90 leading-relaxed">
              基于发言时长、互动频率等数据量化参会者贡献度，解决传统评估主观、缺乏数据支撑的痛点
            </p>
          </div>
          <div class="px-4 pb-4 min-h-[300px]">
            <img
              src="../assets/imgs/参数数据.gif"
              alt="AI interface demo"
              class="w-full h-96 md:h-120 object-cover rounded-xl hover:scale-105 transition-transform duration-300 border-2 border-pink-100/50 hover:border-purple-200"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

    <section id="showcase" class="bg-white py-12">


      <div class="container mx-auto px-4">
        <!-- 标题部分 -->
        <div data-aos="fade-up" class="text-center mb-16">
          <h2 class="text-4xl md:text-5xl font-bold text-gray-800 mb-4">产品展示</h2>
          <div class="h-1 mx-auto gradientbutton w-32 opacity-25 rounded-full"></div>
        </div>

        <!-- 动态演示容器 -->
        <div
          class="w-[95%] mx-auto rounded-2xl shadow-xl overflow-hidden border border-gray-100"
          data-aos="fade-up"
        >
          <!-- 动图展示区域 -->
          <div class="relative h-[600px] bg-gradient-to-br from-blue-48 to-purple-48">
            <!-- 动态演示内容 -->
            <img
              src="../assets/imgs/会议展示.gif"
              class="w-full h-full object-contain p-4 lg:p-8"
              alt="产品动态演示"
              loading="lazy"
            />
          </div>

          <!-- 功能指示条 -->
          <div class="grid grid-cols-4 bg-white-50 divide-x divide-gray-200 text-center">
            <div class="p-4 hover:bg-white transition-colors cursor-help">
              <div class="text-blue-600 text-2xl mb-2">💭</div>
              <p class="font-medium">会议聊天</p>
            </div>
            <div class="p-4 hover:bg-white transition-colors cursor-help">
              <div class="text-purple-600 text-2xl mb-2">📝</div>
              <p class="font-medium">转录字幕</p>
            </div>
            <div class="p-4 hover:bg-white transition-colors cursor-help">
              <div class="text-green-600 text-2xl mb-2">📈</div>
              <p class="font-medium">服务质量</p>
            </div>
            <div class="p-4 hover:bg-white transition-colors cursor-help">
              <div class="text-red-600 text-2xl mb-2">🖥️</div>
              <p class="font-medium">屏幕共享</p>
            </div>
          </div>
        </div>

        <div class="py-16 bg-white-50 relative max-w-9xl mx-auto">
          <div class="container mx-auto px-4">
            <!-- 四列重叠式布局 -->
            <div
              class="flex flex-col sm:flex-row justify-center pt-12 my-12 sm:my-4 space-y-4 sm:space-y-0"
            >
              <div
                v-for="(card, index) in cards"
                :key="card.title + index"
                @mouseenter="activeIndex = index"
                @mouseleave="activeIndex = null"
                :class="[ 'relative transition-all duration-300 ease-[cubic-bezier(0.4,0,0.2,1)]', 'w-5/6 sm:w-1/4 mx-auto', index === 0 ? 'sm:translate-y-0' : index === 1 ? 'sm:-translate-y-4' : index === 2 ? 'sm:-translate-y-8' : 'sm:-translate-y-12', { 'scale-110 sm:scale-125 z-20 shadow-2xl': activeIndex === index, 'z-10': activeIndex !== null && activeIndex !== index, 'z-0': activeIndex === null } ]"
                data-aos="zoom-out-down"

              >
                <div class="bg-white rounded-lg shadow-xl overflow-hidden h-[500px]">
                  <!-- 文字内容 -->
                  <div class="p-6 text-center">
                    <h3 class="text-xl font-semibold mb-3">{{ card.title }}</h3>
                    <div class="text-gray-600 text-sm leading-relaxed inline-block">

                      <template v-for="(line, lineIndex) in card.description" :key="lineIndex">
                        <span>
                          {{ line }}
                          <br
                            v-if="lineIndex < card.description.length - 1"
                            class="hidden sm:inline"
                          />
                          <span v-else class="sm:hidden"> </span>
                        </span>
                      </template>
                    </div>
                  </div>
                  <div class="h-1 w-full gradient my-0 py-0 rounded-t"></div>

                  <!-- 图片区域 -->
                  <div
                    class="h-[400px] w-full overflow-hidden flex justify-center items-center"
                  >
                    <img
                      :src="card.image"
                      class="max-h-full max-w-full object-contain transform transition-transform duration-300"
                      :class="{ 'scale-110': activeIndex === index }"
                      :alt="card.title"
                      loading="lazy"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <svg
      data-aos="zoom-in-up"
      class="wave-top"
      viewBox="0 0 1439 147"
      version="1.1"
      xmlns="http://www.w3.org/2000/svg"
      xmlns:xlink="http://www.w3.org/1999/xlink"
    >
      <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
        <g transform="translate(-1.000000, -14.000000)" fill-rule="nonzero">
          <g class="wave" fill="#f8fafc">
            <path
              d="M1440,84 C1383.555,64.3 1342.555,51.3 1317,45 C1259.5,30.824 1206.707,25.526 1169,22 C1129.711,18.326 1044.426,18.475 980,22 C954.25,23.409 922.25,26.742 884,32 C845.122,37.787 818.455,42.121 804,45 C776.833,50.41 728.136,61.77 713,65 C660.023,76.309 621.544,87.729 584,94 C517.525,105.104 484.525,106.438 429,108 C379.49,106.484 342.823,104.484 319,102 C278.571,97.783 231.737,88.736 205,84 C154.629,75.076 86.296,57.743 0,32 L0,0 L1440,0 L1440,84 Z"
            ></path>
          </g>
          <g transform="translate(1.000000, 15.000000)" fill="#FFFFFF">
            <g
              transform="translate(719.500000, 68.500000) rotate(-180.000000) translate(-719.500000, -68.500000) "
            >
              <path
                d="M0,0 C90.7283404,0.927527913 147.912752,27.187927 291.910178,59.9119003 C387.908462,81.7278826 543.605069,89.334785 759,82.7326078 C469.336065,156.254352 216.336065,153.6679 0,74.9732496"
                opacity="0.0900000001"
              ></path>
              <path
                d="M100,104.708498 C277.413333,72.2345949 426.147877,52.5246657 546.203633,45.5787101 C666.259389,38.6327546 810.524845,41.7979068 979,55.0741668 C931.069965,56.122511 810.303266,74.8455141 616.699903,111.243176 C423.096539,147.640838 250.863238,145.462612 100,104.708498 Z"
                opacity="0.100000001"
              ></path>
              <path
                d="M1046,51.6521276 C1130.83045,29.328812 1279.08318,17.607883 1439,40.1656806 L1439,120 C1271.17211,77.9435312 1140.17211,55.1609071 1046,51.6521276 Z"
                opacity="0.200000003"
              ></path>
            </g>
          </g>
        </g>
      </g>
    </svg>

    <section
      id="contact"
      data-aos="zoom-in-up"
      class="container mx-auto text-center py-6 mb-12"
    >
      <h2 class="w-full my-2 text-5xl font-bold leading-tight text-center text-black">
        联系我们
      </h2>
      <div class="w-full mb-4">
        <div class="h-1 mx-auto bg-white w-1/6 opacity-30.2 my-0 py-0 rounded-t"></div>
      </div>
      <h3 class="my-4 text-l text-gray-800 leading-tight">
        我们致力于打造领先的 AI
        会议解决方案，通过先进的人工智能技术，为用户提供便捷、高效、智能的会议体验<br />
        我们的团队由一群充满激情和创新精神的专业人士组成，不断追求卓越，为用户创造价值。
      </h3>
      <button
        @click="redirectToUrl"
        class="mx-auto lg:mx-0 bg-white text-gray-800 font-bold rounded-full my-6 py-4 px-8 shadow-lg focus:outline-none focus:shadow-outline transform transition hover:scale-110 duration-300 ease-in-out"
      >
        体验!
      </button>
    </section>
    <LayoutFooter />
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "IndexPage",
  data() {
    return {
      activeIndex: null as number | null,
      cards: [
      {
          title: "最近活动",
          description: [
            "聚合展示用户近期的关键操作记录",
            "涵盖会议创建、文件上传、日程安排等核心事项",
            "实时同步最新动态，助您快速掌握工作进展",
          ],
          image: require("~/assets/imgs/最近活动.gif"),
        },
        {
          title: "预约会议",
          description: ["灵活设置会议时间", "自动同步至日程表", "提升会议安排效率"],
          image: require("~/assets/imgs/预约会议.gif"),
        },
        {
          title: "最近会议统计",
          description: [
            "实时会议数据分析与统计",
            "支持多种图表类型可视化",
            "多维度数据对比功能",
          ],
          image: require("~/assets/imgs/会议统计.gif"),
        },
        {
          title: "文档中心",
          description: ["会议资料版本化管理", "支持AI智能分析", "助力资料优化与决策"],
          image: require("~/assets/imgs/文件管理.gif"),
        },
      ],
    };
  },
  methods: {
    redirectToUrl() {
      window.location.href = "https://ai-meeting.onrender.com";
    },
  },
});
</script>

<style scoped>
/* 优化层级过渡 */

.z-0 {
  z-index: 0;
}
.z-10 {
  z-index: 10;
}
.z-20 {
  z-index: 20;
}

@media (hover: none) {
  .active-touch {
    transform: scale(1.15);
    transition: transform 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  }
}
</style>
