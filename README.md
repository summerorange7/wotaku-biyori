# README

## Userテーブル
| Column | Type       | Options                        |
| ------ | ---------- | ------------------------------ |
| nickname | string | null: false |
| email  | string | null: false, unique: true  |
| password  | string | null: false  |

### Association
has_many :diary 

## Diaryテーブル
| Column | Type       | Options                        |
| ------ | ---------- | ------------------------------ |
| title | string | null: false |
| url  | text | null: false  |
| event_date  | date | null: false  |
| description | text | null: false  |

### Association
belongs_to :user 