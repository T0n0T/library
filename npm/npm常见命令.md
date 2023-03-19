- `npm install`
```shell
# 会把X包安装到node_modules目录中
# 不会修改package.json
# 之后运行npm install命令时，不会自动安装X
npm install X

# 全局安装
-g

# 会把X包安装到node_modules目录中
# 会在package.json的dependencies属性下添加X
# 之后运行npm install命令时，会自动安装X到node_modules目录中
-S， --save

# 包将出现在依赖项中。这是默认值，除非出现-D或-O
# 安装包信息将加到devDependencies（开发阶段的依赖），所以开发阶段一般使用它
-P, --save-prod 

# 包将出现在您的devDependencies中
-D, --save-dev

# 包将出现在optionalDependencies中
-O, --save-optional

# 防止保存到依赖项
–no-save: Prevents saving to dependencies

# 精确安装指定模块版本
# 安装包，默认会安装最新的版本
-E, –save-exact 

```
