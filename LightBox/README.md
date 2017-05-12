#LIGHTBOX v2 is comming soon....

![lightbox](https://cloud.githubusercontent.com/assets/10348820/8272933/e4866ce0-1857-11e5-82e0-843641cf8851.png)

# === PL ===
LightBox jest to prosty plugin galeri napisany w czystym JavaScript.

### Jak używać

Dodaj style CSS i plik JavaScript do swojego pliku
```
<link rel="stylesheet" type="text/css" href="css/lightbox.css">
<script type="text/javascript" src="js/lightbox.js"></script>
```
Wstaw obrazy w takim stylu jak poniżej (caption można pominać)
```
<div data-big="big/ts_img1.jpg" class="lightbox">
	<img src="small/ts_img1.jpg" alt="small">
</div>
```
Odpal LightBox'a
```
document.addEventListener("DOMContentLoaded", function() {
	var init = new lightBox();
});
```

# === ENG ===
LightBox is a simple gallery plugin written in pure JavaScript. 

### How to use
Add CSS file and JS file
```
<link rel="stylesheet" type="text/css" href="css/lightbox.css">
<script type="text/javascript" src="js/lightbox.js"></script>
```
Put your images as below (caption is not required)
```
<div data-big="big/ts_img1.jpg" class="lightbox">
	<img src="small/ts_img1.jpg" alt="small">
</div>
```
Run LightBox
```
document.addEventListener("DOMContentLoaded", function() {
	var init = new lightBox();
});
```


# DEMO
http://projects.lukaszduda.com.pl/lightbox
