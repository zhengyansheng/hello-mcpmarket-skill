# hello-mcpmarket-skill

MCP Market 投稿验证用的最小 Agent Skill（仅含 `SKILL.md`）。

## 推到 GitHub

在空仓库根目录放本目录文件后推送，例如：

```bash
# 在 GitHub 新建空仓库后：
cd /path/to/your/hello-mcpmarket-skill
git init
git add SKILL.md README.md
git commit -m "Add hello-mcpmarket-skill for submit flow test"
git branch -M main
git remote add origin https://github.com/<你的用户名>/<仓库名>.git
git push -u origin main
```

## 在门户提交

1. 登录 MCP Market → **提交** → **Agent 技能**
2. 填技能直链，例如：`https://github.com/<你的用户名>/<仓库名>`
3. 点 **提交审核**，到管理后台把该条从待审改为发布即可

仓库根目录或子目录含 `SKILL.md` 均可；投稿时建议填**技能所在目录**的直链（若 skill 在子目录）。
