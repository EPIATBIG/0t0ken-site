# 0t0KEN · One-Link Investor Site

> 🌐 **在线访问 / Live: [0t0ken.com](https://0t0ken.com)**
> 零 token 确定性执行引擎 / Zero-token deterministic execution engine · i4SaaS
> 双语投资人官网（English default · 中文可选）

## 文件结构

| 文件 | 内容 |
|------|------|
| `index.html` | **英文版（默认着陆页）** |
| `zh.html` | 中文版（页首语言按钮互切） |

## 部署到 GitHub Pages（三步）

1. 在 GitHub 新建公开仓库（建议名 `0t0ken-site`），把本文件夹两个 HTML 文件推上去（连同本 README）：
   ```bash
   git init && git add . && git commit -m "0t0KEN One-Link site v1"
   git branch -M main
   git remote add origin https://github.com/<你的用户名>/0t0ken-site.git
   git push -u origin main
   ```
2. 仓库 **Settings → Pages** → Source 选 `main` 分支 `/ (root)` → Save；
3. 约 1 分钟后站点上线：`https://<你的用户名>.github.io/0t0ken-site/`

## 绑定自有域名（可选，推荐）

- 域名已注册：[0t0ken.com](https://0t0ken.com)（2026-08-29）
- 仓库根目录加 `CNAME` 文件（内容一行：`0t0ken.com`）
- 域名 DNS 添加四条 A 记录指向 GitHub Pages：
  `185.199.108.153` / `185.199.109.153` / `185.199.110.153` / `185.199.111.153`
- Settings → Pages → Custom domain 填 `0t0ken.com` → 勾选 Enforce HTTPS

## 国内访问镜像（重要）

GitHub Pages 国内访问不稳定。国内主战场（投资人/客户）同步部署：
- **Vercel**：导入同一仓库，自动获得 `0t0ken-site.vercel.app`，域名 CNAME 可同样绑定（国内可达性较好）
- **Gitee Pages**：仓库镜像到 Gitee（`0t0ken-site`），开通 Gitee Pages（需实名）

## 发布纪律（上线检查单）

- [ ] L-1 切割完成（对外口径合法化——**上线硬前置**）
- [ ] 联系方式就绪：chenfenhua@0t0ken.com 企业邮箱已开通（DNS MX 记录）
- [ ] 内容过发布前十问＋法务门（判例十六：引用运行实录须脱敏版）
- [ ] 页脚"更新日期"与实际发布日一致

## 维护规则

- 内容更新只改 HTML 源 → 一条命令重导 PDF（Edge headless，流程已验证）；
- 中英两版同步修改：任何数字/口径变更，两版一起改（数字永不单边漂移）；
- 数字纪律：所有运行数据带"截至日期"，对外口径以《口径手册》最新版为准（环境定性见 6.10，运行实录脱敏见 6.9）。

---
*0t0KEN · i4SaaS 的定义者与第一个平台 · Chen Fenhua © 2026*
