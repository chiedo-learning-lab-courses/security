## :tada: 安全なワークフローのコースへようこそ！

このコースでは、GitHub上でリポジトリを安全に保つ方法を学ぶことが出来ます。リポジトリを安全に保つことは多くの理由で重要です。
- 機密データを誤って公開してしまうことを防ぐ
- 安全な開発のベストプラクティスを必須とする
- 意図しないアクセス権を付与してしまうことを防ぐ

このコースでは、下記の内容を学びます：

- プライベートリポジトリでの脆弱性アラートを有効化する
  - _注記：これらのセキュリティの設定はフォークではないパブリックリポジトリではデフォルトで有効化されています。_
- 脆弱性アラートによって通知された脆弱な依存関係を検出し、修正する
- `.gitignore`ファイルを使うことで機密データを保護するというベストプラクティスのやり方

### GitHubを使うのは初めてですか？

このコースでは、GitHub Flowに事前に習熟している必要があります。GitHub Flowをご存じない方は、[Introduction to GitHubコース]({{ host}}/courses/introduction-to-github)を御覧ください。

## ステップ1：GitHub Pages上のプロジェクト

このコースではGitHub Pagesにデプロイされた記憶ゲームを題材に使用します。

{% if private %}

### :keyboard: やってみよう：脆弱性アラートとGitHub Pagesの有効化


1. リポジトリの[**Settings**]({{ repoUrl }}/settings)タブをクリック
1. **Data services**のセクションまで画面をスクロール
1. **Data services**セクションにて、全てのデータサービスにチェックを入れて有効化
1. **GitHub Pages**のセクションまで画面をスクロールし、**Source**として`main`を選択し、**Save**をクリック

{% else %}

### :keyboard: やってみよう：GitHub Pagesの有効化


1. リポジトリの[**Settings**]({{ repoUrl }}/settings)タブをクリック
1. **GitHub Pages**のセクションまで画面をスクロールし、**Source**として`main`を選択し、**Save**をクリック

{% endif %}

このコースの手順は[Quick Reference Guide]({{ host }}/public/{{ course.slug }}.pdf)にもまとまっています。

> GitHub Pagesを有効化すると、リポジトリの内容をデプロイします。デプロイが完了するまで待つ必要があるので、次のコメントまで1分ほどお待ち下さい。

<hr>
<h3 align="center">設定が完了したら、次のコメントをこのイシューに書きます。</h3>

> _時々、追加のコメントが書き込まれないことがあります！正しい操作をしたにも関わらず何のコメントも書き込まれない場合は、数秒待ってからこのペ
ージを再読込してください。_