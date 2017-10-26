## 第一步：启动monogoDb
### 启动方式：
```
$ '/c/Program Files/MongoDB/Server/3.4/bin/mongod.exe' --dbpath=/c/data
```

## 第二步： 开启服务端server
### 启动方式： 
```
npm start
```
## 第三步，开启客户端
### 启动方式：
```
npm run dev
```

最后需要注意将静态文件shop static导入数据库，用软件MongoBooster导入dumall-goods.json和dumall-users.json
