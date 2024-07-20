[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/aMHx-K_k)


截止日期 2024/07/20 2359

1. 找一個網站版型，例如以下網站(其他 template 網站也可以)：
   - [TemplateMonster](https://www.templatemonster.com/)
   - [NicePage](https://nicepage.com/)
   - [htmlrev](https://htmlrev.com/)
2. 使用 Vuetify 或其他前端框架製作
3. 使用三個套件，例如：GSAP, swiper, aos, lightbox, parallax...

  - 檔案 carousel01.vue 使用 swiper 輪播圖
       1. 在終端機安裝 swiper
       2. 先在 swiper 網站找想要的輪播圖並複製Vue語法
       3. 貼在檔案內並修改圖片、輪播效果
       4. 引用在App.Vue上
       ```
          import carousel01 from '@/components/carousel01.vue'
       ```
       5. 使用在 v-main 
      ```
       <v-main class="custom-main" style="width: 70%">
        <v-container>
          <carousel01></carousel01>
        </v-container>
      </v-main>
       ```
          
   [參考網站](https://jo-zu-works.site/)
4. 需具備 RWD 大、中、小三種版型
5. 繳交時不要上傳 node_modules

練習 node 環境下的開發、套件的使用
