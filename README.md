# tf-ci-cd-pipeline

Terraform のコード品質を自動担保するための CI/CD パイプライン

## CI/CD Status
[![Terraform Quality Check](https://github.com/codes-sandbox/tf-ci-cd-pipeline/actions/workflows/terraform-validate.yml/badge.svg)](https://github.com/codes-sandbox/tf-ci-cd-pipeline/actions/workflows/terraform-validate.yml)

## 概要
GitHub Actions を使用しpush 時に以下の検証を自動実行
- `terraform init`: 構成の初期化確認
- `terraform validate`: 構文の正当性チェック

## 利用方法
このリポジトリの `.github/workflows/` 配下をコピーすることで他のTerraformリポジトリにも簡単にCI/CDを導入可能