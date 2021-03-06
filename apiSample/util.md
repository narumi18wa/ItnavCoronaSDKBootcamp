# 便利系Sample

## 端末の幅を取得

```lua
display.contentWidth
```

display.contentWidthが端末の幅の長さです。

参考
CoronaSDK Reference　[contentWidth]

[https://docs.coronalabs.com/api/library/display/contentWidth](https://docs.coronalabs.com/api/library/display/contentWidth.html)

---

## 端末の高さを取得

```lua
display.contentHeight
```

display.contentHeightが端末の高さです。

CoronaSDK Reference[contentHeight]

[https://docs.coronalabs.com/api/library/display/contentHeight](https://docs.coronalabs.com/api/library/display/contentHeight.html)

---

## テキストボックスを生成する

``` lua

defaultBox.newTextBox( centerX, centerY, width, height )

-- テキストボックスを編集可能にする
defaultBox.isEditable = true

```

centerXはx座標の位置を、centerYはY座標の位置を指定でき、
widthは横幅を、heightは高さを指定できます。
isEditableは"false"を入力すると編集できなくなります。


参考
CoronaSDK Reference[newTextBox]

[https://docs.coronalabs.com/api/library/native/newTextBox](https://docs.coronalabs.com/api/library/native/newTextBox.html)

---

## 音を再生する

[外部リンク](http://kwiksher.com/bootcamp/corona1/playing_audio.html)

---

## 画面遷移
[外部リンク](http://kwiksher.com/bootcamp/corona2/composer_gui.html)