# Zenn CLI

* [📘 How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)

## 新しい記事を作成する

```pwsh
pnpm article --slug "$(Get-Date -Format 'yyMMdd')-title-*"
```

```sh
pnpm article --slug $(date +%y%m%d)-title-*
```

ファイル名およびURLの可読性の向上のため以下を追加:
- `$(date +%y%m%d)`: 年月日各二桁
- [zenn-create](https://github.com/soags/zenn-create/tree/main): Zenn CLI改良版

ファイル名の制約: 12-50文字の長さで半角小文字英数字と記号`-`

241127-fallback-og-image-papermod-a8e44cdb6d6b4e

## 投稿をプレビューする

```sh
pnpm preview
```
