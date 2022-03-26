# 幼稚園・保育園・小学校等で使用可能な総会決議用ホームページテンプレート

本レポジトリの事例は[こちら](https://honkoma-minami.vercel.app/)

技術スタック：
Next.js 12.1.1
react 17.0.2
TailwindCSS 3.0.7
react-pdf 5.7.1
file-loader 6.2.0
他は package.json を参照

その他：
議案：議案は pdf で作成し、google docs に配置して下段で誰でも閲覧可能なリンクとして貼る他、本プロジェクトの public フォルダに gian.pdf として保存することで、サイト中に pdf が埋め込まれる。
フォーム：Google Form を利用しリンクを貼った。本アプリにはバックエンド、DB なし。
デプロイ：Vercel が推奨されるが、Next が動けばどこでもよい。他でも可能である。
レスポンシブ：本アプリはモバイルと PC にレスポンシブ。

## 連絡先

Yohei Komori
email:hurumori@gmail.com
