******************************
都道府県コードのIME辞書
******************************

JIS X 0401都道府県コードを都道府県名のよみから変換するMS-IMEユーザ辞書です。


==============
仕様
==============

:文字コード: Shift_JIS
:行区切り: CRLF
:項目区切り: 水平タブ

==============
インストール
==============

1. zipファイル_ をダウンロードして展開

2. jprefdic.txtを適当なフォルダに保存

3. MS-IMEの辞書ツールを起動

  - テキスト入力できるところ(エディタでもWebフォームでも)で、「半角キー」を押す(入力モードの言語バー表示を「あ」にする)
  - コントロールキーを押しながらF10を押す
  - ポップアップメニューから辞書ツールを選択

4. メニューバーで「ツール」 -> 「テキストファイルからの登録」を選択

5. ステップ2.で保存したjprefdic.txtを選択

6. 「登録処理を完了しました」と表示されたら「終了」をクリック


.. _zipファイル: https://github.com/hashimoton/jprefdic/archive/master.zip

==============
使い方
==============

都道府県名から都道府県コードに変換
------------------------------------

日本語入力モードで「＃けん」に続いて都道府県名のよみを入力し、変換(スペースキー)。

例::

  ＃けんほっかいどう -> 01
  ＃けんあおもりけん -> 02
  ＃けんとうきょうと -> 13
  ＃けんおおさかふ   -> 27
  ＃けんおきなわけん -> 47

都道府県コードから都道府県名に変換
-------------------------------------

日本語入力モードで「＃けん」に続いて都道府県名コードを入力し、変換(スペースキー)。

例::
  
  ＃けん０１ -> 北海道
  ＃けん０８ -> 茨城県
  ＃けん１３ -> 東京都
  ＃けん２６ -> 京都府
  ＃けん４３ -> 熊本県
  
===================
アンインストール
===================

1. MS-IME辞書ツールを起動
2. 単語一覧で「＃けん」で始まる行を全て選択
3. メニューバー「編集」->「削除」を選択
4. 「選択された単語を削除しますか?」とダイアログがでたら「はい」をクリック

.. EOF
