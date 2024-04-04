
<div align="center">
<img src="./docs/public/kiwi.svg" width="300" style="padding:3rem;" alt="预览"/>

<h1 align="center">KiwiBlog</h1>

[![Netlify Status](https://api.netlify.com/api/v1/badges/21d806d7-2127-4d4c-8e27-083b59fc10af/deploy-status)](https://app.netlify.com/sites/kiwiblog/deploys)

项目地址：[Netlify 部署](https://kiwi233.top)

</div>

## ☕ 演示

![首页](./assets/image.png)

![博客](./assets/image2.png)

![文章](./assets/image3.png)

## ⏳ 起步 | Project Setup

```sh
# node 版本 >= 18
npm install -g pnpm
pnpm install
```

## ✨ 开发

```sh
pnpm run dev
```

## 📦 打包

```sh
pnpm run build
```

## 🎊 部署

静态托管

## ❌ pnpm install error

查看源

```sh
pnpm get registry 
```

临时修改

```sh
pnpm --registry https://registry.npm.taobao.org install any-touch
```

持久使用

```sh
pnpm config set registry https://registry.npm.taobao.org
```

还原

```sh
pnpm config set registry https://registry.npmjs.org
```
