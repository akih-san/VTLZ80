＜VTLについて＞<br>
<br>
著者である電脳伝説さんの「モトローラ6800伝説　第二章　Chapter3プログラムの再現」<br>
でVTLが紹介されていますが、とてもコンパクトなインタプリタです。<br>
<br>
また、T. Nakagawa氏がWeb、「VTL(Very Tiny Language)の作成」にてＣ言語で書かれた<br>
ＶＴＬを公開されています。<br>
<br>
今回は、このソースをEMUZ80, SBCZ80, AKI-80, SuperMEZ80で動作するようにしました。<br>
Cコンパイラは、SDCCを使用しています。デバイス依存部をアセンブラで書きました。<br>
SDCCを使用してリンクさせようとしましたが、どうしてもうまくいきませんでした。<br>
仕方が無いので、VTLのアセンブルソースをSDCCで作成し、アセンブルソースで結合しました。<br>
アセンブラは、Macro Assembler AS V1.42(http://john.ccac.rwth-aachen.de:8000/as/)を
使用しています。<br>
<br>
<br>
T. Nakagawa氏のWebには、ＶＴＬの基本的なことや、インプリメント方法、サンプルプロ<br>
グラム等がありますので、是非ご覧ください。<br>
<br>
また、シロピョン氏のページ「超ミニ言語で遊ぼう（４）みんなで「スタ☆トレ」」で<br>
ＭＳＸ版のＶＴＬで「STAR TREK」を紹介しています。<br>
（これを動かしたくて、最初にVTLををSBCV20で動かしました。）<br>
<br>
・「VTL(Very Tiny Language)の作成」<br>
http://middleriver.chagasi.com/electronics/vtl.html<br>
<br>
・超ミニ言語で遊ぼう（４）みんなで「スタ☆トレ」<br>
https://ameblo.jp/siropyon/entry-11917965564.html<br>
<br>
<br>
ソースコードは、ライセンスフリーです。<br>
オリジナルのソースコードについては、公開元のライセンスアグリーメントに従うものと<br>
します。<br>
