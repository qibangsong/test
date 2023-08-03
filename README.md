# sgitg-cli

前端脚手架，提供前端开发初始模板。

## 脚手架使用命令

- 安装依赖

```bash
npm install -g sgitg-cli --registry=https://repo.sgitg.cn/repository/npm-all/
```

- 添加模板

```bash
sgitg add
```

- 删除模板

```bash
sgitg delete
```

- 模板列表

```bash
sgitg list
```

- 通过模板初始化应用

```bash
sgitg init
```

## 开发脚手架注意事项

1. 新增模板需要启动本地工程后运行 `npm link`后执行 sgitg add 命令添加模板
2. 更新模板时需要打开 template.json 文件，修改相应模板的版本号，此版本号为受保护的分支标签
3. 修改脚手架后需要修改 package.json 文件中的版本号，并运行 `npm publish` 进行发布，如果没有权限请联系研发平台陈雪（chenxue8）帮忙发布
