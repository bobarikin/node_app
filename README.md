### APP
---------------

## Алгоритм действий
- 1. Постановка задачи
- 2. Создание архитектуры
- 3. Перейти в терминале в папку server
- 4. Инициализируем сервер
```npm init -y```
- 5. Устанавливаем express
```npm install express```
- 6. создаём gitignore и помещаем туда node_modules
- 7. Переход на ES6 modules ("type": "module")
- 8. Создаём структуру сервера
- 9. Запускаем ноду
```node app.js```

-----------------
## Helper (не обязательно)
- 1. Устанавливаем nodemon
```npm i -D nodemon```
- 2. Редактируем script в package.json
```
"scripts": {
    "dev": "nodemon app.js"
  },
```
- 3. Запускаем через nodemon
```npm run dev```
