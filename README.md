# Test project
Test project for study

#Порядок действий:
- установить webstorm
- установить git и nodejs
- создать в github репозиторий
- открыть webstorm и клонировать репозиторий
- создать файл .gitignore и добавить туда .idea
- создать файл package.json >`npm init` и добавить его в git
- сделать комит

#Установка библиотек
- установка библиотек, например jquery >`npm install --save jquery`
- добавить появившуюся папку node_modules в .gitignore

#Webpack
- установка webpack >`npm i webpack --save-dev`
- использование webpack > `node_modules\.bin\webpack ./src/index.js ./public/bundle.js`
- настройка webpack: создание webpack.config.js в корне проекта и добавление его в git
- в package.json в scripts можно прописать `"build": "node_modules\\.bin\\webpack"` и вызывать в консоли >`npm run build`

#ESLint
- создать в корне файл .eslintrc и добавить его в git
- установить eslint >`npm i eslint --save-dev`
- проверка кода >`node_modules\.bin\eslint ./src`
- в настройках webstorm можно включить ESLint, указав ему пути и IDE будет автоматически проверять и подсвечивать ошибки