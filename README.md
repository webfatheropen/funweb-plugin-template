# Remote Component Starter Kit

使用 funweb-start 快速创建 funweb 插件

## Getting Started

复制项目模版然后初始化您的项目

```bash
# 创建项目仓库
mkdir componentx
cd componentx
git init

# 获取项目模版
git pull git@github.com:Fiber-Man/funweb-starter.git --depth=1
git commit -m "pull funweb-starter"

# 安装依赖
yarn install
```

修改 `package.json` 并且替换您的项目信息
- 设置 `name` 为您的项目名称.
- 设置 `description` 为您的项目摘要.
- 设置 `repository` 为您的git仓库地址.

## Files

- `index.js` - 组建必须带有 `default` export.

## Building

项目将编译为 `dist/main.js`.

```bash
yarn build
```
## Debugging

```bash
yarn start
```
