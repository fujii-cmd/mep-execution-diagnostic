TORUS MEP実行診断 Netlifyパッケージ

1. このフォルダ一式をGitHubリポジトリにアップロード
2. NetlifyでそのGitHubリポジトリを接続
3. Publish directory は . (ルート)
4. Deploy後、Forms > mep-contact で問い合わせ受信を確認
5. ロゴ差し替えは assets/torus-logo.svg を差し替え

推奨URL構成
- /               公開版トップポータル
- /members/       メンバー用詳細版
- /reference/     統合版リファレンス

補足
- members配下は noindex を入れていますが、非公開ではありません。
- 本当に限定公開したい場合は Netlify側のアクセス制御を追加してください。
