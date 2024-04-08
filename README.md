# git-playground

## 配置訊息
```bash
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```
## 沒有抓取過的專案用clone
```bash
git clone ${project_name}.git
```
## 抓過的專案要更新用fetch或pull
```bash
git fetch
# git pull = git fatch + git merge
git pull
```
## 利用Pull requests協作步驟
請參考[與其它開發者的互動 - 使用 Pull Request（PR）](https://gitbook.tw/chapters/github/pull-request)
1. fork 一份專案到自己的github
2. 在自己專案上進行修改，並push到自己的分叉上
3. 建立pull request並敘述修改內容
4. 等待管理者合併<BR><BR>

