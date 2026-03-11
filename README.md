# 01MVP Skills

这个仓库用于存放可复用的 AI skills。

## Skills

- `skills/cloudflare-redirector`: Cloudflare Workers 批量重定向技能（包含完整实现：Worker 源码、规则数据、部署配置、脚本与参考文档）

## 目录约定

每个技能使用以下结构：

- `skills/<skill-name>/SKILL.md`
- `skills/<skill-name>/scripts/*`
- `skills/<skill-name>/references/*`（可选）
- `skills/<skill-name>/assets/*`（可选）
- 其他该技能需要的实现文件（如 `src/`, `data/`, `wrangler.jsonc`, `package.json`）
