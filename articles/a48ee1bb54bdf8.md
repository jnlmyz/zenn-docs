---
title: "Deployment Target"
emoji: "🙆"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: [iOS,Xcode]
published: false
---

# 問題

`#available(iOS 14.0, *)`を消したら`CoreLocation`から怒られたので、メモ

![](/images/available_iOS.png)

# 対応策

TargetsのMinimum Deploymentsの設定を変更


# 参考

[iOS10のサポートを切るときにやったこと](https://qiita.com/orimomo/items/299712d5b67214143613)
