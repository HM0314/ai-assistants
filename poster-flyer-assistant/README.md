# Poster / Flyer Assistant

AI assistant for generating structured poster and flyer layouts.

チラシやポスターの構成を生成するAIアシスタントです。

---

## Function / 機能

- Converts product information into poster structure  
  商品情報からポスター構成を生成

- Generates layout blocks and content hierarchy  
  レイアウト構造と情報階層を生成

- Supports export to design workflows  
  デザイン制作ワークフローに対応

---

## System Structure / システム構造

This assistant is composed of multiple subsystems.

このアシスタントは複数のサブシステムで構成されています。

### copy_generation_system
コピーやテキスト要素を生成するシステム

### layout_idea_dictionary
レイアウトアイデア辞書

### module_selection_system
ポスターモジュール選択ロジック

### module_to_slot_mapping_system
モジュールとレイアウトスロットの対応

### export_preparation_system
出力データ整形システム

### html_preview_generation_system
HTMLプレビュー生成システム

### system.yaml
アシスタントの設定エントリーポイント
