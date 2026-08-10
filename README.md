# Tabito 旅行达人 · 站点

App Store 提交需要两个可访问的公开页面，这个仓库只放这两页：

- `index.html` —— 支持页（ASC 的 Support URL）
- `privacy.html` —— 隐私政策（ASC 的 Privacy Policy URL）

**内容必须和 App 的实际行为一致。** 这两页说的是「没有服务器、不收集任何数据」，
而这句话由 `PrivacyInfo.xcprivacy`（`NSPrivacyCollectedDataTypes` 为空）和
App 内「我的 → 数据与隐私」那一页共同背书。三处任何一处改了，另外两处必须同时改 ——
只改一个会在审核时露馅，而那是最伤信誉的一种露馅。

源码仓库在别处，这里不含任何 App 代码。
