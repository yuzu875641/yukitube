偽装ページが本当に雪です。
[mochidukiyukimi](https://github.com/mochidukiyukimi)様にｶﾝｼｬｶﾝｼｬ
ブログをブロックされるとき用  
ASGIで動く  
blog内に静的サイトを入れると認証されていない時にそのサイトが表示されます。  
画像は使えません。  
cookieにyuki=Trueを設定すると認証されます。  
サーバーの起動時に掲示板の公式インスタンスに接続します。定期的にサーバーを再起動してください。  
ちなみにこれは[vercel](https://vercel.com)でも作成できます。
→necolianの[yukitube-vercel-runner](https://github.com/necolian/yukitube-vercel-runner)で大体他のyukiも動作させられます

Renderを使用する場合の手順  
1~4の作業をやらないと、自動でURLがyuki-tangolevel-[4桁の英数字].onrender.comになります。  
1.githubアカウントを作成する  
2.リポジトリを作る(名前はなんでもいい)(プライベートリポジトリにすることをおすすめします)  
3.import codeを押して https://github.com/mochidukiyukimi/Yuki-Youtube-slim/ と入力  
4.render.yamlを開いて編集(鉛筆のマーク)を押し、nameの横のyuki-youtube-slimをサイトのurlの最初の部分にしたい文字列に変更する。(yuki-yだったらurlはhttps://yuki-y.onrender.comになる)  
5.Deploy to renderボタンを押し、Service Group Nameに適当な文字列を入れてapply(事前にrenderのアカウントを作っておく)
<a href="https://render.com/deploy?repo=https://github.com/mochidukiyukimi/Yuki-Youtube-slim-2">
<img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
</a>
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fnecolian%2Fyukitube-ex.git)
