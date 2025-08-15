**Date Updated:** 2021-04-16T21:56:41.000Z

  
Example Java/HTML Code:

  
```html
<style>
 .test
 {
 position: fixed !important;
 top: 0 !important;
 left: 0 !important;;
 right: 0 !important;;
  z-index:999 !important;
  width:300px !important;
  height:200px !important;
 }
</style>
<script>
window.onscroll = function() {myFunction()};
function myFunction() {
 if (document.body.scrollTop > 90 || document.documentElement.scrollTop > 90) {
  document.getElementById("video-PUTHERETHECSSVIDEOSELECTORCODE").className = "test";
 } else {
  document.getElementById("video-PUTHERETHECSSVIDEOSELECTORCODE").className = "";
 }
}
</script>
```

HTML

  
Example CSS:

  
```html
#video-PUTHERETHECSSVIDEOSELECTORCODE {
 float: left;
}
```

HTML

  