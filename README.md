# 概要

本リポジトリにて、org-408 Organization にて使用する、

* Issue template
* PR template

を用意する。
また、厳密には本リポジトリにて用意しているわけではないが、
本Organizationにて用意している Project template について
以下に説明する

## Project template について

GitHub projects を利用して、スクラム開発を想定した Project templeateを用意した。
以下に template の内容について説明する

### フィールドについて

#### 作成したカスタムフィールド

| 名前 | 種別 | 設定内容 | 項目、例など |
|:---:|:----:|:-------:|:-----|
|Item Type|Single select|Issue種別|Epic/PBI/SBI|
|Sprint|Iteration|スプリント期間を設定する|Sprint 1/Sprint 2/...|
|Epic Status|Single select|Epicの状態を設定する|Idea Box: アイデア置き場<br>Selected: スプリントにて進行中<br>Done: 完了<br>Postpone: 見送り|
|PBI Status|Single select|PBIの状態を設定する|Idea Box: アイデア置き場<br>Ice Box: what, whyが明確になっていて見積可能<br>Ready: 見積済で着手可能<br>Selected: スプリントにて進行中<br>Done: 完了|
|Status|Single select|SBIの状態を設定する|ToDo: 未着手<br>In Progress: 進行中<br>In Review: レビュー中<br>Done: 完了|
|Point|Number|見積ポイント|0, 1, 2, 3, 5, 8, 13, ...|
|Priority|Single select|優先度|Low/Middle/High|

#### 既存のフィールド

* Title
* Labels

### ビューについて

以下のビューを作成した

* Table View
  * 表形式のビュー
* Epic View
  * Epicのステータス管理用
* PBI View
  * プロダクトバックログのステータス管理用
* SBI View
  * スプリントバックログのステータス管理用
* Assignees View
  * 担当者単位のステータス管理用

また、既存のビューとして以下も提供される

* Roadmap

