### こんにちは 👋

業務システムの開発を、要件定義・設計といった上流工程から実装・インフラ構築・運用まで一気通貫で担当しています。<br>
テックリードとしてチーム(5〜6名)のコードレビュー・技術指導・マネジメントを行っています。2023年には、既存のインフラ資産がない状態から **AWS 上のコンテナ実行基盤(Docker / ECS / Fargate / ECR)を技術選定・設計・構築まで一人で立ち上げ**、以降3年にわたって運用・改善を続けながら、後続の案件でも同じ基盤の上で開発しています。<br>
別の案件では、クライアントへの課題ヒアリング・企画提案から要件定義・プロジェクト推進までを担当しています。

- 🔭 現在: TypeScript / AWS (ECS・Fargate・ECR) / Docker / Python / Java / テックリード / チームマネジメント(5〜6名) / 要件定義・設計 / PM
- 🌱 学習中: Terraform / GitHub Actions / 生成AI活用 / 英語 / アルゴリズム（競プロ）
- 📜 認定: AWS認定ソリューションアーキテクト – アソシエイト (SAA, 2025-06) / 基本情報技術者 (2021-10)
- 🏨 エンジニアになる前: マーケティング / グラフィックデザイン / ドアマン

### 💪 できること

- **上流から運用まで一気通貫** — 現場の課題を起点に企画を立ち上げ、社内稟議・クライアント折衝・要件定義・設計・開発・テスト・リリース・運用までを自ら推進して完遂した経験が複数あります。
- **アプリケーションだけでなくインフラも自分で建てる** — アプリケーションの Docker によるコンテナ化(Dockerfile・コンテナ定義の作成)、Fargate によるサーバーレスなコンテナ実行環境の設計、ECR でのイメージ管理とデプロイ導線の整備までを担当。ローカルと本番を同一のコンテナ定義で揃え、環境差異に起因する不具合を抑えています。建てて終わりではなく、構築した基盤を3年運用し、後続案件の実行基盤として使い続けています。
- **チームの品質とスキルを底上げする** — プルリクエストベースのコードレビューを可読性・保守性・例外処理などの観点で日常的に実施し、自チームに加えて他チームのレビューも担当。設計方針の共有やペア作業を通じた技術指導、1on1によるメンバーの状況把握も行っています。

### 🛠 Tech Stack

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Amazon ECS](https://img.shields.io/badge/-Amazon%20ECS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![AWS Fargate](https://img.shields.io/badge/-AWS%20Fargate-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Amazon ECR](https://img.shields.io/badge/-Amazon%20ECR-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

| カテゴリ | 技術 |
|---|---|
| フロントエンド | TypeScript, React |
| バックエンド | Python (FastAPI, Flask), Java |
| インフラ / クラウド | AWS (ECS / Fargate / ECR によるコンテナ実行基盤を中心に、Lambda ほか), Docker, Terraform |
| DB | MySQL, PostgreSQL (Supabase), OracleDB |
| CI/CD | GitHub Actions |

### 📌 Featured Project

**[AdaptSheet AI](https://github.com/EisukeHishikawa/adapt-sheet)**<br>
エンジニアが保守しやすいHTML/CSS帳票を、AIの力で構築・管理するプラットフォーム。<br>
CI/CD・AWS・Supabase・生成AI・AI駆動開発(Claude Codeとの協働)の技術キャッチアップを目的に作りました。<br>
生成AIの長時間処理に対応するため、S3署名付きURL + 別Lambda起動による非同期処理を設計しています。<br><br>
デプロイ: https://d3lal8vccjsy5y.cloudfront.net/
