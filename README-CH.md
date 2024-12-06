# Deploy PostgreSQL PgAdmin Guide

使用 Docker 部署 PostgreSQL 與 PgAdmin。

## Overview
- 資料庫：PostgreSQL v13.2

## Run
在 `docker-compose` 文件中將 `PGADMIN_DEFAULT_EMAIL` 修改為您的電子郵件地址。  
```bash
docker compose up -d
```

資料庫運行於 `localhost:5432`  
介面運行於 `http://localhost:8080`  

## UI

![image](pgadmin.png)