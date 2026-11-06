# 政治經濟學教學網站

使用 Quarto 建立的繁體中文政治經濟學公開教材。起始單元：Adam Smith、Karl Marx、兩者理論比較及原典文獻庫。

## 本地預覽
安裝 Quarto 後，在本資料夾執行：
```sh
quarto preview
```

## GitHub Pages 發布
每次推送 main 分支時，GitHub Actions 會建置網站並推送到 gh-pages 分支。

若首次部署失敗，請到 GitHub Settings → Actions → General 設定 Workflow permissions 為 Read and write permissions。
之後至 Settings → Pages，把 Build and deployment Source 設為 Deploy from a branch，選 gh-pages / (root)。

預計網址：https://cmt421-alt.github.io/political-economy/

## 教材維護
編輯 .qmd 頁面；新增學術引用於 references.bib。更新資料時註明原始來源、年份與查核日期。

網站發布分支已初始化；後續由 GitHub Actions 自動建置與更新。
