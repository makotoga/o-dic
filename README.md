# 沖縄辞書に関するドキュメント

## 沖縄辞書とは?

沖縄辞書プロジェクトは有志が行なっている仮名漢字変換用ソフトウェア用の辞書ファイルの語彙強化プロジェクトです。  
集録語数は、基本的な語彙(人名、地名)が約2900語。  
その他の雑多な語を含めると約5800語(品詞の異なるものを同じに数えると約5100語)です。

## 沖縄辞書はどこで作っているの?

保守作業は『沖縄辞書メイリングリスト』というメイリングリストおよび[sourceforge](http://sourceforge.jp/projects/o-dic/)にて行なわれています。

## 沖縄辞書の内容は?

沖縄辞書は、現在、次の15のファイルに分かれています。

|ファイル名|内容|
|--|--|
|[city.dic](city.dic)|市町村および郡の名前|
|[address.dic](address.dic)|市町村内の行政区画の名前|
|[island.dic](island.dic)|島嶼名|
|[geo.dic](geo.dic)|市町村名/字名/島名に含まれない地名(山や川も)|
|[name.dic](name.dic)|人名|
|[school.dic](school.dic)|学校名|
|[park.dic](park.dic)|公園名|
|[history.dic](history.dic)|歴史上の人名・地名|
|[food.dic](food.dic)|食べ物の名前|
|[sakana.dic](sakana.dic)|魚の名前|
|[awamori.dic](awamori.dic)|泡盛の銘柄名|
|[base.dic](base.dic)|基地|
|[amami.dic](amami.dic)|奄美の人名・地名|
|[bus.dic](bus.dic)|バス路線・バス停|
|[misc.dic](misc.dic)|その他|
|||

日本語入力ソフトウェアの(VJEとかCannaとか)の辞書強化が目的であれば、地名と人名(city、address、island、geo、name)だけでも充分に役に立つと思います。  
また、各種日本語入力ソフトウェア用の辞書ファイルへ変換するためのスクリプトをいくつか添付いたします。

|ファイル名|内容|
|--|--|
|[oki2canna.pl](script/oki2canna.pl)|Canna/Anthy辞書への変換|
|[oki2vje.pl](script/oki2vje.pl)|VJE-Deltaの一括登録用テキストへの変換|
|[oki2kotoeri.pl](script/oki2kotoeri.pl)|ことえりの一括登録用テキストへの変換|
|[oki2jis.pl](script/oki2jis.pl)|JIS X 4062形式のテキストへの変換|
|[oki2atk.pl](script/oki2atk.pl)|ATOK13形式のテキストへの変換|
|[oki2cha.pl](script/oki2cha.pl)|茶筌で使える形式のテキストに変換する|
|[oki2mozc.pl](script/oki2mozc.pl)|Mozc/Google日本語入力の一括登録用テキストへの変換</br><small>_ただし、Mozc/Google日本語入力には沖縄辞書の内容が一部マージされているので、それを含みたくない場合にはMozcのソースが必要になります_</small>|
|||

沖縄辞書のデータ形式については、[format.txt](doc/format.txt)を参照してください。

## 配布規定は?

Public Domain Dataです。  
使用・変更・配布に関しては一切の制限をつけません。  
商品などに組み込むことも自由に行なってください。  
すでにいくつかの辞書には沖縄辞書が採用されています。  
勝手ながら、沖縄辞書に寄贈された辞書も `in the Public Domain' 扱いとさせていただきます。

なお、使用・商用にあたって、何かコメントをいただけると、プロジェクト関係者はたいへんうれしいので、メイルでも送ってください。  
_(強制ではありません)_

## 連絡先は?

以下のところへお願いします。

監修者(ずけらん@沖縄)  
shin@opus.or.jp
