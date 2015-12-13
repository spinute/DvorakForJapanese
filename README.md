# extended_dvorak_jp_table
* exported mapping table from GoogleJapaneseInput for DvorakJP (a little extended)
* Google日本語入力用のローマ字テーブル定義ファイルです。

# What's DvorakJP? DvorakJPとは?
* 日本語入力用に拡張されたDvorak配列です。
* 本家(?)を上げておきます。http://www7.plala.or.jp/dvorakjp/
* 導入方法などは https://github.com/shinespark/dvorakjp-romantable に詳しいです。
 * というかこちらのページにもカスタマイズされたDvorakJPのkeymapが置いてあります

# content of extension 拡張の内容
* DvorakJP自体の入力は妨げない範囲で2つほど独自の拡張を行っています。
* 二重母音拡張の拡張
 * 二重母音としてu音が空いているのがもったいない気がしたので母音+pで母音+uuが入力されるようになっています。
  * uのあとに最も頻繁に来る母音がuであるかどうかは確認していません(が、結構あたってくれているような気がします。)
  * 例: 謙虚で優秀な配列(cjcnodeypshpnah'retu)
* ;プレフィックスを使った記号の入力
 * シフト押しながら上の列まで手をのばすのが面倒くさいので;<key>でいくつかの記号が出るようになっています
 * 個人的には日本語を最も使うのはまさにこのドキュメントのようなmarkdownのドキュメント記述なので、例えば;sで\*、;tで\#などが出てきます
 * 日本語で頻繁に;を使う人には邪魔かもしれません
