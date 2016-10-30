# CANVAS LADY WELCOME LIBRARY

##### Add css and js to header html file
# 

```html
    <!-- CSS && JS -->
    <link rel="stylesheet" type="text/css" href="css/style.css">
    <link rel="stylesheet" type="text/css" href="css/owl.carousel.css">
    <link rel="stylesheet" type="text/css" href="css/owl.transitions.css">
    <script type="text/javascript" src="js/easeljs-0.6.0.min.js"></script>
    <script src="js/owl.carousel.min.js"></script>
    <script src="js/canvas.js"></script>
    <!-- CSS && JS -->
```

#Note: Please, don't forget use jquery version 1.x. Add jquery before `owl.carousel.min.js` and `canvas.js`

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/1.12.4/jquery.js"></script>
```

### Add html code to body html file

```html
<!--Suggest Box -->
    <div class="canvasHolder">
        <canvas id="welcomeCanvas" width="300" height="193">Your browser doesn't support canvas. Please download IE9+ on
            <a href="http://ie.microsoft.com/testdrive">IE Test Drive</a>
        </canvas>
        <span class="close-canvas"></span>
        <div class="phone-box">
            <span class="close-phone-box">+</span>

            <div class="content-phone-box suggest-box">
                <div class="header">Có thể bạn quan tâm ?</div>
                <div class="box-content">
                    <div class="inner-slide">
                            <a class="more" href="">
                                <div class="title">Tour Đảo Bình Hưng, Hang Rái, Vĩnh Hy 2n2d</div>
                                <div class="price"><span aria-hidden="true" class="icon-basket"></span> 1,111,000 đ</div>
                            </a>
                        </div>
                        <div class="inner-slide">
                            <a class="more" href="">
                                <div class="title">Tour Côn Đảo, Khám Phá Lịch Sử Văn Hóa Côn Sơn 2N1Đ</div>
                                <div class="price"><span aria-hidden="true" class="icon-basket"></span> 4,590,000 đ</div>
                            </a>
                        </div>
                        <div class="inner-slide">
                            <a class="more" href="">
                                <div class="title">Tour du lịch Vũng Tàu, Long Hải, Suối nước nóng Bình Châu 2N1Đ</div>
                                <div class="price"><span aria-hidden="true" class="icon-basket"></span> 789,000 đ</div>
                            </a>
                        </div>
                        <div class="inner-slide">
                            <a class="more" href="">
                                <div class="title">Tour Ninh Chữ, Vĩnh Hy Hang Rái Siêu Tiết Kiệm 2n2d</div>
                                <div class="price"><span aria-hidden="true" class="icon-basket"></span> 850,000 đ</div>
                            </a>
                        </div>
                        <div class="inner-slide">
                            <a class="more" href="">
                                <div class="title">Tour Ninh Chữ - Vĩnh Hy Khám Phá Bãi Đá Bảy Màu Resort 3sao 2N2Đ</div>
                                <div class="price"><span aria-hidden="true" class="icon-basket"></span> 1,250,000 đ</div>
                            </a>
                        </div>
                        <div class="inner-slide">
                            <a class="more" href="">
                                <div class="title">Tour Đà Lạt Phototrip Khám Phá Những Cung Đường Hoa 3N3Đ</div>
                                <div class="price"><span aria-hidden="true" class="icon-basket"></span> 1,250,000 đ</div>
                            </a>
                        </div>
                        <div class="inner-slide">
                            <a class="more" href="">
                                <div class="title">Tour Đảo Hòn Sơn Khám Phá Đỉnh Ma Thiên Lãnh 2N2Đ</div>
                                <div class="price"><span aria-hidden="true" class="icon-basket"></span> 1,390,000 đ</div>
                            </a>
                        </div>
                        <div class="inner-slide">
                            <a class="more" href="">
                                <div class="title">Tour Đảo Phú Quý, Khám Phá Hòn Đảo Mang Vẻ Đẹp Hoang Sơ 3N3Đ</div>
                                <div class="price"><span aria-hidden="true" class="icon-basket"></span> 2,250,000 đ</div>
                            </a>
                        </div>
                        <div class="inner-slide">
                            <a class="more" href="">
                                <div class="title">Tour Côn Đảo, Trọn Gói Vé Máy Bay 2N1Đ</div>
                                <div class="price"><span aria-hidden="true" class="icon-basket"></span> 3,999,000 đ</div>
                            </a>
                        </div>
                        <div class="inner-slide">
                            <a class="more" href="">
                                <div class="title">Tour Ninh Chữ - Vĩnh Hy - Cổ Thạch đồng giá 2N2Đ</div>
                                <div class="price"><span aria-hidden="true" class="icon-basket"></span> 999,000 đ</div>
                            </a>
                        </div>
                    </div>
            </div>
        </div>
    </div>
<!--End Suggest Box -->   
```

Here is an example:
![alt text](images/example.jpg "Canvas welcome")

