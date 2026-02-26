# A_test

这是一个简易贪吃蛇网页小游戏。

## 项目结构

- `snake/index.html`：游戏页面（可直接运行）

## 本地运行

1. 克隆仓库

```bash
git clone https://github.com/<你的用户名>/<你的仓库名>.git
cd <你的仓库名>
```

2. 启动静态服务器

```bash
python3 -m http.server 4173
```

3. 打开浏览器访问

```text
http://127.0.0.1:4173/snake/index.html
```

## 操作方式

- 方向键控制移动
- 吃到红色食物加分并增长
- 撞墙/撞自己游戏结束
- 游戏结束后按空格重新开始
