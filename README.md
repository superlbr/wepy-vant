# wepy2
[init](https://wepyjs.github.io/wepy-docs/2.x/#/base/getstart) 

## use vant-weapp in wepy2
1. copy vant-weapp dist (version 1.1.0)
2. use in this way
   ```
    usingComponents: {
      "van-button": '~@/static/vant/button'
    }
   ```
3. 已知问题
  a. picker组件toolbar.wxml打包可能丢失，检查之后手动拷贝即可
  b. Tab点击不触发 tabs中this.trigger('click')=>'tap'

## use weui in wepy2
reference [wepy-weui](https://github.com/wepyjs/wepy-weui-demo)
1. copy weui style in src/style
2. use like src/example
