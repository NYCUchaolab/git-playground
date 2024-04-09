# git-playground

## 配置訊息
```bash
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```
## 沒有抓取過的專案 - clone
```bash
$ git clone ${project_name}.git
```
## 新增檔案 - add
```bash
$ git add {file_name}
```
## 提交變更 - commit
```bash
$ git commit -m "提交內容"
```

## 抓過的專案要更新 - fetch, pull
```bash
$ git fetch
# git pull = git fatch + git merge
$ git pull
```

## 不想上傳的東西寫在.gitignore
```bash
*.fastq # 例如不要上傳以.fastq檔案
ref/ # 例如不要上傳ref資料夾內的東西
gdc.token # 絕對不要上傳token或密碼(非常重要)
```

## 利用Pull requests協作步驟
請參考[與其它開發者的互動 - 使用 Pull Request（PR）](https://gitbook.tw/chapters/github/pull-request)
1. fork 一份專案到自己的github
2. 在自己專案上進行修改，並push到自己的分叉上
3. 建立pull request並敘述修改內容
4. 等待管理者合併<BR><BR>

