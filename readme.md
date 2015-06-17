# concrete5 TinyMCE Office Config Sample for 5.6.x and earlier

## Introduction 

日本語の説明は後に

This is the simple copy of concrete5.6.3.3 Office setting of TinyMCE.

When you want to customize the buttons of concrete5 TinyMCE editor, you need to create your own config text file.

If you feel you're troublesome, you may want to subtract the options from `Office Theme` from concrete5.

I've created this option for you.


## How to use

1. Login to your own concrete5 site
2. Go to `System and Setting` from Dashboard
3. Go to `Basic` and `Rich Text Editor`
4. Select `Custom`
5. Paste the content of `office.config` text file in this git repo onto the text area
6. Edit the config text as you wish.
7. Save it
7. Check the Content Block for the change. And repeat until you are happy.

For more information about TinyMCE config, visit [its official documentation](http://www.tinymce.com/wiki.php/Configuration)

Have fun.

## はじめに

concrete5.6.x 以前のバージョンで使用している TinyMCE テキストエディターの「Office」のテンプレートをカスタムで使えるように用意しました。

concrete5 では、記事ブロックに現れる編集バーのボタンやオプションを自由に編集できる機能がありますが、そのオプションを変更するには、難しいテキストの設定を変更する必要があります。

そのため、手っ取り早い方法として「オフィス」の設定をコピーして、不要なボタンを削除していくという方法をとるために、「オフィス」の設定そのままのものをこの GitHub に用意しました。

## 設定方法

1. 自分の concrete5 サイトにログイン
2. `管理画面` - `システムと設定` ページに移動
3. `基本` - `記事ブロックエディター`ページに移動
4. ツールバーセットから `オプション` を選択
4. この Git にある `office.config` をコピー
5. テキストエリアにペースト
6. テキストを編集してボタンを追加・移動・削除。
7. 「保存」
8. 別ウインドウなどで記事ブロックを読み込みなおして変更を確認し、調整を繰り返す

TinyMCE のオプションについて詳しくは[ドキュメントページを参照のこと](http://www.tinymce.com/wiki.php/Configuration)

Katz
@katz515
@katzueno
http://katzueno.com