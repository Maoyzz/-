# Collection

事件分发笔记 19.12.5
{
onInterceptTouchEvent和onTouchEvent其实都是在dispatchTouchEvent里面调用
onTouch是linstener的回调方法，早于onTouchEvent
}
Glide缓存相关的笔记 19.12.17
{
refer to https://juejin.im/post/5dd766e1e51d45233c7e857f
Glide分为两种缓存，内存缓存和磁盘缓存
内存缓存是为了防止频繁的将图片写入到内存
硬盘缓存是为了防止从网络上重复下载
Glide的三级缓存机制：Lru算法缓存 -> 弱引用缓存 ->磁盘缓存

}
