# Сборка содержит:

- Обработка PUG
- Обработка SCSS
- Обработка JS

# Установить зависимости:

npm install

# Запускает режим разработки на http://localhost:8080/

npm run dev

# Собрать итоговую сборку в папку dist/

npm run build

```

## Структура:

- `build/` - конфигурация Webpack
- `dist/` - итоговая сборка проекта
- `src/` - папка с файлами
- `src/components/` - компоненты проекта
- `src/fonts/` - шрифты
- `src/img/` - изображения
- `src/pages/` - основные страницы и стили проекта
- `src/static/` - дополнительные файлы проекта
- `src/index.js` - точка входа для Webpack
- `src/style.scss` - финальный файл со стилями

## Зависимости:

```

"devDependencies": {
"@babel/core": "^7.10.5",
"@babel/preset-env": "^7.10.4",
"autoprefixer": "^9.8.5",
"babel-loader": "^8.1.0",
"copy-webpack-plugin": "^5.1.1",
"css-loader": "^3.6.0",
"css-mqpacker": "^7.0.0",
"cssnano": "^4.1.10",
"file-loader": "^4.3.0",
"html-webpack-plugin": "^3.2.0",
"mini-css-extract-plugin": "^0.8.2",
"node-sass": "^4.14.1",
"postcss-loader": "^3.0.0",
"pug": "^2.0.4",
"pug-loader": "^2.4.0",
"pug-plain-loader": "^1.0.0",
"sass-loader": "^8.0.2",
"style-loader": "^1.2.1",
"vue-loader": "^15.9.3",
"vue-style-loader": "^4.1.2",
"vue-template-compiler": "^2.6.11",
"webpack": "^4.44.1",
"webpack-cli": "^3.3.12",
"webpack-dev-server": "^3.11.0",
"webpack-merge": "^4.2.2"
}

```

```
