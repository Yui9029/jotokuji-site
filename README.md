# 浄徳寺公式サイト

このリポジトリを GitHub Pages で公開するために、以下のファイル・フォルダが必要です。
```
/jotokuji-site
├ index.html
├ README.md
├ .gitignore
├ images/
│   ├ hero.jpg
│   ├ photo1.jpg
│   ├ photo2.jpg
│   ├ photo3.jpg
│   └ photo4.jpg
```

## デプロイ手順
1. GitHub にサインアップ or サインイン  
2. 新規リポジトリ作成（例: `jotokuji-site`）を Public で作成  
3. 本フォルダの内容を `main` ブランチにプッシュ  
   ```bash
   git init
   git add .
   git commit -m "初回公開"
   git branch -M main
   git remote add origin https://github.com/ユーザー名/jotokuji-site.git
   git push -u origin main
   ```  
4. GitHub → リポジトリ → Settings → Pages → Branch: `main` → Save  
5. 数分後、`https://ユーザー名.github.io/jotokuji-site/` で公開

## .gitignore
```
# OS
.DS_Store
Thumbs.db

# IDE
.vscode/
```
