---
title: "M1 MacbookでRealforce for macのUSキーボードを使ってる際、ファンクションキーが使えない 時の対処法"
emoji: "🦁"
type: "other" # tech: 技術記事 / idea: アイデア
topics: []
published: true
---

想定読者が少なすぎて笑うけど、どこかで困ってる人のための備忘録

Realforce for mac USキーボード テンキーレス を使用しておりますが、M1 macbookにて、
・fnキー
・fn 切り替えキー 
が反応、動作しません。

Event viewerでも確認してみたが
・fnキー
・fn 切り替えキー 
については、押下しても何も認識されなかった。

以下確認したこと

-------------

M1 Macbook Air 2020 モデルにてRealforce for mac USキーボード テンキーレスを試し、上記2キーが動かないことを確認しました
M1 Macbook Pro 16インチ 2021 モデルにてRealforce for mac USキーボード テンキーレスを試し、上記2キーが動かないことを確認しました

Macbook Pro 16インチ Intel 2018年モデルにて試し、Realforce for mac USキーボード テンキーレスを上記2キーが「動く」ことを確認しました。
M1 Macbook Pro 16インチ 2021 モデルにて「Realforce for mac JPキーボード テンキーレス」を試し、上記2キーが「動く」ことを確認しました

-------------

つまり、M1 Macbookで、Realforce for mac USキーボードを使ってるときに起きるっぽい。

RealForceの窓口に問い合わせてみたところ、解決方法はなく、回避方法は
System Preference > Keyboard にて"Use F1, F2, etc. keys as standard function keys" ということだった。
![gazou](/images/system_preference.png)

これにチェックを入れれば、Realforce for mac USキーボードでは正しく動作するようになる。
Macbookでは、Mac特殊キーを使いたい(音量下げるなど)ときはFnキーを押さないといけなくなる。

Macbookの動作がいつも使ってるのとは逆になるのは違和感だが、チェック入れないと全く使えないので、我慢してつかいますかね。

以上
