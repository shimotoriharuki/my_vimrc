# .vimrc


# 導入

1. ssh登録
```
$ ssh-keygen
```
`.ssh/id_rsa.pub`をGitHunのに登録

2. クローン

```
$ git clone git@github.com:shimotoriharuki/my_vimrc.git
```

3. シンボリックリンク作成
```
$ ln -s my_vimrc/my_vimrc ~/.vimrc
```
git管理されたリポジトリの中にあるVimの設定ファイルをrootに.vimrcという名前でコピーを作るイメージ

4. deinをインストール
- https://github.com/Shougo/dein.vim

```
$ sh -c "$(wget -O- https://raw.githubusercontent.com/Shougo/dein-installer.vim/master/installer.sh)"
```
