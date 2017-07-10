# BZCircleScrollView

## 一个使用Swift写的Banner轮滚视图

特性
* 通过数据源控制视图的个数和样式,你可以控制在一个banner上显示不同结构的view。并通过delegate灵活的监听到视图的位置和操作。
* 内部的视图是复用的，实现机制类似于tableView，当视图离开视线的时候会将视图放入到缓存池中，当要显示的时候在复用。
* 可以通过控制每个Page的alpha和scale来表现出动画效果。

 
