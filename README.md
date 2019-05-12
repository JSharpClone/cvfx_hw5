# CVFX HW5

```
Team #15
107062503 許博皓
107062513 鄭家鈞
107062566 黃鈺程
```

## Photo

![](https://i.imgur.com/HLxbWEK.jpg)

![](https://i.imgur.com/uf8HeII.jpg)

![](https://i.imgur.com/3uxFpmf.jpg)

![](https://i.imgur.com/PWuIZis.jpg)


## Feature Matching
![](https://i.imgur.com/tI0u08p.jpg)


![](https://i.imgur.com/fGdwbew.jpg)

## 3D Effect
我們做的是 Stop Motion，實作上分為前景和背景兩部分，操作如下:

1. 背景三張圖經過 align 之後進行 stitching。
    ![](https://i.imgur.com/f3gclw0.jpg)
2. 手動將前景「杯子」取出，並製作其 mask。
    ![](https://i.imgur.com/YJTpxNy.png)
    ![](https://i.imgur.com/i35HOOA.png)
3. 透過 mask 的方式將前景放置於背景上，並讓前景和後景以不同速度移動。
    ![image](https://github.com/JSharpClone/cvfx_hw5/blob/master/small.gif)
    
    




## Enhance
原本的 mask 周圍有許多雜訊，透過影像處理的方法將物體周圍變得更銳利，貼在背景上的效果更好。
