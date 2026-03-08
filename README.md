# いつやったっケア

**「最後にいつやったっけ？」を解決する打刻記録アプリ**

🕐 [アプリを開く](https://stillnova-studio.github.io/itsuyattacare/)

---

## 概要

白髪染め、フィルター掃除、水やり、水換え——定期的にやるけど頻度が一定じゃない作業の「前回いつやったか」を、タップするだけで記録できるWebアプリです。

通知もリマインダーもありません。アプリを開いて、前回の記録を見て、自分で判断する。それだけのシンプルなアプリです。

---

## 特徴

- **タップで即打刻** — ボタンひとつで記録完了
- **経過時間を自然な言葉で表示** — 「3週間前」「2ヶ月前」など
- **通知ゼロ** — リマインダーに追われない
- **データは端末の中だけ** — サーバー送信なし・アカウント不要
- **ブラウザだけで使える** — インストール不要
- **バックアップ機能** — JSONファイルで保存・復元対応

---

## 使い方

1. [アプリを開く](https://stillnova-studio.github.io/itsuyattacare/)
2. 項目を登録する（絵文字アイコン付き）
3. やったら「✓」をタップ

Safariで「共有」→「ホーム画面に追加」でアプリのように使えます。

---

## 技術仕様

| 項目 | 内容 |
|------|------|
| 構成 | 単一HTMLファイル |
| データ保存 | IndexedDB（端末内のみ） |
| 外部依存 | Google Fonts（Noto Sans JP）のみ |
| フレームワーク | なし（Vanilla JS） |

---

## ファイル構成

```
itsuyattacare/
├── index.html           # アプリ本体
├── privacy-policy.html  # プライバシーポリシー・利用規約
└── README.md            # このファイル
```

---

## Stillnova Studio

静かに使えるシンプルな記録ツールを作っています。

- [てまひまケア](https://stillnova-studio.github.io/temahima-care/) — 植物ケア記録
- [てまひまアクア](https://stillnova-studio.github.io/temahima-aqua/) — 水槽・メダカ管理
- [いつやったっケア](https://stillnova-studio.github.io/itsuyattacare/) — 日常の打刻記録
- [note](https://note.com/stillnova_studio)

---

## ライセンス

© Stillnova Studio. All rights reserved.  
個人利用の範囲でのカスタマイズは自由に行っていただけます。  
ソースコードを改変して自身の制作物として再配布することはお控えください。
