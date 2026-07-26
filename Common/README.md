# Common

このディレクトリでは、**Unreal Engine 1** および **Unreal Engine 2.5** に共通する機能や開発手法について学びます。

クラシック Unreal Engine はバージョンごとに追加・変更された機能はありますが、基本的な開発思想や UnrealEd の操作方法には多くの共通点があります。

そのため、本リポジトリでは複数のタイトルで共通する内容を **Common** にまとめ、タイトル固有の機能については各ディレクトリで解説します。

---

# Purpose

Common の目的は、クラシック Unreal Engine を利用する上で必要となる基礎知識を身につけることです。

ここで学ぶ内容は、

* Unreal Gold
* Unreal Tournament (1999)
* Unreal Tournament 2004

のすべてで活用できます。

---

# Contents

Common では、以下のような内容を扱います。

* UnrealEd の画面構成
* Viewport の操作
* ブラシ編集（Brush）
* BSP / CSG
* Actor
* Texture
* Lighting
* Movers
* Navigation
* マップのビルド
* UnrealScript 基礎
* テストプレイ
* 開発時のベストプラクティス

---

# Learning Order

初めて学習する方は、以下の順番で読み進めることを推奨します。

1. Interface
2. Viewports
3. Navigation
4. Brushes
5. BSP
6. Actors
7. Textures
8. Lighting
9. Movers
10. Build
11. UnrealScript

この順番で学ぶことで、UnrealEd の基本操作からゲームプレイ構築までを段階的に理解できます。

---

# Version Differences

本ディレクトリでは、可能な限り Unreal Engine 1 と Unreal Engine 2.5 の共通事項を扱います。

バージョン固有の仕様や新機能については、それぞれのタイトル別ディレクトリで詳しく解説します。

例

| Common          | Title-specific  |
| --------------- | --------------- |
| Viewport 操作     | UnrealEd 3 の新機能 |
| Brush           | Static Mesh     |
| BSP             | Karma Physics   |
| Actor           | Vehicle         |
| Lighting        | GUI             |
| UnrealScript 基礎 | Onslaught       |

---

# Relationship with Other Directories

学習全体の流れは以下のようになります。

```text
GettingStarted
        │
        ▼
      Common
   ┌────┼────┐
   ▼    ▼    ▼
UnrealGold
UT99
UT2004
```

まず **GettingStarted** で学習環境を構築し、その後 **Common** で基礎知識を身につけます。

基礎を理解した後は、各タイトルのディレクトリへ進み、ゲームごとの機能や開発手法を学習してください。

---

# Notes

Common は本リポジトリの基礎となるディレクトリです。

以降のドキュメントでは、ここで学んだ知識を前提として解説を進めます。

分からない内容があった場合は、必要に応じて Common に戻り、基礎を確認することをおすすめします。

---

# Next Step

まずは **Interface** を読み、UnrealEd の画面構成や各ウィンドウの役割について学びましょう。

UnrealEd の基本的な画面構成を理解することが、その後の学習をスムーズに進める第一歩となります。
