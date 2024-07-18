### 添加prettierrc
1. 安装yarn add --dev --exact prettier
2. 新增prettierrc、prettierignore文件
3. yarn prettier . --write格式化当前目录文件
### 添加lint-staged
    Lint-staged是一个Node.js脚本，允许你对当前暂存的文件运行任意脚本。
1. 安装yarn add --dev --exact lint-staged
2. 新增.lintstagedrc文件
3. npx lint-staged
### 添加husky
    husky 是一个 Git 钩子（Git hooks）工具，它可以让你在 Git 事件发生时执行脚本
1. 安装yarn add --dev husky 
2. 安装yarn add --dev pinst
3. package.json的script新增"postinstall": "husky"，执行初始化yarn run postinstall,
   添加执行脚本


