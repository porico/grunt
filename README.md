grunt
=====

#はじめに

generator-katamariを使用するので、yeomanをインストールする
```
npm install -g yo
npm install -g generator-katamari
```
参考：http://yeoman.io/

プロジェクトのディレクトリで以下のコマンドを実行
```
yo katamari
```

#プロジェクトごとに

以下を実行する

```
git clone https://github.com/porico/grunt.git
cd [local directory path]
npm install
grunt
```

画像サイズ最適化のimageminを実行する場合は、gruntのwatchをいったんとめて以下実行。

```
grunt imagemin
```

※CSSはSmartPhone用

