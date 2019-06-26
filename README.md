# Jsonserver 的一个例子

## Project setup mini20190626

```
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/wangbinwww/JsonServer.git
git push -u origin master

git status
```

### 启动程序

```
json-server --watch db.json
启动1
json-server --watch db.json --port 27303 --host 0.0.0.0
启动2
json-server main.js
启动3
node server.js
```

### 安装

```
sudo npm install -g json-server
启动3使用
npm install json-server --save-dev
```

### 深化

```
npm install json-server --save-dev
```

### 技巧

```
按s后存储当前json
  Saved snapshot to db-1561216385121.json

```
