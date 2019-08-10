# 抖音小程序 ttml

为 VSCode 提供 ttml 语法支持及代码片段

## 安装

1. 打开编辑器，`Ctrl + Shift + X`，搜索 **ttml**。
2. 点击 `install`

## 使用

键入关键词，然后回车。关键词不区分大小写


#### 代码示例

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
...more


**Enjoy!​​**