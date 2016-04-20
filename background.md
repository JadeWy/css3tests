# background-size  
 - 百分比  关键词   cover

| 属性            | 描述     |
| :-----:         | :------: |
| background-size |改变背景图片大小,值可以是 length(px)、百分比(%)、cover 把图片占整个元素、contain 把图片扩展宽度或者高度到最大的尺寸使其能够完全的适应整个容器。

# 颜色和透明度

css中颜色表示方式：
1. rgb(0-255,0-255,0-255)
2. #000000  十六进制颜色
3. 关键词 red blue green orange pink
4. rgba(0-255,0-255,0-255,0-1)
	可以让 文字颜色、背景颜色 变成透明


background:transparent
opacity: 0-1;  表示透明度
filter:Alpha(opacity=0-100);   IE滤镜


浏览器的前缀

火狐浏览器前缀  -moz-
IE前缀  -ms-
chrome  -webkit-
欧鹏    -o-

模糊效果   
-webkit-filter:blur(10px);//模糊10个像素
灰度效果
-webkit-filter:grayscale(0 | 1)
1:灰色  0::彩色

线性渐变
//支持角度  left top bottom right 方式
background:linear-gradient()

IE低版本(6-9)线性渐变
progid:DXImageTransform.Microsoft.gradient(startColorstr='#c6ff00', endColorstr='#538300',
GradientType='0');

startColorstr 表示起点的颜色，
endColorstr 表示终点颜色。
GradientType 表示渐变类型，0为缺省值，表示垂直渐变，1表示水平渐变。