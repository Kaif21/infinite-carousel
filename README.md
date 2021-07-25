
# Responsive Infinite icon carousel using (HTML,Bootstrap 5,Slick slider) 

Showcasing skills is essential to attracting new customers. This   Responsive Infinite icon carousel cycles through dozens of items with contemporary styling and necessary responsiveness. Using [Slick Slider by Ken Wheeler](http://kenwheeler.github.io/slick/), this carousel can be adapted to fit your website needs and add a touch of agency inspired design.

## Demo

Check out a working example on[ \[Codepen.io\] ](https://codepen.io/pen/?template=KKmZwZZ).

## HTML

The form includes basic HTML markup:
```
<div  class="container text-center">
<div  class="row mb-5"><h1>We are mastering</h1></div>
<div  class="row multiple-items text-center">
<div><i  class="fab fa-5x fa-html5"></i></div>
<div><i  class="fab fa-5x fa-css3-alt"></i></div>
<div><i  class="fab fa-5x fa-python"></i></div>
<div><i  class="fab fa-5x fa-wordpress"></i></div>
<div><i  class="fab fa-5x fa-bootstrap"></i></div>
</div>
</div>
```

## CSS


No CSS needed.

## JavaScript

In addition to the slick.js resource, the infinite carousel itself needs to be initialized with the following script:
```
<script>

$('.multiple-items').slick({

dots: true,

infinite: true,

arrows: false,

autoplay: true,

autoplaySpeed: 2000,

slidesToShow: 5,

slidesToScroll: 2,

             responsive: [
{breakpoint: 1024,

settings: {

slidesToShow: 3,

slidesToScroll: 1,}},

{breakpoint: 600,

settings: {

slidesToShow: 2,

slidesToScroll: 2}},

{breakpoint: 480,

settings: {

slidesToShow: 3,

slidesToScroll: 2}}

// You can unslick at a given breakpoint now by adding:

// settings: "unslick"

// instead of a settings object

]});

</script>
```

For a full list attributes you can use to customize your carousel, visit [Slick Slider by Ken Wheeler](http://kenwheeler.github.io/slick/).

## External Includes

The form includes the following third-party resources:
```	
<!-- fontaesome -->
<link  rel="stylesheet"  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w=="
crossorigin="anonymous"  referrerpolicy="no-referrer" />
<!-- jquery -->
<script  src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"

integrity="sha512-894YE6QWD5I59HgZOGReFYm4dnWc1Qt5NtvYSaNcOP+u1T9qYdvdihz0PPSiiqn/+/3e7Jo4EaG7TubfWGUrMQ=="

crossorigin="anonymous"  referrerpolicy="no-referrer"></script>
<!-- slick -->
<script  src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"

integrity="sha512-XtmMtDEcNz2j7ekrtHvOVR4iwwaD6o/FUJe6+Zq+HgcCsk3kj4uSQQR8weQ2QVj1o0Pk6PwYLohm206ZzNfubg=="

crossorigin="anonymous"  referrerpolicy="no-referrer"></script>

<link  rel="stylesheet"  href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.css"

integrity="sha512-yHknP1/AwR+yx26cB1y0cjvQUMvEa2PFzt1c9LlS4pRQ5NOTZFWbhBig+X9G9eYW/8m0/4OXNx8pxJ6z57x0dw=="

crossorigin="anonymous"  referrerpolicy="no-referrer" />

<link  rel="stylesheet"  href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick-theme.min.css"

integrity="sha512-17EgCFERpgZKcm0j0fEq1YCJuyAWdz9KUtv1EjVuaOz8pDnh/0nZxmU6BBXwaaxqoi9PQXnRWqlcDB027hgv9A=="

crossorigin="anonymous"  referrerpolicy="no-referrer" />

<!-- Bootstrap-->

<link  href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"  rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"  crossorigin="anonymous">

<script  src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
crossorigin="anonymous"></script>
```
