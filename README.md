![alt text](https://pp.userapi.com/c851036/v851036626/18eb61/eVj7Z4ATJY8.jpg)

# SchoolBot
Лучший помощник для школьников и студентов для ВКонтакте

## Просмотр функционала и не только

Я сделал специальную [страницу](http://sashafromkvartalka.ru/projects/schoolbot), которая поясняет все команды бота, а также демонстрирует работу с ним.

## Установка
Чтобы установить бота, скопируйте репозиторий.
```
$ git clone https://github.com/sashafromlibertalia/SchoolBot.git
```

## Дальнейшая настройка
В папке ```src``` находится файл **```config.js```**. Он нужен для внесения параметров, необходимых для корректной работы бота.
```js
let config = {
    TOKEN: '',  // Сюда вы пишите токен группы, полученный с помощью LongPoll
    poolingGroupID: '', // ID вашей группы, Int
    peerID: 2000000001, // см. документацию ВКонтакте
    homeworkParserURL: '', // Ссылка на файл domashka.txt (Рекомендую хранить его на GitHub в репозитории с ботом)
    className: '', // Ваш класс (или группа)
    schoolName: '', // Название вашего учебного заведение
    adminName: ''. // Ваше имя
    adminNameDat: '', // Ваше имя в дательном падеже (см. код)
    adminDomain: '', // Короткая ссылка вашей страницы
    adminID: '' // Ссылка на вашу страницу, Int
}
```
Как только все параметры будут заполнены, бот будет готов к работе :)

## Команды
Ознакомиться со списком команд можно, написав **```/start```**
