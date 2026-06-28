# {{ Service Name }}

# Overview

## What is this service?

<!--
このサービスを一言で説明してください。

例：
「Amazon S3はAWSのオブジェクトストレージサービスです。」
-->

---

## What problem does it solve?

<!--
このサービスが解決する課題を書きます。

例：
・大量のファイルを保存したい
・高耐久なストレージが欲しい
・バックアップを保存したい
-->

---

## When should I use it?

<!--
どんなシステム・要件で利用するかを書きます。

例：
・画像保存
・ログ保存
・静的Webサイト
・データレイク
-->

---

## Similar Services

<!--
似たサービスと違いを書きます。

例：

S3
→ オブジェクトストレージ

EFS
→ ファイルストレージ

EBS
→ ブロックストレージ
-->

---

# Core Concepts

<!--
このサービスを理解する上で重要な概念を書きます。

例(S3)

・Bucket
・Object
・Versioning
・Lifecycle
・Storage Class
-->

*
*
*

---

# Pricing

## Pricing Model

<!--
何に対して料金が発生するかを書きます。

例：
・保存容量
・リクエスト数
・データ転送量
-->

---

## Free Tier

<!--
無料利用枠を書きます。
-->

---

## Cost Considerations

<!--
料金が高くなりやすいポイントを書きます。
-->

---

# Hands-on Checklist

## Console

<!--
AWS Consoleで実際に試した操作をチェックします。
-->

* [ ] サービスを開く
* [ ] リソースを作成する
* [ ] 設定を変更する
* [ ] 削除する

---

## AWS CLI

<!--
CLIで一通り操作できることを確認します。
-->

* [ ] 一覧取得
* [ ] 作成
* [ ] 更新
* [ ] 削除

---

## SDK

<!--
SDKから操作できることを確認します。
-->

* [ ] Python (boto3)
* [ ] TypeScript
* [ ] Go（必要であれば）

---

## Infrastructure as Code

### Terraform

<!--
Terraformで同じ構成を作れるか確認します。
-->

* [ ] 作成

---

### AWS CDK

<!--
CDKでも作れるか確認します。
-->

* [ ] 作成

---

# CLI Commands

<!--
よく使うCLIコマンドを記録します。
-->

```bash
```

---

# SDK Sample

## Python

<!--
最低限のサンプルコードを書きます。
-->

```python
```

---

## TypeScript

<!--
最低限のサンプルコードを書きます。
-->

```typescript
```

---

# Terraform

<!--
Terraformコードを書きます。
-->

```hcl
```

---

# AWS CDK

<!--
CDKコードを書きます。
-->

```typescript
```

---

# IAM Permissions

## Required Actions

<!--
必要なIAM Actionを書きます。

例：
s3:GetObject
s3:PutObject
-->

```text
```

---

## Managed Policies

<!--
利用できるAWS管理ポリシーを書きます。
-->

*

---

# Integrations

## Common Integrations

<!--
一緒によく利用するAWSサービスを書きます。

例：
CloudFront
Lambda
EventBridge
Athena
-->

*

*

*

---

## Typical Architecture

<!--
どんな構成で利用するかを書きます。
-->

```text
```

---

# Limits

<!--
サービスの制限事項を書きます。

例：
・最大サイズ
・最大数
・リージョン制限
-->

| Item | Value |
| ---- | ----- |
|      |       |

---

# Monitoring

## CloudWatch Metrics

<!--
確認するメトリクスを書きます。
-->

---

## CloudWatch Logs

<!--
確認するログを書きます。
-->

---

## CloudTrail Events

<!--
確認するイベントを書きます。
-->

---

# Security

<!--
セキュリティで意識するポイントを書きます。

例：
・IAM
・KMS
・Encryption
・VPC Endpoint
-->

*

*

*

---

# Best Practices

<!--
AWS公式や実務で推奨される運用を書きます。
-->

*

*

*

---

# Common Pitfalls

<!--
初心者がハマりやすいポイントを書きます。

例：
・権限不足
・料金爆発
・設定ミス
-->

*

*

*

---

# Troubleshooting

<!--
遭遇したエラーと解決方法を書きます。
-->

## Problem

<!-- エラー内容 -->

## Cause

<!-- 原因 -->

## Solution

<!-- 解決方法 -->

---

# Useful Links

<!--
よく使うリンクを書きます。

・公式ドキュメント
・料金ページ
・Workshop
・ブログ
-->

*

*

*

---

# Notes

<!--
自由メモを書きます。
-->

---

# Learning Memo

<!--
学習して理解したこと・気づいたことを書きます。
-->

---

# Completion Checklist

## Understanding

<!--
サービスの役割・料金・制約を説明できるか確認します。
-->

* [ ] サービスの目的を説明できる
* [ ] 料金体系を理解した
* [ ] 制約を理解した

---

## Hands-on

<!--
実際に操作できるか確認します。
-->

* [ ] Console
* [ ] AWS CLI
* [ ] SDK
* [ ] Terraform
* [ ] AWS CDK

---

## Integration

<!--
他サービスと組み合わせて利用できるか確認します。
-->

* [ ] 他サービスと連携した
* [ ] 小規模なハンズオンを作成した

---

## Real-world

<!--
実務レベルで利用イメージを持てるか確認します。
-->

* [ ] 実際の利用シーンを理解した
* [ ] ベストプラクティスを理解した
* [ ] 運用時の注意点を理解した
