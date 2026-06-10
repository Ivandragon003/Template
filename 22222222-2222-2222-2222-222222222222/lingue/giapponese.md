# 技術会議議事録

**プロジェクト名:** {{string:project_name:150:true:プロジェクトの正式名称を入力してください}}
**プロジェクトコード:** {{string:project_code:50:true:社内または顧客側のプロジェクト識別コードを入力してください}}
**顧客名:** {{string:client_name:150:true:顧客または依頼元の正式名称を入力してください}}
**会議日:** {{date:meeting_date:10:true:会議が実施された日付を入力してください}}
**開始時刻:** {{string:start_time:5:true:会議の開始時刻を入力してください}}
**終了時刻:** {{string:end_time:5:true:会議の終了時刻を入力してください}}
**場所 / プラットフォーム:** {{string:meeting_location:150:true:会議室名またはオンライン会議ツール名を入力してください}}
**議事録作成者:** {{string:minutes_author:100:true:議事録を作成した担当者名を入力してください}}
**会議種別:** {{string:meeting_type:80:true:定例会議、技術レビュー、進捗確認などの会議種別を入力してください}}

---

## 1. 会議概要

### 1.1 会議の目的

| 項目                | 内容                                                                       |
| ----------------- | ------------------------------------------------------------------------ |
| 会議目的              | {{string:meeting_objective:1000:true:会議の主な目的や確認すべき事項を入力してください}}          |
| 対象期間              | {{string:reference_period:100:false:会議で扱う対象期間を入力してください}}                 |
| 対象スプリント / マイルストーン | {{string:sprint_or_milestone:100:false:対象となるスプリント名またはマイルストーン名を入力してください}} |
| プロジェクト全体状況        | {{string:project_overall_status:100:true:プロジェクト全体の現在の状況を入力してください}}       |
| 緊急度               | {{string:urgency_level:50:true:対応の緊急度を入力してください}}                         |

---

## 2. 参加者

### 2.1 承認権限者

| 役割           | 氏名                                                                | 会社                                                                     | 承認権限                                                             |
| ------------ | ----------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------- |
| 顧客責任者        | {{string:client_manager_name:100:true:顧客側責任者の氏名を入力してください}}        | {{string:client_manager_company:150:true:顧客側責任者の所属会社を入力してください}}        | {{boolean:client_manager_can_approve:5:true:承認権限の有無を入力してください}}   |
| 技術責任者        | {{string:technical_lead_name:100:true:技術責任者の氏名を入力してください}}         | {{string:technical_lead_company:150:true:技術責任者の所属会社を入力してください}}         | {{boolean:technical_lead_can_approve:5:true:承認権限の有無を入力してください}}   |
| プロジェクトマネージャー | {{string:project_manager_name:100:true:プロジェクトマネージャーの氏名を入力してください}} | {{string:project_manager_company:150:true:プロジェクトマネージャーの所属会社を入力してください}} | {{boolean:project_manager_can_approve:5:true:承認権限の有無を入力してください}}  |
| ベンダー責任者      | {{string:supplier_manager_name:100:true:ベンダー側責任者の氏名を入力してください}}    | {{string:supplier_manager_company:150:true:ベンダー側責任者の所属会社を入力してください}}    | {{boolean:supplier_manager_can_approve:5:true:承認権限の有無を入力してください}} |

---
