# README

## Usersテーブル
| Column | Type       | Options                        |
| ------ | ---------- | ------------------------------ |
| nickname | string | null: false |
| email  | string | null: false, unique: true  |
| password  | string | null: false  |

## Diaryテーブル
| Column | Type       | Options                        |
| ------ | ---------- | ------------------------------ |
| title | string | null: false |
| url  | text | null: false  |
| event_date  | date | null: false  |
| description | text | null: false  |

