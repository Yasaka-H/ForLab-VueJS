# Study Vue.js with CDN

2019.5.13
Sayaka Hoshi

---

### What is Vue.js?

- Vue.js is a one of the JavaScript FrameWork 
- Using a simple templete and draw data in DOM 
(html)
```
<div id="app">
  {{ message }}
</div>
```
(js)
```
var app = new Vue({
  el: '#app',
  data: {
    message: 'Hello Vue!'
  }
})
```
(output)
```
>> Hello Vue!
```
- What is happening in this code? 

---

- Vue.js doing a lot of work in inner
- Data and DOM are related and they are reactive
For example>>
(on console)
```
app.message = "Nice to meet you!"
```
(output)
```
>> Nice to meet you!
```

---

opne url: https://gitpitch.com/Yasaka-H/ForLab-VueJS

---
