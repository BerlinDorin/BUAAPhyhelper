# BUAAPhyhelper

一个北航实验报告小工具，全是垃圾代码，没什么好看的。

（如果你也写了脚本 欢迎fork和pr~）

## 近期更新

- 1051基本完成

## TODO

- 重构1051_1部分，考虑自动舍入。
- **打印和计算分离**
- 模块化，重复代码写个库。

## FAQ

Q：为什么保留位数和书本不同？

A：我大部分数据都多打印了一些位数，请自行按照“四舍六入五取偶”来得到数据（因为我懒）。

Q：如果我用你的脚本报告扣分了怎么办？

A：本人对脚本产生的任何后果概不负责。

## 1051

### 1.自组电位差计（必做）

按照书本P165输入所有数据后就可以按照书本顺序计算出所有值。

### 测试

`python3 main.py < Test.txt`

和课本上的数据对照即可。

### 2.箱式电位差计测固定电阻

电路图略。

### 测试

`python3 main.py < Test.txt`

（其实没有正确答案

