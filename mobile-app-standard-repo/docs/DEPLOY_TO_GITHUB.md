# 上传到 GitHub

## 方式一：网页直接上传

1. 在 GitHub 新建一个仓库
2. 点击 **Add file** → **Upload files**
3. 把这个文件夹里的内容全部上传
4. 提交后即可作为静态仓库保存

## 方式二：本地 Git 推送

```bash
git init
git add .
git commit -m "Initial mobile app repository"
git branch -M main
git remote add origin <你的仓库地址>
git push -u origin main
```

## 如果要用 GitHub Pages

- 这个仓库已经附带了一个基础的 Pages workflow：
  `.github/workflows/static-pages.yml`
- 推送到 GitHub 后，可在仓库设置中启用 Pages（若需要）。
