# PHP 新着情報管理システム

この作品は、PHPを使った「新着情報登録・一覧表示システム」です。  
テキストファイル保存版とXML保存版の2パターンを実装し、データ管理形式の違いを体験・比較できるようになっています。
こちらは**XML保存版**です

## 内容
- `news_entry_xml.html`：情報入力フォーム
- `news_complete_xml.php`：XMLに保存
- `news_list_xml.php`：XMLデータの読み込み・表示

## 💡 製作のPoint
- 訓練講座の課題をベースに、実用的なレイアウトと安全対策を追加
- `htmlspecialchars()` によるXSS対策、未入力バリデーション実装済
- フォームは1つにまとめ、JavaScriptで送信先を動的に切り替える工夫を実装
- 要素数が0件の際の分岐表示も対応

## 🔗 関連リポジトリ
- テキスト保存版：[https://github.com/yourname/php-news-txt]

## 📜 使用技術
- PHP（フォーム処理、ファイル保存）
- HTML / CSS（簡易レイアウト調整）
- JavaScript（フォーム送信先の切り替え）

