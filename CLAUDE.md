# CLAUDE.md

このファイルは、このリポジトリでコードを扱う際の Claude Code (claude.ai/code) へのガイダンスを提供します。

## リポジトリ概要

このリポジトリは nw-union 組織の GitHub 関連ファイルと組織共有の Reusable Workflows を管理しています。組織内の各リポジトリで共通して使用される GitHub Actions ワークフローやテンプレートを一元管理することで、メンテナンスの効率化と一貫性の確保を実現しています。

## Communication Rules

- すべての応答は日本語で行うこと
- コードやコマンドは英語のままで構わないが、説明は日本語で行うこと

## Git Commit Rules

- すべてのコミットメッセージは日本語で記述すること
- コミットメッセージは Conventional Commits に従うこと

## Pull Request Rules

- PR を作成する際は、.github/pull_request_template.md のテンプレートに従うこと
- すべてのセクションを適切に記入すること

## ディレクトリ構造

```
.github/
├── workflows/        # Reusable Workflows と組織共通のワークフロー
├── dependabot.yml    # Dependabot の設定ファイル
└── pull_request_template.md  # PR テンプレート
```

## ワークフローに関する情報

### Reusable Workflows
- 組織内の他のリポジトリから呼び出し可能な共通ワークフローを定義
- ワークフローファイルは `.github/workflows/` ディレクトリに配置
- 新しいワークフローを追加する際は、再利用性と汎用性を考慮すること

### ワークフローの命名規則
- 目的が明確にわかる名前を使用（例: `deploy_workers_with_bun.yml`, `code_analysis.yml`）
- Reusable Workflow は用途に応じた説明的な名前にすること
