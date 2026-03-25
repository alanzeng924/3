# Cloudflare Pages 部署说明

这个仓库现在是纯静态站点，主页文件是 `index.html`（包含三张照片）。

## 部署到 Cloudflare Pages

1. 把这个仓库推到 GitHub。
2. 打开 Cloudflare Dashboard -> `Workers & Pages` -> `Create` -> `Pages`。
3. 选择 `Connect to Git` 并绑定这个仓库。
4. 构建配置填写：
   - Framework preset: `None`
   - Build command: 留空
   - Build output directory: `/`
5. 点击 `Save and Deploy`。

## 自定义域名

- 你仓库里已有 `CNAME`：`xibeiyufei.xiasuming.alanzeng.com`
- 在 Cloudflare Pages 项目里进入 `Custom domains`，添加同一个域名并按提示配置 DNS。
