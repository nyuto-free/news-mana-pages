# news-mana-pages

iOSアプリ **News Mana** の公式ページ（プライバシーポリシー等）。

GitHub Pages（カスタムドメイン）で配信しています:
https://newsmana.mana-app.studio/

## 構成

| ファイル | 内容 |
| --- | --- |
| `index.md` | プライバシーポリシー（トップページ） |
| `_config.yml` | Jekyll サイト設定 |
| `CNAME` | GitHub Pages のカスタムドメイン指定 |

## ローカルでプレビュー（任意）

```bash
bundle install
bundle exec jekyll serve
# → http://127.0.0.1:4000/
```

`Gemfile` がない場合は以下で初期化:

```bash
echo 'source "https://rubygems.org"' > Gemfile
echo 'gem "github-pages", group: :jekyll_plugins' >> Gemfile
bundle install
```

## アプリ本体

- リポジトリ: （非公開）
- App Store: （リリース後に追記）
