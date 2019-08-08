# 前端性能优化-执行篇

我们已经介绍了前端加载方面的优化操作,在实际开发中大部分情况下我们解决的性能优化问题就是加载问题,但是我们依然会碰到一些高性能要求的场景需要优化我们的代码执行速度.

我们不会去介绍用for循环或者forEach那种更快,一方面,这种所谓的快慢在前端场景中的差距几乎是可以忽略的,另一方面,随着JS引擎的迭代,这种差距也会发生变化,并不具有普适性,我们更愿意在更宏观的层面来探究这个问题.

## 动画性能优化
