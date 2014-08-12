[WIP] droidgems
=========

http://droidgems.com/

An awesome libraries for Android development.

![](https://dl.dropboxusercontent.com/u/7817937/_github/droidgems/SS/1407589588.png)

![](https://dl.dropboxusercontent.com/u/7817937/_github/droidgems/SS/1407589600.png)

Designdoc
===

Why?
---

Android のライブラリを探しやすくする。
現状ものすごく探しにくい。

理由は、

1. CocoaControls みたいに画一的かつグラフィカルなサイトが無い
2. GitHub へのリンクしかなくてどんなライブラリか分からない…

How?
---

1. 読むより見る。（AniGIF, ソースコードBefore&After、動画...）
2. 関連情報を充実させる（参考リンク、導入 / 使い方の記事、自前？）
3. 量よりも質。よいライブラリをなぜ良いか一目で理解出来るように。
4. だから、良いライブラリであれば自前で解説記事 / AnimGIF を作りたい。

Specs
---

###gems#index

- スターの数が一目瞭然である。
- または、挙っている記事の数が一目瞭然である。（話題度とか、リソースの充実度とか）
- 良さを理解出来るビジュアルがリストにある。（CocoaControls みたいな）
- または、遷移なしでビジュアルにアクセス出来る
- 新着順（あるいは勢い順）でリストされている
- ランキングへのリンクがある
- タグがリストされている
- ライブラリ毎にタグをリストする
- 検索が出来る
- （つまり、ライブラリを探すためのインターフェースとして「トレンド」「タグ」「検索」がある。）

###gems#show

- AniGIF、ソースコード、各種画像、動画の優先度順に上にドーンと置く。
- README から 画像、動画、ソースコードを取ってくる。
- 参考リンクを張る。上のほうが良い。どのリンクが参考になるか指針を与える。
- コメントとか、レビューみたいなの欲しいが難しいか？
- 他諸々の情報（Github の README とかは空間的優先度低め）
- Twitter の "#{Library Name} android" の検索でとれる Tweets を表示する
- 検索結果とかブログ検索とかイイ感じに API からとって表示する
- Droid Gems 単体のエコシステムではなく、外部のエコシステムから情報を集めて一元化する

###管理

- クロール + 手動
- GitHub / markdown / Middleman / Wercker
- pullrequest を受け付ける。（参考リンク、記事、内容etc...）
- 投稿の導線

OK & NOTS
---

#### OK

- http://android-arsenal.com/
- https://www.cocoacontrols.com/
- http://www.producthunt.com/
- http://nomadlist.io/
