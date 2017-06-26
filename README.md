# SVG
SVG的练习

# clip-path和mask的具体应用场景
首先来复习下，clip-path和mask概念和区别：

cliping-path：clip-path是由path, text或者基本图形组成的图形。所有在裁剪路径内的图形都可见，所有在裁剪路径外的图形都不可见。
mask是一种容器，它定义了一组图形并将它们作为半透明的媒介，可以用来组合前景对象和背景。
clip-path和mask一个重要的区别就是：clip-path是1位蒙板，也就是说clip-path覆盖的对象要么就是全透明(可见的，位于clip-path内部)，
要么就是全不透明(不可见，位于clip-path外部)。而mask可以指定不同位置的透明度