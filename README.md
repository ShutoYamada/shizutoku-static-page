# shizutoku-static-page

## 概要

このプロジェクトは、`shizutoku.com` ドメインの静的 Web ページです。以前運営していたサービスは終了しましたが、ドメインの人気性を考慮し、引き続き確保・管理しています。

## 目的

- 終了したサービスのドメイン `shizutoku.com` を引き続き確保
- ドメイン利用希望者への連絡先情報の提供
- プロフェッショナルで美しいデザインの静的ページの公開

## 連絡先

ドメインの利用をご希望の方は、X（旧 Twitter）の [@pyoncoin](https://x.com/pyoncoin) までお問い合わせください。

## ファイル構成

```
shizutoku-static-page/
├── index.html      # メインHTMLファイル
├── styles.css      # スタイルシート
└── README.md       # このファイル
```

## 特徴

- **モダンなデザイン**: グラデーション、アニメーション、グラスモーフィズム効果を使用
- **レスポンシブ対応**: モバイル、タブレット、デスクトップに最適化
- **ダークテーマ**: 目に優しいダークカラースキーム
- **アニメーション**: 浮遊効果、フェードイン、ホバーエフェクトなど
- **アクセシビリティ**: セマンティック HTML、適切なコントラスト比

## デプロイ方法

### GitHub Pages

1. GitHub リポジトリの Settings > Pages に移動
2. Source を `main` ブランチに設定
3. 自動的にデプロイされます

### Netlify

1. Netlify にログイン
2. "New site from Git" を選択
3. リポジトリを接続
4. Publish directory は空欄のまま
5. Deploy を実行

### Vercel

```bash
npm install -g vercel
vercel --prod
```

### カスタムドメイン設定

デプロイ後、各サービスの設定画面でカスタムドメイン `shizutoku.com` を設定してください。

## ローカルでの確認

シンプルな HTTP サーバーで確認できます：

```bash
# Python 3の場合
python3 -m http.server 8000

# Node.jsの場合
npx serve
```

ブラウザで `http://localhost:8000` にアクセスしてください。

## ライセンス

© 2026 shizutoku.com. All rights reserved.
