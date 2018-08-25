# build_ijaas

ijaasのビルドが完了したプロジェクト

ライセンスはもとのままです。

https://www.jetbrains.com/idea/download/previous.html

※ InteliJは2017.2.7現在を使います。

クローン設定

```txt
cd ~/.vim

git clone https://github.com/takkii/build_ijaas.git
```

InelliJ側

```txt
プラグインの追加先は、

build/distributions/ijaas-0.1.zip

です。
```

Vim側

```vim
.vimrc

set runtimepath+=~/.vim/build_ijaas/vim

```

※ Vim8はvim-kaoriyaを使います。
