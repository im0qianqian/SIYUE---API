# Siyue API #
    看过了 四月是你的谎言 这部动漫真的挺不错哎~ 很多难忘的独白，很多经典的对话，还有，看吧，星星只有在夜里才璀璨夺目啊。

**更新：**2016年4月3日

**数据获取：**数据获取

**调用示例：**JavaScript + HTML （同步）

## 数据获取 ##

- 请求地址     ：http://www.dreamwings.cn/api/siyue/

- 请求地址(SSL)：https://www.dreamwings.cn/api/siyue/

- 请求方式：GET

- charset：字符集，支持GBK

- encode数据格式，js返回函数名为siyueapi的JavaScript脚本，用于同步调用

## 实例： ##

**请求：**https://www.dreamwings.cn/api/siyue/

**返回：**或许前路永夜，即便如此我也要前进，因为星光即使微弱也会为我照亮前路

## 调用举例 – JavaScript + HTML ##

**脚本地址(SSL)：**https://www.dreamwings.cn/api/siyue/?encode=js

## 使用方法： ##

1.将下面这段代码放入HTML页面的head标签内

    <script type="text/javascript" src="https://www.dreamwings.cn/api/siyue/?encode=js&charset=utf-8"></script>

2.将下面这段代码放入页面内需要展示一句话的位置即可

    <div id="siyueapi"><script>siyueapi()</script></div>

> 该脚本实质为document.write的脚本。

# (。・`ω´・)然后，完成！ #

## one more thing... ##

所有的数据都存在数组**array**中，你可以手动更改其中的内容进行DIY。
