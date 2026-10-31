# 常州超晟捷激光科技有限公司 · 正式发布版

站点目标域名：https://csjlaser.cn/（需完成 DNS 解析、部署与 HTTPS 配置后才能实际访问）

## GitHub Pages 发布
上传本文件夹 **内部** 的所有文件到 main 根目录，在 Settings → Pages 中选择 main/(root)。根目录包含 CNAME，配置 `csjlaser.cn` 域名时需在域名 DNS 管理平台按 GitHub 官方 Pages 文档添加根域名 A/AAAA 记录，并在 Settings → Pages 核验 HTTPS。若最终采用腾讯云/阿里云静态托管，仍可使用相同静态文件，按照服务商要求解析域名并配置 HTTPS；与 GitHub Pages 的 DNS 解析方案不要同时冲突。

## 页面更新
- 首页 index.html；产品目录 products.html；15 个产品详情 product/；其他页面 detail/
- 展示用单设备裁切图 static/img/products/，来自企业手册截图；完整产品参数图 static/img/pdf_manual/，详情页按需加载
- Logo static/img/company-logo.webp 和 company-symbol.webp，从用户提供的企业 PDF 截取加工，非生成
- 修改站点内容后提交 GitHub 并完成 Pages 部署即可更新网址所显示内容。
- qr.png 当前编码 https://csjlaser.cn/；域名尚未上线前二维码无法保证可访问。
