# Universal Base Converter 🌐

[![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-blue?style=flat-square)](https://kotetsu0000.github.io/Universal_Base_Converter/)

2進数から36進数まで対応したモダンなWebベースの基数変換ツール。リアルタイムに変換結果を表示します。

## ✨ 特徴

- **多進数変換**: 2進数から36進数まで即時変換
- **大数対応**: `BigInt`を使用した超大数の処理
- **モダンUI**: グラスモーフィズムデザイン & システム連動テーマ
- **レスポンシブ設計**: PC/スマホで最適表示
- **エラーチェック**: 入力検証と分かりやすいエラー表示
- **高性能**: Web Workersによる最適化された変換処理

## 🚀 使い方

1. **入力値**: 現在の基数で有効な数値を入力
   - 大文字/小文字自動変換対応（10進超はA-F）
2. **変換元基数**: 現在の基数を選択（2-36）
3. **変換**: ボタンクリックで全基数の結果を表示

入力例:
- 2進数: `1101` (基数2)
- 16進数: `FF3A` (基数16)
- 36進数: `ZYX` (基数36)

## ⚙️ 技術概要

コアアルゴリズム:
```javascript
// 文字列→10進数(BigInt)変換
function stringToDecimal(str, base) { ... }

// 10進数→任意進数変換
function decimalToString(num, base) { ... }
```

主な技術要素:
- 高精度計算のためのBigInt統合
- 入力検証用正規表現
- テーマ管理のCSSカスタムプロパティ
- 結果表示のレスポンシブグリッドレイアウト
- 非同期変換処理

## 🌍 ライブデモ

公開先URL:  
[https://kotetsu0000.github.io/Universal_Base_Converter/](https://kotetsu0000.github.io/Universal_Base_Converter/)

## 📄 ライセンス

MIT License © 2025 Kotetsu0000
