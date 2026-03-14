# Script Assistant

AI assistant for generating structured video scripts.

資料から構造化された動画台本を生成するAIアシスタントです。

---

## Function / 機能

- Converts source materials into modular script structure  
  資料からモジュール構造の台本を生成

- Supports narration and telop separation  
  ナレーションとテロップを分離した構造に対応

- Outputs spreadsheet-ready script format  
  スプレッドシート形式で出力可能

---

## System Structure / システム構造

This assistant is composed of several subsystems.

このアシスタントは複数のサブシステムで構成されています。

### video_script_system

Main script generation system.  
台本生成のメインシステム。

### module_dictionary

Defines reusable script modules.  
再利用可能な台本モジュールを定義。

### module_transition_map

Defines allowed transitions between modules.  
モジュール間の遷移ルールを定義。

### system.yaml

Configuration entry point for the assistant.  
アシスタントの設定エントリーポイント。
