# 如何 Deploy 一段 Nodejs 程式到 GCE

## 操作步驟

1. 安裝 Nginx
2. 寫好 index.js 的進入點
3. ```npm install express```
4. ```node index.js```
5. 編輯設定檔 ```sudo vim /etc/nginx/sites-enabled/default``` 設定 proxy
6. 重啟 ```sudo nginx -s reload```
7. 設定 DNS 指向該 IP
8. 執行 ```sudo certbot```