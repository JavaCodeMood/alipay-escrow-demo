### 验证通知来自支付宝

涉及到 money，我们就应该保证交易百分百的安全可靠，那我们怎么知道通知来自支付宝，而不是钓鱼网站呢？

支付宝已经提供了解决方案，信息验证机制。

这个我们也不必感到烦恼，只要调用 alipay 这个 gem 的 verify 方法就能做出判断了。

演示一下