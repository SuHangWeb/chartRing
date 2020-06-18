# echarts 百分比图 (可二次开发)

> 依赖于百度echarts 官网地址[传送门](https://echarts.apache.org/zh/index.html)

### 安装 

```
npm install echarts --save
```

### 调用方法（单独页面调用）

> import 引用
```
 import ring from './modules/ring.vue'
```

> 注册组件
```
components {
    ring
}
```

### 组件使用
```
<ring color="#289DE7" :data="{value: 80.88, text:'已确认问题', subtext:'疑似问题'}"/>
```
* data 数据
    * value 百分比值 Number类型数值
    * text 主标题
    * subtext 副标题
* color 百分比占用颜色
