# [blog for luox78](https://luox78.github.io)

### updates
#### 2018
1/3 添加表格样式

1/4 添加meta使chrome手机版有有一致体验;改变搜索栏样式

1/6 添加引用的背景颜色，更瞩目

1/7 添加[Valine](https://valine.js.org/#/quickstart)评论

1/8 修改搜索栏样式，标题添加位移
```
                a {
                    -webkit-transition-property: all;
                    -webkit-transition-duration: 0.3s;
                    -moz-transition-property: all;
                    -moz-transition-duration: 0.3s;
                    -o-transition-property: all;
                    -o-transition-duration: 0.3s;
                    transition-property: all;
                    transition-duration: 0.3s;
                    display: inline-block;
                    line-height: 1.25;
                    font-weight: normal;
                    color: lighten(@black, 2%);
                    &:hover {
                        margin-left: 5px;
                        color: @accent-color;
                    }
                    &:hover:after{
                        width: 25px;
                        left: -50px;
                        
                    }
                }
```