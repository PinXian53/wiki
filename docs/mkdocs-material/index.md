# MkDocs & mkdocs-material

## 介紹
`MkDocs` 是一個 用 Python 寫成的靜態網站生成器 (Static Site Generator)，專門用來建立文件網站 (Documentation Website)。它的特色是簡單、快速，而且對 Markdown 支援非常好。

`mkdocs-material` 是 MkDocs 的一個主題，專注於提供 現代化、好看的文件網站，同時支援許多實用功能。它是目前最受歡迎的 MkDocs 主題之一。

## 常用指令
- 安裝 MkDocs 與 Material 主題
    ```shell
    pip3 install mkdocs mkdocs-material
    ```
- 建立新專案
    ```shell
    # 建立一個名為 my-project 的 MkDocs 專案
    mkdocs new my-project
    ```
- 本地預覽 (啟動本地伺服器，支援即時渲染 Markdown)
    ```shell
    mkdocs serve
    ```
    - 預設網址：[http://127.0.0.1:8000](http://127.0.0.1:8000)
- 部署到 GitHub Pages (轉換成 HTML 再推到 gh-pages 分支)
    ```shell
    mkdocs gh-deploy
    ```
    - 部署完成後，可透過 `https://<username>.github.io/<repository>/` 存取網站
