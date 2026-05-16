# 4,320N 完整ファイルセット

このフォルダ一式を GitHub リポジトリにアップロードしてください。

## 置き方

```
index.html
public/
  space_background.png
  assets/
    macarons/
    characters/
```

## 背景

コードは `public/space_background.png` だけを背景として読み込みます。
ルート直下の `space_background.png` は使いません。

## マカロン画像

正式名は次の6つです。

```
public/assets/macarons/pink_crystal_macaron.png
public/assets/macarons/blue_crystal_macaron.png
public/assets/macarons/yellow_crystal_macaron.png
public/assets/macarons/white_crystal_macaron.png
public/assets/macarons/green_crystal_macaron.png
public/assets/macarons/purple_crystal_macaron.png
```

古い名前で参照しても壊れにくいように、同じ画像の別名ファイルも同梱しています。

## キャラクター画像

正式な置き場所は次の形式です。

```
public/assets/characters/character_id/happy.png
public/assets/characters/character_id/sad.png
public/assets/characters/character_id/sleep.png
```

character_id は次の6つです。

```
penguin_yellow
cat_purple
rabbit_pink
lizard_green
seal_gray
kangaroo_blue
```

画像を差し替える場合は、同じファイル名で上書きしてください。
背景リムーブ済みPNGを使うと、宇宙背景の上にきれいに出ます。

## 追加済みの機能

- 5日間のお世話ゲーム
- 多言語対応 日本語・英語・中国語
- 名前入力
- クリスタル付きマカロン6種類
- キャラクター6種類 × happy/sad/sleep
- 20種類のごはん2択
- 20種類のおでかけ2択
- 動く💩掃除ゲーム
- 指定色の💩をクリックするミニゲーム
- `public/space_background.png` 固定背景
- リセットボタン、パスワード `JA2026`
- 管理者モード `?admin=1`
- CSV/JSONログ出力
- Googleフォーム遷移
