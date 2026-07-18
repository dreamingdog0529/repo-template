<!-- TEMPLATE:START -->
> ### 📄 これはリポジトリテンプレートです
>
> GitHub のコミュニティヘルスファイル・CI・リリース自動化を同梱し、公開プロジェクトを
> 良い初期設定で始められるようにしたものです。自分のプロジェクトに合わせるには、初期化
> スクリプトを一度実行してください。リポジトリ全体の `{{PLACEHOLDER}}` トークンを置換し、
> このバナーも削除します:
>
> ```powershell
> pwsh ./scripts/init-template.ps1
> ```
>
> 採用手順の全体（メンテナが一度だけ行う GitHub 側設定を含む）は
> [CHECKLIST.md](CHECKLIST.md) を参照してください。スクリプトを使わない場合は、この
> ブロックを手動で削除してください。
<!-- TEMPLATE:END -->

<a id="readme-top"></a>

<div align="center">

[English](./README.md) | 日本語

<!-- TODO: ロゴを追加してコメントを外してください
<img src="assets/logo.png" alt="{{PROJECT_NAME}} logo" width="120" height="120">
-->

<h1>{{PROJECT_NAME}}</h1>

<p><em>{{DESCRIPTION_JA}}</em></p>

[![CI](https://github.com/{{OWNER}}/{{REPO_NAME}}/actions/workflows/ci.yml/badge.svg)](https://github.com/{{OWNER}}/{{REPO_NAME}}/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/{{OWNER}}/{{REPO_NAME}}?include_prereleases&sort=semver)](https://github.com/{{OWNER}}/{{REPO_NAME}}/releases/latest)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/{{OWNER}}/{{REPO_NAME}}/badge)](https://securityscorecards.dev/viewer/?uri=github.com/{{OWNER}}/{{REPO_NAME}})

<p>
  <a href="docs/development.md"><strong>ドキュメントを見る »</strong></a>
  <br /><br />
  <a href="https://github.com/{{OWNER}}/{{REPO_NAME}}/issues/new?template=bug_report.yml">バグ報告</a>
  ·
  <a href="https://github.com/{{OWNER}}/{{REPO_NAME}}/issues/new?template=feature_request.yml">機能リクエスト</a>
  ·
  <a href="https://github.com/{{OWNER}}/{{REPO_NAME}}/discussions">ディスカッション</a>
</p>

</div>

<details>
  <summary>目次</summary>
  <ol>
    <li><a href="#about">概要</a></li>
    <li><a href="#features">機能</a></li>
    <li>
      <a href="#getting-started">はじめに</a>
      <ul>
        <li><a href="#prerequisites">前提条件</a></li>
        <li><a href="#installation">インストール</a></li>
      </ul>
    </li>
    <li><a href="#usage">使い方</a></li>
    <li><a href="#development">開発</a></li>
    <li><a href="#roadmap">ロードマップ</a></li>
    <li><a href="#contributing">コントリビュート</a></li>
    <li><a href="#project-docs">プロジェクト文書</a></li>
    <li><a href="#license">ライセンス</a></li>
    <li><a href="#acknowledgments">謝辞</a></li>
  </ol>
</details>

<a id="about"></a>

## 概要

<!-- TODO: スクリーンショットを追加してコメントを外してください
<img src="assets/screenshot.png" alt="{{PROJECT_NAME}} screenshot">
-->

{{DESCRIPTION_JA}}

<!-- TODO: 何をするプロジェクトか、誰向けか、なぜ存在するかを簡潔に記載してください。 -->

### 使用技術

<!-- TODO: 主なフレームワーク・言語・ツールを記載してください。 -->

- ツールその1
- ツールその2

<p align="right">(<a href="#readme-top">トップへ戻る</a>)</p>

<a id="features"></a>

## 機能

<!-- TODO: プロジェクトの機能を記載してください。 -->

- 機能その1
- 機能その2
- 機能その3

<p align="right">(<a href="#readme-top">トップへ戻る</a>)</p>

<a id="getting-started"></a>

## はじめに

<!-- TODO: ローカルで動かすための手順。 -->

<a id="prerequisites"></a>

### 前提条件

<!-- TODO: 事前に必要なものを記載してください。 -->

<a id="installation"></a>

### インストール

```sh
git clone https://github.com/{{OWNER}}/{{REPO_NAME}}.git
cd {{REPO_NAME}}
```

<p align="right">(<a href="#readme-top">トップへ戻る</a>)</p>

<a id="usage"></a>

## 使い方

<!-- TODO: 使用例。スクリーンショットやコードブロックがあると分かりやすいです。 -->

<p align="right">(<a href="#readme-top">トップへ戻る</a>)</p>

<a id="development"></a>

## 開発

```sh
{{BUILD_COMMAND}}
{{TEST_COMMAND}}
```

詳細な開発・ビルド手順: **[docs/development.md](docs/development.md)**
コントリビュート手順: **[CONTRIBUTING.md](.github/CONTRIBUTING.md)**

<p align="right">(<a href="#readme-top">トップへ戻る</a>)</p>

<a id="roadmap"></a>

## ロードマップ

計画中の機能や既知の課題は [Issues](https://github.com/{{OWNER}}/{{REPO_NAME}}/issues) と
[ROADMAP.md](ROADMAP.md) を参照してください。

<p align="right">(<a href="#readme-top">トップへ戻る</a>)</p>

<a id="contributing"></a>

## コントリビュート

コントリビュートを歓迎します。ワークフロー（Conventional Commits・DCO サインオフ・PR 手順）は
**[CONTRIBUTING.md](.github/CONTRIBUTING.md)** を、コミュニティ標準は
[行動規範](.github/CODE_OF_CONDUCT.md) を参照してください。

貢献者一覧は英語 README の [Contributors](README.md#contributing) を参照してください（git 履歴から自動更新）。

<p align="right">(<a href="#readme-top">トップへ戻る</a>)</p>

<a id="project-docs"></a>

## プロジェクト文書

リポジトリの自動化とコミュニティ文書は
[container-registry/oss-project-template](https://github.com/container-registry/oss-project-template)
を基にしています。

| 文書 | 内容 |
|------|------|
| [CONTRIBUTING.md](.github/CONTRIBUTING.md) | 開発・テスト・PR・DCO・CI/CD・リリース |
| [SUPPORT.md](.github/SUPPORT.md) | サポートの受け方 |
| [ROADMAP.md](ROADMAP.md) | 方向性と提案の仕方 |
| [CODE_OF_CONDUCT.md](.github/CODE_OF_CONDUCT.md) | 行動規範 |
| [SECURITY.md](.github/SECURITY.md) | 脆弱性の非公開報告 |
| [CODEOWNERS](CODEOWNERS) | デフォルトのレビュー担当 |
| [CHANGELOG.md](CHANGELOG.md) | 変更履歴 |
| [LICENSE](LICENSE) | MIT ライセンス本文 |

<p align="right">(<a href="#readme-top">トップへ戻る</a>)</p>

<a id="license"></a>

## ライセンス

MIT ライセンスで配布しています。詳細は [LICENSE](LICENSE) を参照してください。

MIT © {{YEAR}} {{AUTHOR}}

<p align="right">(<a href="#readme-top">トップへ戻る</a>)</p>

<a id="acknowledgments"></a>

## 謝辞

<!-- TODO: プロジェクトが依拠するリソース・ライブラリ・人物を列挙してください。下の例は置き換えてください。 -->

- [リソース名](https://example.com) — 提供内容

<p align="right">(<a href="#readme-top">トップへ戻る</a>)</p>
