# 2020年夏季休暇課題
# 課題内容

## 必須課題
### NWプログラミング
- VirtualBox上にUbuntuをインストールし、Nginxを用いたPHP開発環境を構築する。  
  去年の2年生が作成した環境構築手順書は[こちら](https://github.com/human-osaka-game-2018/NWAndToolHomework/tree/master/HowToCreatePhpDevelopmentEnvironment)。  
  自分で行ってみた後や、作業に詰まったときに参考にして下さい。
- 上記UbuntuマシンにMariaDBをインストールし、コンソール上でSQLを実行できるように設定する。  
  同時に基本的なSQLの文法を勉強し実験する。
- 情報リテラシーの方の課題でインストールするMySQLWorkbenchからUbuntu上のMariaDBにSQL実行を行う環境を構築する。

### 情報リテラシー
- Windows上にMySQLとMySQLWorkbenchをインストールし、MySQLWorkbenchからSQL実行を行う環境を構築する。  
- 授業で作成したWindowsFormsプロジェクトに複数の敵情報を登録する画面を追加し、登録内容をMySQLに保存する機能を追加する。  
- 画面初期表示時はDBに保存しているデータを読み込み、更新も行えるようにする。

## 選択課題
下記から1つ以上コースを選択し、その課題を実施する。  
選択したコースと作業内容、成果物、課題実施により身に付いたものや気付いたこと等をMarkdown形式のレポートにまとめる。  
成果物もリポジトリに上げ、レポート内にリンクを設定すること。

### フロントエンド強化コース
- 前期課題のSlackWebAPI利用サイトのオプション課題を実施する(未実施の場合)。
- [MDN](https://developer.mozilla.org/ja/docs/Learn/Getting_started_with_the_web)を順次読み込み、途中にある問題を実施する。
- 前期の授業で作成したWebページのページTOPへスクロールするボタンとハンバーガーメニューの機能をJavaScriptで実装する。
- 前期課題提出物をデザイン、UI、UXを洗練された状態へとバージョンアップする。

### サーバサイド強化コース
- 前期課題のSlackWebAPI利用サイトと同じ機能をUbuntu上にPHPで構築する。
- HTTPメソッドについて調査する。
- RESTについて調査する。

### DB強化コース
- 主キー、複合キー、外部キーについて勉強する。
- 正規化について勉強する。
- Slackと同等の機能を持つチャットツールを構築するのに必要なDBのテーブル設計を行い、ER図を作成する。  
  ER図はMySQLWorkbehchで作成するのが便利。
- 授業で作成したWindowsFormsプロジェクトから接続するDBをUbuntu上のDBに変更する。  
  Windows,UbuntuどちらのDBにも接続可能なように、app.configの設定で簡単に切替可能な仕組みを構築する。 

### C#強化コース
- [未確認飛行のC#の解説ページ](https://ufcpp.net/study/csharp/)を最初から最後まで読み込む。
- [パフォーマンス向上で知っておくべきコンピューターサイエンスの基礎知識とその実践](https://qiita.com/higty/items/306eebe988af39ba775d)を記事からのリンク先も含め読み込む。
- 授業で作成したWindowsFormsプロジェクトに以下の機能を追加する。
  - 出力したXMLファイルを読み込んで画面に表示する。
  - XMLだけでなくJSONでも入出力を行えるようにする。
  - 仕様変更が発生してコンボボックスの文字列表現が変更になったとしても、仕様変更前に出力したXML/JSONファイルを読み込めるようにする仕組みを構築する。
  - 敵情報をCSV形式でエクスポートできるようにする。
  - Genericsを用いてInfrastructure層からDomain層への依存をなくす。

### 設計強化コース
- 授業で作成したWindowsFormsプロジェクトの設計を以下のように変更する。
  - Genericsを用いてInfrastructure層からDomain層への依存をなくす。
  - Interfaceを用いて依存性逆転の原則を実現し、Application層からDomain層への依存、Infrastructure層からDomain層への依存(存在すれば)をなくす。  
    参考: [1分でわかる依存関係逆転の原則(DIP)](https://qiita.com/wanko5296/items/29e74cc7dd7562624d08)
  - 出力仕様がXMLからJSONに切り替わったときに関連する部分のみのプログラム変更で済むようにクラス設計を行いリファクタリングする。  
    その後JSON出力処理を追加してプログラム変更量を少なくできていることを確認する。（できていなかったら設計見直し）
  - 接続するDBをUbuntu上のDBに変更する。  
    Windows,UbuntuどちらのDBにも接続可能なように、app.configの設定で簡単に切替可能な仕組みを構築する。
- MVx, MVVMについて調査する。
- Slackと同等の機能を持つチャットツールを構築するためのクラス設計を行い、クラス図を作成する。（WPF、MVVM前提とする）

### 就活コース
就職活動に関する調査、書類作成、面接、作品制作等を行う。  
※ レポートに企業名や個人情報が含まれる場合はSlackで提出すること。  
※ 企業向けの提出書類を成果物とする場合はSlackで提出すること。  

### 自主計画コース
資格取得等、特定の勉強したい項目が定まっている人用。


# 提出方法
ここに個人ごとのfolderを作成し、その中にレポートを置いて下さい。  
実験コード、手書きの図、ER図等夏季休暇中の作業成果物も整理して置いて下さい。  
（ある程度ボリュームのあるプロジェクトは別途リポジトリを作成すること）

IssueやWikiなどは自由に活用して下さい。