# bootstrap demo



# nginx服务器配置 
> 配置config
>   开发目录： E:/codeDev
>   生产目录： D:/snserDev

# npm 安装
 需要配置proxy 代理
 #### 4.3 区块引用 ####
在段落的每行或者只在第一行使用符号`>`,还可使用多个嵌套引用，如：
> + 下载node环境
> + 打开node.js command prompt(命令提示)
> + 设置代理 使用 npm config set proxy http://10.19.110.32:8080
> + 使用config 命令 npm config set registry https://registry.npm.taobao.org
> + 安装cnpm :  npm install -g cnpm --registry=https://registry.npm.taobao.org


# fis3安装 
> npm安装



#  sass 安装 
需要设置http-proxy http代理 
> 1. 首先参考http:w3cplus.com/sassguide/install.html  安装ruby
> 
> 2. 如果gem install sass 报错，安装不成功，往下走
> 
> 3. 先安装淘宝rubyGems镜像，参考以上网页
> 
> 4. 如果镜像安装不成功，使用代理安装
> 
> 5. 先将文件放到 C:\RubyCertificates 目录下，该目录是新建的
 
> 6.  然后添加系统环境变量SSL_CERT_FILE  C:/RubyCertificates/cacert.pem ，并重启
 
> 7. 移除原生gem镜像
        gem sources --remove https://rubygems.org/

> 8. 添加淘宝gem镜像
        gem sources --add https://ruby.taobao.org/  --http-proxy http://10.19.110.32:8080/

> 9.  安装sass 
        gem install sass --http-proxy http://10.19.110.32:8080/




> [younghz的Markdown库](https:://github.com/zuotaogithub/ "bootstrap-demo")


> [younghz的Markdown库1][1]    
> [younghz的Markdown库2][2]

[1]: https:://github.com/zuotaogithub/ "bootstrap-demo"
[2]: https:://github.com/zuotaogithub/ "bootstrap-demo"
> `ctrl ＋ c`
