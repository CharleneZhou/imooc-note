> opacity替代visibility

* visibility : 69 + 51 + pain(18) + 93 = 231

* opacity: 65 + 68 + 100 = 233us
    * 没有paint的过程，因为paint的过程是生成图层，但是opacity实际上是直接改变的图层的alpha通道，所以不涉及图层的重绘
    * recaculate style(76us) -> update layer tree(58us) -> composite layers(100us)

```
<html>
    <head>
        <!-- #rect{
            <!-- position: relative;
            top: 0; -->
            transform: translateY(0)
            width: 100px;
            height: 100px;
            background: blue;
        } -->
        #rect{
            <!-- position: relative;
            top: 0; -->
            transform: translateY(0)
            width: 100px;
            height: 100px;
            opacity: 1;
        }
    </head>
    <body>
        <div id="rect"></div>
        <script>
            setTimeout( () => {
                <!-- document.getElementById('rect').style.top = '100px' -->

                document.getElementById('rect').style.opacity = '0'

            })
        </script>
    </body>
</html>
```