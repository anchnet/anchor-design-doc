# Anchor-Design 文档（中文版） {#gitbook文档（中文版）}

> 项目源码地址：[https://github.com/51idc/anchor-design](https://github.com/51idc/anchor-design)
>
> NPM 项目地址：[https://www.npmjs.com/package/anchor-design](https://www.npmjs.com/package/anchor-design)
>
> GitBook 源码地址：[https://github.com/51idc/anchor-design-doc](https://github.com/51idc/anchor-design-doc)
>
> GitBook 在线地址：[https://anchnet.gitbooks.io/anchor-design/content/](https://anchnet.gitbooks.io/anchor-design/content/)

Anchor-Design 是一套基于Vue 2.3的前端 UI 组件库，适合设计师、前端工程师和后端工程师用于快速构建和设计网站前端界面。

## 安装

#### npm

```bash
npm install anchor-design
```

## 开始

```javascript
//1 全局引入
import Vue from 'vue'
import anchorDesign from 'anchor-design'

Vue.use(anchorDesign)

//2.1 单独引入
import Vue from 'vue'
import { ComponentName } from 'anchor-design'
new Vue({
    //...
    components: {
        ComponentName
    },
    templete: '<div><component-name></component-name></div>',
    //...
})

//2.2 或者
import Vue from 'vue'
import { ComponentName } from 'anchor-design'
<templete>
    <div>
        <component-name></component-name>
    </div>
</templete>
<script>
    export default {
        //...
        components: {
            ComponentName
        }
        //...
    }
</script>
```

## 贡献者列表

> 动态更新，排名不分先后

* [戴立勤](https://github.com/xiaoda)

## 作者

* [Zhimeng Liu](https://github.com/liuzmeng)

## 许可证

MIT

