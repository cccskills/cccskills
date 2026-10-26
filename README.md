### cccskills — 日本語で探せる Agent Skills マーケット

[cccskills.com](https://cccskills.com) は、Claude Code や Codex に入れる Agent Skills を日本語で探せるサイトです。GitHub で公開されているスキルを集め、スキルを入れた場合と入れない場合で同じ依頼を実際に実行させて比べた**実行スコア**と、SKILL.md の中身から判定した**安全面**で選べるようにしています。

A Japanese-first marketplace for Agent Skills. Skills are compared by execution scores (running the same task with and without the skill) and safety checks, not by stars.

#### 作っているスキル

| スキル | できること |
| --- | --- |
| [skill-md-review](https://github.com/cccskills/skills/tree/main/skills/skill-md-review) | SKILL.md を 4 項目で A/B/C 採点し、直し方を出す |
| [cccskills-find](https://github.com/cccskills/skills/tree/main/skills/cccskills-find) | やりたい作業に合うスキルを探して比べ、入れるコマンドまで案内する |
| [jp-business-mail](https://github.com/cccskills/skills/tree/main/skills/jp-business-mail) | 日本語のビジネスメールを書く・直す。敬語の誤りを直した理由も示す |

```bash
npx skills add https://github.com/cccskills/skills --skill cccskills-find
```

#### リンク

[スキルを探す](https://cccskills.com) · [評価の基準](https://cccskills.com/evaluation) · [API・MCP](https://cccskills.com/developers) · [読みもの](https://cccskills.com/media) · [MiraiPage](https://www.miraipage.net/cccskills)
