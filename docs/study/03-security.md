# 3. セキュリティ

> 📝 これから書くノート。下の「読むときの問い」に答える形でまとめる。

## 読むときの問い
- [ ] ログインはどう実現しているか（JWT・セッション）。トークンはどこに保存・送信されるか
- [ ] 認可：他人の記事・コメントを編集・削除できないことを、どこで確かめているか
- [ ] 入力の検証はどこで行っているか
- [ ] CORS の設定はどうなっているか

## 見つけたコード

| 場所 | 内容 |
|------|------|
| | |

## 学び
- 

## メモ
- （調査メモ）JWT の有効期限は [AuthTokenProvider.java](../../server/api/src/main/java/io/zhc1/realworld/config/AuthTokenProvider.java) で設定されている。フロント側のバグ調査（[フロントの README](https://github.com/tottemoren/react-vite-realworld-example-app)）で、5分と短いことが原因の1つと分かった

## 自分の言葉で追記する
- [ ] （ここに自分の気づきを書く）
