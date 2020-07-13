# V2ray安装教程

### 在终端运行 

- #### *curl-Ohttps://install.direct/go.sh*

### 完成后将下载的config.json文件移动到/etc/v2ray/config.json中

- #### *`sudo` cp config.json /etc/v2ray/config.json*

### 启动v2ray:

- #### *service v2ray start*

### 在home目录下打开.bashrc文件，在最下面天际代理地址和端口：

- ### *export http_proxy=127.0.0.1:8001*

- ### *export https_proxy=127.0.0.1:8001*

- ### *exportsocket_proxy=127.0.0.1:1081*

## 在浏览器中，也需要配置代理，有时候在系统设置中也需要配置

