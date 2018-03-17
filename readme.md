##  siteServer Stl lang autoTip
- siteServer CMS STL语言自动补全
- author:JackLee
- email:dzlishen@163.com

安装说明：
在vscode的扩展搜索框中输入siteserver stl即可搜索到本插件，点击安装之后重新加载即可使用了。

在html页面代码书写时，输入stl:c的时候会提示stl:channel和stl:channels组件，点击tab键或者用鼠标点击选中即可快速输入组件。

```
输入stl后有提示时点击tab即可输出如下代码
<stl:channel
            channelIndex="栏目索引"
            channelName="栏目名称"
            ellipsis="文字超出部分显示的文字"
            formatString="显示的格式"
            isClearTags="是否清除HTML标签"
            isDynamic="是否动态显示"
            isLower="是否转换为小写"
            isReturnToBr="是否将回车替换为HTML换行标签"
            isUpper="是否转换为大写"
            leftText="显示在信息前的文字"
            length="指定字符长度"
            parent="显示父栏目属性"
            replace="需要替换的文字，可以是正则表达式"
            rightText="显示在信息后的文字"
            separator="显示多项时的分割字符串"
            startIndex="字符开始位置"
            to="替换replace的文字信息"
            topLevel="从首页向下的栏目级别"
            type="显示的类型"
            upLevel="上级栏目的级别"
            wordNum="显示字符的数目">
        </stl:channel>
```

