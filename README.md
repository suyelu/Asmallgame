# 弹球小游戏

## 游戏

![](http://47.93.11.51:88/img/2020-07-08/74A514993D6343C4873F4B5A3D34E3E5.jpg)

## 如何玩

1. 方向上 开始游戏
2. 方向左 向左移动
3. 方向右 向右移动

## 如何编译运行

1. 克隆代码

```bash
git clone https://github.com/suyelu/Asmallgame.git
```

1. 下载`ncurses`界面库

```bash
sudo apt-get install libncurses5-dev
```

2. 编译

```bash
cd Asmallgame
gcc game.c -lncurses -o game
```

3. 运行

```bash
./game
```
