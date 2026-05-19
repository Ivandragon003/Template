# 技術会議議事録

**プロジェクト名:** {{string:project_name}}  
**プロジェクトコード:** {{string:project_code}}  
**顧客名:** {{string:client_name}}  
**会議日:** {{date:meeting_date}}  
**開始時刻:** {{string:start_time}}  
**終了時刻:** {{string:end_time}}  
**場所 / プラットフォーム:** {{string:meeting_location}}  
**議事録作成者:** {{string:minutes_author}}  
**会議種別:** {{string:meeting_type}}

---

## 1. 会議概要

### 1.1 会議の目的

| 項目 | 内容 |
| --- | --- |
| 会議目的 | {{text:meeting_objective}} |
| 対象期間 | {{string:reference_period}} |
| 対象スプリント / マイルストーン | {{string:sprint_or_milestone}} |
| プロジェクト全体状況 | {{string:project_overall_status}} |
| 緊急度 | {{string:urgency_level}} |

### 1.2 関連資料

| ID | 資料名 | バージョン | 担当者 | 状態 |
| --- | --- | --- | --- | --- |
| DOC-01 | {{string:document_1_name}} | {{string:document_1_version}} | {{string:document_1_owner}} | {{string:document_1_status}} |
| DOC-02 | {{string:document_2_name}} | {{string:document_2_version}} | {{string:document_2_owner}} | {{string:document_2_status}} |
| DOC-03 | {{string:document_3_name}} | {{string:document_3_version}} | {{string:document_3_owner}} | {{string:document_3_status}} |

---

## 2. 参加者

### 2.1 参加者一覧

| 氏名 | 役割 | 会社 | 出席状況 | 備考 |
| --- | --- | --- | --- | --- |
| {{string:participant_1_name}} | {{string:participant_1_role}} | {{string:participant_1_company}} | {{string:participant_1_attendance}} | {{text:participant_1_notes}} |
| {{string:participant_2_name}} | {{string:participant_2_role}} | {{string:participant_2_company}} | {{string:participant_2_attendance}} | {{text:participant_2_notes}} |
| {{string:participant_3_name}} | {{string:participant_3_role}} | {{string:participant_3_company}} | {{string:participant_3_attendance}} | {{text:participant_3_notes}} |
| {{string:participant_4_name}} | {{string:participant_4_role}} | {{string:participant_4_company}} | {{string:participant_4_attendance}} | {{text:participant_4_notes}} |
| {{string:participant_5_name}} | {{string:participant_5_role}} | {{string:participant_5_company}} | {{string:participant_5_attendance}} | {{text:participant_5_notes}} |

### 2.2 承認権限者

| 役割 | 氏名 | 会社 | 承認権限 |
| --- | --- | --- | --- |
| 顧客責任者 | {{string:client_manager_name}} | {{string:client_manager_company}} | {{boolean:client_manager_can_approve}} |
| 技術責任者 | {{string:technical_lead_name}} | {{string:technical_lead_company}} | {{boolean:technical_lead_can_approve}} |
| プロジェクトマネージャー | {{string:project_manager_name}} | {{string:project_manager_company}} | {{boolean:project_manager_can_approve}} |
| ベンダー責任者 | {{string:supplier_manager_name}} | {{string:supplier_manager_company}} | {{boolean:supplier_manager_can_approve}} |

---

## 3. 議題

### 3.1 予定議題

| ID | 議題 | 予定時間 | 発表者 |
| --- | --- | --- | --- |
| AGENDA-01 | 進捗状況の確認 | {{integer:agenda_1_duration_minutes}} 分 | {{string:agenda_1_speaker}} |
| AGENDA-02 | 技術課題の確認 | {{integer:agenda_2_duration_minutes}} 分 | {{string:agenda_2_speaker}} |
| AGENDA-03 | リスクと依存関係の確認 | {{integer:agenda_3_duration_minutes}} 分 | {{string:agenda_3_speaker}} |
| AGENDA-04 | 次回作業計画 | {{integer:agenda_4_duration_minutes}} 分 | {{string:agenda_4_speaker}} |
| AGENDA-05 | その他 | {{integer:agenda_5_duration_minutes}} 分 | {{string:agenda_5_speaker}} |

### 3.2 追加議題

| ID | 追加議題 | 提案者 | 理由 |
| --- | --- | --- | --- |
| EXTRA-01 | {{text:extra_topic_1}} | {{string:extra_topic_1_proposer}} | {{text:extra_topic_1_reason}} |
| EXTRA-02 | {{text:extra_topic_2}} | {{string:extra_topic_2_proposer}} | {{text:extra_topic_2_reason}} |

---

## 4. 進捗状況

### 4.1 領域別進捗

| 領域 | 状態 | 進捗率 | 備考 |
| --- | --- | --- | --- |
| 要件定義 | {{string:requirements_status}} | {{percentage:requirements_progress}} | {{text:requirements_notes}} |
| バックエンド開発 | {{string:backend_status}} | {{percentage:backend_progress}} | {{text:backend_notes}} |
| フロントエンド開発 | {{string:frontend_status}} | {{percentage:frontend_progress}} | {{text:frontend_notes}} |
| インテグレーション | {{string:integration_status}} | {{percentage:integration_progress}} | {{text:integration_notes}} |
| テスト / QA | {{string:testing_status}} | {{percentage:testing_progress}} | {{text:testing_notes}} |
| ドキュメント作成 | {{string:documentation_status}} | {{percentage:documentation_progress}} | {{text:documentation_notes}} |
| リリース / デプロイ | {{string:deployment_status}} | {{percentage:deployment_progress}} | {{text:deployment_notes}} |

### 4.2 マイルストーン

| ID | マイルストーン | 予定日 | 状態 | 遅延リスク |
| --- | --- | --- | --- | --- |
| MS-01 | {{string:milestone_1_name}} | {{date:milestone_1_due_date}} | {{string:milestone_1_status}} | {{boolean:milestone_1_delay_risk}} |
| MS-02 | {{string:milestone_2_name}} | {{date:milestone_2_due_date}} | {{string:milestone_2_status}} | {{boolean:milestone_2_delay_risk}} |
| MS-03 | {{string:milestone_3_name}} | {{date:milestone_3_due_date}} | {{string:milestone_3_status}} | {{boolean:milestone_3_delay_risk}} |

---

## 5. 議論内容

### 5.1 主な議論

| テーマ | 内容 |
| --- | --- |
| 全体状況 | {{text:discussion_overall_status}} |
| 技術事項 | {{text:discussion_technical_topics}} |
| 運用事項 | {{text:discussion_operational_topics}} |
| 顧客側コメント | {{text:client_comments}} |
| ベンダー側コメント | {{text:supplier_comments}} |

### 5.2 課題

| ID | 課題内容 | 影響度 | 担当者 | エスカレーション要否 |
| --- | --- | --- | --- | --- |
| ISSUE-01 | {{text:issue_1_description}} | {{string:issue_1_impact}} | {{string:issue_1_owner}} | {{boolean:issue_1_requires_escalation}} |
| ISSUE-02 | {{text:issue_2_description}} | {{string:issue_2_impact}} | {{string:issue_2_owner}} | {{boolean:issue_2_requires_escalation}} |
| ISSUE-03 | {{text:issue_3_description}} | {{string:issue_3_impact}} | {{string:issue_3_owner}} | {{boolean:issue_3_requires_escalation}} |

---

## 6. 決定事項

### 6.1 決定ログ

| ID | 決定事項 | 理由 | 承認者 | 決定日 |
| --- | --- | --- | --- | --- |
| DEC-01 | {{text:decision_1}} | {{text:decision_1_reason}} | {{string:decision_1_approver}} | {{date:decision_1_date}} |
| DEC-02 | {{text:decision_2}} | {{text:decision_2_reason}} | {{string:decision_2_approver}} | {{date:decision_2_date}} |
| DEC-03 | {{text:decision_3}} | {{text:decision_3_reason}} | {{string:decision_3_approver}} | {{date:decision_3_date}} |

### 6.2 保留事項

| ID | 保留事項 | 保留理由 | 担当者 | 次回確認日 |
| --- | --- | --- | --- | --- |
| PEND-01 | {{text:pending_decision_1}} | {{text:pending_reason_1}} | {{string:pending_owner_1}} | {{date:pending_review_date_1}} |
| PEND-02 | {{text:pending_decision_2}} | {{text:pending_reason_2}} | {{string:pending_owner_2}} | {{date:pending_review_date_2}} |

---

## 7. アクションアイテム

### 7.1 新規アクション

| ID | アクション | 担当者 | 優先度 | 期限 | 状態 |
| --- | --- | --- | --- | --- | --- |
| AI-01 | {{text:action_1}} | {{string:action_1_owner}} | {{string:action_1_priority}} | {{date:action_1_due_date}} | {{string:action_1_status}} |
| AI-02 | {{text:action_2}} | {{string:action_2_owner}} | {{string:action_2_priority}} | {{date:action_2_due_date}} | {{string:action_2_status}} |
| AI-03 | {{text:action_3}} | {{string:action_3_owner}} | {{string:action_3_priority}} | {{date:action_3_due_date}} | {{string:action_3_status}} |
| AI-04 | {{text:action_4}} | {{string:action_4_owner}} | {{string:action_4_priority}} | {{date:action_4_due_date}} | {{string:action_4_status}} |

### 7.2 前回会議から完了したアクション

| ID | 完了アクション | 担当者 | 完了日 | 備考 |
| --- | --- | --- | --- | --- |
| DONE-01 | {{text:completed_action_1}} | {{string:completed_action_1_owner}} | {{date:completed_action_1_date}} | {{text:completed_action_1_notes}} |
| DONE-02 | {{text:completed_action_2}} | {{string:completed_action_2_owner}} | {{date:completed_action_2_date}} | {{text:completed_action_2_notes}} |

---

## 8. リスク・課題・依存関係

### 8.1 RAID 管理表

| ID | 種別 | 内容 | 影響度 | 発生確率 | 担当者 |
| --- | --- | --- | --- | --- | --- |
| RAID-01 | {{string:raid_1_type}} | {{text:raid_1_description}} | {{string:raid_1_impact}} | {{percentage:raid_1_probability}} | {{string:raid_1_owner}} |
| RAID-02 | {{string:raid_2_type}} | {{text:raid_2_description}} | {{string:raid_2_impact}} | {{percentage:raid_2_probability}} | {{string:raid_2_owner}} |
| RAID-03 | {{string:raid_3_type}} | {{text:raid_3_description}} | {{string:raid_3_impact}} | {{percentage:raid_3_probability}} | {{string:raid_3_owner}} |

### 8.2 対応策

| RAID ID | 対応策 | 期限 | 状態 |
| --- | --- | --- | --- |
| RAID-01 | {{text:raid_1_mitigation}} | {{date:raid_1_mitigation_due_date}} | {{string:raid_1_mitigation_status}} |
| RAID-02 | {{text:raid_2_mitigation}} | {{date:raid_2_mitigation_due_date}} | {{string:raid_2_mitigation_status}} |
| RAID-03 | {{text:raid_3_mitigation}} | {{date:raid_3_mitigation_due_date}} | {{string:raid_3_mitigation_status}} |

---

## 9. 変更要求

### 9.1 変更要求一覧

| ID | 変更内容 | 想定費用影響 | 想定スケジュール影響 | 承認要否 |
| --- | --- | --- | --- | --- |
| CR-01 | {{text:change_request_1}} | {{currency:change_request_1_cost_impact}} | {{integer:change_request_1_schedule_impact_days}} 日 | {{boolean:change_request_1_requires_approval}} |
| CR-02 | {{text:change_request_2}} | {{currency:change_request_2_cost_impact}} | {{integer:change_request_2_schedule_impact_days}} 日 | {{boolean:change_request_2_requires_approval}} |
| CR-03 | {{text:change_request_3}} | {{currency:change_request_3_cost_impact}} | {{integer:change_request_3_schedule_impact_days}} 日 | {{boolean:change_request_3_requires_approval}} |

### 9.2 変更要求の評価結果

| ID | 評価結果 | 理由 | 次の対応 |
| --- | --- | --- | --- |
| CR-01 | {{string:change_request_1_result}} | {{text:change_request_1_reason}} | {{text:change_request_1_next_step}} |
| CR-02 | {{string:change_request_2_result}} | {{text:change_request_2_reason}} | {{text:change_request_2_next_step}} |
| CR-03 | {{string:change_request_3_result}} | {{text:change_request_3_reason}} | {{text:change_request_3_next_step}} |

---

## 10. 次回会議

### 10.1 次回会議予定

| 項目 | 内容 |
| --- | --- |
| 予定日 | {{date:next_meeting_date}} |
| 予定時刻 | {{string:next_meeting_time}} |
| 場所 / プラットフォーム | {{string:next_meeting_location}} |
| 予定時間 | {{integer:next_meeting_duration_minutes}} 分 |
| 必須参加者 | {{text:next_meeting_required_participants}} |

### 10.2 次回議題

| ID | 議題 | 担当者 |
| --- | --- | --- |
| NEXT-01 | {{text:next_topic_1}} | {{string:next_topic_1_owner}} |
| NEXT-02 | {{text:next_topic_2}} | {{string:next_topic_2_owner}} |
| NEXT-03 | {{text:next_topic_3}} | {{string:next_topic_3_owner}} |

---

## 11. 承認

### 11.1 議事録承認状況

| 項目 | 内容 |
| --- | --- |
| 承認要否 | {{boolean:minutes_approval_required}} |
| コメント期限 | {{integer:comment_deadline_hours}} 時間 |
| 顧客承認済み | {{boolean:client_approved}} |
| ベンダー承認済み | {{boolean:supplier_approved}} |
| 承認に関する備考 | {{text:approval_notes}} |

### 11.2 署名

| 役割 | 氏名 | 日付 | 署名 |
| --- | --- | --- | --- |
| 顧客代表 | {{string:client_representative_name}} | {{date:client_signature_date}} | ____________ |
| ベンダー代表 | {{string:supplier_representative_name}} | {{date:supplier_signature_date}} | ____________ |
| 議事録作成者 | {{string:minutes_author}} | {{date:meeting_date}} | ____________ |

---

_本議事録は {{string:minutes_author}} により作成され、{{string:project_name}} プロジェクトに関する会議内容を記録したものです。コメントは受領後 {{integer:comment_deadline_hours}} 時間以内に提出してください。_