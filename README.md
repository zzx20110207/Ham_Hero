# Ham Hero

> 无线电爱好者个人主页生成器

[![License](https://img.shields.io/github/license/dariondong/Ham_Hero)](https://github.com/dariondong/Ham_Hero)
[![GitHub Stars](https://img.shields.io/github/stars/dariondong/Ham_Hero)](https://github.com/dariondong/Ham_Hero)

## 介绍

Ham Hero 是一个开源的无线电爱好者个人主页模板，帮助你快速搭建属于自己的专属个人页面。

只需修改配置文件，即可轻松更新你的呼号、设备、电台信息等内容。

## 特性

- 📁 JSON 配置 - 无需修改 HTML，通过配置文件轻松更新
- 📱 响应式设计 - 完美适配桌面端和移动端
- 🎬 视频背景 - 精美的动态视频背景
- 📡 无线电专用 - 专为业余无线电爱好者设计
- ☁️ GitHub Pages - 一键部署，免费托管
- 🔓 开源免费 - 完全免费使用

## 快速开始

### 1. Fork 项目

点击 GitHub 右上角的 Fork 按钮，将项目复制到你的仓库。

### 2. 修改配置

编辑 `ham/data.json` 文件，配置你的个人信息：

```json
{
    "callsign": "BG7LZQ",
    "name": "你的呼号",
    "operatorLevel": "A级",
    "cqZone": 24,
    "ituZone": 44,
    "grid": "OL51",
    "location": {
        "country": "中国",
        "省份": "广东",
        "城市": "茂名"
    },
    "description": "A级业余无线电操作员 | 追求通联的乐趣",
    "equipment": {
        "handheld": ["设备1", "设备2"],
        "antenna": ["天线1", "天线2"]
    },
    "social": {
        "qrz": "https://www.qrz.com/db/BG7LZQ"
    }
}
```

### 3. 添加背景视频

将你的背景视频重命名为 `bg.mp4`，放入项目根目录。

### 4. 启用 GitHub Pages

1. 进入仓库 → Settings → Pages
2. Source 选择 "main branch"
3. 保存后访问 `https://你的用户名.github.io/Ham_Hero/ham`

## 文件结构

```
Ham_Hero/
├── index.html          # 项目介绍页面
├── bg.mp4             # 背景视频（需自行添加）
└── ham/
    ├── data.json       # 个人信息配置
    ├── index.html      # 个人主页
    ├── log.html        # 通联日志
    ├── qso.html       # QSO 详情
    └── log.csv        # 通联记录
```

## 演示

- [项目介绍](https://dariondong.github.io/Ham_Hero/)
- [个人主页](https://dariondong.github.io/Ham_Hero/ham/)
- [通联日志](https://dariondong.github.io/Ham_Hero/ham/log.html)

## 依赖

- [Font Awesome](https://fontawesome.com/) - 图标库
- [Google Fonts](https://fonts.google.com/) - 字体

## 许可证

MIT License - 欢迎自由使用和修改

## 感谢

The pages Power By [Ham_Hero](https://github.com/dariondong/Ham_Hero) with [BG7LZQ](https://www.theez.top/)

---

欢迎贡献代码！如果你有任何问题或建议，请提交 Issue。
