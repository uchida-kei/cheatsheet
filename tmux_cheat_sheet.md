## tmuxCheatSeet

### コマンド

#### セッション一覧
```
tmux ls
```

#### 接続クライアント一覧
```
tmux lsc
```

#### セッション終了
```
tmux kill-session
```

#### 全てのセッション終了
```
tmux kill-server
```

### キーバインド
Ctrl+aの後に入力

#### セッション操作
```
s	一覧選択
d	離脱
$	名前変更
```

#### ウインドウ操作
```
c	新規作成
w	一覧選択
0-9	指定番号のウインドウへ移動
&	破棄
n	次のウインドウへ移動
p	前のウインドウへ移動
f	検索
```

#### ペイン操作
```
\	左右分割
-	上下分割
q	番号表示
h	左に移動
j	下に移動
k	上に移動
l	右に移動
x	破棄
z	最大化
{	前に入れ替え
}	後ろに入れ替え
t	時計表示
```

#### その他
```
?	キーバインド一覧
```
