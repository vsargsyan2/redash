# Файлы для установки Redash на локальный компьтер (Windows) с помощью Docker Compose.

Подразумевается, что у вас уже установлен и запущен Docker Desktop. Если это не так, сначала [скачайте и установите его](https://www.docker.com/products/docker-desktop).

Для загрузки всех необходимых файлов нажмите на кнопку "Clone or download" и выберите в открывшемся меню пункт "Download ZIP".

После загрузки архива распакуйте его, перейдите в папку `redash-stepik-course/redash` и запустите start_redash.bat

Если не сработает, можно попробовать открыть в папке `redash-stepik-course/redash` командную строку и напечатать

```
docker-compose up
```

После этого Redash будет доступен в браузере по адресу http://localhost:5000/.
