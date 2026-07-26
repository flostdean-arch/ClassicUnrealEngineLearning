# Troubleshooting

このページでは、**Classic Unreal Engine Learning** の学習環境を構築する際によく発生する問題と、その対処方法についてまとめています。

ここに掲載されている内容は、**OldUnreal** 版を前提としています。

---

# Before Troubleshooting

問題が発生した場合は、まず以下を確認してください。

* 使用しているタイトルは本リポジトリの対象環境か
* 最新の OldUnreal 版を使用しているか
* Windows を再起動しているか
* ゲームを一度終了し、再度起動しているか

多くの問題は、これらを確認することで解決できます。

---

# Game Does Not Start

## Symptoms

* ゲームが起動しない
* 起動直後に終了する
* エラーメッセージが表示される

## Possible Causes

* インストールが正常に完了していない
* 必要なファイルが不足している
* セキュリティソフトによるブロック

## Solutions

* インストール先を確認する
* ゲームを再インストールする
* 必要に応じて管理者権限で実行する

---

# UnrealEd Does Not Start

## Symptoms

* UnrealEd が起動しない
* 起動途中で終了する
* 画面が表示されない

## Possible Causes

* 設定ファイルの破損
* インストールの不備
* 初回起動時の設定エラー

## Solutions

* 設定ファイルを初期化する
* UnrealEd を再起動する
* 必要に応じて再インストールする

---

# Rendering Problems

## Symptoms

* 画面が真っ黒になる
* テクスチャが表示されない
* Viewport が更新されない
* 描画が乱れる

## Solutions

* レンダラー設定を確認する
* グラフィックスドライバーを更新する
* 別のレンダラーを試す

---

# Audio Problems

## Symptoms

* BGM が再生されない
* 効果音が鳴らない
* 音が途切れる

## Solutions

* Windows の音量設定を確認する
* ゲーム内のオーディオ設定を確認する
* オーディオデバイスを確認する

---

# Input Problems

## Symptoms

* マウスが動かない
* キーボード入力を受け付けない
* カメラ操作ができない

## Solutions

* ゲームを再起動する
* 入力設定を確認する
* 他の入力デバイスとの競合を確認する

---

# Performance Problems

## Symptoms

* 動作が重い
* フレームレートが低い
* UnrealEd の操作が遅い

## Solutions

* 不要なアプリケーションを終了する
* 描画設定を見直す
* グラフィックスドライバーを更新する

クラシック Unreal Engine は比較的軽量なため、現代の PC では大きな性能不足が原因となるケースはほとんどありません。

---

# Configuration Problems

## Symptoms

* 設定が保存されない
* 毎回初期設定に戻る
* UnrealEd の設定が反映されない

## Solutions

* インストールフォルダへの書き込み権限を確認する
* 設定ファイル（INI）が正常に生成されているか確認する
* 必要に応じて設定ファイルを再生成する

---

# Still Having Problems?

ここに掲載されていない問題が発生した場合は、以下を確認してください。

* 最新版の OldUnreal を使用しているか
* インストール手順に誤りがないか
* 設定ファイルを変更していないか

それでも解決しない場合は、OldUnreal コミュニティや関連フォーラムなどの情報も参考にしてください。

---

# Next Step

Getting Started の内容は以上です。

環境構築が完了したら、**Common** ディレクトリへ進み、UnrealEd の基本操作やクラシック Unreal Engine に共通する開発手法を学びましょう。
