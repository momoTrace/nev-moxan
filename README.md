
# Moxan 导航站 v1.x

由 **Momo Trace (别名 Mogo)** 开发的美观导航网站，用于统一入口访问 **Moxan（默纤）** 物联网生态的所有子站、服务与资源。

---

## 功能特性

- **现代前端风格**：融合赛博美学 + Apple 极简设计风格
- **暗黑模式支持**：一键切换亮/暗模式
- **中英文双语切换**：简体中文 / English 切换支持
- **分类折叠展示**：清晰分类，交互式展开/折叠
- **动态搜索栏**：支持站点名模糊搜索，自动显示匹配项
- **图标支持**：使用 Font Awesome 图标集
- **粒子背景效果**：赛博氛围感动效
- **响应式设计**：兼容移动端、平板与桌面

---

## 在线预览

> 访问地址：[https://nev.moxan.top](https://nev.moxan.top)

---

## 快速开始

1. 克隆本项目或下载 HTML 文件：

```bash
git clone https://github.com/yourusername/moxan-nav.git
```

2. 直接打开 `index.html` 文件，即可使用。

---

## 文件结构

```
moxan-nav/
├── index.html         # 主站页面
├── README.md          # 项目说明
└── assets/            # （可选）图标或自定义资源目录
```

---

## 自定义说明

### 添加新站点

- 找到 `index.html` 中的 `<details>` 分类块
- 按照如下结构添加：

```html
<details class="...">
  <summary>分类名称</summary>
  <ul>
    <li><a href="https://example.com" target="_blank">站点名称</a></li>
  </ul>
</details>
```

### 修改默认语言

- 网页默认显示为中文，点击右上角 “中 / EN” 可切换语言显示
- 所有语言对映内容包裹在 `.t`（中文）和 `.e`（英文）类中

---

## 开发者

**Momo Trace / Mogo**

- 博客：[https://cnblogs.com/momotrace](https://cnblogs.com/momotrace)
- 歌单：[网易云音乐](https://music.163.com/#/playlist?id=8170701761)

---

## 许可

本项目遵循 MIT License，欢迎自由使用、修改与部署。
