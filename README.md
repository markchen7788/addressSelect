# addressSelect
用JS简单的实现了国内地址的联动选择，用到了Layui和国内地址Json数据集
# 简单的引入方式
* 引入layui
    ```html
    <link rel="stylesheet" type="text/css" href="https://www.layuicdn.com/layui/css/layui.css" />
  ```
* 编写选择框
    ```html
     <form class="layui-form">
            <div class="layui-input-inline">
                <select id="province" lay-filter="province" name="province">
                </select>
            </div>
            <div class="layui-input-inline">
                <select id="city" lay-filter="city" name="city">
                </select>
            </div>
            <div class="layui-input-inline">
                <select id="area" lay-filter="area" name="area">
                </select>
            </div>
    </form>
    ```
* 引入JS
    ```html
    <script src="./adress.js"> </script>
    ```
    或者
     ```html
    <script src=" https://markchen7788.github.io/addressSelect/adress.js"> </script>
    ```
#点击查看[Demo](https://markchen7788.github.io/addressSelect/)
![Image text](./test.JPG)
