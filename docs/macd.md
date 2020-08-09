# 指数平滑异同移动平均线(MACD)

组成：DIFF、DEA、MACD 柱线、零轴组成(三线一柱)，通过对这些数据的交叉，背离，突破，支撑，阻力来判断趋势，这个指标是一个延后指标，有延迟

MACD 默认参数是 12、26、9

- DIFF

DIFF 值 = EMA12(12 日价格均值) - EMA26(26 日价格均值)，个人理解表示的是 12 日均价与 26 日均价的差值，反应的是过去半个月与过去一个半月的均价比较，更为通俗的解释为近半个月的变动趋势

- DEA

DEA = DIFF(9)，个人理解，由于每天我们都可以得到以前每一天的 DIFF 值，然后我没在对 9 日的 DIFF 取个平均值，那么就得到了一个变动相对更加平稳的值

_那么通过对**DIFF 于 DEA(DIFF-9)**的比较就更容易确定个股趋势_

也正是由于 DEA = DIFF(9)，所以 DEA 更为稳重，DIFF 更为灵敏

- MACD 柱线

柱线反应的就是这个差值大小了，也可以说是变动的波动大小，从而反映股价的变动趋势

- 零轴

零轴就是柱线的分界，图形上表示多空强度是多方占有，还是空方

**MACD 不适用与短期和超短期投资指标，也不适合在盘整周期**

## 参考

- [MACD](https://www.bilibili.com/video/BV1ib411i7jg?p=7)
- [MACD](http://www.75111.net/book/macdrumen/201608/22095.html)
- [终于有人把 MACD 讲清楚了：MACD 的价值不在“金叉死叉”，而在“红柱绿柱”](https://zhuanlan.zhihu.com/p/149677872)
- [股票投资与入门实践-从零开始学习炒股 | 第 166 页](#)
- [MACD 中 0 轴是代表什么意思?它和 DIF DEA 有什么区别?](https://zhidao.baidu.com/question/68750569.html)
- [在 MACD 指标中 0 轴线在哪？？](https://zhidao.baidu.com/question/109113579.html)
- [什么是 MACD 顶背离和底背离？](https://zhuanlan.zhihu.com/p/67262365)
