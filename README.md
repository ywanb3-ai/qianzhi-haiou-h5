# 千智海欧（青岛）人工智能科技有限公司 · H5 官网

移动端优先的单页官网，部署于 GitHub Pages。设计语言参考「克制高级感」排版体系：中性纸感底 + 双点缀（海蓝 / 智金），无渐变、无阴影、无花哨图标。

## 目录结构

```
qianzhi-haiou-h5/
├── index.html            # 主页面（含 Organization JSON-LD 结构化数据）
├── assets/
│   ├── css/style.css     # 样式
│   └── img/              # logo（long / square）
└── .nojekyll
```

## 部署

仓库根目录即站点根，推送到 `main` 分支后，在仓库 **Settings → Pages** 选择 `main` 分支 `/ (root)` 启用。

## 上线前需替换的占位

- `index.html` 中 `contact@qianzhihaio.com`（商务邮箱占位）
- JSON-LD 中的 `url` 占位 `https://example.com/...`
- 如需正式电话，补充至「联系我们」区块

## 内容来源

公司名称、统一社会信用代码、法定代表人、成立日期、住所、经营范围等工商信息，提取自 `company-info/` 下的营业执照 OCR（见 `company-info/千智海欧-工商信息.md`）。
