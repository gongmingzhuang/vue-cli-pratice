# vue-cli-pratice
vue-cli 练习

# 1.初始化node 项目 - npm init -y 

- 生成package.json 文件，用于记录项目的详细信息以及开发中使用的依赖包。
  |- 添加启动命令
  ```javascript
  {
    "name": "vue-basic",
    "bin": {
    	"es": "bin/es",
      "es-add": "bin/es-add",
      "es-delete": "bin/es-delete",
      "es-list": "bin/es-list",
      "es-init": "bin/es-init"
    }
  }
  ```

# 2.文件系统

- bin - 脚手架入口文件
-  |-es
-  |-es-add
-  |-es-del
-  |-es-list
-  |-es-init


# 3.使用
## 添加模板
> es add 
- 请输入模板名称：
- 请输入模板地址：

## 删除模板
> es delete
- 请输入要删除的模板名称:

## 查看已添加模板
> es list

## 拉取远程项目到本地
> es init <template_name> [project_name]
