## step1:
- tao thu muc backup
```
mkdir /root/backup
```
- cap quyen cho thu muc nay
```
chmod +x autobackupmysql.sh
```
- run *autobackupmysql.sh* de test
## step2: tao crontab
- crontab -e
```
10 10 * * * /root/backup/autobackupmysql.sh
```
