# Change of job

<p align="center">
  <img src="https://github.com/hisasann/change-of-job/blob/master/assets/macbookpro16.png">
</p>

転職時せっかくなので、 MacBookPro を新調しました！😻

16 インチは大きい！💻

そしてこちらは、転職時に、時間を作って新しくやったことを学んでいっているログの記録です。

## Slack

- [x] Workflow を試してみるが、フリープランではワークフロービルダーが使えなかった

## hisasann.github.ioのPWA化

- [x] done

[DJ lemon-Sour's diary (prod.hisasann)](https://hisasann.github.io/)

https なサイトから http のリクエストをしていたことや、

適切な png 画像が配置されていないことが、原点となっていたので、こちらは解消した。

## React Native

- [x] 初めてのビルドの記事を作成する

[初めてのReactNative-ビルド編🍱 - DJ lemon-Sour's diary (prod.hisasann)](https://hisasann.github.io/2020/02/13/first-time-react-native/)

## React Native の入門 Udemy をやる

[hisasann/news-app: React Native 入門 Udemy の写経用リポジトリ](https://github.com/hisasann/news-app)

- [] 30%

その後、こちらの Undemy を購入して初学者向け勉強をし始めました。

内容は理解しやすく、 expo-cli を使う場合のメリット・デメリットが知れたのででかいです。

[React Native入門：ニュースアプリを作りながら覚えよう/Hooks対応 2020年版 | Udemy](https://www.udemy.com/course/react-native-first-step/)

## React Hooks

## GraphQL

[apollographql/apollo-client: A fully-featured, production ready caching GraphQL client for every UI framework and GraphQL server](https://github.com/apollographql/apollo-client)

## React Native Web

[necolas/react-native-web: React Native for Web](https://github.com/necolas/react-native-web)

## TypeScript

- [x] package.json の npm モジュールアップデート

[hisasann/typescript-study: study about frontend with TypeScript](https://github.com/hisasann/typescript-study)

## asdfを使ってみる

asdf-vm/asdf: Extendable version manager with support for Ruby, Node.js, Elixir, Erlang & more - https://github.com/asdf-vm/asdf

Linux Mint に asdf で Node.js をインストールする - Qiita - https://qiita.com/takeru08ma/items/c344dd3f6117c14d0fad

- [x] `node.js` と `java` は asdf で入れた

[asdf-vmで各言語のバージョン管理をしてみた🧞‍♀️ - DJ lemon-Sour's diary (prod.hisasann)](https://hisasann.github.io/2020/02/10/asdf-vm/)

## contentfulを使ってみる

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

## Github Actions

田村くんの本を買って写経

## lemon-sour

[lemon-sour.js](https://github.com/lemon-sour)

- [x] もろもろバージョンアップ

辛かったのが、 `mkdirp` がいつの間にか Promise を返すようになっていて、コールバックパターンではなくなっていたこと。

これで、結構修正点が発生してしまったので、いったん古いバージョンで運用してみる。

- [] github actions 追加

## Gatsby

1.Jekyll のブログから移行できるかためす

    * つらそうなので、なにかのページ netlify に使いたい
    
1.lemon-sour-fm に採用決定！

## lemon-sour-fm（ポッドキャスト）

**JAMstack** で netlify を使って、サイトだけ作った状態。

まだ、記事とかは仮。

[hisasann/lemon-sour-fm: lemon-sour-fm](https://github.com/hisasann/lemon-sour-fm)

[All posts | lemon-Sour fm](https://lemon-sour-fm.netlify.com/)

### 参考にしたいポッドキャスト

[Rebuild - Podcast by Tatsuhiko Miyagawa](http://rebuild.fm/)

[ポッドキャスト Export](https://export.fm/)

[STILL RENDERING // スティレン • A podcast on Anchor](https://anchor.fm/stillrendering)

## neovim

- [x] 最近やってなかったの neovim の環境を整備して、 README にまとめました。

[hisasann/neovim](https://github.com/hisasann/neovim)

## 家族

1. Macbook Air を娘に買う
1. 3月にUSJ
