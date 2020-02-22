# Micorservices

 - созданы Dockerfile в папках post-py, comment, ui
 - скачен последний образ mongo с dockerhub
 - созданы контейнеры korbind/post:1.0, korbind/comment:1.0, korbind:1.0
 - создана сеть reddit
 - запущены контейнеры с mongo, korbind/post:1.0, korbind/comment:1.0, korbind:1.0
 - проверена работа приложения
 - собран образ с новым содержимым Dockerfile в папаке ui для уменьшения размера
 - собран образ на базе alpine для ui и comment (файлы Dockerfile.1)
 - запущены новые версии контейнеров на базе alpine, проверен работа приложения
 - создан volume reddit_db
 - перезапущены контейнеры с использоанием volume reddit_rb, проверена работа приложения
 
 
 
