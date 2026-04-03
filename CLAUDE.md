# Writing Agent Project

SEO特化型ライティングエージェントシステム。プロのライティング手法とSEOベストプラクティスを組み合わせ、検索上位に表示され、かつ読者に価値を提供する記事を生成する。

## プロジェクト構造

```
Writing/
├── CLAUDE.md              # プロジェクト設定
├── agents/
│   ├── writing-agent.md   # メインライティングエージェント
│   └── seo-analyzer.md    # SEO分析エージェント
├── templates/
│   ├── blog-post.md       # ブログ記事テンプレート
│   ├── how-to-guide.md    # ハウツー記事テンプレート
│   ├── listicle.md        # リスト記事テンプレート
│   └── pillar-content.md  # ピラーコンテンツテンプレート
└── guides/
    └── workflow.md         # ワークフローガイド
```

## 使い方

1. `agents/writing-agent.md` をClaude Codeのカスタムエージェントとして読み込む
2. キーワードとトピックを指定して記事生成を依頼
3. SEO分析エージェントで品質チェック
