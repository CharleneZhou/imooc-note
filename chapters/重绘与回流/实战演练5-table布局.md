> table:
* 30行 修改 最后一行 layout 1.15ms

> div:
* 30行 0.01ms


```
<html>
    <head>
        #rect{
            <!-- position: relative;
            top: 0; -->
            transform: translateY(0)
            width: 100px;
            height: 100px;
            display: none;
        }
    </head>
    <body>
        <!-- <table style="width: 500px">
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr><tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td>world~~~</td>
            </tr>
            <tr>
                <td>hello~~~</td>
                <td id="last">world~~~</td>
            </tr>
        </table> -->
        <div>
            <div>
                <span>hello~~</span>
                <span>world~~</span>
            </div>
            <div>
                <span>hello~~</span>
                <span id="last">world~~</span>
            </div>
        </div>
        <script>
            setTimeout( () => {

                document.getElementById('last').style.width = '100px'
                document.getElementById('last').innerHTML = 'table~~~'

            })
        </script>
    </body>
</html>
```