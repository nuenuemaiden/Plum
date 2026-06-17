# Plum.

**金沢大学生のための授業管理ツール**  
A course management tool for Kanazawa University students.
I’m unable to use an iPhone for technical reasons, so I’d appreciate your understanding.
---

## 概要 / Overview

Plum は金沢大学のスクールカラー「茄子紺」をブランドカラーとした、金大生向けの授業管理Webアプリです。インストール不要で、HTMLファイルをブラウザで開くだけで使えます。データはすべてブラウザのlocalStorageに保存されるため、外部サーバーには一切送信されません。

Plum is a course management web app for Kanazawa University students, themed around the university's school color "Nasu-kon" (deep indigo). No installation required — just open the HTML file in a browser. All data is stored locally in your browser and never sent to any server.

---

## 機能 / Features

| 機能 | 説明 |
|------|------|
| 時間割 | Q1〜Q4のクォーター別時間割。今日の授業・現在の時限をハイライト表示 |
| Today パネル | 学年暦に基づいて現在のQを自動判定し、本日の授業を一覧表示 |
| 出席管理 | 授業ごとに出席・欠席を記録。2回欠席で警告、3回で危険アラート |
| 宿題・課題管理 | 期限付きで課題を登録。期限が近づくと赤くハイライト |
| 成績・GPA計算 | S/A/B/C/D形式で成績を登録し、GPA・取得単位数を自動計算。パスワードロック機能付き |
| Tier機能 | 教授・授業内容・睡魔レベルでS〜Dランク表示 |
| CSV保存・読込 | データのエクスポート・インポートに対応 |

| Feature | Description |
|---------|-------------|
| Timetable | Quarter-based (Q1–Q4) timetable with today's column and current period highlighted |
| Today Panel | Automatically detects the current quarter based on the academic calendar |
| Attendance | Track attendance per course. Warns at 2 absences, alerts at 3 |
| Homework | Register assignments with deadlines. Highlights approaching due dates |
| Grades / GPA | Log grades (S/A/B/C/D) and auto-calculate GPA and earned credits. Password lock available |
| Tier | Rank courses by professor, content, and drowsiness level (S–D) |
| CSV | Export and import timetable data |

---

## 使い方 / How to Use

### PC / Desktop
1. `pc.html` をブラウザで開く
2. 左サイドバーの「設定 / 登録」から授業を登録する

---

## 動作環境 / Requirements

- モダンブラウザ（Chrome / Safari / Firefox / Brave）
- インターネット接続（Googleフォントの読み込みに必要）
- Modern browser (Chrome / Safari / Firefox / Brave)
- Internet connection (required for Google Fonts)

---

## データについて / About Data

- すべてのデータはブラウザの `localStorage` に保存されます
- 外部サーバーへの送信は一切ありません
- ブラウザのデータを消去するとデータが失われます。定期的にCSVでバックアップしてください

- All data is stored in the browser's `localStorage`
- No data is sent to any external server
- Clearing browser data will erase all records. Please back up regularly via CSV export

---

## クレジット / Credits

- フォント: [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) / [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) (Google Fonts)
- ブランドカラー: 金沢大学スクールカラー「茄子紺」をモチーフに / Inspired by Kanazawa University's school color "Nasu-kon"

---

*Plum. — Made for KU students*
