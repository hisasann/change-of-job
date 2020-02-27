# Change of job

<p align="center">
  <img src="https://github.com/hisasann/change-of-job/blob/master/assets/macbookpro16.jpg" width="50%">
</p>

転職時せっかくなので、 MacBookPro を新調しました！😻

16 インチは大きい！💻

そしてこちらは、転職時に、時間を作って新しくやったことを学んでいっているログの記録です。

## Slack

- [x] Workflow を試してみるが、フリープランではワークフロービルダーが使えなかった。

## hisasann.github.ioのPWA化

- [x] 3つほどエラーが出てしまったが、解消したらうまくいきました。

[DJ lemon-Sour's diary (prod.hisasann)](https://hisasann.github.io/)

https なサイトから http のリクエストをしていたことや、

適切な png 画像が配置されていないことが、原点となっていたので、こちらは解消した。

## React Native

- [x] 初めてのビルドの記事を作成する

何も考えず WebStorm から template を使って、ビルドまでした記録です。

[初めてのReactNative-ビルド編🍱 - DJ lemon-Sour's diary (prod.hisasann)](https://hisasann.github.io/2020/02/13/first-time-react-native/)

### React Native の入門 Udemy をやる

[hisasann/news-app: React Native 入門 Udemy の写経用リポジトリ](https://github.com/hisasann/news-app)

- [ ] 50%

その後、こちらの Undemy を購入して初学者向け勉強をし始めました。

内容は理解しやすく、 expo-cli を使う場合のメリット・デメリットが知れたのででかいです。

[React Native入門：ニュースアプリを作りながら覚えよう/Hooks対応 2020年版 | Udemy](https://www.udemy.com/course/react-native-first-step/)

### React Native Web

[necolas/react-native-web: React Native for Web](https://github.com/necolas/react-native-web)

## GraphQL

- [x] **apollo** を使ってクライアントサイドとサーバーサイド両方を軽めに実装してみました。 🚀 

[hisasann/react-with-graphql: react-with-graphql using apollo-client](https://github.com/hisasann/react-with-graphql)

[hisasann/graphql-server: graphql-server using apollo-server](https://github.com/hisasann/graphql-server)

## TypeScript

[hisasann/typescript-study: study about frontend with TypeScript](https://github.com/hisasann/typescript-study)

- [x] package.json の npm モジュールアップデート

[asdf-vmで各言語のバージョン管理をしてみた🧞‍♀️ - DJ lemon-Sour's diary (prod.hisasann)](https://hisasann.github.io/2020/02/10/asdf-vm/)

## Github Actions

田村くんの本を買って写経

## lemon-sour

[lemon-sour.js](https://github.com/lemon-sour)

- [x] もろもろバージョンアップ

辛かったのが、 `mkdirp` がいつの間にか Promise を返すようになっていて、コールバックパターンではなくなっていたこと。

これで、結構修正点が発生してしまったので、いったん古いバージョンで運用してみる。

- [ ] github actions 追加

### Next.jsを使ってみる

[lemon-sour.js](https://lemon-sourjs-site.netlify.com/)

を

Nuxt から Next.js に移行した。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">lemon-sour.js - <a href="https://t.co/1OG0ntsIor">https://t.co/1OG0ntsIor</a> のページを Nuxt から Next.js に移行してみた。<br>基本的には netlify が JAMstack してくれるから、 github に push するだけでデプロイされる。便利！🥋</p>&mdash; hisasann@DJ lemon-Sour🍌 (@hisasann) <a href="https://twitter.com/hisasann/status/1231879657865170945?ref_src=twsrc%5Etfw">February 24, 2020</a></blockquote>

さらに、 Netlify でデプロイがされたときの通知として Discord にメッセージを出したかったので、

[Zapier | The easiest way to automate your work](https://zapier.com/)

を使ってみました。

すごく簡単でした！

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">Zapier 便利だなー<br>Netlify to Discord にデプロイしたことを send するようにしてみたんだけど、ポチポチするだけで繋げられた。<br><br>Zapier | The easiest way to automate your work - <a href="https://t.co/8BN6294kj9">https://t.co/8BN6294kj9</a></p>&mdash; hisasann@DJ lemon-Sour🍌 (@hisasann) <a href="https://twitter.com/hisasann/status/1232158129695014912?ref_src=twsrc%5Etfw">February 25, 2020</a></blockquote>

[IFTTT: Every thing works better together](https://ifttt.com/) ライクですね。

### contentfulを使ってみる

まだ使い所がうまくつかめていないが、ポッドキャストを始めたら音源が置いてあるパスとかを返す API とか作ってみようかな。

```javascript
const contentful = require("contentful");
const client = contentful.createClient({
  // This is the space ID. A space is like a project folder in Contentful terms
  space: "ra794i9t0yln",
  // This is the access token for this space. Normally you get both ID and the token in the Contentful web app
  accessToken: "U1Wffn5NIhptGsWKyliQCILCWpoaCjJK6mwJwYO_58g"
});
// This API call will request an entry with the specified ID from the space defined at the top, using a space-specific access token.
client.getEntries()
  .then((response) => console.log(response.items))
  .catch(console.error)

client.getEntry('7gXAjvVRrjBMK4XbuJ8TVO')
  .then((entry) => console.log(entry))
  .catch(console.error)
```

### [lemon-sour.js](https://lemon-sourjs-site.netlify.com/) のロゴのURLを返す部分で使ってみた

[🥓 feat: add to get logo image from contentful · lemon-sour/lemon-sourjs-site@a160c5e](https://github.com/lemon-sour/lemon-sourjs-site/commit/a160c5ef071dd5dc9472c9150a44914beff9bb93#diff-e14ec8fd2b038fbccea5f8090d26ace4R2-R17)

## Gatsby

Jekyll のブログから移行できるかためす。

    * つらそうなので、なにかのページ netlify に使いたい
    
lemon-sour-fm に採用決定！

### lemon-sour-fm（ポッドキャスト）

**JAMstack** で netlify を使って、サイトだけ作った状態。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">Zapier 便利だなー<br>Netlify to Discord にデプロイしたことを send するようにしてみたんだけど、ポチポチするだけで繋げられた。<br><br>Zapier | The easiest way to automate your work - <a href="https://t.co/8BN6294kj9">https://t.co/8BN6294kj9</a></p>&mdash; hisasann@DJ lemon-Sour🍌 (@hisasann) <a href="https://twitter.com/hisasann/status/1232158129695014912?ref_src=twsrc%5Etfw">February 25, 2020</a></blockquote>

**Netlify** にデプロイしたらその通知を **Discord** くるようにして、その繋ぎになってくれてるのが、 `zapier` ポチポチでいけたからほんと便利ー！

[hisasann/lemon-sour-fm: lemon-sour-fm](https://github.com/hisasann/lemon-sour-fm)

[All posts | lemon-Sour fm](https://lemon-sour-fm.netlify.com/)

### 参考にしたいポッドキャスト

[Rebuild - Podcast by Tatsuhiko Miyagawa](http://rebuild.fm/)

[ポッドキャスト Export](https://export.fm/)

[STILL RENDERING // スティレン • A podcast on Anchor](https://anchor.fm/stillrendering)

## Tools

### asdfを使ってみる

asdf-vm/asdf: Extendable version manager with support for Ruby, Node.js, Elixir, Erlang & more - https://github.com/asdf-vm/asdf

Linux Mint に asdf で Node.js をインストールする - Qiita - https://qiita.com/takeru08ma/items/c344dd3f6117c14d0fad

- [x] `node.js` と `java` は asdf で入れた

### neovim

- [x] 最近やってなかったの neovim の環境を整備して、 README にまとめました。

[hisasann/neovim](https://github.com/hisasann/neovim)

### exa

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">`abbr -a la exa -l -a` でエイリアスきった。<br>これで `la` が少しキレイに表示される。<br><br>ogham/exa: A modern version of ‘ls’. - <a href="https://t.co/0Cju5xFLjb">https://t.co/0Cju5xFLjb</a></p>&mdash; hisasann@DJ lemon-Sour🍌 (@hisasann) <a href="https://twitter.com/hisasann/status/1232716411509673984?ref_src=twsrc%5Etfw">February 26, 2020</a></blockquote>

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">exa 入れたらこんな配色になっててかわいい！ <a href="https://t.co/hwSg82buwK">pic.twitter.com/hwSg82buwK</a></p>&mdash; hisasann@DJ lemon-Sour🍌 (@hisasann) <a href="https://twitter.com/hisasann/status/1232717833978560512?ref_src=twsrc%5Etfw">February 26, 2020</a></blockquote>

[ogham/exa: A modern version of ‘ls’.](https://github.com/ogham/exa)

### Googleパスワードマネージャーを整理する

- [x] かなり不要なものをいまだに管理しているので削除した。

[パスワード マネージャー](https://passwords.google.com/)

## ゲーム

### 仁王

- [x] クリアした。

### 仁王2（まだ未発売）

### BFV

また久々にやり始めてる。

一日30分ほどやってエイム力を高めてる。

### Apex Legends

1年ぶりだが、またやり始めた。

ライフラインでサポートするのがすごく楽しい（看護兵が好きなので）

### ストリートファイターV（シーズン5）

相変わらずガイルを使っているが、 KAGE が強くなったようなので、こちらもためしたい。

[#9 [スト5] STREET FIGHTER V Guile Training Day - ダイブソニックサマーソルトキックキャンセルCA - YouTube](https://www.youtube.com/watch?v=l2j8YX5mOjE)

[#10 [スト5] STREET FIGHTER V Guile Training Day - ダイブソニックVトリガーサマーソルトキックキャンセルCA - YouTube](https://www.youtube.com/watch?v=ndci6SVKPhA)

## 家族

- [x] Macbook Air を娘に買う。

- [ ] 3月にUSJ（コロナのため様子見）
