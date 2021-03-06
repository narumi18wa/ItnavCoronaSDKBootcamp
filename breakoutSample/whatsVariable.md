# 2. 変数とは

## 変数とは

プログラミング言語では変数というシステムがあります。  
変数は数字や物を名前をつけて保存できるシステムです。

たとえば、Lua言語では、  
`number = 10`  
と書けば `number` という名前で10が保存されます。

また、環境上で既に確保されている変数もあります。  
`display.contentWidth` や `display.contentHeight` がそれにあたります。

しかし、それらは使用頻度が高く、毎回長い名前を書くのは面倒です。  
自前で用意した短い変数に保存して使いやすくしておきましょう。

自前で変数を用意する場合は、 `width = display.contentWidth` のように、  
`=` を真ん中に、左辺を保存先の変数名にし、右側を保存する物\(変数名、文字、数字等\)にします。  
試しに以下のコードを入力しましょう。 `width` に横幅、 `height` に縦幅が保存されます。

```lua
-- `width` は画面の横幅(1080)が入っている
width = display.contentWidth
-- `height` は画面の縦幅(1920)が入っている
height = display.contentHeight
```

書いた後にWindowsは `Ctrl + s` , Mac `Command + s` をすることで保存できます。  
エラーが表示されなければ成功です。

---

## displayGroupを作ろう

CoronaSDKで画面を描画する際に必要な描画グループを作ってdisplayGroupに保存しておきましょう。  
以下のコードを入力しましょう。

```lua
-- 描画グループ
displayGroup = display.newGroup()
```

参考
CoronaSDK Reference [displayGroup]

[https://docs.coronalabs.com/api/library/display/newGroup](https://docs.coronalabs.com/api/library/display/newGroup.html)

---

## セクション中の全文

このセクションで書いたコードの全文は以下になります。

```lua
-----------------------------------------------------------------------------------------
--
-- ピンボールゲームを作ってみよう
-- main.lua
--
-----------------------------------------------------------------------------------------



-- ############################## 変数とは？ ##############################

-- `width` は画面の横幅(1080)が入っている
width = display.contentWidth
-- `height` は画面の縦幅(1920)が入っている
height = display.contentHeight

-- 描画グループ
displayGroup = display.newGroup()

-- ############################## 変数とは？ ##############################
```

画面は以下のようになっていれば成功です。

![](./image/execBreakoutSample1.png)
