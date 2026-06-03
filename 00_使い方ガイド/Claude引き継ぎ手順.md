# Claudeを新しいチャットで引き継ぐ手順

## なぜ必要？
Claudeは新しいチャットを開くと記憶がリセットされる（コンテキストウィンドウの限界）。
でもmemoryフォルダに情報を保存＆GitHubにpushしておけば、
新しいチャットでもすぐに「続き」から始められる！

---

## 毎日の流れ

### 【STEP 1】今日の学習・進捗をClaudeに保存させる
```
今日やったことをまとめて6/〇〇の学習ログに保存してGitHubにpushして
```

### 【STEP 2】GitHubにpush（STEP1で一緒にやってもOK）
```
GitHubにpushして
```

### 【STEP 3】新しいチャットを開くとき
新しいチャットの最初にこれを貼る↓

---

## ★新チャット開始時にコピペするプロンプト

```
以下のGitHubのファイルを読んで、私のことを把握してください。

https://github.com/encamp14/AI_test/blob/main/memory/MEMORY.md
https://github.com/encamp14/AI_test/blob/main/memory/user_misaki_profile.md
https://github.com/encamp14/AI_test/blob/main/memory/study_log_20260603.md
※最新の日付のログに変えてね

把握したら「準備OK！何をしようか？」と教えてください。
```

---

## memoryフォルダの中身

| ファイル | 内容 |
|---|---|
| MEMORY.md | 全ファイルの目次（まずこれを渡す） |
| user_misaki_profile.md | 美咲さんのプロフィール・仕事・目標 |
| project_recipe_list.md | okraレシピ133件のチェック状況 |
| study_log_2026060〇.md | 日付ごとの学習ログ |

---

## GitHubのリポジトリ
https://github.com/encamp14/AI_test

memoryフォルダ：
https://github.com/encamp14/AI_test/tree/main/memory
