#sshp
采用expect, 在ssh登陆时自动输入密码.

可以用在iterm2等软件ssh登陆上.

## 使用
直接在sshp后面输入ssh的参数,将会解析host,从特定密码配置文件中查找到密码来自动登陆

>  eg: sshp root@ip

## 密码本配置
直接在脚本中配置地址.

密码本的格式如下:

>  ip [一些额外信息,例如内网ip或者说明,无空格] 密码
