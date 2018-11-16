# phpmyadmin

phpmyadminをdockerで動かす  
データベースに直接アクセスできる環境に限ります。  

## 設定は編集が必要
config.user.inc.phpは自分で埋めてください。  

## 使用方法
コンテナの開始  
`docker-compose up -d`  

コンテナの停止  
`docker-compose stop`  

## URL
Win：http://192.168.99.100:9090  
Mac：http://localhost:9090  
