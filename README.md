# BoltSite - 高性能ホームページ制作サービス

BoltSite by Cor.Incは、Jamstack技術を活用した高性能ホームページ制作サービスです。0.3秒の高速表示とSEO満点を実現し、中小企業のDXを加速します。

## 🚀 特徴

- **高速表示**: 0.3秒の爆速表示を実現
- **SEO最適化**: Google PageSpeed 95点以上を保証
- **セキュリティ**: Firebase Hosting + Cloudflare CDNで完全防御
- **コスト効率**: 月額15,000円〜の低コスト
- **初期費用0円**: リスクなしでスタート可能

## 🛠️ 技術スタック

- **フレームワーク**: Astro 5.0.9
- **スタイリング**: Tailwind CSS 3.4.3
- **型安全性**: TypeScript 5.4.5
- **デプロイ**: Vercel
- **アニメーション**: Lenis (スムーススクロール)
- **スライダー**: Swiper 11.1.3

## 📁 プロジェクト構造

```
src/
├── components/          # 再利用可能なコンポーネント
│   ├── ui/             # UIコンポーネント
│   │   ├── Button.astro
│   │   ├── Card.astro
│   │   ├── Navbar.astro
│   │   └── ...
│   ├── sections/       # ページセクション
│   │   ├── BoltHero.astro
│   │   ├── PricingPlans.astro
│   │   └── ...
│   └── seo/           # SEO関連コンポーネント
├── data/              # データファイル
│   ├── siteData.json
│   ├── priceData.json
│   └── clientData.json
├── layouts/           # レイアウトコンポーネント
├── pages/            # ページファイル
├── styles/           # スタイルファイル
├── types/            # TypeScript型定義
└── utils/            # ユーティリティ関数
```

## 🎨 デザインシステム

### カラーパレット

- **Primary**: Blue (#3b82f6)
- **Secondary**: Green (#10b981)
- **Accent**: Purple (#8b5cf6)
- **Neutral**: Gray scale

### コンポーネント

- **Button**: Primary, Secondary, Tertiary variants
- **Card**: Standard, Featured variants
- **Typography**: Heading 1-3, Body, Caption

## 🚀 開発環境のセットアップ

1. **リポジトリのクローン**

   ```bash
   git clone https://github.com/your-username/BoltSite.git
   cd BoltSite
   ```

2. **依存関係のインストール**

   ```bash
   npm install
   ```

3. **開発サーバーの起動**

   ```bash
   npm run dev
   ```

4. **ブラウザで確認**
   ```
   http://localhost:4321
   ```

## 📦 利用可能なスクリプト

### 開発コマンド

- `npm run dev` - 開発サーバーを起動 (http://localhost:4321)
- `npm run build` - 型チェック後、本番用ビルド
- `npm run preview` - ビルド結果のプレビュー
- `npm run astro` - Astro CLIコマンド

### コード品質チェック

- `npm run format` - Prettierでコードフォーマット
- `npm run format:check` - フォーマットチェックのみ
- `npm run lint` - ESLintでコード検査
- `npm run lint:fix` - ESLint問題を自動修正
- `npm run type-check` - TypeScript型チェック
- `npm run check` - Astro固有のチェック
- `npm run check:watch` - チェックをウォッチモードで実行

### メンテナンス

- `npm run clean` - ビルド成果物とキャッシュを削除
- `npm run analyze` - バンドルサイズを分析

## 🔧 設定ファイル

- `astro.config.mjs` - Astro設定
- `tailwind.config.mjs` - Tailwind CSS設定
- `tsconfig.json` - TypeScript設定

## 📊 パフォーマンス

- **Lighthouse Score**: Performance 98, Accessibility 99, Best Practices 100, SEO 100
- **Core Web Vitals**: LCP < 0.3s, FID < 100ms, CLS < 0.1
- **Bundle Size**: 最小限に最適化

## 🎯 SEO最適化

- 構造化データ（JSON-LD）の実装
- メタタグの最適化
- サイトマップの自動生成
- パンくずリストの実装
- Open Graphタグの自動生成
- Twitter Cardの対応
- robots.txtの最適化
- 正規URLの設定

## ♿ アクセシビリティ

- WCAG 2.1 AA準拠
- キーボードナビゲーション対応
- スクリーンリーダー対応
- 適切なARIA属性の実装

## 📱 レスポンシブデザイン

- Mobile First アプローチ
- ブレークポイント: sm(640px), md(768px), lg(1024px), xl(1280px)
- タッチデバイス対応

## 🔒 セキュリティ

- HTTPS強制
- CSP（Content Security Policy）の実装
- XSS対策
- CSRF対策

## 📈 分析・監視

- Google Analytics 4対応
- Core Web Vitals監視
- エラー追跡
- パフォーマンス監視

## 🤝 コントリビューション

### 開発フロー

1. このリポジトリをフォーク
2. フィーチャーブランチを作成 (`git checkout -b feature/amazing-feature`)
3. 開発を行い、コードを変更
4. コード品質チェックを実行:
   ```bash
   npm run format
   npm run lint:fix
   npm run type-check
   npm run build
   ```
5. 変更をコミット (`git commit -m 'Add some amazing feature'`)
6. ブランチにプッシュ (`git push origin feature/amazing-feature`)
7. プルリクエストを作成

### コーディング規約

- TypeScript: 厳格な型付けを使用
- Astro: コンポーネントベースの開発
- Tailwind CSS: ユーティリティファーストのアプローチ
- コミットメッセージ: [Conventional Commits](https://www.conventionalcommits.org/)に従う

## 📄 ライセンス

このプロジェクトはMITライセンスの下で公開されています。詳細は[LICENSE](LICENSE)ファイルを参照してください。

## 📞 サポート

- **Email**: company@cor-jp.com
- **Phone**: +81-070-8561-1659
- **Website**: https://cor-jp.com

## 🙏 謝辞

- [Astro](https://astro.build/) - 素晴らしいフレームワーク
- [Tailwind CSS](https://tailwindcss.com/) - ユーティリティファーストCSS
- [Vercel](https://vercel.com/) - デプロイメントプラットフォーム

---

**BoltSite by Cor.Inc** - 速さ・品質・コストで成長を加速
