# テーマ構成

## テンプレートファイル構成

|ページ名|HTMLファイル名|テンプレートファイル名|備考|
|:---|:---|:---|:---|
|トップページ|index.html|front-page.php|
|Recipe Diary について|about.html|page-about.php|
|お知らせ|news.html|home.php|
|お知らせカテゴリーアーカイブ|news-category.html|archive.php|
|お知らせ詳細|news-detail.html|single.php|
|レシピ一覧|recipe-list.html|archive-recipe.php|
|レシピカテゴリー|recipe-category.html|taxonomy-recipe_category.php|
|レシピ詳細|recipe-detail.html|single-recipe.php|
|お問い合わせ|contact.html|page-contact.php|
|プライバシーポリシー|privacy-policy.html|privacy-policy.php|
|404|404.html|404.php|

## テンプレートパーツ構成

|パーツ名|テンプレートパーツファイル名|備考|
|:---|:---|:---|
|共通ヘッダー|header.php|トップページのみメインビジュアルを表示|
|共通フッター|footer.php||
|お知らせリスト|template-parts/news-list.php||
|レシピリスト|template-parts/recipe-list.php||

## カテゴリー・タクソノミー設定案

### お知らせ（標準の投稿）
- **タクソノミー名**: カテゴリー (`category`)

|カテゴリー名|スラッグ|備考|
|:---|:---|:---|
|お知らせ|news||
|重要|important||
|イベント|event||

### レシピ（カスタム投稿タイプ）
- **投稿タイプスラッグ**: `recipe`
- **タクソノミー名**: レシピカテゴリー (`recipe_category`)

|カテゴリー名|スラッグ|備考|
|:---|:---|:---|
|洋食|western||
|和食|japanese||
|エスニック|ethnic||