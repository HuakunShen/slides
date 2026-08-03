# Deployment

```bash
docker run -p 8090:8090 \
  --network=host \
  -e SUPERUSER_EMAIL=<root@example.com> \
  -e SUPERUSER_PASSWORD=<your password> \
  -v ./pb_data:/app/pb_data \
  huakunshen/wol:latest
```