# GitLab 繁體中文教學站

把 GitLab 從平台概念、第一個專案、Merge Request 協作，到 CI/CD、Pages，以及與 GitHub 的詳細比較，做成**中英對照**的分層教學。

- 目標讀者：初階工程師 / 學生
- 單元數：8 單元（含「GitLab vs GitHub 詳細比較」專章）
- 授權：本站內容 CC-BY-4.0
- 網站：[https://shumingyang-opencode.github.io/gitlab-tech-zh-tw/](https://shumingyang-opencode.github.io/gitlab-tech-zh-tw/)

## 網站結構

```
gitlab-tech-zh-tw/
├── index.html            # 課程總覽 + 入口卡片
├── map.html              # 平台功能地圖
├── learning-path.html    # 學習路線：L0 → L4 分層
├── about.html            # 關於本站
├── docs/                 # 單元教學頁
│   ├── index.html        # 單元一覽
│   ├── unit-01-*.html    # …共 8 篇
├── assets/site.css       # 單一共享樣式
└── .nojekyll
```

## 單元列表

| # | 單元 | 內容 |
|---|------|------|
| 01 | GitLab 是什麼 | GitLab.com vs 自架（CE/EE）、一體化 DevOps |
| 02 | 第一個專案 | Project / Group、clone / push、README |
| 03 | 分支與 Merge Request | branch、MR、衝突處理 |
| 04 | Merge Request 協作 | MR 流程、Approvals、code review、保護分支 |
| 05 | Issues 與專案管理 | Issues、labels、milestones、Boards |
| 06 | GitLab CI/CD | .gitlab-ci.yml、Runners、Pipeline、stages |
| 07 | GitLab Pages | 靜態網站部署 |
| 08 | GitLab vs GitHub | 詳細比較與選型建議 |

## 開發

本站為純靜態 HTML，無建置步驟。`assets/site.css` 為唯一樣式來源，所有頁面引用之。

```sh
python3 -m http.server 8000
```

## 授權

本站教學內容（繁體中文解說）為本站原創，採 CC-BY-4.0；文中技術名詞與操作引用自 GitLab Docs 與 Git 官方文件。

## 相關連結

- 學習路徑建議服務：[learning-path-advisor](https://shuming-yang.github.io/learning-path-advisor/) — 依角色推薦教學網站學習路徑
