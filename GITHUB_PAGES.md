# 启用 GitHub Pages 教程

## 步骤 1：进入仓库设置

1. 打开浏览器访问：https://github.com/yangfuhe/privacy
2. 点击顶部的 **"Settings"** 标签

## 步骤 2：配置 Pages

1. 在左侧边栏找到 **"Pages"**（可能在 "Code and automation" 分组下）
2. 点击 **"Pages"**

## 步骤 3：选择源

在 **"Build and deployment"** 部分：

| 设置项 | 选择值 |
|--------|--------|
| Source | Deploy from a branch |
| Branch | main → / (root) |

3. 点击 **"Save"** 按钮

## 步骤 4：等待部署

1. GitHub 会在几秒内开始构建
2. 约 1-2 分钟后页面将上线
3. 您可以刷新 Pages 设置页查看部署状态

## 步骤 5：获取链接

部署成功后，您将在顶部看到：

```
Your site is live at https://yangfuhe.github.io/privacy/
```

## 可用的链接

| App | 链接 |
|-----|------|
| NexClean（合页） | https://yangfuhe.github.io/privacy/nexclean/ |
| NexClean（中文） | https://yangfuhe.github.io/privacy/nexclean/privacy-cn.html |
| NexClean（英文） | https://yangfuhe.github.io/privacy/nexclean/privacy-en.html |

## 将来添加新 App

当您需要添加新 App 的隐私政策时：

1. 在 `privacy/` 目录下创建新文件夹，如 `other-app/`
2. 添加 `index.html` 等文件
3. 提交并推送：`git add . && git commit -m "Add OtherApp privacy policy" && git push`
4. 更新 `README.md` 中的表格

## 验证部署

部署完成后，访问：
- https://yangfuhe.github.io/privacy/
- https://yangfuhe.github.io/privacy/nexclean/

确认页面可以正常访问。

---

**预计完成时间：2-3 分钟（GitHub 处理时间）**
