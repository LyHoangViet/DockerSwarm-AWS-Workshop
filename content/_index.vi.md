+++
title = "Tích hợp Docker Swarm với AWS Services"
date = 2024
weight = 1
chapter = false
+++

# Tích hợp Docker Swarm với AWS Services

#### Tổng quan
Trong Workshop này, mình sẽ trình bày quy trình triển khai và làm việc với **Docker**, một công cụ mạnh mẽ để quản lý và vận hành Container. Để điều phối và quản lý các container hiệu quả, mình đã sử dụng **Docker Swarm** – một giải pháp tích hợp sẵn của Docker. Bên cạnh đó, mình cũng tận dụng một số dịch vụ trên **AWS** để tối ưu hóa quá trình triển khai và quản lý hệ thống trên nền tảng Cloud, giúp nâng cao tính linh hoạt và khả năng mở rộng của ứng dụng.

#### Kiến trúc

![Architecture](/images/1-Introduce/Architecture-img.png?width=90pc)

#### Quy trình triển khai:
Clone Repository từ GitHub -> Khởi tạo EC2 Instance -> Khởi tạo EC2 Instance -> Tạo Dockerfile -> Tạo Dockerfile -> Tạo Dockerfile -> Docker Compose -> Triển khai dịch vụ -> Docker Swarm Cluster.

#### Nội dung chính

1. [Giới thiệu](1-create-new-aws-account/)
2. [Chuẩn bị](2-mfa-setup-for-aws-user-(root)/)
3. [RDS (Cơ sở dữ liệu)](3-create-admin-user-and-group/)
4. [Elastic Container Registry (ECR)](4-verify-new-account/)
5. [Docker Swarm](4-verify-new-account/)
6. [Docker Compose](4-verify-new-account/)
7. [Xử lý sự cố](4-verify-new-account/)
8. [Dọn dẹp tài nguyên](4-verify-new-account/)