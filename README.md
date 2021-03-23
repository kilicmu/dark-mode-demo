### 网站暗黑模式原理

最近看 learn-x-in-y-minutes 的demo，发现它有一个暗黑模式很有意思。好像最近好多的网站都添加了这个功能啊。
虽然不知道它是如何实现的，但是我这里有了个思路，简单写了一个demo，就酱~

原理就是利用CSS中的重叠覆盖规则，动态修改theme，实现此效果。

效果：
![demo]("https://github.com/kilicmu/dark-mode-demo/blob/main/assets/demo.gif")