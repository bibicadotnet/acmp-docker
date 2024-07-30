# Docker ACMP WordPress - Alpine - Caddy - MariaDB - PHP

### Cài đặt:

Trỏ DNS A về IP của VPS (domain.com và www.domain.com)

Tiếp theo chạy:
```
git clone https://github.com/bibicadotnet/acmp-docker-wordpress
cd ./acmp-docker-wordpress
```
Thay đổi domain của bạn bên trong `_config/.env` 
Sau đó chạy
```
docker-compose up -d
```
