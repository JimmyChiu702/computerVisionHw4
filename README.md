# Computer Vision Homework 4
## Sequence of Moving-forward Images
![](https://i.imgur.com/h5im0oI.gif)

## Feature Extraction and Matching Result
![](https://i.imgur.com/IdFQRqs.jpg)

## Image Stiching Result
* Original Input Image

![](https://i.imgur.com/LGjYu1v.png)

* Aligned Result (image2)

![](https://i.imgur.com/xeImJCn.png)

* Original Stitching Result (cropped)

![](https://i.imgur.com/dxSVSMb.png)

* Stitching Result with Linearly Blend

![](https://i.imgur.com/DaHJckF.png)

## Infinite Zooming Effect
![](https://i.imgur.com/5o474YR.gif)


## Different Feature Extraction Comparisson
由於SIFT和SURF都是擁有專利利的演算法，所以我們拿ORB與BRISK比較

Examples：

ORB1：
![](https://i.imgur.com/4Ykui2b.png)

BRISK1：
![](https://i.imgur.com/qRPEOLr.png)

ORB2：
![](https://i.imgur.com/GqQ7w8N.png)

BRISK2：
![](https://i.imgur.com/fPNByCe.png)

ORB3：
![](https://i.imgur.com/1PHPUjc.png)

BRISK3：
![](https://i.imgur.com/aMJ8NjK.png)

Comparison：

ORB：
* 效能較優，計算速度較快
* 特徵點傾向偵測顏⾊色與周圍差異異較⼤大的像素

BRISK：
* 效能其次，比ORB略慢一些
* 特徵點傾向偵測⾓角落落、邊的構造

結論：BRISK對於稜角很多例如文書表格的alignment很有效，但是對於稜角不多的圖片就沒輒了，這時候用ORB會好一些
