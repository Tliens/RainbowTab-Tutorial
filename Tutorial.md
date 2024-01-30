## 一、基础配置
0. 安装homebrew
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
1. 安装npm
`brew install node`
2. 安装yarn
`brew install yarn --ignore-dependencies`
3. 新建项目
`yarn create vite`

```
✔ Project name: … Rainbowtab
✔ Package name: … rainbowtab
✔ Select a framework: › Vue
✔ Select a variant: › JavaScript
```
4. 安装依赖包
`yarn`
```
yarn install v1.22.21
info No lockfile found.
[1/4] 🔍  Resolving packages...
⠁ (node:86643) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
(Use `node --trace-deprecation ...` to show where the warning was created)
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 🔨  Building fresh packages...
success Saved lockfile.
```
5. 运行
`yarn dev`

```
yarn run v1.22.21
$ vite

  VITE v5.0.12  ready in 201 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h + enter to show help
```
![Alt text](image.png)

