#  はじめに
TDD勉強会用のJavaのblankプロジェクトです

# Eclipseプラグイン
* JavaでTDDやる時は下記のどちらかのプラグインが必須
* TDDやる分にはどちらも同じなのでお好みで

## Quick JUnit
* http://quick-junit.sourceforge.jp/
* Update siteに http://quick-junit.sourceforge.jp/updates/current/ を登録して「Quick JUnit for Java Developer」を選択

## S2JUnit4 Plugin for Eclipse
* http://s2junit4plugin.sandbox.seasar.org/
* Seasar2用のテストクラスを作れるので、Seasar2を使うことが多ければこちらを推奨

## 使い方
* Ctrl + 0 : カーソル位置のテストを実行
 * メソッド内ならそのメソッドだけ
 * それ以外ならクラス全部
* Ctrl + 9 : テスティングペアを移動
 * Foo <-> FooTest を往復できる
 * もしテストクラスがなければ生成できる


# リンク集
* eclipse - aqubi+shin1
 * https://sites.google.com/site/shin1ogawa/eclipse
 * Eclipseの設定とか使い方とか
* hamcrestのMatcherメモ - 都元ダイスケ IT-PRESS
 * http://d.hatena.ne.jp/daisuke-m/20090710/1247181113
 * hamcrestの使い方が詳しい
* JUnit のセカイ #JJUG - やさしいデスマーチ
 * http://d.hatena.ne.jp/shuji_w6e/20111205/1323098690
 * テストケースの書き方が参考になる
* GitHub Flavored Markdown - Live Preview
 * http://github.github.com/github-flavored-markdown/preview.html
 * markdown書くには便利ｗ
