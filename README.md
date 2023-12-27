# @nuxt-template/monorepo

## 开发

1. 如果使用 vscode 开发安装 [eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) 插件

2. 添加 git hooks

   ```sh
   # 加入git钩子
   git config core.hooksPath .git/hooks/
   rm -rf .git/hooks

   # Update ./git/hooks
   npx simple-git-hooks
   ```
