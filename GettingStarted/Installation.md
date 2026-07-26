# Installation

このページでは、**Classic Unreal Engine Learning** の学習環境を構築する方法について説明します。

本リポジトリでは、**OldUnreal** コミュニティが提供する **Unreal Gold**、**Unreal Tournament (1999)**、**Unreal Tournament 2004** を前提として解説します。

---

# Before You Begin

インストールを始める前に、以下を確認してください。

* **SystemRequirements.md** を確認済みであること
* **Download.md** を読み、必要なタイトルを入手済みであること
* Windows 10 または Windows 11 を使用していること

---

# Installation Order

初めて学習する方は、以下の順番でインストールすることを推奨します。

1. Unreal Gold
2. Unreal Tournament (1999)
3. Unreal Tournament 2004

すべてを一度にインストールする必要はありません。

まずは **Unreal Gold** のみインストールし、学習を進めながら必要に応じて他のタイトルを追加するとよいでしょう。

---

# Installation Directory

特別な理由がない限り、インストール先はデフォルト設定のまま利用することを推奨します。

例

```text
C:\Games\UnrealGold\
C:\Games\UnrealTournament\
C:\Games\UT2004\
```

> **Note**
>
> `Program Files` 配下へのインストールでも動作する場合がありますが、Windows のアクセス権限によって設定ファイルや MOD の管理がしづらくなることがあります。
>
> 学習用途では、ユーザーが自由に読み書きできるフォルダへインストールすることを推奨します。

---

# Verify the Installation

インストールが完了したら、以下を確認してください。

* ゲームが正常に起動する
* タイトル画面が表示される
* エラーが発生しない
* 設定ファイルが自動生成される

この時点では、ゲームをプレイする必要はありません。

正常に起動できることを確認できれば十分です。

---

# UnrealEd

次に、各タイトルに付属する **UnrealEd** が起動できることを確認してください。

確認する内容

* UnrealEd が起動する
* エディタ画面が表示される
* Viewport が正常に描画される
* エラーが表示されない

UnrealEd の基本操作については **UnrealEd.md** で詳しく解説します。

---

# Folder Structure

インストール後のディレクトリ構成はタイトルによって多少異なりますが、一般的には以下のような構成になります。

```text
Game Folder
│
├── System/
├── Maps/
├── Textures/
├── Sounds/
├── Music/
├── Help/
├── Save/
└── ...
```

学習を進める中で、これらのフォルダを頻繁に利用します。

各フォルダの役割については、今後のドキュメントで順次解説します。

---

# Recommended Backup

学習を始める前に、インストール直後の状態をバックアップしておくことを推奨します。

バックアップを作成しておくことで、

* 設定を元に戻したい場合
* MOD を試した後に初期状態へ戻したい場合
* 学習環境を再構築したい場合

などに簡単に復元できます。

---

# Common Problems

インストール時によくある問題

* ゲームが起動しない
* UnrealEd が起動しない
* 画面が真っ黒になる
* 設定ファイルが生成されない

これらの問題については **Troubleshooting.md** を参照してください。

---

# Next Step

インストールが完了したら **FirstLaunch.md** に進み、初回起動時の設定や確認事項について学びましょう。
