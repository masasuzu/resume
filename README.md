# 職務経歴

## 基本情報

- twitter: [@masasuz](https://twitter.com/masasuz)
- LinkedIn: https://www.linkedin.com/in/suzuki-masashi
- blog:
  - main(まとまった記事): http://masasuzu.hatenablog.jp/
  - sub(日記、雑記、メモ): http://masasuzu.hatenadiary.jp/
- github: https://github.com/masasuzu/
- CPAN: https://metacpan.org/author/MASASUZU
- Speaker Deck: https://speakerdeck.com/masasuzu
- Slide(古いもの): https://masasuzu.net/slide/
- credly https://www.credly.com/users/masasuzu/badges

## 保持技術

- 基本的なネットワーク知識
- AWSを使ったインフラ構築/運用
  - ECS Fargate
  - RDS/Aurora
  - terraform
- Google Cloudを使ったインフラ構築/運用
  - Cloud Run
  - Cloud SQL
- CI/CDの整備
  - GitHub Acions
  - GitLab CI/CD
- webシステムのインフラ構築/運用
  - Linux OS(主にDebian系)の運用
  - MySQL
  - Ansible
- シェルスクリプト/Perlによるツール作成

#### 保持しているがここ数年使ってないもの

- 基本的なネットワーク機器の操作
  - Cisco IOS
  - Juniper Junos
- webアプリケーション開発(Perl)

## 主な保持資格

全資格は[保持資格](./certifications.md)を参照。

| 年月 |資格 |
|:---------|:--------|
| 2021/09 | AWS Certified Solutions Architect - Professional |
| 2021/11 | AWS Certified DevOps Engineer - Professional |
| 2022/10 | Google Cloud Certified - Professional Cloud Architect |
| 2022/11 | Google Cloud Certified - Professional Cloud Developer |

その他 https://www.credly.com/users/masasuzu 参照

## 表彰
| 年月 | 表彰 |
|:---------|:--------|
| 2024/03 | AWS Community Builder 2024 Cloud Operations |
| 2025/05 | AWS Community Builder 2025 Cloud Operations |
| 2025/06 | 2025 Japan All AWS Certifications Engineers |
| 2025/11 | Google Cloud Partner Top Engineer 2026 |

## 学歴/職歴

| 年月    |        |
|:--------|:-------|
| 2003/04 | 私立明治大学 文学部史学地理学科 西洋史専攻 入学 |
| 2007/03 | 私立明治大学 文学部史学地理学科 西洋史専攻 卒業 |
| 2007/04 | 株式会社情報工房 入社 |
| 2010/05 | 株式会社情報工房 退社 |
| 2010/06 | 株式会社モバイルファクトリー 入社 |
| 2020/03 | 株式会社モバイルファクトリー 退職 |
| 2020/04 | 弁護士ドットコム株式会社 入社 |
| 2022/04 | 弁護士ドットコム株式会社 退職 |
| 2022/05 | 株式会社スリーシェイク 入社 |

## 職務経歴

### 株式会社スリーシェイク(2022/05-現在)

主に他社のインフラ改善や構築支援、SRE導入支援などを行う。

支援内容はクライアントに依存し、外部からインフラの設計、構築、運用支援のコンサルティング、アセスメント、ドキュメントレビューや技術QA対応などを行う。また、内部からインフラチームの一員としてインフラ運用のモダナイズ、内製化支援、スキルトランスファー等を行う。

- AWS上での機械学習基盤の設計構築支援
  - 設計支援
  - 構築支援
    - Terraform導入支援
    - CI/CD整備
- AWSにおけるOrganization統合支援
  - 技術QA支援
    - Control Tower
    - Security Hub
    - Config 
- オンプレミスに構築されたウェブサービスの基盤をCloud Runへ移行する支援
- AWSにおける複数アカウント管理の基盤整備、Control Towerの導入
    - IAM Userでのアカウント管理からIAM Identity Centerによる複数アカウントの統一的にID管理の導入
    - [GNUS様の管理するAWS環境に対して、アカウント管理のベストプラクティスを整備・適用し、運用負荷の低減を実現 | sreake.com | 株式会社スリーシェイク](https://sreake.com/case/gnus/)
- AWS上に構築した金融機関向けのCRMシステムの共通基盤の移行支援
    - 設計アセスメント
    - Control Tower導入の支援
    - CI/CDの改善支援
    - 各種QA対応
    - [【株式会社インテック様】インフラのIaC化と、シンプルな構成の追求により、運用コストとヒューマンエラーの削減を実現 | sreake.com | 株式会社スリーシェイク](https://sreake.com/case/intec/)

### 弁護士ドットコム株式会社(2020/04-2022/04)

主に契約締結サービスの運用および運用基盤整備を行う。

- 運用作業及び運用改善
  - terraformによるAWSリソースの管理
  - AnsibleによるEC2インスタンス構成管理
  - Datadogによる監視
  - Amazon Elasticsearch VPC移行
  - 各種ミドルウェアアップデート
- etc...


### 株式会社モバイルファクトリー(2010/06-2020/03)

主にソーシャルアプリケションの開発/運用および社内の開発/運用基盤の整備を行う。

- フィーチャーフォン向けサイトの開発/運用
  - Perl/Apache/mod_perl/Debian/MySQL
- ソーシャルアプリケーションの開発/運用
  - Perl/Apache/mod_perl/Nginx/Debian/Ubuntu/MySQL
  - MySQLチューニングおよびSQLチューニングによる負荷軽減
- 開発/運用基盤整備
  - リバースプロキシのPerlbalからNginxへの移行
  - Fluentd導入
  - Fluentd + Elasticsearchによるログ基盤整備
  - Gitbucket導入
  - プライベートCPAN(Darkpan)の整備
  - アプリケションサーバのApache/mod_perlからPSGI/Plackへの移行
  - 監視基盤の整備
  - アプリケーションパフォーマンスの改善およびプロジェクトチームへの助言
  - デプロイ環境の整備(fabric導入)
  - GitHub.com導入
  - 社内基幹サービスのAWS移管
    - プライベートaptレポジトリ
    - プライベートCPAN(Darkpan)
  - Github Enterprise Server導入
  - CircleCI オンプレミス導入
  - プロジェクトへのCircleCI導入支援

### 株式会社情報工房(2007/04-2010/05)

海外製のネットワークシミュレータの代理店業をしており、業務として主に導入支援や導入後のサポートおよび、シミュレータの拡張開発を行う。

- キャリアネットワーク設計支援ツール開発
  - ネットワークシミュレーションツールの拡張開発
    - C/Python
  - MPLS/OSPF/BGP
- ネットワークシミュレータのカスタマーサポート
  - 英語による開発元への問い合わせ 
- ネットワークシミュレータおよびネットワークデバイスのコンフィグ収集ツール導入支援
- ネットワーク機器のコンフィグ収集ツール開発
  - Perl

## OSS

### Author

- [ WebService::Slack::IncomingWebHook](https://metacpan.org/pod/WebService::Slack::IncomingWebHook)

### Contribute

- [Pithub](https://metacpan.org/release/Pithub)
- [File::RotateLogs](https://metacpan.org/pod/File::RotateLogs)

## コミュニティ活動

- Jagu'e'r クラウドネイティブ分科会 運営

過去の活動は[コミュニティ活動](./community.md)を参照
