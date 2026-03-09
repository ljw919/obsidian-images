# Obsidian Images

Obsidian 笔记图片存储仓库 - 用于存储 Obsidian 笔记中的图片。

## 📝 说明

这个仓库作为图床，存储 Obsidian 笔记中的图片。通过 [PicGo](https://github.com/PicGo/PicGo) 和 [Obsidian Image auto upload Plugin](https://github.com/renmu123/obsidian-image-auto-upload-plugin) 实现图片自动上传。

---

## 🚀 使用方式

### 访问图片

图片存储在 `images/` 目录下，格式为：

```
https://github.com/ljw919/obsidian-images/raw/main/images/图片文件名.png
```

### 示例

```markdown
![图片描述](https://github.com/ljw919/obsidian-images/raw/main/images/20260309-abc123.png)
```

---

## 📁 目录结构

```
obsidian-images/
├── images/              # 图片存储目录
│   ├── 20260309-abc123.png
│   ├── 20260309-def456.png
│   └── ...
└── README.md           # 本文件
```

---

## 🛠️ 配置说明

### PicGo 配置

**Linux (CLI):**
- 安装：`npm install -g picgo`
- 配置文件：`~/.picgo/config.json`

**macOS (APP):**
- 下载：https://github.com/PicGo/PicGo/releases
- 配置：图形界面配置

**GitHub 图床配置:**
- 仓库：`ljw919/obsidian-images`
- 分支：`main`
- 路径：`images/`

### Obsidian 插件配置

**插件名称：** `obsidian-image-auto-upload-plugin`

**PicGo 服务器地址：**
```
http://127.0.0.1:36677/upload
```

---

## 💡 工作流程

1. 在 Obsidian 中粘贴图片
2. Image auto upload Plugin 自动调用 PicGo
3. PicGo 上传图片到 GitHub
4. 自动替换为 GitHub 链接
5. 笔记通过 Nutstore 同步到其他设备

---

## 📱 多设备访问

- **Linux:** PicGo-CLI
- **macOS:** PicGo-APP
- **同步:** Nutstore (笔记) + GitHub (图片)

所有设备使用同一个 GitHub 仓库，确保图片链接统一。

---

## ⚠️ 注意事项

- 本仓库为公开仓库
- 图片公开可访问
- 不要上传敏感或私密图片
- 定期清理不必要的图片
- GitHub 有流量限制（免费账户足够使用）

---

## 🔗 相关链接

- [PicGo 官网](https://github.com/PicGo/PicGo)
- [Obsidian 插件](https://github.com/renmu123/obsidian-image-auto-upload-plugin)
- [Obsidian 官网](https://obsidian.md)

---

## 📅 创建时间

2026-03-09

---

**仓库用途：** Obsidian 笔记图床
**维护者：** ljw919
