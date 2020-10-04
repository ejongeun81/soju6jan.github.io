# php #

php 모듈은 nginx 플러그인 설치시 같이 설치됩니다.

기본적인 모듈은 같이 설치되어 있으면 [phpinfo.php](/www/phpinfo.php)에서 확인 가능합니다.

추가로 필요한 모듈은 ssh에서 ```apk add 모듈명``` 으로 설치할 수 있습니다.

-----

# 프로그램

## myComix ##

URL : [/www/myComix/index.php](/www/myComix/index.php)

참고 : [마이코믹스 만화뷰어 0.17 업데이트](https://sjva.me/bbs/board.php?bo_table=tip&wr_id=1916)

imurRoid 님이 만드신 최고의 만화뷰어입니다.


### 설치방법 ###
ssh 혹은 command /bin/sh 실행 후 아래 명령 입력
```
cd /app/data/nginx/www
git clone https://github.com/imueRoid/myComix
chmod 777 -R /app/data/nginx/www
```
[설치](/nginx/install?cmd=cd /app/data/nginx/www|git clone https://github.com/imueRoid/myComix|chmod 777 -R /app/data/nginx/www)



