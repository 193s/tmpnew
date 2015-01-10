# tmpnew
一時的な作業ファイルを作成するアレ

## Install
1. clone
 ```sh
 $ git clone https://github.com/193s/tmpnew.git
 $ cd tmpnew
 ```

2. パスを通す  
 `tmpnew`をパスの通った適当な場所に移動しよう

3. alias  
 `. tmpnew`で実行出来るけど不便なので`alias tmpnew='. tmpnew'`とかやりましょう



## Usage
`tmpnew`で`/tmp/$RANDOM`に,  
`tmpnew hoge`で`/tmp/hoge`に作業ファイルを作成して移動します．

## たすけて
aliasさせたりかなり酷い設計になっています．  
もうちょっと良い方法があればプルリク投げるなりして助けてください．
