---
title: Bikpela Poteto Bilong Miができるまで（動作確認）
date: "2021-02-21T10:00:00.000Z"
description: "Gatshby JS Starter Libraryからスターターの取得、動作確認までを行います。"
---

1. Gatsbyのスターターライブラリから、`gatsby-starter-blog`を取得
```sh
gatsby new bikpera-poteto-bilong-mi https://github.com/gatsbyjs/gatsby-starter-blog
```

1. 作成されたディレクトリに移動
```sh
cd bikpera-poteto-bilong-mi/
```

1. お約束
```sh
git init
```
```sh
git add .
```

1. メールアドレスとユーザ名を設定
```sh
git config --global user.email sgktmk@gmail.com
```
```sh
git config --global user.name sgktmk
```

1. コミット
```sh
git commit -m "initial commit"
```

1. リモートリポジトリの追加
```sh
git remote add origin git@github.com:sgktmk/bikpera-poteto-bilong-mi.git
```

1. 
```sh
git branch -M main
```
```sh
git push -u origin main
```

1. 動作確認
```sh
gatsby develop
```

![動作確認完了](./image-20210221101717629.png)