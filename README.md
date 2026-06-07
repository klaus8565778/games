# Games

一个轻量的静态网页项目，收录了几个可以直接在浏览器中打开的 HTML 页面，包括小游戏和餐厅展示页。项目不依赖构建工具，也不需要安装 npm 依赖。

## 页面列表

| 文件 | 说明 |
| --- | --- |
| `snake.html` | 贪吃蛇小游戏，支持键盘方向键和触屏滑动操作。 |
| `liangliankan.html` | 连连看小游戏，包含关卡、计时、连线判定和游戏结束提示。 |
| `restaurant.html` | 中式餐厅单页展示，包含导航、品牌介绍、菜单和预约表单等区块。 |

## 使用方式

直接用浏览器打开任意 HTML 文件即可运行：

```text
snake.html
liangliankan.html
restaurant.html
```

也可以使用一个本地静态服务器预览，例如：

```bash
python -m http.server 8000
```

启动后访问：

```text
http://localhost:8000
```

## 项目结构

```text
.
├── README.md
├── liangliankan.html
├── restaurant.html
└── snake.html
```

## 说明

- 所有样式和脚本都写在对应的 HTML 文件中，便于单文件部署和分享。
- 项目适合作为静态页面、小型游戏练习或 GitHub Pages 演示项目。
