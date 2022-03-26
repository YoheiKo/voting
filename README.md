#### 保育園・小学校等で使用可能な Web 総会決議用ホームページ

作成日：2022 年 3 月

技術スタック：<br>
Next.js 12.1.1<br>
react 17.0.2<br>
TailwindCSS 3.0.7<br>
react-pdf 5.7.1<br>
file-loader 6.2.0<br>
他は package.json を参照<br>

その他：<br>
議案：議案は pdf で作成し、google docs に配置して下段で誰でも閲覧可能なリンクとして貼る他、本プロジェクトの public フォルダに gian.pdf として保存することで、サイト中に pdf が埋め込まれる。<br>
フォーム：Google Form を利用しリンクを貼った。本アプリにはバックエンド、DB なし。<br>
デプロイ：Vercel が推奨されるが、Next が動けばどこでもよい。<br>
レスポンシブ：本アプリはモバイルと PC にレスポンシブ。<br>

#### 連絡先

Yohei Komori<br>
email:hurumori@gmail.com
