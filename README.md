### son-jo-sokora

メインフレーム（IBM Z / z/OS）を学ぶためのコンテンツと、言語を作って調べる道具を作っています。
哲学のテキストを計算できる模型にして読む遊びも進めています（いまは非公開）。

*Learning tools for IBM Z / z/OS mainframes (Japanese UI), and a browser-based conlang generator (Japanese / English).*

---

#### 🖥️ メインフレームを、インストールなしで触る

| | |
|---|---|
| **[JCL 練習端末](https://son-jo-sokora.github.io/jcl-terminal/)**<br>[jcl-terminal](https://github.com/son-jo-sokora/jcl-terminal) | ISPF に似た画面で JCL を書き、`SUB` で投入し、SDSF に似た画面で JES2 の出力を確かめる。書き間違えると、実機に近い JCL エラーが返る |
| **[MVS コンソール シミュレータ](https://son-jo-sokora.github.io/mvs-console-sim/)**<br>[mvs-console-sim](https://github.com/son-jo-sokora/mvs-console-sim) | オペレーターの立場で IPL から停止まで。障害シナリオ、SYSLOG での原因調査、手順例16本と演習17本つき。メッセージを押すと意味とマニュアルの出典ページが出る |

2つを別々のタブで開いて連携させると、JCL 練習端末で投入したジョブを、シミュレータの JES2 が実行します。利用者とオペレーターの両方の立場を一度に体験できます。

#### 🔎 マニュアルを手元で検索する

| | |
|---|---|
| **[mainframe-manual-search](https://github.com/son-jo-sokora/mainframe-manual-search)** | 自分で入手した IBM のマニュアル PDF を、自分の PC の中だけで検索する。メッセージ ID やアベンドコードから説明のページを出し、日本語の文章でも英語のマニュアルを探せる。ジョブのログの解析と、版どうしの比較もできる。マニュアルそのものは含まない |

> どれも個人の非公式なもので、IBM とは関係がなく、IBM の承認も受けていません。シミュレータは学習用で、本物の z/OS ではありません。IBM、IBM Z、z/OS、MVS、ISPF、SDSF、JES2、Db2、IMS、CICS、IBM MQ は International Business Machines Corporation の商標です。

#### 🗣️ 言語を作る

| | |
|---|---|
| **[人工言語ジェネレーター](https://son-jo-sokora.github.io/conlang-generator/)**<br>[conlang-generator](https://github.com/son-jo-sokora/conlang-generator) | 押すたびに、音・文法・独自の文字まで新しい言語を作り、その言語の文章を出す。統計で「言語らしさ」を確かめる分析、音の変化で作る姉妹言語、対訳つきの答えつき。生成に AI は使わない。日本語と英語で使える |

---

#### ✍️ 記事（Qiita）

- [インストールなしで z/OS を触る：ブラウザで動く JCL 練習端末と MVS コンソールを作った](https://qiita.com/son-jo-sokora/items/356b755c864b90ece8d4)
- [読めないのに「言語らしい」と分かる文章を作る：ブラウザで動く人工言語ジェネレーター](https://qiita.com/son-jo-sokora/items/0373db6e8da277be7a5c)

📮 X: [@son_jo_sokora](https://x.com/son_jo_sokora)　📝 Qiita: [son-jo-sokora](https://qiita.com/son-jo-sokora)
