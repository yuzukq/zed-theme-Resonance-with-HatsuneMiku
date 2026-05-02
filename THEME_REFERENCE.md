# Zed テーマ属性リファレンス

## ボーダー (Border)

| 属性 | 説明 |
|------|------|
| `border` | 各UIパネル・要素の境界線 |
| `border.variant` | サブ的な境界線（より薄い区切り線） |
| `border.focused` | フォーカス中の要素の境界線 |
| `border.selected` | 選択中の要素の境界線 |
| `border.transparent` | 透明な境界線（スペーサー用途） |
| `border.disabled` | 無効状態の要素の境界線 |

---

## サーフェス・背景 (Surface / Background)

| 属性 | 説明 |
|------|------|
| `background` | アプリ全体のベース背景色 |
| `elevated_surface.background` | 浮き上がった要素の背景（モーダル・ポップオーバーなど） |
| `surface.background` | 一般的なサーフェスの背景（サイドバー・パネルなど） |

---

## 要素 (Element)

クリック可能なボタン・リスト項目などのインタラクティブ要素に使われる色。

| 属性 | 説明 |
|------|------|
| `element.background` | 要素の通常背景 |
| `element.hover` | ホバー時の背景 |
| `element.active` | クリック中（アクティブ）の背景 |
| `element.selected` | 選択中の背景 |
| `element.disabled` | 無効状態の背景 |

---

## ゴースト要素 (Ghost Element)

背景なしで表示されるアイコンボタンなどの透明ベース要素。

| 属性 | 説明 |
|------|------|
| `ghost_element.background` | 通常時（透明） |
| `ghost_element.hover` | ホバー時の背景 |
| `ghost_element.active` | クリック中の背景 |
| `ghost_element.selected` | 選択中の背景 |
| `ghost_element.disabled` | 無効状態の背景 |

---

## ドロップターゲット (Drop Target)

| 属性 | 説明 |
|------|------|
| `drop_target.background` | ドラッグ&ドロップ時のターゲット領域の背景 |

---

## テキスト (Text)

| 属性 | 説明 |
|------|------|
| `text` | 通常のテキスト色 |
| `text.muted` | 目立たせないテキスト（ラベル・メタ情報など） |
| `text.placeholder` | 入力欄のプレースホルダーテキスト |
| `text.disabled` | 無効状態のテキスト |
| `text.accent` | アクセントカラーのテキスト（リンク・強調など） |

---

## アイコン (Icon)

| 属性 | 説明 |
|------|------|
| `icon` | 通常のアイコン色 |
| `icon.muted` | 目立たせないアイコン |
| `icon.disabled` | 無効状態のアイコン |
| `icon.placeholder` | プレースホルダーアイコン |
| `icon.accent` | アクセントカラーのアイコン |

---

## UIバー・タブ (Bars / Tabs)

| 属性 | 説明 |
|------|------|
| `status_bar.background` | 画面下部のステータスバー背景 |
| `title_bar.background` | ウィンドウ上部のタイトルバー背景（アクティブ時） |
| `title_bar.inactive_background` | タイトルバー背景（非アクティブ時） |
| `toolbar.background` | エディタ上部のツールバー背景 |
| `tab_bar.background` | タブバー全体の背景 |
| `tab.inactive_background` | 非アクティブタブの背景 |
| `tab.active_background` | アクティブタブの背景 |

---

## 検索 (Search)

| 属性 | 説明 |
|------|------|
| `search.match_background` | 検索ヒット箇所のハイライト背景 |

---

## パネル (Panel)

ファイルツリー・アウトラインなどのサイドパネル。

| 属性 | 説明 |
|------|------|
| `panel.background` | パネル背景 |
| `panel.focused_border` | フォーカス中のパネル境界線 |
| `panel.indent_guide` | インデントガイド線 |
| `panel.indent_guide_active` | アクティブなインデントガイド線 |
| `panel.indent_guide_hover` | ホバー中のインデントガイド線 |

---

## ペイン (Pane)

エディタを分割した各ペイン。

| 属性 | 説明 |
|------|------|
| `pane.focused_border` | フォーカス中のペイン境界線 |
| `pane_group.border` | ペイングループの境界線 |

---

## スクロールバー (Scrollbar)

| 属性 | 説明 |
|------|------|
| `scrollbar.thumb.background` | スクロールバーのサム（つまみ）背景 |
| `scrollbar.thumb.hover_background` | サムのホバー時背景 |
| `scrollbar.thumb.border` | サムの境界線 |
| `scrollbar.track.background` | スクロールバーのトラック（溝）背景 |
| `scrollbar.track.border` | トラックの境界線 |

---

## エディタ (Editor)

| 属性 | 説明 |
|------|------|
| `editor.foreground` | エディタの基本テキスト色 |
| `editor.background` | エディタ背景 |
| `editor.gutter.background` | 行番号エリア（ガター）の背景 |
| `editor.subheader.background` | エディタサブヘッダー背景（ファイルパス表示など） |
| `editor.active_line.background` | カーソルがある行のハイライト背景 |
| `editor.highlighted_line.background` | 強調表示された行の背景 |
| `editor.line_number` | 行番号の色 |
| `editor.active_line_number` | カーソル行の行番号の色 |
| `editor.invisible` | 不可視文字（スペース・タブ記号など）の色 |
| `editor.wrap_guide` | 折り返しガイドライン |
| `editor.active_wrap_guide` | アクティブな折り返しガイドライン |
| `editor.indent_guide` | インデントガイド線 |
| `editor.indent_guide_active` | アクティブなインデントガイド線 |
| `editor.document_highlight.read_background` | シンボルの参照箇所（読み取り）のハイライト |
| `editor.document_highlight.write_background` | シンボルの参照箇所（書き込み）のハイライト |
| `editor.document_highlight.bracket_background` | 対応する括弧のハイライト |

---

## ターミナル (Terminal)

| 属性 | 説明 |
|------|------|
| `terminal.background` | ターミナル背景 |
| `terminal.foreground` | ターミナルの基本テキスト色 |
| `terminal.bright_foreground` | ターミナルの明るいテキスト色 |
| `terminal.dim_foreground` | ターミナルの暗いテキスト色 |

### ターミナル ANSIカラー

| 属性 | 説明 |
|------|------|
| `terminal.ansi.black` / `bright_black` / `dim_black` | 黒（通常・明・暗） |
| `terminal.ansi.red` / `bright_red` / `dim_red` | 赤（通常・明・暗） |
| `terminal.ansi.green` / `bright_green` / `dim_green` | 緑（通常・明・暗） |
| `terminal.ansi.yellow` / `bright_yellow` / `dim_yellow` | 黄（通常・明・暗） |
| `terminal.ansi.blue` / `bright_blue` / `dim_blue` | 青（通常・明・暗） |
| `terminal.ansi.magenta` / `bright_magenta` / `dim_magenta` | マゼンタ（通常・明・暗） |
| `terminal.ansi.cyan` / `bright_cyan` / `dim_cyan` | シアン（通常・明・暗） |
| `terminal.ansi.white` / `bright_white` / `dim_white` | 白（通常・明・暗） |

---

## リンク (Link)

| 属性 | 説明 |
|------|------|
| `link_text.hover` | ホバー時のリンクテキスト色 |

---

## ステータス色 (Status Colors)

Git・診断・ファイル状態などの表示に使われる。

| 属性 | 説明 |
|------|------|
| `conflict` / `.background` / `.border` | コンフリクト（競合）状態 |
| `created` / `.background` / `.border` | 新規作成ファイル |
| `deleted` / `.background` / `.border` | 削除されたファイル |
| `error` / `.background` / `.border` | エラー |
| `hidden` / `.background` / `.border` | 隠しファイル |
| `hint` / `.background` / `.border` | ヒント（軽微な提案） |
| `ignored` / `.background` / `.border` | Gitで無視されたファイル |
| `info` / `.background` / `.border` | 情報 |
| `modified` / `.background` / `.border` | 変更されたファイル |
| `predictive` / `.background` / `.border` | AI予測テキスト |
| `renamed` / `.background` / `.border` | リネームされたファイル |
| `success` / `.background` / `.border` | 成功 |
| `unreachable` / `.background` / `.border` | 到達不能な状態 |
| `warning` / `.background` / `.border` | 警告 |

---

## プレイヤー (Players)

複数人編集時の各ユーザーのカーソル・選択色。配列の順番がプレイヤー番号に対応。

| 属性 | 説明 |
|------|------|
| `cursor` | カーソル色 |
| `background` | カーソル背景色 |
| `selection` | テキスト選択ハイライト色 |

---

## シンタックスハイライト (Syntax)

| 属性 | 説明 |
|------|------|
| `attribute` | HTML/JSX属性、アノテーション（`#[derive]`など） |
| `boolean` | `true` / `false` などのブール値 |
| `comment` | 通常コメント |
| `comment.doc` | ドキュメントコメント（`///`、`/** */`など） |
| `constant` | 定数（`UPPER_CASE`など） |
| `constructor` | コンストラクタ・型コンストラクタ |
| `embedded` | 埋め込みコード（テンプレートリテラル内など） |
| `emphasis` | Markdownのイタリック体 |
| `emphasis.strong` | Markdownの太字 |
| `enum` | 列挙型 |
| `function` | 関数名 |
| `function.method` | メソッド名 |
| `hint` | インレイヒント（型推論の表示など） |
| `keyword` | `if`・`for`・`return`などのキーワード |
| `label` | ラベル（`loop`ラベルなど） |
| `link_text` | Markdownリンクのテキスト部分 |
| `link_uri` | MarkdownリンクのURI部分 |
| `namespace` | 名前空間・モジュール名 |
| `number` | 数値リテラル |
| `operator` | 演算子（`+`・`=`・`&&`など） |
| `parameter` | 関数の引数名 |
| `predictive` | AI補完の予測テキスト |
| `preproc` | プリプロセッサ命令（`#include`・`#define`など） |
| `primary` | 基本テキスト |
| `property` | オブジェクトプロパティ・構造体フィールド |
| `punctuation` | 一般的な句読点 |
| `punctuation.bracket` | 括弧 `()`・`{}`・`[]` |
| `punctuation.delimiter` | 区切り文字（`,`・`;`など） |
| `punctuation.list_marker` | Markdownリストマーカー（`-`・`*`など） |
| `punctuation.special` | 特殊な句読点（`$`・`#`など） |
| `string` | 文字列リテラル |
| `string.escape` | 文字列内のエスケープシーケンス（`\n`・`\t`など） |
| `string.regex` | 正規表現 |
| `string.special` | 特殊な文字列（生文字列など） |
| `string.special.symbol` | シンボル文字列（Rubyの `:symbol`など） |
| `tag` | HTMLタグ名 |
| `text.literal` | Markdownのインラインコード・コードブロック |
| `title` | Markdownの見出し |
| `type` | 型名 |
| `type.builtin` | 組み込み型（`int`・`str`・`bool`など） |
| `variable` | 変数名 |
| `variable.special` | 特殊変数（`self`・`this`・`super`など） |
| `variant` | enum のバリアント |
