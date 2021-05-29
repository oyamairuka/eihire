# Eihire

<br>
小さなc++ライブラリ<br>
<br>

## 概略
ライブラリ作成及びテストツール(Google Test)の練習も兼ねたもの<br>
機能は非常に簡単なものになるが<br>
実際のコンソールアプリケーションの作成等に利用可能な内容を目指す<br>
<br>

## ビルド
CMakeを利用する<br>
ローカルのマシン上での簡単なコンソールアプリケーション等での利用を想定しているので<br>
まずはWindows上でのビルドに限定する<br>
<br>

## 機能
機能ごとにディレクトリを分けて<br>
その配下にREADMEを作成して機能を記述する予定<br>
<br>
今現在の簡単な一覧<br>
- Configuration
    - 設定ファイル(****.properties)を指定してその内容を読み込んだ連想配列を作るクラス等が入る
- Exception
    - エラー内容を見分けやすくするための簡単な独自例外クラスが入る
- Logging
    - ログ出力のためのクラスが入る
