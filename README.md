# ECS CI/CD Workshop

## Mục tiêu

Dự án này là một demo ứng dụng nhiều container (frontend + backend) để triển khai trên ECS Fargate.

## Cách chạy local

1. Cài đặt Docker và Docker Compose.
2. Chạy lệnh:

```bash
docker-compose up
```

3. Truy cập:
   - Frontend: [http://localhost:8080](http://localhost:8080)
   - Backend: [http://localhost:3000](http://localhost:3000)

## Cấu trúc thư mục

```
ecs-cicd-workshop/
├── frontend/
│   └── Dockerfile
├── backend/
│   └── Dockerfile
├── docker-compose.yml
├── .gitignore
└── README.md
```
# ecs-cicd-workshop
