# 抖音小程序 ttml

使VSCode 编写 ttml 语法支持及代码片段

## github地址

[https://github.com/Tinolee615/ttml]('https://github.com/Tinolee615/ttml')

## 安装

1. 编辑器Extensions搜索 **ttml**。
2. 点击安装

## 使用方法

键入关键词，然后回车。关键词不区分大小写


#### 示例

- view

    ```html
    <view>
        
    </view>
    ```
- swiper
    ```html
    <swiper indicator-dots="{{indicatorDots}}" autoplay="{{autoplay}}" interval="{{interval}}" duration="{{duration}}">
        <block tt:for="{{imgUrls}}">
            <swiper-item>
                <image src="{{item}}" class="slide-image" />
            </swiper-item>
        </block>
    </swiper>

    ```
- ttfor

    ```html
    tt:for="{{items}}"
    ```
...
