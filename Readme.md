# Version

```bash
$ emacs --v
GNU Emacs 24.3.1
```

# How to use
`clone`するだけで動くっぽい．

# Using package lists
- `auto-comlete`  
補完

- `smooth-scroll`  
その名の通り

- `yatex`  
TeX用

- `popwin`, `popwin-yatex`  
`compile`の結果などを`C-g`とかで消せるようになる．

- `elscreen`  
emacsをタブエディタ化．タブごとにウィンドウ分割が維持できる．

- `smartparent`  
カッコなどの補完．リージョンに開きカッコを入力すればリージョンの初めと終わりにカッコを補完したりとか．

- `gnuplot-mode`  
プロットファイルのハイライトとか，実行とか．

- `pdf-tools`  
emacsの中でpdfを綺麗に開ける．検索とかダブルクリックでソースに移動とか．

- `tramp`  
デフォルトで入ってる．
ssh先のファイルをローカルのように扱える．

```bash
C-x C-f /scp:user@xxx.xxx.com:/home/user/hogehoge/huga.txt
```

- `web-mode`  
htmlのシンタックスハイライトとかインデントとかフォールディングとか．

- `fcitx.el`
[prefix] + hogehoge のときに自動で日本語をoffにする．
http://qiita.com/Ouvill/items/d21be847753eb5adf414
https://github.com/cute-jumper/fcitx.el

- `jedi`

```bash
sudo pip install virtualenv
sudo emacs
```

`sudo emacs`で`M-x install-server`を実行．

- `google-this`
`C-f1`でGoogle検索


# Required
- Ricty（フォント）
- mkup(http://mattn.kaoriya.net/software/lang/go/20150703125421.htm)

# TODO
- forward search( yatex + pdf-tools )の設定．
- 環境ごとに文字の大きさを設定する．

# Note
- Cocoaだとダメっぽい. Portsでインストールしたemacsなら可能.
- package lists にはおそらく抜けがある．
