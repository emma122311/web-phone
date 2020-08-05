# web-phone
## 1.網頁手機版互換圖片的CSS 
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
## 2.手機版縮成2個
```
 @media (min-width: 0px) and (max-width: 576px) {
       .col-sm-6 {
           -ms-flex: 0 0 50%;
            flex: 0 0 50%;
            max-width: 50%;
        }
    }
    // 當熒幕寬度小於576px 時，手機版會自動縮成2個
```
