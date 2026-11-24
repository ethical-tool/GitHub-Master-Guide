<p align="center">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="200" alt="GitHub公式ロゴ">
</p>

<h1 align="center">GitHub Master Guide</h1>

<p align="center">
  <b>GitHubの完全ガイド：ルール、リポジトリ、ライセンス、セキュリティ、開発者向けドキュメント</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-GitHub-black?logo=github" alt="GitHub">
  <img src="https://img.shields.io/badge/Guide-Japanese-red" alt="Japanese">
  <img src="https://img.shields.io/badge/License-GPL--3.0-blue" alt="GPL 3.0">
  <img src="https://img.shields.io/badge/Status-Documentation-success" alt="Documentation">
</p>

---

## 📖 このガイドについて

GitHubは、開発者がソースコード、プロジェクト、スクリプト、ドキュメント、オープンソースソフトウェアを公開・管理するための強力なプラットフォームです。

このリポジトリの目的は、GitHubの重要な機能、ルール、ポリシー、制限事項、ベストプラクティスを一か所にまとめて解説することです。

このガイドは、初心者から経験豊富な開発者まで、誰もがGitHubを理解できるように構成されています。

**このガイドで学べる内容：**

- GitHubアカウントとプロフィールの管理。
- リポジトリの作成と管理。
- PublicリポジトリとPrivateリポジトリ。
- リポジトリの命名規則とファイル構成。
- READMEファイルとドキュメント。
- オープンソースライセンスと法的要件。
- アカウントのフラグ、制限、停止。
- アカウントの復旧と異議申し立て。
- 日常的なリポジトリ作成。
- ファイルサイズとアップロードの制限。
- Git LFSを使用した大容量ファイルのアップロード。
- Gitコマンドとバージョン管理。
- Fork、Pull Request、Issue。
- ReleasesとGitHub Actions。
- プロフィールの実績とバッジ。
- コントリビューショングラフとプロフィールの最適化。
- アカウントのセキュリティと責任ある開発。

---

# 📑 目次

1. [GitHubの概要](#1-githubの概要)
2. [GitとGitHubの違い](#2-gitとgithubの違い)
3. [GitHubアカウントの作成](#3-githubアカウントの作成)
4. [アカウントのセキュリティ](#4-アカウントのセキュリティ)
5. [GitHubプロフィール](#5-githubプロフィール)
6. [リポジトリの概要](#6-リポジトリの概要)
7. [リポジトリの作成](#7-リポジトリの作成)
8. [PublicとPrivateリポジトリ](#8-publicとprivateリポジトリ)
9. [リポジトリの命名規則](#9-リポジトリの命名規則)
10. [リポジトリのファイル構成](#10-リポジトリのファイル構成)
11. [README.mdガイド](#11-readmemdガイド)
12. [リポジトリへのアップロード規則](#12-リポジトリへのアップロード規則)
13. [著作権に関する規則](#13-著作権に関する規則)
14. [ライセンス完全ガイド](#14-ライセンス完全ガイド)
15. [GNU GPL v3の解説](#15-gnu-gpl-v3の解説)
16. [ライセンスの追加方法](#16-ライセンスの追加方法)
17. [GitHubアカウントのフラグ](#17-githubアカウントのフラグ)
18. [アカウント停止の理由](#18-アカウント停止の理由)
19. [アカウントの復旧](#19-アカウントの復旧)
20. [異議申し立ての手続き](#20-異議申し立ての手続き)
21. [毎日のリポジトリ作成](#21-毎日のリポジトリ作成)
22. [GitHubのファイルサイズ制限](#22-githubのファイルサイズ制限)
23. [大容量ファイルのアップロード](#23-大容量ファイルのアップロード)
24. [Git LFSのインストール](#24-git-lfsのインストール)
25. [2 GBファイルのアップロード](#25-2-gbファイルのアップロード)
26. [Git Pushの制限](#26-git-pushの制限)
27. [リポジトリサイズの管理](#27-リポジトリサイズの管理)
28. [Gitコマンド](#28-gitコマンド)
29. [コミットとブランチ](#29-コミットとブランチ)
30. [ForkとPull Request](#30-forkとpull-request)
31. [GitHub Issues](#31-github-issues)
32. [GitHub Releases](#32-github-releases)
33. [GitHub Actions](#33-github-actions)
34. [GitHub Discussions](#34-github-discussions)
35. [GitHub Pages](#35-github-pages)
36. [GitHub StarsとFollowers](#36-github-starsとfollowers)
37. [GitHub Achievements](#37-github-achievements)
38. [GitHubプロフィールバッジ](#38-githubプロフィールバッジ)
39. [コントリビューショングラフ](#39-コントリビューショングラフ)
40. [GitHubのセキュリティ機能](#40-githubのセキュリティ機能)
41. [倫理的ハッキング関連リポジトリの規則](#41-倫理的ハッキング関連リポジトリの規則)
42. [.gitignoreガイド](#42-gitignoreガイド)
43. [GitHubでよくある間違い](#43-githubでよくある間違い)
44. [開発者のベストプラクティス](#44-開発者のベストプラクティス)
45. [GitHub公式リンク](#45-github公式リンク)
46. [最終ガイドライン](#46-最終ガイドライン)

---

# 1. GitHubの概要

GitHubは、Gitバージョン管理システムを利用したクラウドベースの開発プラットフォームです。

GitHubでは、次のことができます。

- プロジェクトをオンラインでホストする。
- ソースコードを共有する。
- プロジェクトの変更履歴を管理する。
- チームで共同作業を行う。
- オープンソースプロジェクトに貢献する。
- バグを報告する。
- ソフトウェアのリリースを公開する。
- テストやデプロイを自動化する。
- 開発者としてのポートフォリオを作成する。

**公式ウェブサイト：**

https://github.com/

**公式ドキュメント：**

https://docs.github.com/

# 2. GitとGitHubの違い

### Git

Gitは分散型バージョン管理システムです。

主な機能：

- コードの変更を追跡する。
- Commitを作成する。
- Branchを管理する。
- 過去のバージョンを復元する。
- 複数の開発者による変更を統合する。

### GitHub

GitHubは、Gitリポジトリをホストするオンラインプラットフォームです。

次のような追加機能を提供します。

- Pull Requests。
- Issues。
- Discussions。
- Actions。
- Releases。
- Projects。
- セキュリティアラート。

Gitはコンピューター上でローカルに使用できます。一方、GitHubはオンラインでの共同作業機能を提供します。

**Git公式ウェブサイト：**

https://git-scm.com/

# 3. GitHubアカウントの作成

GitHubアカウントを作成するには、次の手順に従ってください。

1. https://github.com/ を開きます。
2. **Sign Up** をクリックします。
3. メールアドレスを入力します。
4. 強力なパスワードを作成します。
5. 固有のユーザー名を選択します。
6. メールアドレスの認証を完了します。
7. 二要素認証を有効にします。

### ユーザー名のルール

- プロフェッショナルなユーザー名を選択してください。
- 他の開発者の身元を偽装しないでください。
- 不必要な数字や記号は避けてください。
- シンプルで覚えやすいユーザー名にしてください。

**公式ガイド：**

https://docs.github.com/en/account-and-profile

# 4. アカウントのセキュリティ

GitHubアカウントを安全に保つことは非常に重要です。

### 重要なセキュリティルール

- 強力で固有のパスワードを使用してください。
- 二要素認証を有効にしてください。
- リカバリーコードを安全な場所に保管してください。
- 不明なSSHキーを削除してください。
- 不明なPersonal Access Tokenを取り消してください。
- 不審なOAuthアプリケーションのアクセスを削除してください。
- アカウントの復旧用メールアドレスを安全に保ってください。
- 公共のコンピューターを使用した後はサインアウトしてください。

### 二要素認証（Two-Factor Authentication）

2FAは、アカウントに追加のセキュリティ層を提供します。

パスワードに加えて、2つ目の認証方法が必要になります。

**公式ガイド：**

https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa

# 5. GitHubプロフィール

GitHubプロフィールは、開発者としてのあなたの身元を表します。

プロフィールには、次の情報を掲載できます。

- Profile Picture。
- Username。
- Display Name。
- Bio。
- Location。
- Website。
- Social Links。
- Profile README。
- Pinned Repositories。
- Contributions。
- Achievements。

### Profile README

GitHubのユーザー名と完全に同じ名前のPublicリポジトリを作成し、その中に `README.md` ファイルを追加してください。

例：

```text
Username: ethical-tool

Repository: ethical-tool/ethical-tool

File: README.md
```

GitHubは、このREADMEをプロフィールページに表示します。

**ガイド：**

https://docs.github.com/en/account-and-profile

# 6. リポジトリの概要

リポジトリとは、Gitの変更履歴を含むプロジェクトフォルダーです。

ソースコード、ドキュメント、画像、スクリプト、設定ファイルなどを保存できます。

例：

```text
ByteBreaker/
│
├── README.md
├── LICENSE
├── install.sh
├── requirements.txt
├── .gitignore
│
├── src/
│   └── main.py
│
├── assets/
│   └── logo.png
│
└── docs/
    └── guide.md
```

# 7. リポジトリの作成

リポジトリを作成するには、次の手順に従ってください。

1. GitHubにサインインします。
2. **New Repository** を選択します。
3. リポジトリ名を入力します。
4. 説明を追加します。
5. **Public** または **Private** を選択します。
6. 必要に応じてREADMEを使ってリポジトリを初期化します。
7. 必要に応じてライセンスを選択します。
8. **Create Repository** をクリックします。

**公式ガイド：**

https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository

# 8. PublicとPrivateリポジトリ

### Public Repository

Publicリポジトリは、インターネット上のユーザーが閲覧できます。

特徴：

- 公開状態である。
- GitHubユーザーがForkできる。
- StarsやWatchersを受け取ることができる。
- コントリビューションを受け付けることができる。
- オープンソースプロジェクトの公開に利用できる。

### Private Repository

Privateリポジトリは、許可されたユーザーだけが利用できます。

特徴：

- アクセスが制限される。
- チームで共同作業できる。
- 非公開で開発できる。
- アクセス権限を管理できる。

### 重要

Publicリポジトリだからといって、すべてのユーザーにそのコンテンツを自由に再利用する法的権利が自動的に与えられるわけではありません。

適用されるライセンスとGitHubの利用規約の両方を理解することが重要です。

# 9. リポジトリの命名規則

リポジトリ名は、プロジェクトの内容が分かるものにしてください。

**良い例：**

```text
GitHub-Complete-Handbook
ByteBreaker
Network-Scanner
Linux-Toolkit
Web-Security-Guide
Python-Automation
```

**避けるべき例：**

```text
test123
newrepo999
project-final-final
random-files
```

ヒント：

- プロジェクトの目的が分かる名前にしてください。
- 短く、プロフェッショナルな名前を使用してください。
- 誤解を招く名前は避けてください。
- 不必要に重複したリポジトリを作成しないでください。
- 不必要な特殊文字は避けてください。

# 10. リポジトリのファイル構成

プロフェッショナルなリポジトリは、適切に整理されている必要があります。

例：

```text
Project/
│
├── README.md
├── LICENSE
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── CODE_OF_CONDUCT.md
├── .gitignore
├── requirements.txt
│
├── src/
├── docs/
├── tests/
├── assets/
└── examples/
```

### 重要なファイル

| ファイル | 目的 |
|---|---|
| README.md | プロジェクトのドキュメント |
| LICENSE | 使用および配布の許可条件 |
| CHANGELOG.md | バージョン変更履歴 |
| CONTRIBUTING.md | コントリビューションのガイドライン |
| SECURITY.md | セキュリティ問題の報告方法 |
| CODE_OF_CONDUCT.md | コミュニティの行動規範 |
| .gitignore | Gitで追跡しないファイルの指定 |
| requirements.txt | Pythonの依存関係 |

すべてのプロジェクトに、これらのファイルが必要なわけではありません。

# 11. README.mdガイド

READMEは、リポジトリの主要なドキュメントファイルです。

優れたREADMEには、次のセクションを含めることをおすすめします。

1. プロジェクト名。
2. 説明。
3. 機能。
4. 必要条件。
5. インストール方法。
6. 使用方法。
7. コマンド。
8. 使用例。
9. スクリーンショット。
10. トラブルシューティング。
11. 免責事項。
12. ライセンス。
13. クレジット。
14. 作者情報。

### Markdownの例

```markdown
# Project Name

Project description.

## Features

- Feature One
- Feature Two

## Installation

```bash
git clone REPOSITORY_URL
cd PROJECT
```

## Usage

```bash
python3 main.py
```

## License

GNU GPL v3.0
```

READMEはシンプルで読みやすく、常に最新の状態に保ってください。

**公式ガイド：**

https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes

# 12. リポジトリへのアップロード規則

### アップロードできるもの

- オリジナルのソースコード。
- Pythonスクリプト。
- Bashスクリプト。
- JavaScriptアプリケーション。
- CおよびC++プロジェクト。
- 倫理的ハッキングツール。
- 教育目的のサイバーセキュリティプロジェクト。
- ドキュメント。
- チュートリアル。
- スクリーンショット。
- ロゴ。
- 設定ファイル。
- オープンソースプロジェクト。

### アップロードすべきではないもの

- 盗まれたパスワード。
- 流出したデータベース。
- 非公開の個人情報。
- 盗用されたソースコード。
- 許可されていない認証情報。
- 秘密のSSHキー。
- APIシークレット。
- 海賊版ソフトウェア。
- 許可のない著作権保護ファイル。
- 有害な悪意のあるコンテンツ。
- スパムや誤解を招く内容。

GitHubのAcceptable Use Policy（利用規定）を守ることが不可欠です。

https://docs.github.com/en/site-policy/acceptable-use-policies/github-acceptable-use-policies

# 13. 著作権に関する規則

著作権は、オリジナル作品に対する所有権を保護します。

ルール：

- 自分で作成したオリジナルコードを公開してください。
- 他人のコードをコピーする前にライセンスを確認してください。
- 元の著作権表示を保持してください。
- サードパーティ製依存関係のライセンスを確認してください。
- 許可なく著作権保護ファイルを再配布しないでください。
- 外部の素材をプロジェクトで使用する場合は、適用される条件に従ってください。

Publicリポジトリであっても、著作権保護がなくなるわけではありません。

# 14. ライセンス完全ガイド

ライセンスとは、他の開発者があなたのプロジェクトをどのように使用、変更、配布できるかを定める法的文書です。

ライセンスがない場合、通常の著作権法が適用されます。

GitHubで使用できる一般的なライセンスの例：

### 14.1 MIT License

MITは、制限の少ないオープンソースライセンスです。

許可されること：

- 商用利用。
- 変更。
- 配布。
- 私的利用。
- サブライセンス。

条件：

- 著作権表示を保持すること。
- ライセンス表示を含めること。

MIT Licenseでは、変更したソフトウェアをオープンソースにすることは必須ではありません。

https://opensource.org/license/mit

### 14.2 Apache License 2.0

Apache 2.0は、制限の少ないライセンスです。

特徴：

- 商用利用が許可される。
- 変更が許可される。
- 配布が許可される。
- 特許ライセンスに関する規定が含まれる。
- 著作権表示を保持する必要がある。
- ライセンスの要求に応じて変更内容を記録する必要がある場合がある。

https://www.apache.org/licenses/LICENSE-2.0

### 14.3 GNU GPL v2.0

GPL v2は、コピーレフトライセンスです。

特徴：

- ソフトウェアを使用できる。
- ソフトウェアを変更できる。
- ソフトウェアを配布できる。
- 対象となる変更版を配布する場合、GPL v2の条件に従う必要がある。
- 適用されるソースコード提供要件に従う必要がある。

https://www.gnu.org/licenses/old-licenses/gpl-2.0.html

### 14.4 GNU GPL v3.0

GPL v3は、強いコピーレフトを持つオープンソースライセンスです。

特徴：

- ソフトウェアを使用できる。
- ソースコードを変更できる。
- コピーを配布できる。
- 商用配布が許可される。
- 対象となる変更版を配布する場合、GPL v3に従う必要がある。
- 適用されるソースコード提供要件を満たす必要がある。
- 特許およびAnti-Tivoizationに関する規定も含まれる。

**重要：** GPL v3はコピーや変更を禁止するライセンスではありません。これらの権利を認める一方で、再配布や変更版に特定の条件を課します。

https://www.gnu.org/licenses/gpl-3.0.en.html

### 14.5 GNU LGPL

LGPLは、ライブラリ向けのコピーレフトライセンスです。

他のソフトウェアとライブラリを組み合わせて使用する際の柔軟性を提供することを目的としています。

LGPLには、リンク、変更、配布に関する独自の条件があります。

https://www.gnu.org/licenses/lgpl-3.0.en.html

### 14.6 GNU AGPL v3

AGPL v3は、ネットワーク経由で利用されるソフトウェアに追加のコピーレフト要件を導入します。

対象となる変更済みソフトウェアをユーザーがネットワーク経由で操作する場合、ソースコードの提供要件が適用されることがあります。

https://www.gnu.org/licenses/agpl-3.0.en.html

### 14.7 BSD 2-Clause

これは制限の少ないライセンスです。

- 商用利用。
- 変更。
- 配布。
- 著作権表示とライセンス表示の保持。

https://opensource.org/license/bsd-2-clause

### 14.8 BSD 3-Clause

BSD 2-Clauseと同様に、制限の少ないライセンスです。

ただし、許可なく元の貢献者の名前を派生製品の推奨や宣伝に使用することも制限されています。

https://opensource.org/license/bsd-3-clause

### 14.9 ISC License

ISCは、シンプルな制限の少ないライセンスです。

- 使用が許可される。
- 変更が許可される。
- 配布が許可される。
- 著作権表示と許可表示を保持する必要がある。

https://opensource.org/license/isc-license-txt

### 14.10 Mozilla Public License 2.0

MPL 2.0は、ファイル単位のコピーレフトライセンスです。

対象となるファイルへの変更を配布する場合、MPLの条件に従う必要があります。

https://www.mozilla.org/en-US/MPL/2.0/

### 14.11 Creative Commons Licenses

Creative Commonsライセンスは、一般的にドキュメント、記事、教育コンテンツ、画像、その他の創作物に使用されます。

主な種類：

- CC BY：クレジット表記が必要。
- CC BY-SA：クレジット表記と同一ライセンスでの共有が必要。
- CC BY-NC：非営利目的に限定される。
- CC BY-ND：改変物の配布が許可されない。
- CC0：パブリックドメインへの提供を目的とする仕組み。

**公式ウェブサイト：**

https://creativecommons.org/share-your-work/cclicenses/

### 14.12 Unlicense

Unlicenseは、パブリックドメインへの提供によって最大限の自由を目指すライセンスです。

https://unlicense.org/

### ライセンス比較

| ライセンス | 商用利用 | 変更 | コピーレフト |
|---|---|---|---|
| MIT | はい | はい | なし |
| Apache 2.0 | はい | はい | なし |
| GPL v2 | はい | はい | あり |
| GPL v3 | はい | はい | あり |
| LGPL | はい | はい | 限定的 |
| AGPL | はい | はい | 強い |
| BSD 2-Clause | はい | はい | なし |
| BSD 3-Clause | はい | はい | なし |
| ISC | はい | はい | なし |
| MPL 2.0 | はい | はい | ファイル単位 |
| CC BY | はい | はい | なし |
| CC BY-SA | はい | はい | 同一条件での共有 |

ライセンスを選択する前に、完全な法的条件を確認してください。

**公式ライセンス選択ガイド：**

https://choosealicense.com/

# 15. GNU GPL v3の解説

このリポジトリで選択されているライセンスはGNU GPL v3.0です。

これは、次のことを意味します。

1. ユーザーはプロジェクトのコピーを作成できます。
2. ユーザーはソースコードを変更できます。
3. ユーザーは変更版を配布できます。
4. ユーザーはプロジェクトを商用目的で使用できます。
5. ソフトウェアを配布する際は、適用されるGPLの条件に従う必要があります。
6. 対象となるソースコードを提供する要件が適用される場合があります。
7. 著作権表示とライセンス表示を保持する必要があります。

### GPL v3で許可されないこと

- 元の著作権表示を削除することは許可されません。
- ライセンス条件を無視して、対象となる変更済みソフトウェアを配布することは許可されません。
- 適用される条件を守らずに、GPL対象の作品を独占的なプロプライエタリ配布物に変更することは、原則として認められません。

### 重要な補足

GitHubの利用規約に従えば、ユーザーはPublicリポジトリをForkできます。

GPL v3はさらに踏み込み、ライセンス対象の作品をコピー、変更、配布する権利と条件を定めています。

コピーや変更を防ぐことが目的であれば、GPL v3はその目的に適したライセンスではありません。

# 16. ライセンスの追加方法

新しいリポジトリを作成する場合：

1. **Create Repository** を開きます。
2. **Add a license** オプションを開きます。
3. **GNU General Public License v3.0** を選択します。
4. リポジトリを作成します。

既存のリポジトリの場合：

1. **Add file** をクリックします。
2. **Create new file** を選択します。
3. ファイル名を `LICENSE` にします。
4. 公式GPL v3ライセンスのテキストを追加します。
5. 変更をCommitします。

**公式GPLテキスト：**

https://www.gnu.org/licenses/gpl-3.0.txt

# 17. GitHubアカウントのフラグ

アカウントへのフラグ付与、制限、停止は、それぞれ異なるものです。

GitHubは、さまざまな状況に応じてコンテンツやアカウントに対してモデレーション措置を取る場合があります。

考えられる影響：

- コンテンツの公開範囲が制限される場合がある。
- リポジトリが無効化される場合がある。
- 一部のアカウント操作が利用できなくなる場合がある。
- アカウントが停止または終了される場合がある。

リポジトリが報告されたからといって、必ずアカウントが停止されるわけではありません。

# 18. アカウント停止の理由

考えられる理由は次のとおりです。

### スパム行為

- 繰り返し投稿されるスパムコンテンツ。
- 偽の宣伝活動。
- 自動化された迷惑行為。
- 不必要に繰り返されるIssue。
- 誤解を招くリポジトリ。

### 著作権侵害

- 許可されていない著作権保護ソフトウェアの配布。
- 有効な削除通知を無視すること。
- 他人の知的財産権を侵害すること。

### セキュリティ違反

- 盗まれた認証情報の配布。
- 許可されていない有害な活動。
- 悪意のあるコンテンツの配布。
- ユーザーのプライバシー侵害。

### ハラスメント

- 脅迫的な行為。
- 特定の人物への嫌がらせ。
- Doxxing（個人情報の暴露）。
- コミュニティガイドラインへの違反。

### 不審な活動

- 侵害されたアカウント。
- 不正アクセス。
- 不審な自動化行為。

### 法的制限

適用される法律やGitHubのポリシーに基づき、追加の制限が適用される場合があります。

**公式ポリシー：**

https://docs.github.com/en/site-policy/acceptable-use-policies/github-acceptable-use-policies

https://docs.github.com/en/site-policy/github-terms/github-community-guidelines

# 19. アカウントの復旧

アカウントが制限された場合、または侵害された場合：

### Step 1：メールを確認する

GitHubから届いた公式メールを確認してください。

SpamフォルダーとJunkフォルダーも確認してください。

### Step 2：アカウントを保護する

- パスワードを変更する。
- 不明なセッションやアプリケーションを確認する。
- 不明なSSHキーを削除する。
- Personal Access Tokenを取り消す。
- メールアカウントを保護する。
- 2FAを有効にする。

### Step 3：制限の内容を理解する

GitHubの通知に記載されている理由を確認してください。

### Step 4：必要な変更を行う

コンテンツがポリシーに違反している場合、必要な修正措置を完了してください。

### Step 5：公式の異議申し立てを提出する

https://support.github.com/contact/reinstatement

### Step 6：審査を待つ

GitHubチームが異議申し立てを審査します。

アカウントの復旧が保証されるわけではありません。

**重要：** 停止措置を回避するために、新しいアカウントを作成しないでください。

# 20. 異議申し立ての手続き

Appeal（異議申し立て）とは、GitHubのモデレーション判断に対して異議を申し立てることです。

Reinstatement（復旧）とは、必要な変更を完了した後に、アカウントまたはコンテンツへのアクセス再開を申請することです。

異議申し立てを提出する際：

- GitHubユーザー名を記載してください。
- 制限の詳細を説明してください。
- 関連する証拠を提供してください。
- アカウントが侵害された場合は、その状況を説明してください。
- プロフェッショナルな言葉遣いを使用してください。
- 虚偽の情報を提供しないでください。

このガイドで参照しているGitHubの公開手続きによれば、モデレーション判断から6か月以内に異議申し立てを提出できる場合があります。

**公式ガイド：**

https://docs.github.com/en/site-policy/acceptable-use-policies/github-appeal-and-reinstatement

# 21. 毎日のリポジトリ作成

GitHubは、個人アカウント向けの一般的な1日あたりのリポジトリ作成上限を公開していません。

ただし、これは自動化された活動が無制限に許可されるという意味ではありません。

### 推奨される方法

- 意味のあるリポジトリを作成する。
- 空のリポジトリを避ける。
- 重複したプロジェクトを作成しない。
- スパム行為を避ける。
- すべてのリポジトリに説明を記載する。
- READMEを維持する。
- 各プロジェクトを適切に整理する。

### 質と量

空のリポジトリを複数作成するよりも、完成度が高く、役立つ、十分に文書化されたリポジトリを1つ作成する方が優れています。

これは推奨事項であり、GitHubの公式な1日あたりの作成上限ではありません。

# 22. GitHubのファイルサイズ制限

GitHubでは、アップロード方法によって異なる制限があります。

| アップロード方法 | 制限 |
|---|---:|
| ブラウザーからのアップロード | 1ファイルあたり25 MiB |
| 通常のGitファイル | 最大100 MiB |
| Gitの警告 | 50 MiBを超える場合 |
| GitHub Free LFS | 1ファイルあたり2 GB |
| GitHub Pro LFS | 1ファイルあたり2 GB |
| GitHub Team LFS | 1ファイルあたり4 GB |
| GitHub Enterprise Cloud LFS | 1ファイルあたり5 GB |

100 MiBを超えるファイルは、通常のGitではアップロードできません。

大容量ファイルにはGit LFSを使用してください。

**公式ガイド：**

https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github

# 23. 大容量ファイルのアップロード

ファイルが100 MiBを超える場合、通常のGitではなくGit LFSを使用してください。

Git LFSは、大容量ファイルを別に保存し、Gitリポジトリ内ではポインターファイルを管理します。

メリット：

- 大容量のバイナリファイルを管理できる。
- リポジトリのCloneサイズを管理しやすくする。
- 大規模なプロジェクト素材を追跡できる。
- バージョン管理でファイルを管理できる。

# 24. Git LFSのインストール

Ubuntu / Debian：

```bash
sudo apt update

sudo apt install git-lfs
```

インストールを確認する：

```bash
git lfs version
```

Git LFSを初期化する：

```bash
git lfs install
```

**公式ウェブサイト：**

https://git-lfs.com/

# 25. 2 GBファイルのアップロード

GitHub FreeとProでは、Git LFSの個別ファイルサイズ上限は2 GBです。

### Step 1：リポジトリをCloneする

```bash
git clone https://github.com/USERNAME/REPOSITORY.git

cd REPOSITORY
```

### Step 2：Git LFSを初期化する

```bash
git lfs install
```

### Step 3：大容量ファイルを追跡する

```bash
git lfs track "*.zip"
```

または、特定のファイルを追跡します。

```bash
git lfs track "large-file.zip"
```

### Step 4：Attributesを追加する

```bash
git add .gitattributes
```

### Step 5：ファイルを追加する

```bash
git add large-file.zip
```

### Step 6：Commitする

```bash
git commit -m "Add large file using Git LFS"
```

### Step 7：Pushする

```bash
git push origin main
```

### 重要

- ファイルは1ファイルあたり2 GBの制限を超えてはいけません。
- ストレージ容量の上限を確認してください。
- 帯域幅の上限を確認してください。
- 安定したインターネット接続を使用してください。
- Git LFSがインストールされている必要があります。

**Git LFSの料金と請求：**

https://docs.github.com/en/billing/concepts/product-billing/git-lfs

# 26. Git Pushの制限

GitHubでは、1回のGit Pushに対して最大2 GiBのサイズ制限があります。

これは1ファイルごとの制限ではありません。

Pushが2 GiBを超える場合：

- Pushを小さなCommitに分割してください。
- 小さな単位でPushしてください。
- 不要なファイルを削除してください。
- 大容量バイナリにはGit LFSを使用してください。

**公式ガイド：**

https://docs.github.com/en/get-started/using-git/troubleshooting-the-2-gb-push-limit

# 27. リポジトリサイズの管理

GitHubリポジトリを小さく保つことをおすすめします。

公式の推奨事項：

- 理想的には、リポジトリを1 GB未満に保ってください。
- 5 GB未満に保つことを強くおすすめします。

ヒント：

- 不要なバイナリファイルを削除する。
- 一時ファイルをCommitしない。
- ビルドディレクトリをIgnoreする。
- パッケージマネージャーで依存関係を管理する。
- 不必要に大きなGit履歴を避ける。
- 大容量ファイルにはGit LFSまたはReleasesを検討する。

**公式ガイド：**

https://docs.github.com/en/repositories/creating-and-managing-repositories/repository-limits

# 28. Gitコマンド

### Gitのインストール

Ubuntu / Debian：

```bash
sudo apt install git
```

### バージョンの確認

```bash
git --version
```

### ユーザー名の設定

```bash
git config --global user.name "Your Name"
```

### メールアドレスの設定

```bash
git config --global user.email "your@email.com"
```

### リポジトリの初期化

```bash
git init
```

### Statusの確認

```bash
git status
```

### すべてのファイルを追加

```bash
git add .
```

### Commit

```bash
git commit -m "Initial commit"
```

### Remoteの追加

```bash
git remote add origin https://github.com/USERNAME/REPOSITORY.git
```

### Branch名の変更

```bash
git branch -M main
```

### Push

```bash
git push -u origin main
```

### Clone

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

**Git公式ドキュメント：**

https://git-scm.com/doc

# 29. コミットとブランチ

### Commit

Commitとは、プロジェクトの変更を保存した記録です。

良いCommitメッセージの例：

```text
Initial commit
Add installation script
Fix bugs
Update README
Improve performance
Add new feature
Update dependencies
```

### Branch

Branchとは、独立した開発作業を行うための開発ラインです。

例：

```bash
git branch
git branch development
git switch development
```

BranchをMergeする：

```bash
git switch main
git merge development
```

Branchを使用すると、メインプロジェクトに直接影響を与えずに開発作業を進めることができます。

# 30. ForkとPull Request

### Fork

Forkとは、GitHub上の別のリポジトリを自分のアカウントにコピーすることです。

### Pull Request

Pull Requestとは、自分の変更を元のリポジトリにMergeするためのリクエストです。

### コントリビューションのルール

- 元の作者にクレジットを付けてください。
- プロジェクトのガイドラインに従ってください。
- 意味のある変更を提出してください。
- 不必要なPull Requestは避けてください。
- コードレビューのプロセスを尊重してください。

**公式ガイド：**

https://docs.github.com/en/pull-requests

# 31. GitHub Issues

Issuesは、プロジェクトのバグや改善について話し合うために使用されます。

Issuesの用途：

- Bug Reports。
- Feature Requests。
- Questions。
- Documentation Problems。
- Improvements。

Issueを作成する際：

1. 明確なタイトルを書く。
2. 問題を説明する。
3. 再現手順を提供する。
4. 期待される結果を説明する。
5. 実際の結果を説明する。
6. 関連するスクリーンショットやログを追加する。

**公式ガイド：**

https://docs.github.com/en/issues

# 32. GitHub Releases

Releasesは、プロジェクトの安定版を公開するために使用されます。

例：

```text
v1.0.0
v1.1.0
v1.2.0
v2.0.0
```

Releaseには、次の内容を含めることができます。

- バージョン番号。
- リリースノート。
- バグ修正。
- 新機能。
- インストール手順。
- ダウンロード可能なファイル。

GitHub Releasesは、大容量のバイナリファイルを配布する際にも役立ちます。各ファイルは、利用プランに適用されるGit LFSの最大ファイルサイズ制限内に収める必要があります。

**公式ガイド：**

https://docs.github.com/en/repositories/releasing-projects-on-github

# 33. GitHub Actions

GitHub Actionsは、自動化とCI/CDに使用されます。

次の用途に利用できます。

- 自動テスト。
- コード品質チェック。
- ビルドの自動化。
- デプロイ。
- スケジュールされたワークフロー。
- リリースの自動化。

ワークフローの例：

```yaml
name: Python Check

on:
  push:
    branches: [main]

jobs:
  test:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v4

      - name: Setup Python
        uses: actions/setup-python@v5
        with:
          python-version: "3.12"

      - name: Check Python
        run: python --version
```

セキュリティに関する注意：サードパーティ製Actionsを使用する前に、その真正性と権限を確認してください。ログにシークレットを公開しないでください。

**公式ガイド：**

https://docs.github.com/en/actions

# 34. GitHub Discussions

Discussionsは、コミュニティ内で会話するために設計されています。

用途：

- 一般的な質問。
- お知らせ。
- アイデア。
- コミュニティによるサポート。
- Q&A。

**公式ガイド：**

https://docs.github.com/en/discussions

# 35. GitHub Pages

GitHub Pagesは、静的ウェブサイトをホストするためのサービスです。

次のようなコンテンツを公開できます。

- ドキュメントサイト。
- ポートフォリオ。
- プロジェクトのランディングページ。
- チュートリアル。
- 静的HTMLウェブサイト。

**公式ガイド：**

https://docs.github.com/en/pages

# 36. GitHub StarsとFollowers

### Stars

Starは、リポジトリをブックマークしたり、評価を示したりするために使用されます。

### Followers

Followersは、あなたのGitHub上の活動をフォローするユーザーです。

### Watchers

Watchersは、リポジトリからの通知を受け取るユーザーです。

### 重要なルール

- 偽のStarsを購入しないでください。
- 偽のFollowersを作成しないでください。
- Star交換スパムを避けてください。
- 誤解を招く宣伝を使用しないでください。
- 本物のプロジェクトと貢献に集中してください。

# 37. GitHub Achievements

GitHub Achievementsは、特定の活動やマイルストーンを認識するプロフィールバッジです。

Achievementsは、プロフィールのサイドバーに表示される場合があります。

Achievementをクリックまたはホバーすると、その説明や関連する活動の詳細を確認できます。

### 主なAchievementの例

**1. Quickdraw**

特定のGitHubコントリビューションイベントにおいて、迅速に対応したことに関連するAchievementです。

**2. Pull Shark**

Pull RequestがMergeされたことに関連するAchievementです。

**3. YOLO**

必要なレビュー条件を満たさずに特定のPull RequestをMergeしたことに関連するAchievementです。

**4. Galaxy Brain**

GitHub Discussionsで受け入れられた回答や役立つ貢献に関連するAchievementです。

**5. Starstruck**

自分のリポジトリが獲得したStar数のマイルストーンに関連するAchievementです。

**6. Pair Extraordinaire**

共同執筆されたコントリビューションに関連するAchievementです。

**7. Mars 2020 Helicopter Contributor**

NASA Mars Helicopterのオープンソースリポジトリに対する、条件を満たす過去の貢献によって付与されたAchievementです。このイベントは終了しており、現在は取得できません。

### Achievementsを獲得する方法

- オープンソースプロジェクトに貢献する。
- Pull Requestを提出する。
- 役立つコードレビューを行う。
- GitHub Discussionsで有益な回答を提供する。
- 他の開発者と共同でCommitを作成する。
- 役立つオリジナルプロジェクトを公開する。
- コミュニティと誠実に協力する。

### 重要

- Achievementの条件や提供状況は変更される場合があります。
- すべてのAchievementが、すべてのユーザーに自動的に提供されるわけではありません。
- 偽の活動によってAchievementを取得しようとしないでください。
- 一部のAchievementはPublic Previewです。

**公式Achievementリファレンス：**

https://docs.github.com/en/account-and-profile/reference/profile-reference

# 38. GitHubプロフィールバッジ

Achievementsに加えて、GitHubプロフィールには特定のプログラムに関連するバッジが表示される場合があります。

例：

### Developer Program Member

GitHub Developer Programに登録し、GitHub APIを使用したアプリケーションを開発している開発者向けのバッジです。

https://github.com/developer

### PRO Badge

GitHub Proのサブスクリプションを利用しているユーザーには、プロフィールにPROバッジが表示される場合があります。

https://github.com/pricing

### Security Bug Bounty Hunter

GitHub Securityプログラムを通じた、対象となるセキュリティ調査への貢献に関連しています。

https://bounty.github.com/

### GitHub Campus Expert

GitHub Campus Programに参加する資格を持つメンバー向けです。

https://education.github.com/

### Security Advisory Credit

GitHub Advisory Databaseに受け入れられたセキュリティアドバイザリを提出した場合、クレジットが付与されることがあります。

https://github.com/advisories

**注意：** プロフィールバッジとAchievementsは同じものではありません。それぞれ参加条件が異なります。

# 39. コントリビューショングラフ

GitHubのコントリビューショングラフは、カレンダー形式でコントリビューション活動を表示します。

条件を満たすさまざまな活動がコントリビューションとしてカウントされる場合があります。

- Commits。
- Pull Requests。
- Issues。
- Discussions。

### 緑色のマス

グラフ上の異なる色合いは、活動レベルの違いを表します。

### コントリビューションのルール

- CommitのメールアドレスはGitHubアカウントに紐付けられている必要があります。
- コントリビューションは、対象となるリポジトリとブランチで行う必要があります。
- デフォルトブランチや適用条件が重要です。
- 設定からPrivateコントリビューションを表示するよう選択できます。
- コントリビューションの日付は、UTCやCommitのタイムスタンプに基づいて計算される場合があります。

### コントリビューショングラフを改善する方法

- 定期的にコードを書く。
- オリジナルプロジェクトを開発する。
- オープンソースプロジェクトに貢献する。
- 意味のあるバグ修正を提出する。
- ドキュメントを改善する。
- 誠実に共同作業を行う。

グラフを緑色のマスで埋めるためだけに、偽のCommitを作成しないでください。

**公式ガイド：**

https://docs.github.com/en/account-and-profile/concepts/contributions-on-your-profile

# 40. GitHubのセキュリティ機能

GitHubは、複数のセキュリティ機能を提供しています。

### Dependabot

プロジェクトの依存関係にあるセキュリティ脆弱性や更新を特定するのに役立ちます。

https://docs.github.com/en/code-security/dependabot

### Secret Scanning

リポジトリ内に公開されたシークレットの検出に役立ちます。

https://docs.github.com/en/code-security/secret-scanning

### Code Scanning

ソースコード内の潜在的なセキュリティ脆弱性を特定するのに役立ちます。

https://docs.github.com/en/code-security/code-scanning

### Security Advisories

セキュリティ脆弱性を責任ある方法で文書化し、報告するために使用されます。

https://docs.github.com/en/code-security/security-advisories

### 重要

- パスワードをCommitしないでください。
- APIキーをアップロードしないでください。
- 秘密鍵を公開しないでください。
- `.env` ファイルをIgnoreしてください。
- セキュリティアラートを無視しないでください。

# 41. 倫理的ハッキング関連リポジトリの規則

サイバーセキュリティや倫理的ハッキングのプロジェクトを公開するには、追加の責任が伴います。

### 推奨されるコンテンツ

- 教育目的のセキュリティツール。
- 許可されたペネトレーションテスト用ユーティリティ。
- ネットワーク監査スクリプト。
- 脆弱性調査。
- 防御用セキュリティツール。
- ログ分析ユーティリティ。
- Linuxセキュリティ自動化。
- ドキュメントとチュートリアル。

### 重要な要件

- ツールの目的を説明してください。
- インストールガイドを提供してください。
- 依存関係を記載してください。
- 許可されたテストが必要であることを説明してください。
- 法的免責事項を含めてください。
- ユーザーのプライバシーを尊重してください。
- 不正アクセスを推奨しないでください。
- 盗まれた認証情報や非公開データベースをアップロードしないでください。

### 免責事項の例

```text
DISCLAIMER:

This project is intended for educational
purposes and authorized security testing.

Users must obtain proper permission before
testing any system or network.

The author does not support unauthorized
access, data theft, or illegal activities.

Users are responsible for their own actions
and compliance with applicable laws.
```

免責事項を記載したからといって、違法行為が合法になるわけではありません。ツールの実際の動作や配布方法も重要です。

# 42. .gitignoreガイド

`.gitignore` ファイルは、Gitがリポジトリに含めない未追跡ファイルを指定するために使用されます。

例：

```gitignore
# Environment Files
.env
.env.local

# Private Keys
*.pem
*.key
id_rsa

# Python
__pycache__/
*.pyc
venv/

# Node
node_modules/

# Logs
*.log

# Build Files
dist/
build/

# Temporary Files
*.tmp
*.bak
```

### 重要

シークレットをすでにCommitしてしまった場合、`.gitignore` に追加してもGitの履歴から自動的に削除されるわけではありません。

公開された認証情報は、直ちに取り消すか、新しいものに変更してください。

**公式ガイド：**

https://git-scm.com/docs/gitignore

# 43. GitHubでよくある間違い

次のような間違いを避けてください。

1. READMEなしでプロジェクトを公開する。
2. 理解せずにライセンスを選択する。
3. APIキーをアップロードする。
4. パスワードをコードに直接記述する。
5. 著作権を無視する。
6. 許可されていないコードをコピーする。
7. 重複したリポジトリを作成する。
8. 偽のStarsを購入する。
9. 不必要な大量Commitを行う。
10. 通常のGitで大容量ファイルをアップロードする。
11. 依存関係を更新しない。
12. セキュリティ脆弱性を無視する。
13. 誤解を招くプロジェクト説明を書く。
14. 不必要な数の空リポジトリを作成する。
15. コミュニティメンバーに対して攻撃的な態度を取る。

# 44. 開発者のベストプラクティス

プロフェッショナルなGitHub開発者は、次のことを心がけるべきです。

- オリジナルプロジェクトを開発する。
- READMEファイルを完全な状態に保つ。
- 適切なライセンスを選択する。
- 意味のあるCommitメッセージを書く。
- プロジェクトの構成を整理する。
- 依存関係を文書化する。
- セキュリティチェックを実施する。
- リリースノートを管理する。
- 責任を持ってバグを修正する。
- オープンソースコミュニティに貢献する。
- 他の開発者の権利を尊重する。
- GitHubのポリシーを定期的に確認する。

**覚えておいてください：** 量よりも、品質、独創性、ドキュメントが重要です。

# 45. GitHub公式リンク

以下は、重要な公式リソースです。

### GitHubメイン

- GitHub: https://github.com/
- GitHub Docs: https://docs.github.com/
- GitHub Blog: https://github.blog/
- GitHub Changelog: https://github.blog/changelog/
- GitHub Status: https://www.githubstatus.com/

### アカウントとプロフィール

- Account Guide: https://docs.github.com/en/account-and-profile
- Profile Guide: https://docs.github.com/en/account-and-profile/concepts/personal-profile
- Achievements: https://docs.github.com/en/account-and-profile/reference/profile-reference
- Contributions: https://docs.github.com/en/account-and-profile/concepts/contributions-on-your-profile
- Authentication: https://docs.github.com/en/authentication

### リポジトリ管理

- Creating a Repository: https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository
- README: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes
- Repository Limits: https://docs.github.com/en/repositories/creating-and-managing-repositories/repository-limits
- Git LFS: https://docs.github.com/en/repositories/working-with-files/managing-large-files
- Releases: https://docs.github.com/en/repositories/releasing-projects-on-github

### ライセンス

- License Guide: https://choosealicense.com/
- MIT: https://opensource.org/license/mit
- Apache 2.0: https://www.apache.org/licenses/LICENSE-2.0
- GPL v3: https://www.gnu.org/licenses/gpl-3.0.en.html
- GPL v2: https://www.gnu.org/licenses/old-licenses/gpl-2.0.html
- LGPL: https://www.gnu.org/licenses/lgpl-3.0.en.html
- AGPL: https://www.gnu.org/licenses/agpl-3.0.en.html
- BSD: https://opensource.org/licenses/
- Creative Commons: https://creativecommons.org/

### アカウント制限と復旧

- Terms of Service: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service
- Acceptable Use: https://docs.github.com/en/site-policy/acceptable-use-policies/github-acceptable-use-policies
- Community Guidelines: https://docs.github.com/en/site-policy/github-terms/github-community-guidelines
- Appeal & Reinstatement: https://docs.github.com/en/site-policy/acceptable-use-policies/github-appeal-and-reinstatement
- GitHub Support: https://support.github.com/contact

### 開発ツール

- Git: https://git-scm.com/
- Git LFS: https://git-lfs.com/
- GitHub Actions: https://docs.github.com/en/actions
- GitHub Pages: https://docs.github.com/en/pages
- GitHub Issues: https://docs.github.com/en/issues
- GitHub Pull Requests: https://docs.github.com/en/pull-requests
- GitHub Discussions: https://docs.github.com/en/discussions

### セキュリティ

- GitHub Security: https://docs.github.com/en/code-security
- Dependabot: https://docs.github.com/en/code-security/dependabot
- Secret Scanning: https://docs.github.com/en/code-security/secret-scanning
- Code Scanning: https://docs.github.com/en/code-security/code-scanning
- Security Advisories: https://docs.github.com/en/code-security/security-advisories

---

# 46. 最終ガイドライン

GitHubは単なるプラットフォームではありません。開発者が自分の知識、スキル、オリジナルプロジェクトを世界中の人々と共有できる機会を提供します。

責任ある開発者は、常に次のことを守るべきです。

- オリジナルコードを公開する。
- 著作権とライセンス条件を尊重する。
- アカウントのセキュリティを維持する。
- リポジトリを適切に文書化する。
- GitHubのポリシーに従う。
- コミュニティメンバーに対してプロフェッショナルに接する。
- 許可されていない活動を避ける。
- プロジェクトを定期的にメンテナンスする。

**LEARN • BUILD • SECURE • SHARE**

**Stay Ethical. Stay Secure. Keep Building.**

---

<p align="center">
  <b>GitHub Complete Handbook</b>
  <br>
  <i>開発者、オープンソース貢献者、サイバーセキュリティ学習者のための日本語ガイド。</i>
</p>

<p align="center">
  学習と責任ある開発のために作成されました。
</p>

<p align="center">
  <a href="https://github.com/">GitHub</a> ·
  <a href="https://docs.github.com/">Documentation</a> ·
  <a href="https://support.github.com/">Support</a>
</p>

