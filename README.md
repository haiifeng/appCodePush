1、安装指定版本的react-native
    `npm i -g rninit`
    `rninit init [Project Name] --source react-native@0.38.0`

2、<a href="https://github.com/Microsoft/react-native-code-push">安装codepush服务</a>
    `npm install -g code-push-cli`
    `code-push -v` 查看版本

    `code-push register` 创建codepush账号

    `code-push login` 登陆
    `code-push logout` 注销

    `code-push access-key ls` 列出登陆的token
    `code-push access-key rm` 删除某个 access-key

    `code-push app add` 在账号里面添加一个新的app
    `code-push app remove` 或者 rm 在账号里移除一个app
    `code-push app rename` 重命名一个存在app
    `code-push app list`或`code-push app ls` 列出账号下面的所有app
    `code-push app transfer` 把app的所有权转移到另外一个账号

    `npm install --save react-native-code-push@latest` 安装copde-push模块
