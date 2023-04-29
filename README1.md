
### Как запустить: 
#### создание образа, в кавычках ваше имя образа
    docker build -t "dockerfile" . 

#### запуск образа где dockerfile ваше имя образа
    docker run -p 80:80 dockerfile
