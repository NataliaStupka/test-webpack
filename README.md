# test-webpack

1.вводим в консоли npm init -y; 2.npm install webpack webpack-cli --save-dev; 3.создаем index.html и
index.js; 4.скрипт в html не подключаем, webpack как и parcel будет автоматически добавлять ссылку;
5.в корне проекта создаем файл webpack.config.js (в этом файле в виде обьекта будем описывать его
настройки, после из этого файла их экспортируем); 6.в packege.json создаем скрипт "build":
"webpack"(по умолчанию он идет в корень проекта находит находит конфигурации для себя и выплняет
их);...; npm install webpack-dev-server --save-dev;
