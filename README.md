#### PTA で使用可能な Web 総会決議用ホームページ

作成日：2022 年 3 月

技術スタック：<br>
+-- @types/node@17.0.4<br/>
+-- @types/react-pdf@5.0.9<br/>
+-- @types/react@17.0.38<br/>
+-- autoprefixer@10.4.4<br/>
+-- file-loader@6.2.0<br/>
+-- next@12.1.1<br/>
+-- postcss@8.4.12<br/>
+-- prettier-plugin-tailwindcss@0.1.8<br/>
+-- prettier@2.6.1<br/>
+-- react-dom@17.0.2<br/>
+-- react-pdf@5.7.1<br/>
+-- react@17.0.2<br/>
+-- tailwind-scrollbar-hide@1.1.7<br/>
+-- tailwindcss@3.0.23<br/>
`-- typescript@4.5.4<br/>

仕様等：<br>
議案：議案は pdf で作成し、google docs に配置して下段で誰でも閲覧可能なリンクとして貼られてます。また、本プロジェクトの public フォルダに gian.pdf として保存することで、サイト中に pdf が埋め込まれます。<br>
フォーム：Google Form を利用しリンクを貼りました。よって本アプリにはバックエンド、DB ないです。<br>
デプロイ：Vercel を推奨しますが、Next.js が動けばどこでもよいと思います。<br>
レスポンシブ：本アプリはモバイルと PC にレスポンシブです。<br>
代替手段：Google サイト（2022 年 7 月に大きなバージョン変更あり）にも pdf 埋め込み機能があり、本サイトと同様のサイトが作成可能です。

#### 連絡先

Yohei Komori<br>
email:hurumori@gmail.com
