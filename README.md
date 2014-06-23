closure-libraryビルド用サブモジュール
======================
closure-libraryをビルドコマンドで圧縮する時は
このプロジェクトとclosure-libraryをサブモジュールとして使ってください。


使い方
------
	git submodule add https://github.com/htanaka0828/closure-builder.git closure-builder
	git submodule add https://github.com/google/closure-library.git ./closure-library
	git submodule init
	git submodule update

