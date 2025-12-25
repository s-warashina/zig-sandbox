# Hello, world! (Zig)

このディレクトリには、Zig 製の Hello World プロジェクトが入っています。Zig のビルドシステムを使ってビルドや実行、テストを行えます。

## 前提条件

- Zig 0.12 以降がインストールされていること  
  インストール方法は公式サイトを参照してください: <https://ziglang.org/download/>

## セットアップと実行

```bash
# 1. プロジェクトのルートに移動
cd hello-world

# 2. 依存関係を取得（なし）
# 3. ビルドと実行
zig build run
```

標準出力に `Hello, world!` が表示されます。

## テストの実行

```bash
cd hello-world
zig build test
```

## プロジェクト構成

- `build.zig`: Zig のビルドスクリプト。`zig build` の手順や `run`/`test` ステップを定義しています。
- `src/main.zig`: エントリーポイント。標準出力に Hello World を表示します。
