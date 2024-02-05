---
markdown:
- image_dir: /assets
- path: README.md
- ignore_from_front_matter: true
- absolute_image_path: false
export_on_save:
- markdown: true
---

[TOC]

# k8sLearning

<div id="top"></div>
<!-- シールド一覧 -->
<p style="display: inline">
<img src="https://img.shields.io/badge/-Kubernetes-326CE5.svg?logo=kubernetes&style=plastic">
</p>

## k8sのリソース

### Workoads API

@import "workloads.md"

### Service API

@import "service.md"

### Config/Storage API

@import "config-storage.md"

### Cluster API

@import "cluster.md"

### Metadata API

@import "metadata.md"

<!--
| 変数名                 | 役割                                      | デフォルト値                       | DEV 環境での値                           |
| ---------------------- | ----------------------------------------- | ---------------------------------- | ---------------------------------------- |
| MYSQL_ROOT_PASSWORD    | MySQL のルートパスワード（Docker で使用） | root                               |                                          |
| MYSQL_DATABASE         | MySQL のデータベース名（Docker で使用）   | django-db                          |                                          |
| MYSQL_USER             | MySQL のユーザ名（Docker で使用）         | django                             |                                          |
| MYSQL_PASSWORD         | MySQL のパスワード（Docker で使用）       | django                             |                                          |
| MYSQL_HOST             | MySQL のホスト名（Docker で使用）         | db                                 |                                          |
| MYSQL_PORT             | MySQL のポート番号（Docker で使用）       | 3306                               |                                          |
| SECRET_KEY             | Django のシークレットキー                 | secretkey                          | 他者に推測されないランダムな値にすること |
| ALLOWED_HOSTS          | リクエストを許可するホスト名              | localhost 127.0.0.1 [::1] back web | フロントのホスト名                       |
| DEBUG                  | デバッグモードの切り替え                  | True                               | False                                    |
| TRUSTED_ORIGINS        | CORS で許可するオリジン                   | http://localhost                   |                                          |
| DJANGO_SETTINGS_MODULE | Django アプリケーションの設定モジュール   | project.settings.local             | project.settings.dev                     |
-->
