# Gizumo Lesson

Gizumo のカリキュラムを管理。やったこと、メモなどをまとめる。

---

**7/27(金)**

- 範囲　2,3　初めてのマークアップ　DIV_PUZZULE1,2,3

      - 枠はrelativeで配置→その中のボタンなどは配置やサイズなど絶対的な位置にしたいので、absolute
      
      - マークアップは上から一つづつ順が基本。横に並べるときはfloatを使用.
      
      - DIV や body タグに直接設定はしない。　全体を変えたいときは、そのタグを作って、それで囲む。
      
      - [.タグ名]tabキーで枠をショートカット作成。便利。[!]tabキーでDOCTYPE html　を記入など色々
      
      - コメントアウトは/**/で行う。//はダメ。
      
      - http://giztech.gizumo-inc.work/categories/4/140


自分メモ　file:///C:/Users/runashi-hosi/Desktop/Gizumo/DIV_PUZZLE3/puzzle2.html

***

**7/30(月)**

-　4, HTML CSS コーディングルール

      - [メンテナブル](https://coliss.com/articles/build-websites/operation/css/maintainable-css-by-adam.html):タグの命名は分かりやすくだが、見た目の名前はわからない。(ex: red / solorset)
      
      - タグ名は既存の物は使えない。ただし、繰り返し使うものは使いやすくして、再利用。
      
      - [よく使う命名例](https://qiita.com/pugiemonn/items/eaa597b79fe59a1f1506)
      
      - (新)レイアウト・パーツ 1,2,3,4,5
      
      - sellは個々でborder要素を追加して全体枠を作ります。
      
      - オブジェクト毎に情報があるから、それは分ける。共通情報はクラスを一つで対応できれば嬉しい。
      
      - レビューまだ。。



***

**8/22**

- 一回目PC　Bolt　レビュー 数回分忘れてました。。

      - 概要を取り、boxを作って仮置きからレイアウト完成→が２０日
      
      - fontや　レイアウトを画像通りに調整。
      
      - レビューを受けました。PCの方
      
      - 改善
      
            - hoverするものが足りない。
            
            - hoverするものは、大体リンクを持っているもの。リンク用のタグをつける
            
            - h1は見出しです。多用しないのと、小さなセッションではつかわない。
            
            - fixedでheaderを作っているため、ヘッダー分を開けないといけない。
            
            - 要素の塊をinnerで囲む。。→どうゆうこと？
            
            - article sectionは同じようなもの。それに一つしか中身ないのに使わないでおｋ。
            
            - 画像６枚も一塊なので、まとめる。
            
            - floatは浮いてる。回り込んでしまうため、レイアウトには気を付ける。
            
            - 今回はフォントが基本統一なので、bodyに着けておｋ、全体に掛かるもんは全体に！
            
            
***

**8/27**

- bolt PC レスポンシブデザイン

      - ＰＣ用のレビュー二回受けました。（前回直し忘れ＋細かい修正箇所）
      
      - ＰＣ版最終レビュー（hover時のcssアタッチが重複していた。修正）
      
      - レスポンシブの方、スマホ版のレイアウトを完了。細かい調整などは全部終わってから。
      
      - インデントに注意。タグの改行で、たまにしなかったりすると、自動インデントがずれる。
      
      - ホバー要素は基本リンクに付加。つまりaタグ内。
      
      - pad版はまだ。３０までには調整しておく。頑張る。３０にレビュー修正して、完成できればいいなー
      
      - 若干違うやり方してるかも。レイアウト数値を再度確認。全体にかかるものとか独立.
      
***

**8/30**

- bolt　レスポンシブ　レビュー一回目

      - 画面サイズ指定は、基礎となるものは被らせて、別は別で作る。
      
      - min-width: 0 とかいらねーでしょ。。。
      
      - innerで右にずれているものがあるheader sns
      
      - table 使いすぎ、　flexいらない　
      
      - 画像のところ、スマホパッド用のいらない列表示で　画像出ないところも、クリックできる。
      
      - varticle-alignとか、flexとか、いらないものを重複、追加しない。
      
      - inline-blockとかで横並びはできる、特殊な形は基本それでないと難しい時に使う。
      
***

**9/07**

      - 最終レビュー完了。inline-blockとか、余白とか、細かいとこに気を付ける
      
      - javascript レッスン開始　最初の基礎完了（c#まんまやんけ。。）
      
      - レイアウト気を付ける。普段の感じでやるとダメ。;後　＋　後 スペースに気を付ける。
      
      - jQuery 開始　クローンして、first   4  まで完了

***

**9/14**

      - jQuery -thirdまで 完了
      
      - レビュアーをそろそろほかの人に。。お願いしましょう。。。。
      
      - slackの宛名を入れる　　　@相手のアカウント をつけておけば　わかりやすい。。


***

**9/18**

- jQuery first からsixthまで完了。（１２３は直し。）

      - functionの全体の書き方で括りました。（グローバルになっていたので、ちょっと気を付ける。。。）

      - ４５６はやった。はやく終わったけど、書き方とかの直しがちらほら。。。

      - レビューした内容は　しっかりと確認しましょう！！！！ (調べる内容について、もうちょっと頑張る！！)

***

**9/21**

- jQuery seventh,eighth完了

      - 7.画像サイズが一律じゃないことを考えて設計する。画像の左の位置を取得して行きます。
      
      - 8はおｋ。今回課題ではeachで配列要素全部回して、一致したやーつに処理という感じ、私は直接data属性指定して、選択しました。まあ、おｋ
      
      - ninthは入ったが、サーバー立ち上げで躓いたｗｗ　後でまとめて記事に手順記入！　綺麗に作って、他で使ってもらいましょうｗ
      
***

**9/26**

- jQuery ninth 参考　https://www.sria.co.jp/blog/2014/10/lets-use-ajax-part-1-try-it-with-ajax-and-json/

      - ninth 完了
      
      - seventh 画像サイズは均一とは限らないー＞　画像サイズを端から足していき、配列にあらかじめポジションを入れておく。
      
      - 

***

**9/**


***
