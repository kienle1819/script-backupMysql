## step1:
- tao thu muc backup
mkdir /root/backup
- cap quyen cho thu muc nay
 chmod +x autobackupmysql.sh
- chay:#./autobackupmysql.sh de test
## step2: tao crontab
- crontab -e
them:10 10 * * * /root/backup/autobackupmysql.sh
