# web-phone
## 網頁手機版互換圖片的CSS 
```
<div class="modal-header web">
    <img src="/assets2/img/banner/teacher.jpg"   alt="">                           
</div>
<div class="phone">
     <img src="/assets2/img/banner/teacher_2.jpg"   alt=""> 
</div>
<style>
 // 當熒幕寬度大於 1023px 時，手機版則隱藏
    @media (min-width:1023px) {
        .phone{
            display: none;
        }
    }
     // 當熒幕寬度小於 500px 時，網頁版則隱藏
    @media (max-width: 500px) {
        .web{
            display: none;
        }
    }
</style>

```
