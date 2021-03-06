# 3. 物理演算とは

## 物理演算とは
CoronaSDKは物理演算(ボールが地面にぶつかって跳ねる挙動をアプリで再現する等)の機能をもっています。  
物理演算は以下のコードで呼び出すことができます。

```lua
-- 物理演算をするための機能を読み込んで `physics` に入れておく
physics = require("physics")
-- 物理演算を起動する
physics.start(true)
physics.setGravity(0, 0)
```

現状では何も動きませんが、次からのセクションで効果を発揮するのでどんどん進みましょう。

参考
CoronaSDK Reference [physics]

[https://docs.coronalabs.com/api/library/physics/index](https://docs.coronalabs.com/api/library/physics/index.html)

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



-- ############################## 物理演算とは？ ##############################

-- 物理演算をするための機能を読み込んで `physics` に入れておく
physics = require("physics")
-- 物理演算を起動する
physics.start(true)
physics.setGravity(0, 0)

-- ############################## 物理演算とは？ ##############################
```

画面は以下のようになっていれば成功です。  
まだ前のセクションと同じ画面です。

![](./image/execBreakoutSample2.png)
