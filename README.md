# Blog server

step1 預設環境:
db  mysql (port 3306) - 須先建立資料庫,並命名為：blog (有migration,無需建置資料表)
docker    - 若未安裝,請先預先下載 https://docs.docker.com/engine/install/ubuntu/

step2
下載專案後,於config/database.yml 修改db參數
 -> config/database.yml -> host, username, password

step3
於專案內,使用docker-compose up 即可啟動server
