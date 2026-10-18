# LanceSkill

可公開使用的 Codex Skill 工作流集合，來源為使用者層的全域 Skill 設定，已排除私人路徑、系統層規則、外掛快取、機密設定與本機專用執行資源。

## 目前內容

`skills/` 內提供 15 個可公開的 `SKILL.md`：

- 文章與內容：`article-noah`、`humanizer-zh-tw`、`presentation-coach`、`video-spec-builder`
- 研究與工程：`research`、`brainstorming`、`implement`、`tdd`、`diagnosing-bugs`、`code-review`、`qa`
- 設計與介面：`ui-ux-pro-max`、`cola-uiux-game-design`、`draw`
- 專案流程：`project-init`

## 安全邊界

- 這個 repo 不存放個人 Vault 內容、私人筆記、API 金鑰、登入資訊或本機絕對路徑。
- Obsidian 的個人知識保留在本機 Vault；本 repo 只保存可重複使用的工作規則。
- 只有經過人工檢查的 Skill 才能加入公開套件。

## 在 Codex 中使用

將需要的 `skills/<skill-name>/` 複製到本機的使用者 Skill 目錄，再重新啟動 Codex 或重新載入 Skill。不同主機的安裝方式可能不同，請以該主機的 Skill 管理方式為準。

## 更新原則

每次同步都要更新 `manifest.yaml` 的 `synced_at`、來源位置與排除項目，並檢查是否新增私人路徑或機密內容。
