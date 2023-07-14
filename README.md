# lab-7
<h1 align="center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<p align="center">Лабораторная работа №7</p>
<p align="center"></p>
<br>
<p align="right">Работу выполнил Гурков Владислав Викторович</p>
<p align="right">Работу проверил Соболев Евгений Игоревич</p>


### **Цели и задачи:**
Повторить по образцу, то есть сделать такой же макет используя материалы из архива lab7.zip

### **Решение задачи**
```html 
<body style="margin: 0px; padding: 0px; background-image: url(wrapper-bg.png);">
    <div style="background-image: url(header-wrapper-bg.png);height:187px; text-align: center; ">
        <div style="margin: auto; padding-top: 35px; text-align: center; display: flex; align-items: center; justify-content: center;">
            <span class="name">
                Elysa4t 
            </span> 
            <div id="left"></div>
            <div id="curr">
                <span style="float: left; width: 50px; height: 65px; color: white; font-size: 17px; padding-top: 10px;">
                    Home
                </span>
            </div>
            <span id="right"></span> 
            <span class="but">
                Archives
            </span>  
            <span class="but">
                Gallery
            </span> 
            <span class="but">
                About
            </span> 
            <span class="but">
                Contact
            </span></div>
    </div>


    <div style="background-image: url(banner-wrapper-bg.png); height: 350px">
        <div style="width: 950px;margin: auto; padding-top: 30px">
            <img src="banner-image.jpg" alt="" style="position: absolute; width: 950px;"> 
                <div style="background: url(footer-content-bg-02.png); width: 950px; height: 80px; margin-top: 210px; border-radius: 5px; position: absolute; 
                color: white; text-align: center;">
                    <p style="margin: 0px; padding-top: 20px; font-size: 35px; font-family: Ex;">Magna sed phasellus consequat lorem ipsum dolor</p>
                </div>
        </div>
    </div>

    <div style="background-image: url(page-wrapper-bg.png); height: 520px;text-align: center; display: flex; 
    align-items: center; justify-content: center;">
        <div>
            <div style="float: left; width: 600px; height: 480px; background-color: white; border-radius: 4px; margin-right: 30px; 
            margin-top: 5px;">
                <div>
                    <img id="post" src="post-posted-bg.png" alt="">
                    <p id="posttext">Posted by Someone on April 14, 2012</p>
                </div>
                <br>
                <span id="lorem">Lorem ipsum sed veroeros amet</span>
                <img id="postbig" src="pics01.jpg">
                <br>
                <p id="posttext2">Nam vestibulum hendrerit orci, sed pharetra elit elementum in. 
                    Donec in eros sed odio varius tempus. 
                    Vestibulum quis quam et velit rutrum ornare nec a massa. 
                    Curabitur malesuada ullamcorper nunc in suscipit. 
                    Donec semper venenatis dui sed facilisis. 
                    Morbi congue facilisis ante in feugiat. 
                    Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. 
                    aecenas semper massa ac odio ornare sodales. 
                    Nunc rhoncus vulputate nisi sed malesuada. 
                    Fusce ac mauris dui, id luctus ligula. 
                    Integer hendrerit.
                </p>
                <div id="lastpost">
                    <span id="lasttext">Posted in <a href="" style="color: #804b3d;">News</a>, 
                        <a href="" style="color: #804b3d;">Design</a>, <a href="" style="color: #804b3d;">Other</a></span> 
                        <a id="comm" href="" style="color: #804b3d;">235 Comments</a>
                </div>
            </div>

            <div style="float: left; width:350px; height: 490px; border-radius: 5px;">
                <div style="background-image: url(sidebar-bg-01.png);background-repeat: no-repeat; height: 15px;"> </div>
                <div style="background-image: url(sidebar-bg-02.png); background-repeat: repeat-y; height: 460px;">
                        <div style="height: 135px;">
                            <img id="sbpost" src="sidebar-title-bg.png" alt="" style="margin-top: 10px;">
                            <p id="posttext" style="margin-top: 15px;"><b>About Elysa4t</b></p>
                            <p id="sba">Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet.
                                Maecenas semper massa amet et odio mauris dui, id luctus amet ligula.</p>
                        </div>
                        <div style="height: 190px;">
                            <img id="sbpost" src="sidebar-title-bg.png" alt="" style="margin-top: 10px;">
                            <p id="posttext" style="margin-top: 15px;"><b>Recent Post</b></p>
                            <p id="rec" style="margin-top: 50px;">Hendrerit orci sed pharetra elit</p>
                            <hr id="line" color="#301c16">
                            <p id="rec" style="margin-top: 78px;">Donec in eros odio varius tempus</p>
                            <hr id="line" color="#301c16" style="margin-top: 98px;">
                            <p id="rec" style="margin-top: 106px;">Vestibulum quis quam et velit</p>
                            <hr id="line" color="#301c16" style="margin-top: 126px;">
                            <p id="rec" style="margin-top: 134px;">Rutrum ornare nec sed curabitur</p>
                            <hr id="line" color="#301c16" style="margin-top: 154px;">
                            <p id="rec" style="margin-top: 162px;">Malesuada ullamcorper nunc</p>
                        </div>
                        <div>
                            <img id="sbpost" src="sidebar-title-bg.png" alt="" style="margin-top: 10px;">
                            <p id="posttext" style="margin-top: 15px;"><b>Something Else</b></p>
                            <p id="sba" style="margin-top: 55px;">Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. 
                                Maecenas semper massa amet et odio mauris dui, id luctus amet ligula.</p>
                        </div>
                </div>
                <div style="background-image: url(sidebar-bg-03.png);background-repeat: no-repeat; height: 15px;"></div>
            </div>
        </div>
    </div>
    
    <div style="background-image: url(footer-content-bg-02.png); height: 283px;">
        <div style="width: 1000px; margin: auto; color: #ceaba4;">
            <div style="width: 300px;float: left; margin-right: 30px;">
                <div id="top"></div>
                <div id="middle">
					<h2 style="color: white;">Just another widget</h2>
					<p>Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. 
                        Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
                </div>
                <div id="bottom"></div>
			</div>
            <div style="width: 300px;float: left; margin-right: 30px;">
                <div id="top"></div>
                <div id="middle">
					<h2 style="color: white;">Just another widget</h2>
					<p>Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. 
                        Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
                </div>
                <div id="bottom"></div>
			</div>
            <div style="width: 300px;float: left; margin-right: 30px;">
                <div id="top"></div>
                <div id="middle">
					<h2 style="color: white;">Just another widget</h2>
					<p>Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. 
                        Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
                </div>
                <div id="bottom"></div>
			</div>
        </div>
    </div>

    <div style="background-image: url(footer-bg.png); height: 120px;">
        <br>
        <p style="text-align: center; font-size: 15px; color: rgba(170, 112, 73, 0.486);"> &copy Your website Name | Elysa4t by <a href="" style="color:rgba(170, 112, 73, 0.486);">4Templates</a> | Photos by <a href="https://www.youtube.com/" style="color:rgba(170, 112, 73, 0.486);">Fotogrph</a></p>
    </div>
</body>



```cs
@font-face{
        font-family:Ex;
        src: url(Cookie-Regular.ttf);
    }
    #top {
        height: 15px; 
        background-image: url(box-widget-bg-01.png); 
        background-repeat: no-repeat; 
        margin-top: 25px;
    }
    #middle {
        padding: 20px 30px 20px 30px; 
        background-image: url(box-widget-bg-02.png);
    }
    #bottom {
        height: 15px; 
        background-image: url(box-widget-bg-03.png); 
        background-repeat: no-repeat;
    }
    span.name
    {
        font-family: Ex;
        float: left;
        margin-right: 150px; 
        font-size: 55px; 
        width: 221px; 
        height: 110px; 
        background-image:url(logo-bg.png); 
        background-repeat: no-repeat;
        padding-top: 25px;
        color: white;
    }
    .but {
        font-size: 17px;
        float: left;
        width: 50px;
        margin-right: 45px; 
        height: 40px;
        color: white;
    }
    #left{
        float: left;
        width: 15px;
        height: 65px;
        background-image: url(menu-active-bg-01.png);
        background-repeat: no-repeat;
    }
    #curr{
        float: left;
        width: 50px;
        height: 65px;
        background-image: url(menu-active-bg-02.png);
        background-repeat: repeat-x;
    }
    #right{
        float: left;
        width: 15px;
        height: 65px;
        margin-right: 30px;
        background-image: url(menu-active-bg-03.png);
        background-repeat: no-repeat;
    }
    #post {
        height: 30px;
        width: 280px;
        text-align: left; 
        align-items:baseline; 
        display: block;
        margin-top: 20px;
        position: absolute;
    }
    #postbig {
        height: 170px;
        width: 550px;
        border-radius: 5px;
    }`
    
    
    ### **Вывод:**
После выполнения данной лабораторной работы я улучшил свои навыки работы с стилями.
