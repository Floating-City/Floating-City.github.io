# GitHub Pages 个人主页

Enbo Wang (Floating-City) 的个人主页,纯 HTML/CSS/JS 单页,无需构建,推到 GitHub 即可用。

## 自定义

1. 打开 `index.html`,修改各区块内容:首屏一句话介绍、关于我、技能列表、项目卡片。
2. 联系方式里把 `you@example.com` 换成真实邮箱。

## 部署到 GitHub Pages

```bash
git init
git add .
git commit -m "Initial homepage"
git branch -M main
git remote add origin git@github.com:Floating-City/Floating-City.github.io.git
git push -u origin main
```

仓库名必须是 `Floating-City.github.io`,推送后约一分钟,访问
`https://floating-city.github.io` 即可看到页面。

> 如果仓库名不是 `Floating-City.github.io`,需要到仓库
> Settings → Pages 里手动选择 main 分支开启 Pages,地址会变成
> `https://floating-city.github.io/仓库名/`。

## 本地预览

直接用浏览器打开 `index.html`,或者:

```bash
python -m http.server 8000
# 访问 http://localhost:8000
```
