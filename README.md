# 数据库docker compose配置

## 文件目录及说明

```bash
├── docker-compose.yml # docker compose 配置文件
├── mysql
│   ├── conf
│   │   ├── my.cnf # mysql配置文件
│   │   └ .env # docker环境变量配置文件
│   ├── data # 数据库数据目录
│   └── sql # sql文件存放目录
└── redis
    └── redis.conf # redis配置文件
```

## docker-compose 部署

进入docker-compose.yml目录，执行`docker compose up -d`即可启动相关容器。
