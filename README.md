# Teams（分工 + Git + Onshape）

## 1. 分工建議

* **設計者**：負責繪製主要零件，定義尺寸。
* **報告負責者**：整理設計紀錄與說明。
* **整合者**：把零件組裝起來。

## 2. Git 操作（簡單流程）

1. **Clone**：先下載專案 → `git clone`
2. **建立分支**：每人開一個分支 → `git checkout -b 分支名`
3. **修改與提交**：修改完 → `git add .` + `git commit -m "訊息"`
4. **推送**：上傳到遠端 → `git push origin 分支名`
5. **合併**：整合者用 Pull Request 合併到 main。
