# EMrel

## 概要
電磁相対論に関するプロジェクト。

## リポジトリ情報
- パス: `~/Claude/EMrel/`
- ブランチ: `main`
- リモート: `odakin/EMrel` (public, GitHub)

## 構造
```
EMrel/
├── CLAUDE.md
├── SESSION.md
└── README.md
```

## 実行環境
- 未定

## How to Resume（autocompact 復帰手順）
**autocompact 後・新規セッション開始時、必ずこの手順を実行:**
1. `SESSION.md` を読む → 現在の作業状態と次のステップを把握
2. SESSION.md の「次のステップ」に従って作業を継続
3. 不明点があればユーザーに確認

## 自動更新ルール（必須）
以下を人間に言われなくても自動で行う:
- タスク完了時 → SESSION.md のその案件の現在地の行を置き換える (成果物は git log と正本が持つ)
- 重要な判断時 → DESIGN.md に判断と理由を記録し、 SESSION.md は現在地の行を置き換える
- ファイル作成/大幅変更時 → CLAUDE.md の構造を直す (SESSION.md には経緯を書かない = CONVENTIONS.md#session-no-durable-record)
- CLAUDE.md のルールの詳細は `~/Claude/CONVENTIONS.md` 参照
