# Deploy_Mysql
部署mysql

## 环境变量

确保运行脚本的目录下有`.env`文件。格式参考`.env.example`。

## 启动容器

```bash
# 正常启动 （使用 .env 文件中的环境变量）
docker-compose up -d

# 生产环境启动
docker compose --env-file .env.prod up -d

# 验证配置
docker compose config
```
