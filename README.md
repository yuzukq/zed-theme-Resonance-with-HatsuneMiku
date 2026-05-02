# Resonance with Hatsune Miku
初音ミクのカラーパレットをイメージした、Zed用カスタムテーマ。

## ベースカラー
| 役割 | 色 |
| --- | --- |
| エディタ背景 | `#1d2021` |
| サイドバー / パネル背景 | `#232627` |
| カーソル | `#39c5bb` |
| 前景 (テキスト) | `#add6d7` |
| ミュート前景 | `#5b666f` |
| アクセント (シーグラスのティール) | `#458588` / `#83a598` |
| キーワード / 演算子 | `#f92672` |
| 文字列 | `#91f697` |
| 変数 / プロパティ | `#00bcaf` |
| 型 / 定数 | `#b7f3db` |
| 数値 / 真偽値 | `#dba5c8` |
| 関数 | `#009489` |

## テーマ属性リファレンス

各カラー属性がZedのどのUI部分に対応しているかは [THEME_REFERENCE.md](./THEME_REFERENCE.md) を参照。
カスタマイズ時の手がかりになります。

## ローカルインストール

Zed の `~/.config/zed/themes/` に JSON をコピー、テーマセレクタ (`cmd-k cmd-t`) から選べる。

```sh
mkdir -p ~/.config/zed/themes
cp themes/resonance-with-hatsune-miku.json ~/.config/zed/themes/
```

**カスタマイズをしたい場合：**
シンボリックリンクを作成
```sh
ln -sf "$PWD/themes/resonance-with-hatsune-miku.json" \
       ~/.config/zed/themes/resonance-with-hatsune-miku.json
```

## 拡張としてインストール

このリポジトリには `extension.toml` を含めてあるので、Zed の`zed: install dev extension` コマンドからこのディレクトリを指定すれば拡張として読み込める。
