Vue.js是一套构建用户界面的渐进式框架。同reactjs和angularjs比起来，它更加的小巧、轻盈。当框架渲染在客户端进行时，Vue.js用起来更加得心应手。下面的例子，是自己学习Vue.js的时候的demo，提供给大家参考。

![](https://graphis.zhuyan.me/data/20170420/1.gif)


这是一个两级的省市插件，省市的数据来源不详，格式采用六位编码，比如广东省是440000,深圳则是440300。每两位代表一级行政区域。


初始化很简单
```
<div id="demo">
    <j-city cvalue="440300" cname="city-code"></j-city>
</div>
<script>
new Vue({el:'#demo'});
</script>
```



如果有需要的话，点击查看详细的例子。