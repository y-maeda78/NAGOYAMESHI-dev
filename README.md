# NAGOYAMESHI（なごやめし）

### 名古屋のB級グルメを紹介している飲食店検索プラットフォーム
公開中URL：
https://nagoyameshi-app-v1-251b66a50825.herokuapp.com/

---

## 概要
NAGOYAMESHIは、名古屋市内の飲食店を検索・予約できるポータルサイトです。
店舗検索をはじめ、有料会員限定で予約、お気に入り登録、レビュー投稿が行えます。

## 主な機能
- **店舗検索機能**:
  - カテゴリやキーワードによる店舗検索と、エリアによる絞り込みが可能
- **お気に入り機能（有料会員限定）**:
  - 気に入ったお店を保存し一覧表示できる機能
- **予約システム（有料会員限定）**:
  - 日時や人数を指定して、飲食店を予約できる機能
- **サブスクリプション決済**:
  - `Stripe API` を利用した有料会員登録（サブスク）機能。会員限定のレビュー投稿や予約権限を管理
- **クラウド画像管理**:
  - `Cloudinary` を活用し、店舗写真を管理
- **管理者ダッシュボード**:
  - 会員数や売上集計を一元管理。Django管理画面へのアクセスが可能。

## 使用技術
- **Backend**: Python 3.10 / Django 4.0
- **Database**: MySQL
- **Frontend**: HTML5 / CSS3 / Bootstrap 5 / JavaScript
- **Infrastructure**: Heroku / Cloudinary (Image Hosting)
- **Payment**: Stripe API (Subscription Model)

