# 曹雨萱个人作品集

这是一个 Vite + React 静态个人作品集网站。

## 免费 GitHub Pages 部署

1. 登录 GitHub。
2. 新建一个公开仓库，仓库名建议使用：

   ```text
   你的GitHub用户名.github.io
   ```

   例如 GitHub 用户名是 `abc123`，仓库名就填 `abc123.github.io`。

3. 上传本项目里的所有文件，但不要上传 `node_modules`、`dist`、`.env.local`。
4. 进入仓库 `Settings` -> `Pages`。
5. 在 `Build and deployment` 里选择 `GitHub Actions`。
6. 等待 `Actions` 跑完，网站地址就是：

   ```text
   https://你的GitHub用户名.github.io/#profile
   ```

## 构建命令

```bash
pnpm install --frozen-lockfile
pnpm run build
```

## 国内访问说明

GitHub Pages 是免费的，但国内访问不稳定，部分网络可能仍然需要梯子。

如果目标是国内网络稳定打开，建议使用腾讯 EdgeOne Pages、阿里云 OSS + CDN、腾讯云 COS + CDN 等国内或带中国节点的静态网站托管/CDN 服务。
