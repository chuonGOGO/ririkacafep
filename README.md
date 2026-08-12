# ririkacafep

りりかカフェ ワールドの権限データ(admin / staff / cast)を配布するための公開用リポジトリです。
GitHub Pages で公開し、ワールド内のUdonから `VRCStringDownloader` 経由で取得することを想定しています。

## データファイル

- [`permissions.txt`](permissions.txt) — 権限リスト本体

### 書式

```
[admin]
表示名1
表示名2

[staff]
表示名3

[cast]
表示名4
```

- `#` で始まる行はコメント
- 空行は無視
- 判定にはVRChatの **DisplayName(表示名)** を使用します(usr_... の内部IDではありません)。表示名変更時は更新が必要です。

## 公開URL(GitHub Pages有効化後)

```
https://chuongogo.github.io/ririkacafep/permissions.txt
```
