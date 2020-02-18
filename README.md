# Change of job

<p align="center">
  <img src="https://github.com/hisasann/change-of-job/blob/master/assets/macbookpro16.png">
</p>

どうでもいいことですが、転職時せっかくなので、 MacBookPro を新調しました！😻

そしてこちらは、転職時に、時間を作って新しくやったことを学んでいっているログの記録です。

## Slack

- [x] Workflow を試してみるが、フリープランではワークフロービルダーが使えなかった

## hisasann.github.ioのPWA化

- [] done

[DJ lemon-Sour's diary (prod.hisasann)](https://hisasann.github.io/)

https なサイトから http のリクエストをしていたことや、

適切な png 画像が配置されていないことが、原点となっていたので、こちらは解消した。

## React Native

✔ビルドの記事

[初めてのReactNative-ビルド編🍱 - DJ lemon-Sour's diary (prod.hisasann)](https://hisasann.github.io/2020/02/13/first-time-react-native/)

[React Native入門：ニュースアプリを作りながら覚えよう/Hooks対応 2020年版 | Udemy](https://www.udemy.com/course/react-native-first-step/)

その後、こちらの Undemy を購入して初学者向け勉強をし始めました。

内容は理解しやすく、 expo-cli を使う場合のメリット・デメリットが知れたのででかいです。

## React Hooks

## GraphQL

[apollographql/apollo-client: A fully-featured, production ready caching GraphQL client for every UI framework and GraphQL server](https://github.com/apollographql/apollo-client)

## React Native Web

[necolas/react-native-web: React Native for Web](https://github.com/necolas/react-native-web)

## TypeScript

知らないことをない状態へ

〆package.json の npm モジュールアップデート

## asdf

〆asdf-vm/asdf: Extendable version manager with support for Ruby, Node.js, Elixir, Erlang & more - https://github.com/asdf-vm/asdf

Linux Mint に asdf で Node.js をインストールする - Qiita - https://qiita.com/takeru08ma/items/c344dd3f6117c14d0fad

〆node.js と java は asdf で入れた

[asdf-vmで各言語のバージョン管理をしてみた🧞‍♀️ - DJ lemon-Sour's diary (prod.hisasann)](https://hisasann.github.io/2020/02/10/asdf-vm/)

## contentful使ってみる

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

✔もろもろバージョンアップ

github actions 追加

## Gatsby

1.Jekyll のブログから移行できるかためす

    * つらそうなので、なにかのページ netlify に使いたい
    
1.lemon-sour-fm に採用決定！

## neovim

〆最近やってなかったの neovim の環境を整備して、 README にまとめました。

[hisasann/neovim](https://github.com/hisasann/neovim)

## 家族

1. Macbook Air を娘に買う
1. 3月にUSJ
1. ディズニーランド
1. としまえん
