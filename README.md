# 🚀 FreelanceHub — 自由职业服务网站

中英双语自由职业服务展示网站，包含服务展示、双语发票生成器、定价方案、支付宝收款码和联系表单。

---

## 🌐 部署到 GitHub Pages（免费）

### 前置准备
1. **安装 Git**：https://git-scm.com/download/win
2. **注册 GitHub**：https://github.com

### 部署步骤
打开 PowerShell 终端，依次执行：
```
cd "C:\Users\osk\Documents\New project"
git init
git add -A
git commit -m "初始提交"
```
然后去 https://github.com/new 创建仓库，再执行：
```
git remote add origin https://github.com/你的用户名/freelance-hub.git
git branch -M main
git push -u origin main
```
最后在仓库 Settings → Pages 中开启 GitHub Pages，选 main 分支，搞定！

### 其他方式
- **Vercel**：注册 vercel.com，导入项目自动部署
- **本地查看**：直接双击打开 site\index.html

---

## 🛠️ 个性化修改
- 换收款码：替换 site\alipay-qr.jpg
- 改价格/服务：编辑 site/index.html
- 修改联系方式：编辑 site/index.html 中 Contact 部分

---

## 📁 文件结构
```
New project/
├── README.md
├── site/
│   ├── index.html
│   └── alipay-qr.jpg
```

祝接单顺利！🎉
