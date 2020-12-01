# frontend

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
# index.js
กำหนด App เมื่อเริ่มต้นรันโปรเคให้เรียกใช้งาน component App
https://github.com/naratsaporn/vue/blob/0d9d58e0c552dd5e761b17acbb96430be2b28150/src/router/index.js#L11

# main.js
กำหนด liberry ที่ใช้งาน เช่น bootstrap-vue ( css ), vue-router( กำหนดเส้นทาง ) , vue-axios ( เชื่อต่อ Api )
https://github.com/naratsaporn/vue/blob/0d9d58e0c552dd5e761b17acbb96430be2b28150/src/main.js#L3

# App.vue 
กำหนด components ที่ใช้โดยมี components top และ footer เป็นส่วน header และ footer
router-view จะเป็นส่วนแสดงข้อมูลตาม path
https://github.com/naratsaporn/vue/blob/0d9d58e0c552dd5e761b17acbb96430be2b28150/src/App.vue#L2
