# 練習

nginx のコンテナを立てて、最低限の html を表示する。

```
docker run -v $(pwd):/usr/share/nginx/html   -p 8080:80 nginx
```

```
open http://localhost:8080/
```
