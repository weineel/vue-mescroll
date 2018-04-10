# vue-mescroll

> 封装 mescroll 为 vue组件

## 使用示例

```html
<vue-mescroll
  class="body-wrapper"
  :up="{page: {num: 0, size: 2}}"
  @up-callback="upCallback">
  <p slot="down-html-content" class="downwarp-tip" style="color: #30ccb5;">下拉刷新</p>
  <span slot="down-html-content" style="text-align: center;width: auto">
    <img style="height: 1rem;" src="../../assets-legacy/images/loading.gif" alt="加载中..."/>
  </span>
  <p slot="up-html-loading" style="width: 1rem;height: 1rem; text-align: center; " class="upwarp-tip">
  <img slot="up-html-loading" src="../../assets-legacy/images/loading.gif" alt="加载中..."></p>
  <p slot="up-html-nodata" class="upwarp-nodata" style="color:#30ccb5;">-- 我是有底线的 --</p>
</vue-mescroll>
```

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
