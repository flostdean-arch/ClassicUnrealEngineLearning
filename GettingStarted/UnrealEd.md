# UnrealEd

このページでは、**UnrealEd** の概要と起動方法について説明します。

UnrealEd は、**Unreal Engine 1** および **Unreal Engine 2.5** に付属する統合開発環境（IDE）です。

マップ制作をはじめ、オブジェクト配置、ライティング、スクリプト編集、ゲームプレイ構築など、ゲーム開発に必要な機能が統合されています。

本リポジトリでは、以降の学習で UnrealEd を中心に使用します。

---

# What is UnrealEd?

UnrealEd は、Epic Games が Unreal Engine 向けに開発したレベルエディタです。

単なるマップエディタではなく、ゲーム開発全体を支える統合開発環境として設計されています。

UnrealEd では、以下のような作業を行えます。

* レベル制作
* BSP モデリング
* Static Mesh の配置（UE2.5）
* テクスチャ設定
* ライティング
* アクター配置
* Trigger の設定
* パスネットワークの作成
* UnrealScript の編集
* マップのビルド
* テストプレイ

---

# Supported Versions

本リポジトリでは、以下の UnrealEd を対象としています。

| Title                    | Editor     |
| ------------------------ | ---------- |
| Unreal Gold              | UnrealEd 1 |
| Unreal Tournament (1999) | UnrealEd 2 |
| Unreal Tournament 2004   | UnrealEd 3 |

バージョンごとに機能やユーザーインターフェースには違いがありますが、基本的な操作方法や開発の考え方は共通しています。

---

# Starting UnrealEd

UnrealEd は各タイトルの **System** フォルダから起動できます。

起動方法はタイトルによって異なりますが、一般的にはゲームランチャーまたは UnrealEd 実行ファイルから起動できます。

初回起動時は設定ファイルの生成などにより、通常より時間がかかる場合があります。

---

# Main Window

起動すると、UnrealEd のメインウィンドウが表示されます。

通常は以下のような構成になっています。

* メニューバー
* ツールバー
* 2D Viewport
* 3D Viewport
* ブラウザウィンドウ
* ログウィンドウ

これらの役割については、**Common** ディレクトリで詳しく解説します。

---

# Basic Workflow

UnrealEd を利用した一般的な開発の流れは以下のようになります。

1. 新しいマップを作成する
2. BSP を配置する
3. テクスチャを設定する
4. ライトを配置する
5. アクターを配置する
6. パスネットワークを作成する
7. マップをビルドする
8. テストプレイを行う
9. 必要に応じて修正する

本リポジトリでは、この流れに沿って各機能を学習していきます。

---

# Differences Between Versions

UnrealEd は世代によって機能が進化しています。

| Version    | Main Features                                                 |
| ---------- | ------------------------------------------------------------- |
| UnrealEd 1 | Unreal Gold に付属する初期バージョン                                      |
| UnrealEd 2 | Unreal Tournament 向けに改良されたバージョン                               |
| UnrealEd 3 | Unreal Tournament 2004 に付属し、Static Mesh や Karma Physics などに対応 |

基本的な考え方は共通しているため、一度操作を覚えれば他のバージョンにも応用できます。

---

# Notes

本リポジトリでは、各バージョン固有の機能については、それぞれのタイトル別ディレクトリで解説します。

一方、複数のバージョンで共通する内容については **Common** ディレクトリにまとめています。

---

# Next Step

Getting Started はこれで終了です。

次は **Common** ディレクトリへ進み、UnrealEd の画面構成や Viewport 操作、ブラシ編集など、クラシック Unreal Engine に共通する基礎知識を学びましょう。
