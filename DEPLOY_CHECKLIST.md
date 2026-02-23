# 上线检查清单（Global Dynasties）

## 1. 署名与法务
- [x] `attribution.html` 已写入真实信息：
  - 项目名：`Global Dynasties`
  - 署名主体：`ACMFC_WEB / Dankin`
  - 联系邮箱：`contact@acmfc.fr`
- [x] 版权策略已明确：
  - 当前：`© 2026 ACMFC_WEB / Dankin. All rights reserved.`
  - 如需开源，请改写 `LICENSE`（例如 MIT/Apache-2.0）
- [ ] 核对 `sources.html` 的来源链接是否完整且可访问

## 2. 域名与 SEO
- [x] `robots.txt` 与 `sitemap.xml` 已配置为：`https://gd.acmfc.fr`
- [ ] 若使用自定义域名，确认 DNS 指向 Vercel 项目

## 3. 安全与隐私
- [ ] 根据实际情况完善 `privacy.html`（如果接入分析/日志）
- [ ] 根据实际许可补充 `terms.html`

## 4. 发布前功能回归
- [ ] 三语言切换正常
- [ ] 国家列显示/隐藏正常
- [ ] 抽屉“同期其他地区”分组显示正常（洲 -> 国家 -> 政权）
- [ ] 在 Chrome 和 Safari 强制刷新后都能正常加载

## 5. Vercel 发布
- [ ] 预览部署成功
- [ ] 预览链接验证完成
- [ ] 需要生产发布时再执行 `--prod`
