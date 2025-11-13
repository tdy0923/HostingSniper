
## 🚀 快速开始

### 1. 修改安全密钥

编辑 `backend/.env` 文件：

```env
API_SECRET_KEY=你的密钥
```

### 2. 启动服务

```bash
docker-compose up -d --build
```

### 3. 访问系统

**入口地址：** http://YOUR_IP:20000

---

## 🔑 首次配置

1. 打开 http://YOUR_IP:20000/settings
2. 填写"网站安全密钥"（与 backend/.env 中的 API_SECRET_KEY 一致）
3. 填写 OVH API 凭据
4. 保存



