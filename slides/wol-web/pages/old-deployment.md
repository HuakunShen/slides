# Old Version Deployment

```bash
PORT=9090
JWT_SECRET=secret
JWT_VALID_TIME=14400

NUM_USER_ALLOWED=1
```

```bash
docker run -d \
  --network=host --name wol-web \
  -v ${PWD}/wol-web-data:/wol-server/data \
  -e PORT=9090 \
  -e JWT_SECRET=wol-secret \
  -e JWT_VALID_TIME=20000 \
  -e NUM_USER_ALLOWED=1 \
  huakunshen/wol:latest
```