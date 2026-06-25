# Plum. made by nuenuemainden

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
1. `Plum_ver○○.html` をブラウザで開く
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

---# Plum.

**金沢大学生のための授業管理ツール**
A course management tool for Kanazawa University students.

> 金沢大学スクールカラー「茄子紺」をブランドカラーとした、金大生向けWebアプリ。
> インストール不要。HTMLファイルをブラウザで開くだけで動く。

---

## ファイル構成 / Files

| ファイル | 説明 |
|---------|------|
| `Plum_ver4.4.html` | PC版 |
| `plum_ver6.0.html` | PC版改良版 |

---

## 機能一覧 / Features

### 基本機能
| 機能 | 説明 |
|------|------|
| 時間割 | Q1〜Q4のクォーター別時間割。今日の列・現在時限をハイライト |
| Today パネル | 学年暦に基づいてQを自動判定し、本日の授業を一覧表示 |
| 出席管理 | 授業ごとに出席・欠席を記録。2回欠席で警告、3回で危険アラート |
| 宿題・課題管理 | 期限付きで課題を登録。期限が近づくと赤くハイライト |
| テストカウントダウン | テスト日程を登録し「あと○日」を表示 |
| 成績・GPA計算 | S/A/B/C/D形式で成績を登録し、GPA・取得単位数を自動計算 |
| GPA推移グラフ | クォーター別のGPA推移を折れ線グラフで可視化 |
| Tier機能 | 教授・授業内容・睡魔レベルでS〜Dランク表示 |
| CSV保存・読込 | データのエクスポート・インポートに対応 |

### UI・体験
| 機能 | 説明 |
|------|------|
| ダークモード | 茄子紺ベースのダークテーマに切替可能 |
| スプラッシュ画面 | 起動時のブランドアニメーション |
| 週間カレンダー | ホームに一週間分の授業をコンパクト表示 |
| 次の授業カウントダウン | 今日の次の授業まで「あと○分」 |
| ダッシュボード | 出席率リング・GPA・取得単位・連続出席を一画面に |
| 称号システム | 出席・成績・課題達成で称号アンロック（全9種） |
| オンボーディング | 初回起動時のウェルカム案内 |

### セキュリティ
| 機能 | 説明 |
|------|------|
| 成績パスワードロック | 成績・GPAページをパスワードで保護 |
| GPA表示切替 | ホームのGPA表示をON/OFF（デフォルトOFF） |

### PWA・通知
| 機能 | 説明 |
|------|------|
| PWA対応 | ホーム画面に追加してアプリとして使用可能 |
| オフライン動作 | Service Workerによるキャッシュでオフラインでも動く |
| 課題リマインダー通知 | 期限2日前の課題を1日1回ブラウザ通知(利用不可) |

---

## Q（クォーター）判定基準

金沢大学 令和8(2026)年度学年暦に基づく自動判定。

| クォーター | 期間 |
|-----------|------|
| Q1 | 4/6 〜 6/10 |
| Q2 | 6/11 〜 8/1 |
| Q3 | 10/1 〜 12/8 |
| Q4 | 12/9 〜 2/20 |

---

## 称号一覧 / Achievements

| 称号 | 解除条件 |
|------|---------|
| 皆勤 | 全授業の出席率100% |
| 10連続出席 | 欠席なしの授業記録が10回以上 |
| 授業マスター | 10科目以上登録 |
| S評価ハンター | S評価を3つ以上取得 |
| GPA帝王 | GPA 3.5以上 |
| 課題完遂 | 課題を5件以上完了 |
| テスト戦士 | テストを3件以上登録 |
| 夜型 | ダークモードをオンにする |
| 通知マスター | 課題リマインダー通知をオンにする(利用不可) |

---

## データについて / About Data

- すべてのデータはブラウザの `localStorage` に保存
- 外部サーバーへの送信は一切なし
- ブラウザのデータを消去するとデータが失われます。定期的にCSVでバックアップを

All data is stored locally in `localStorage`. No data is sent to any external server.

---

## 動作環境 / Requirements

- モダンブラウザ（Chrome / Safari / Firefox / Brave）
- インターネット接続（Google Fonts の読み込みに必要）

---

## クレジット / Credits

- フォント: [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) / [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) (Google Fonts)
- ブランドカラー: 金沢大学スクールカラー「茄子紺」をモチーフに

---

*Plum. — Made for KU students*
