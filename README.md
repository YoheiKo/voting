#### PTA で使用可能な Web 総会決議用ホームページ

作成日：2022 年 3 月

技術スタック：<br>
Next.js 12.1.1<br>
react 17.0.2<br>
TailwindCSS 3.0.7<br>
react-pdf 5.7.1<br>
file-loader 6.2.0<br>
他は package.json を参照<br>

その仕様等：<br>
議案：議案は pdf で作成し、google docs に配置して下段で誰でも閲覧可能なリンクとして貼る他、本プロジェクトの public フォルダに gian.pdf として保存することで、サイト中に pdf が埋め込ます。<br>
フォーム：Google Form を利用しリンクを貼りました。よって本アプリにはバックエンド、DB ないです。<br>
デプロイ：Vercel 推奨ですが、Next が動けばどこでもよいと思います。<br>
レスポンシブ：本アプリはモバイルと PC にレスポンシブです。<br>
代替手段：Google サイト（2022 年 7 月に大きなバージョンあり）にも pdf 埋め込み機能があり、本サイトと同様のサイトが作成可能です。

#### 連絡先

Yohei Komori<br>
email:hurumori@gmail.com
