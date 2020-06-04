## docker 部署 rap2-delos / rap2-doloes 

修改docker-compose.yml实现文件替换

also see start.sh


## 手动运行
##### ./ -> ./patches
```
cd patches
npm install
npm run build
```

##### ./
```
docker-compose up 
# docker-compose up -d
```

## 通过start.sh运行
##### ./
```
chmod +x ./start.sh
./start.sh -d
```


