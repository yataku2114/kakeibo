# 家計簿 ～お金持ちへの第一歩～

## サイト概要
誰でも簡単に使うことができる家計簿アプリ。
科目設定、収支登録、収支確認を行うことができる。
使用方法は、初めに科目設定で収入、費用の登録をします。
次に収支登録で日々の金額を登録をします。
最後に収支確認で月々、年間の収支結果をグラフで確認できます。
家計簿の機能だけではなく、サイト内にはお金の増やし方についても記述しています。
この家計簿を使うことで日々のお金の管理だけではなく、お金を増やす方法について学べます。


### サイトテーマ
いつでもお金の管理ができる家計簿サイト

### テーマを選んだ理由

「老後2000万円問題」

この言葉を聞いたことはあるでしょうか？
今後、老後資金が2000万円不足となると発表され話題となった言葉です。
つまり老後（65歳）になるまでに少なくとも2000万円が必要になるということです。
しかし、今現在、老後のために2000万円貯めることは容易ではありません。

そこで！
このアプリを通じて「お金の増やし方」をお手伝いさせて頂ければと思っています。
銀行の渉外担当として様々なお客さまの資産形成をサポートさせて頂きました。
その経験をこのアプリに活用し、より多くの方へ役立てるためにこのテーマを選びました。

まずは現状を理解するためにも家計簿を通じてお金の動きを見えるようにします。
そのうえで、これからどう増やしていくかをサイトを通じて利用していただくユーザーにお伝えするために家計簿を選びました。


### ターゲットユーザ
お金を管理したい人

### 主な利用シーン
お金の収入・支出がある時

## 設計書
テーブル一覧
https://docs.google.com/spreadsheets/d/1ls3e3DvFT5kyNQswl9CV2eIwt_IyeHRDYHXTNZJiHvE/edit#gid=1243549839

ER図
https://app.diagrams.net/#G1hB0s40S_okEdq4uD83scDNaXFhE46Hm3

## チャレンジ要素一覧
https://docs.google.com/spreadsheets/d/1MKukODIPIKP0dX-Ij9MOxgNNewZDcx5iFNIExAHcPp8/edit#gid=0

## 機能一覧
- ユーザー登録、ログイン機能（devise）
- 収入、固定、変動費科目登録機能
- 各項目の金額登録機能
- 各月の収支差表示機能
- 要望機能

## 開発環境
- OS：Linux(CentOS)
- 言語：HTML,CSS,JavaScript,Ruby,SQL
- フレームワーク：Ruby on Rails
- JSライブラリ：jQuery
- IDE：Cloud9
