# this project is a module for clock in web(这是一个网页时钟的模块)

# this project rely to 'jquery' and the license  in "jquery/jquery.license" (这个项目依赖于'jquery'，许可证在"jquery/jquery.license"中)

## how to use   (如何使用)
### copy the structure of the project to your project(将结构完整地复制到你的项目中)
```html
    <link rel="stylesheet" href="./clock.css">
    <script src="./jquery/jquery.js"></script>
    <script src="./clock.js"></script>
    <div id="clock" style="transform-origin: top right;">
        <div id="hour">
            <div class="show_num">
                <div class="ele1">00</div>
                <div class="ele3">01</div>
                <div class="ele4">01</div>
                <div class="ele2">00</div>
            </div>
            <div class="text">
                时
            </div>
        </div>
        <span>:</span>
        <div id="minute">
            <div class="show_num">
                <div class="ele1">00</div>
                <div class="ele3">01</div>
                <div class="ele4">01</div>
                <div class="ele2">00</div>
            </div>
            <div class="text">
                分
            </div>
        </div>
        <span>:</span>
        <div id="second">
            <div class="show_num">
                <div class="ele1">00</div>
                <div class="ele3">01</div>
                <div class="ele4">01</div>
                <div class="ele2">00</div>
            </div>
            <div class="text">
                秒
            </div>
        </div>
    </div>
```

### show it in iframe(嵌入iframe)
```html
    <iframe src="./clock.html" frameborder="0" width="100%" height="100%"></iframe>
```


## how to resize (如何使用)
### change the css variable in the clock(修改css变量)
```css
    #clock{
        --clock-height: 100px; /* the height of the clock ,and the width will change with it*/
                                /* zh:时钟的高度，并且宽度会随着高度变化 */
    }

    .clock_container{
        --clock-height: 100px; /*change the outside container will get the same effect*/
                                /* zh:修改外部容器也能得到相同的效果 */
    }
```
