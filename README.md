# 康康个人工具 - 管理后台

纯静态前端，调用 [baoming-server](https://github.com/ckd919/baoming-server) API。

## 部署

直接打开 `index.html`，或用 nginx 托管：

```nginx
server {
    listen 80;
    server_name admin.ledbell.cn;
    root /opt/baoming-web;
    index index.html;
}
```

## 数据来源

所有数据来自 `https://ledbell.cn/api/admin/*`，由 baoming-server 提供。
