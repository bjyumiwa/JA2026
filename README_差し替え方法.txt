# 差し替え方法

1. zipを解凍します。
2. 中身をそのままGitHubリポジトリのルートへアップロードします。
3. すでに同名ファイルがある場合は、上書きしてください。
4. GitHub Pagesを開き、Ctrl + F5 で強制更新します。

## キャラ画像だけ差し替えたい場合

例：ペンギンの通常画像を差し替える場合

```
public/assets/characters/penguin_yellow/happy.png
```

この場所に、透過PNGを同じ名前で上書きします。

## 背景だけ差し替えたい場合

```
public/space_background.png
```

この画像だけを上書きします。


【2026-05-16 v5修正版メモ】
・白い枠が残っていたキャラクター画像を再抽出しました。
・キャラクター表示を大きめに戻しました。
・宇宙背景は public/space_background.png を contain 表示にし、少し引いて見えるようにしました。
