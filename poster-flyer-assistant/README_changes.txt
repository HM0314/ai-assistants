Poster system revised package (v3)

Main changes in this revision:
- Added strict separation between display copy and review notes
- Added customer-facing copy check to avoid creator-side wording on the flyer itself
- Switched review table to a derived view from block_list_master
- Added rule that every major visible block in preview must exist in the review table
- Added export validation to ensure review notes never leak into final outputs
- Kept the lightweight module / block workflow and the simple review table format:
  - No
  - 場所
  - 何が書いてあるか


[追加反映 v4]
- layout_idea_dictionary_.txt を追加（標準 + 5レイアウト）
- poster_layout_flow_memo.txt を追加
- review 画面で selected_layout を1行表示する前提を追加
- 初稿は原則「標準レイアウト」、大きな構図変更時だけ layout 辞書で再構成する流れを明文化


[v5 additions]
- poster_layout_flow_memo に initial_block_guideline を具体化
- 再構成判定条件と確認質問を追加
- レイアウト修正の目的カテゴリを追加
- 「同一areaに複数content blockを保持してよい」方針を明記


[v6 updates]
- Runbook を新フロー基準（content_pool → selected_layout → block_list_master → preview/review → export）に一本化
- module_selection_system の template 候補を用途名ではなく composition 名に変更
- poster_template_slot_schema を用途ベース template から構図ベース composition schema に変更
- html preview のレビュー表示を人間向け構成表中心に寄せる補足を追加

- v7: Runbook のファイル拡張子表記を実ファイル名（*.txt）に統一
- v7: color palette 辞書を構造整理し、用途ラベルより見え方・印象ベースへ中立化
