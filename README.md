### 改动
  * 只读
  * 初始账号`user`，密码`qwer1234`

### 使用
  * 修改`Dockerfile`中的 `ENV PASV_ADDRESS`为外部地址
  * 修改`docker-compose.yml`中的`volume`，`/映射目录:/home/vsftpd/user`
  * `docker-compose up -d`启动，`docker-compose down`关闭