# **Gizumo Lesson**
      
Gizumo のカリキュラムを管理。やったこと、メモなどをまとめる。**/()**

---
***

**2/22**


***

**2/22**


***

**2/22**


***

**2/22**
- greenhorn管理者作成　作成メール送信機能

      - まだ受け取り切れてない。createもコメントアウトしてるから後で、完成したら直す。
      
      - 次回課題にいきたいところだ。。

***

**2/21**
- GreenHorn課題開始

      - GD拡張モジュール追加
      
      - katakanaのバリデーション処理を追加（変数の直し）
      
      - updateメソッドのwhereでカラム指定する
      
      - 課題は他にあるけど、基本はエラーがあるから、その修正をして、完全版にしたら、課題。
***

**2/19**
- vagrant 使用なしで進める。まあ、すぐにできた。。ｗ

      - .envファイルの扱いには気を付ける。変更・登録ー＞（キー取得）ー＞マイグレート
      
      - composerで入れると管理してくれる。mysql でのdatabaseを自動で作ってくれるので、別段設定いらない。（別projectのは絶対ダメ！）
      
      - .envファイル　や vendorフォルダ は初期はないはず。cloneしてきたものに入っている場合、管理が間違っている。環境依存になってる。
      
      - 以上反省点　とりあえず理解。 次回、課題！！
      
***

**2/15**
- homestead でやったけど　初期のページしか出せない。　構成が違うからポートがすべておかしいのと、手順が違う

      - 3度目の正直で、もうピュアでやるしかないことになった。。
      
      - こんなにきょうりょくしてもらったのに。。。ひえ。。
***

**2/14**
- vagrant virtualbox laravel 起動までやったけど

      - laravel homesteadを使うことになった。これが失敗ならもう無理。。
      
      - 明日で完了しないといよいよまずい。。。何もできてない。。。
      
      - 問題はssh通信によるポートのアクセス権限など、目に見えないのでしっかりと手順通りに焼ていくしかない。

***

**2/08**
- 再度vagrantとdoker からのgreenhornに入った。

      - もう一回試してみたけど、無理。。。　クローンの仕方が最後の最後で分かったので、それで進める！！！
      
      - greenhornに入って、起動できた。　

***

**2/01**
- vagrant docker

       - docker インストールでこけた。。やっぱりこのPCじゃ無理。。
       
       - greenhornのやつをもらったので、それを早速やってOK。早く頑張るぞ。内容はわかってるのだ。。

***

**1/25(金)**
- vagrant できたわ。。　面談に際して、、

      - 面談の前の心構えをいくつか　５つの要素などメモったよー
      
      - windows10 homeの設定だったので。仮想環境の設定がdisableだったのが原因だった。 
      
      - 直したらすぐにうごいたのと、vagrant sshでRlogin使わずにログインできた。
      
      - mysql　のインストール５章バージョン確認から開始！！
      
***

**1/18(金)**
- 仮想環境　vagrant 

      - 全く進まなかった。
      
      - ssh でログインするのはrloginでやるけど、どうやるの？？
      
      - keyが違う？ポート番号？

***

**1/11(金)**
- 仮想環境　vagrant

      - vagrant 内のcentOSを使って、インストールとかの補助してもらう形。
      
      - セッションロックに掛かり、起動できなかったので、タイムアウトしていた。
      
      - ３章　インスト―ル終わった。
      
***

**12/28(金)**
- php laravel Unit test機能　修正　

      - testはログイン前だけで、やっぱりよかったん。。
      
      - すべてloginによるエラー　failで、loginにないテーブルにアクセスできない、遷移した場所と違うなどなど。
      
      - ログインしてからならおKだし、今回indexで俺がやってるのは、login画面介してtodoにいっているという確認。
      
      - setup がテストの最初には動いているので、そこで、ログインなどの機能を入れ込んでしまえば、問題なくテストが通るはず。。。
      
      - 次回は仮想環境進めます。まずvagrantで、作成の作業から行います。初回起動まで完了。c< vagrant_test<vagrentfileが入ってる　編集完了済

***

**12/21(金)**
 - php laravel Unit 仮想環境
 
      - インストール済なので、設定などと、一通り作業してみた。
      
      - テストをしてログイン機能をつけた。（ほかのユーザーから閲覧できないようにカラムをつけた。）
      
      - ログインつけたらテストの種類がかわるので、次回は302のエラーを直す
      
      - 200番エラーは[HTTPステータスコード](https://ja.wikipedia.org/wiki/HTTP%E3%82%B9%E3%83%86%E3%83%BC%E3%82%BF%E3%82%B9%E3%82%B3%E3%83%BC%E3%83%89)で確認できる。
      
      - 302ではリダイレクト（リンク先が変更しているエラー）その先をテストしないと意味ないので、それを次にやる。
      
***

**12/14(金)**
- php laravel　レビュー

      - 前回の質問で解決していたので、ラクラク！　一部反省点↓
      
      - フォームの記述は　laravel Corective の機能で、特殊な書き方をしているので、利点は？→エスケープ、チェックトークンなどを行ってくれるし、post getなどのアクセス方法をしていなどができる。
      
      - レビュー　完了　次回は　php Unitのお話。　tera termとか使ってるやつまんま。。virtualbox何かも使って、やったことの復習ですな。。
      
***

**12/7(金)**
- php laravel 開始

      - 手順通りに作成完了　laravel Corectiveの機能を使っている
      
      - 質問：route list について、　何で、最初にindex呼ばれるんや？
      　　A :getでページを呼び出している場合はindexが呼ばれる　ブラウザの検索はURLにデータを入れて、getでアクセスしている！！
        
      - 質問：redirect->to()って、再読み込み？
          A :redirectで状態遷移メソッド　to はその場所指定。to内部で指定したものをgetで送るため、indexが再度呼ばれる。
          　 そうしないと、全件取得してないので、更新追加内容が反映されていない状態となる。

***

**11/30(金)**

- ペアプロやった（あざましたー！）

      - laravelの導入
      
      - もうすでにやっていたこともあり、インストールなんかを再度消してからやった。
      
      - 次はやってきてレビュー。一文づつしっかりと説明。
      
      - レビュー手順https://trello.com/c/7SCxZmBJ/86-%E3%83%AC%E3%83%93%E3%83%A5%E3%83%BC%E6%89%8B%E9%A0%86

***

**11/16(金)**

- php lesson レビュー完了

      - ペアプロは再来週
      
      - PDOstatement　メソッドの理解。まとめておく。
      
      - Laravel　インストールしておく。（分からないところはslackで）


***

**11/02(金)**
- php lesson 一週目完了！！

      - 今度はペアプロらしいです。。それまでに完璧にまとめておこうかな。。。
      
      - デバッグログ様ですわ。。分からなくなったら一度離して、順をたどっていく。
      
      - 値が入っているか、ちゃんと通っているか、しっかりと試すことが重要！！
      
      - var_dump();exit();  （）内のを表示して、、、exitで停止させる。どこで止まったかもわかるし、便利。
      
***

**10/26(金)**

- mysql 再インストール　

      - サービスから、動いているファイル全消ししてインストールをし直します。残ったファイルがあると事故る。
      
      - 再起動重要　インストールは特に行わない気がするが、アンインストールでは、更新しておくのに再起動で一新。
      
      - 起動がポートを指定せずにできる。バージョンもそろえたので、次回からはしっかりとphpレッスンを進めていきましょう。
      
      - 今回は既存のものが入っていたため、混乱したが、これが言い訳にならぬよう、しっかりと環境構築をしていく。。

***

**10/19(金)**

- php app　todo 8- 13

      - コマンド系統が全然わからない。使うコマンドは分かるけど、インストールされてなかったり、あとバージョン、
      
      - 最大の難関はそこ。。使えないとかよくある話。。
      
      - やり直します。最初からできるものでやれば良かったんです。。もう一回やってるmysql5.7ならすぐに使えたし、
      
      - 情報載ってたし、、調子に乗りすぎたのが原因。。反省。。
***

**10/12(金)**

- php 環境構築

      - すべて教える人が知ってるわけではなく、その探す能力と、経験からの予測がある。。
      
      - windowsとmacで結構違う。。macやってる人でも、概念は分かってるから、調べりゃできる。。そんな風になりたい。。
      
      - 今日の進捗はphp　lesson 11下準備まで。インストールやらなにやら、完了。
      
            - 起動　　mysql -u root -p -P 3307　　　とかやってポート指定して起動する。
            
            - 終了　　mysql exit                    でおｋ。


***

**10/9(火)**

- jQuery tenth 完了

      - errorメッセージは、コンソールに表示したり、開発者がみるなら分かるが、ユーザーは、〇〇errorとか言っても分からない。
      
      - エラーメッセージは分かりやすく、ユーザーにして欲しい操作を示すのが吉。
      
      - リクエストの制限など、できるにはできるが、動きがおかしくならないなら、それに対する手順を示唆するだけでいい。
      
      - オブジェクト指向のやつは、やっていけばいい。。。。
      
      - php はいったー。練習問題１完了。基本的な構文あたり、簡単だが、他とごっちゃになってる。。。頑張る。。
      
      - php コーディングルールが違うらしい。if () { : for () { という具合に、開けて書く。関数は↓
            
```js
function ooo()
{
//処理
}

      - 演算子は間隔開け、,なども、、これは同じ。。
      
      - ネストは避ける。。これも同じ。。
      
- まあ、アルゴリズムはわかっているから、別段、綺麗に書いたり、パフォーマンスを気を付けるだけ。。
            
```


***

**10/5(金)**

- jQuery seventh tenth 

      - seventh は画像サイズに対応したやりかた。レビューＯＫ。nextで次にアクセスしていたが、効率悪いカモ。。
      
      - tenth ちょっと焦りすぎやん。。一日でレビューまでと、一回直ししたけども、調べることが調べられなかった。。
      
      - failの引数で、エラーのmessageを変えるのと、done とで処理を分けること、
      
      - リクエスト送るだけで、こんなに簡単な形にしてくれるとは思ってなかった。。早とちりが原因です。。
      
***

**9/26(水)**

- jQuery ninth 参考　https://www.sria.co.jp/blog/2014/10/lets-use-ajax-part-1-try-it-with-ajax-and-json/

      - ninth 完了 appendで一要素ず追加していたのを、まとめて文字列にして、htmlメソッドで一気にぶち込んだ。
      
      - seventh 画像サイズは均一とは限らないー＞　画像サイズを端から足していき、配列にあらかじめポジションを入れておく。
      
      - tenth 途中まで。。やることは書いた。あとはやるだけ、関数分けもおｋかな??
      
      - サーバー立てないとダメみたいやねん。楽天ＡＰＩか、ＡＰＩの意味的なのを調べるのも和すｒ図に
      
***

**9/21(金)**

- jQuery seventh,eighth完了

      - 7.画像サイズが一律じゃないことを考えて設計する。画像の左の位置を取得して行きます。
      
      - 8はおｋ。今回課題ではeachで配列要素全部回して、一致したやーつに処理という感じ、私は直接data属性指定して、選択しました。まあ、おｋ
      
      - ninthは入ったが、サーバー立ち上げで躓いたｗｗ　後でまとめて記事に手順記入！　綺麗に作って、他で使ってもらいましょうｗ
      
***


**9/18(火)**

- jQuery first からsixthまで完了。（１２３は直し。）

      - functionの全体の書き方で括りました。（グローバルになっていたので、ちょっと気を付ける。。。）

      - ４５６はやった。はやく終わったけど、書き方とかの直しがちらほら。。。

      - レビューした内容は　しっかりと確認しましょう！！！！ (調べる内容について、もうちょっと頑張る！！)

***

**9/14(金)**

      - jQuery -thirdまで 完了
      
      - レビュアーをそろそろほかの人に。。お願いしましょう。。。。
      
      - slackの宛名を入れる　　　@相手のアカウント をつけておけば　わかりやすい。。

***

**9/07(金)**

      - 最終レビュー完了。inline-blockとか、余白とか、細かいとこに気を付ける
      
      - javascript レッスン開始　最初の基礎完了（c#まんまやんけ。。）
      
      - レイアウト気を付ける。普段の感じでやるとダメ。;後　＋　後 スペースに気を付ける。
      
      - jQuery 開始　クローンして、first   4  まで完了

***

**8/30(木)**

- bolt　レスポンシブ　レビュー一回目

      - 画面サイズ指定は、基礎となるものは被らせて、別は別で作る。
      
      - min-width: 0 とかいらねーでしょ。。。
      
      - innerで右にずれているものがあるheader sns
      
      - table 使いすぎ、　flexいらない　
      
      - 画像のところ、スマホパッド用のいらない列表示で　画像出ないところも、クリックできる。
      
      - varticle-alignとか、flexとか、いらないものを重複、追加しない。
      
      - inline-blockとかで横並びはできる、特殊な形は基本それでないと難しい時に使う。
      
***

**8/27(月)**

- bolt PC レスポンシブデザイン

      - ＰＣ用のレビュー二回受けました。（前回直し忘れ＋細かい修正箇所）
      
      - ＰＣ版最終レビュー（hover時のcssアタッチが重複していた。修正）
      
      - レスポンシブの方、スマホ版のレイアウトを完了。細かい調整などは全部終わってから。
      
      - インデントに注意。タグの改行で、たまにしなかったりすると、自動インデントがずれる。
      
      - ホバー要素は基本リンクに付加。つまりaタグ内。
      
      - pad版はまだ。３０までには調整しておく。頑張る。３０にレビュー修正して、完成できればいいなー
      
      - 若干違うやり方してるかも。レイアウト数値を再度確認。全体にかかるものとか独立.
      
***

**8/22(水)**

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

**7/27(金)**

- 範囲　2,3　初めてのマークアップ　DIV_PUZZULE1,2,3

      - 枠はrelativeで配置→その中のボタンなどは配置やサイズなど絶対的な位置にしたいので、absolute
      
      - マークアップは上から一つづつ順が基本。横に並べるときはfloatを使用.
      
      - DIV や body タグに直接設定はしない。　全体を変えたいときは、そのタグを作って、それで囲む。
      
      - [.タグ名]tabキーで枠をショートカット作成。便利。[!]tabキーでDOCTYPE html　を記入など色々
      
      - コメントアウトは/**/で行う。//はダメ。
      
      - http://giztech.gizumo-inc.work/categories/4/140


自分メモ　file:///C:/Users/runashi-hosi/Desktop/Gizumo/DIV_PUZZLE3/puzzle2.html

