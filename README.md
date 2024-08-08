# zenn-qiita-content

Zenn, Qiita の記事集。

## qiita

### 新しい記事を作成：
```
npx qiita new 記事のファイルのベース名
```
### プレビュー：
```
npx qiita preview
```
### 記事を投稿：
```
npx qiita publish 記事のファイルのベース名
```
### 記事ファイルをQiitaと同期：
```
npx qiita pull
```

## zenn
### 新しい記事を作成（slugを指定）：
article1と指定する場合：
```
npx zenn new:article --slug article1
```
作成後のリポジトリ構造：
```
├── articles/
│   ├── article1.md
│    ...
```

[slugの指定（Zenn公式記事）](https://zenn.dev/zenn/articles/what-is-slug)

### プレビュー：
```
npx zenn preview
```
### 記事の投稿：

zennと同期したリポジトリの対象ブランチにプッシュすると、自動で投稿（Zennにも反映される）。
