调用说明
---
1. labelname参数说明
> 内容文字Tag列表(通用)  
> 内容文字Tag列表(通用-x天内点击数降序_带点击数_评论)  

```javascript
var jsondata = {
    type:"updatelabel", 
    labelname:"内容文字Tag列表(通用)", //具体可用值待和后端确认后完善
    attr:{
        Tag:'tag', 
        outputQty:10,//输出10条
        Nodes:11001, //节点id
        Specials:110, //专题id
        InDay:7 //7天内数据
    }
}
$.ajax({
    type: "GET",
    dataType: "jsonp",
    url: "https://db2.gamersky.com/LabelTemplateJsonpAjax.aspx",
    data: {
        jsondata: JSON2.stringify(jsondata)
    },
    success: function(responseJson) {
        //responseJson
    }
});
```

