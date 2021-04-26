# vue-cli-pratice
vue-cli 练习

# 1.初始化node 项目 - npm init -y 

- 生成package.json 文件，用于记录项目的详细信息以及开发中使用的依赖包。
  |- 添加启动命令
  ```javascript
  {
    "name": "vue-basic",
    "bin": {
    	"ev": "bin/ev",
      "ev-add": "bin/ev-add",
      "ev-del": "bin/ev-del",
      "ev-list": "bin/ev-list",
      "ev-init": "bin/ev-init"
    }
  }
  ```

# 2.文件系统

- bin - 脚手架入口文件
  |-ev
  |-ev-add
  |-ev-del
  |-ev-list
  |-ev-init