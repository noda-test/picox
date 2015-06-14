# これは何？
省メモリの組み込み環境を想定した超軽量汎用ライブラリです。

----------------------------------------------------------------------

# 特徴
各モジュールはそれぞれ独立している為、基本的には1ソース、1ヘッダのみで
ビルドすることができます。
プロジェクトに未使用のソースコードが大量に存在することが好ましくなけれ
ば、必要なものだけをコピーして使用することもできます。


その結果、各モジュール内で重複したコードが発生することになっても、この
ライブラリでは、モジュール間の依存を一切なくすことを優先しています。

----------------------------------------------------------------------

# 移植及び使用方法
各モジュールのヘッダファイルを参照してください。

OSやターゲットに依存していない為、適切なグルーコードを用意してやるだけ
で使用可能です。


----------------------------------------------------------------------

# 外部ライブラリ URLリスト
picoxと同等以上に、単機能でシンプルに使用できる外部ライブラリは積極的
に取り込んでいます。
ビルド可能なソースコードはpicox/external 以下にまとめられています。
各ライブラリの使用方法は、それぞれのライブラリの解説を参照してくださ
い。


[Unity][Unity]
[minIni][minIni]
[sds][sds]
[uthash][uthash]

[Unity]:https://github.com/ThrowTheSwitch/Unity.git
[minIni]:https://github.com/compuphase/minIni.git
[sds]:https://github.com/maskedw/sds.git
[uthash]:https://github.com/troydhanson/uthash.git
