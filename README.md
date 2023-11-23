# Winter-gin

```sh

export DEBIAN_FRONTEND=noninteractive

apt install -y golang-go git wget

# 如果访问 GitHub.com 需要代理在此设置
# export http_proxy=http://192.168.1.109:3128/
# export https_proxy=http://192.168.1.109:3128/

cd ~/ ; git clone https://github.com/AndyInAi/Winter-gin.git

cd ~/Winter-gin

go mod init Winter-gin

go get github.com/gin-gonic/gin

go build .

./Winter-gin

```
