# docker_development
dokcer compose nginx-proxy, laravel-backend, react-frontend, mysql, redis, minio

project-root/
├─ docker-compose.yml
├─ .env
├─ nginx-proxy/
│  └─ conf.d/
│     └─ default.conf
├─ laravel-backend/
│  ├─ Dockerfile
│  └─ (Laravel application files)
├─ nginx/
│  └─ conf.d/
│     └─ default.conf
├─ react-frontend/
│  ├─ Dockerfile
│  └─ (React application files)
├─ mysql_data/ (created automatically)
└─ minio_data/ (created automatically)

# env
UID=1000
GID=1000
MYSQL_ROOT_PASSWORD=rootpassword
MYSQL_DATABASE=testdb
MYSQL_USER=user
MYSQL_PASSWORD=password
MINIO_ROOT_USER=minio
MINIO_ROOT_PASSWORD=minio123

Laravel API: http://api.test.local

React Frontend: http://app.test.local

MySQL: localhost:3306

Redis: localhost:6379

MinIO Console: http://localhost:9001
