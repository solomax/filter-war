# filter-war
### quick start project illustrating issue with web resources filtering

to test
1. `mvn clean package`
2. `ls -la src/main/webapp/public/ target/filter-war-1.0-SNAPSHOT/public/`

Output:
```
src/main/webapp/public/:
total 72
drwxr-xr-x 4 solomax solomax  4096 May 20 18:16 .
drwxr-xr-x 4 solomax solomax  4096 May 20 18:16 ..
-rw-r--r-- 1 solomax solomax  4597 May  1 10:48 chat_message.mp3
drwxr-xr-x 3 solomax solomax  4096 May 20 18:16 cliparts
-rw-r--r-- 1 solomax solomax  8266 May 20 13:50 config.xml
-rw-r--r-- 1 solomax solomax  5361 May 20 13:50 config.xsd
-rw-r--r-- 1 solomax solomax 11294 May  1 10:48 favicon.ico
drwxr-xr-x 3 solomax solomax  4096 May 20 18:16 themes
-rw-r--r-- 1 solomax solomax 10449 May 20 13:50 theme.xml
-rw-r--r-- 1 solomax solomax  1777 May 20 13:50 theme.xsd

target/filter-war-1.0-SNAPSHOT/public/:
total 80
drwxr-xr-x 4 solomax solomax  4096 May 20 18:22 .
drwxr-xr-x 5 solomax solomax  4096 May 20 18:22 ..
-rw-r--r-- 1 solomax solomax  8793 May 20 18:22 chat_message.mp3
drwxr-xr-x 3 solomax solomax  4096 May 20 18:22 cliparts
-rw-r--r-- 1 solomax solomax  8266 May 20 18:22 config.xml
-rw-r--r-- 1 solomax solomax  5361 May 20 18:22 config.xsd
-rw-r--r-- 1 solomax solomax 14276 May 20 18:22 favicon.ico
drwxr-xr-x 3 solomax solomax  4096 May 20 18:22 themes
-rw-r--r-- 1 solomax solomax 10449 May 20 18:22 theme.xml
-rw-r--r-- 1 solomax solomax  1777 May 20 18:22 theme.xsd
```

NOTE the size difference
