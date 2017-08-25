**Процесс установки.**

1. Клонируем репозиторий
```js
git clone https://github.com/dmgame/template.git
```
2. Перейдите в склонированную папку или откройте е в редакторе кода
```js
cd template
```

3. Разворачивание проекта (установка всех модулей). У вас должен быть установлен nodejs и gulp глобально
```js
 npm up
```
---
**Запуск gulp**

1. Запуск gulp. Запустится таск default
```js
 gulp
```
---
***Установка gulp глобально `(если он не установлен)`***
1. Установите nodejs по ссылке [Nodejs](https://nodejs.org/uk/)

2. Установите gulp глобально
```js
npm i gulp -g
```
---
**Структура папок**
---
**Используемые по модули**

```js
var gulp         = require('gulp'), // Подключаем Gulp
    browserSync  = require('browser-sync'), // Подключаем Browser Sync
    concat       = require('gulp-concat'), // Подключаем gulp-concat (для конкатенации файлов)
    uglify       = require('gulp-uglifyjs'), // Подключаем gulp-uglifyjs (для сжатия JS)
    cssnano      = require('gulp-cssnano'), // Подключаем пакет для минификации CSS
    rename       = require('gulp-rename'), // Подключаем библиотеку для переименования файлов
    imagemin     = require('gulp-imagemin'), // Подключаем библиотеку для работы с изображениями
    pngquant     = require('imagemin-pngquant'), // Подключаем библиотеку для работы с png
    cache        = require('gulp-cache'), // Подключаем библиотеку кеширования
    autoprefixer = require('gulp-autoprefixer'),// Подключаем библиотеку для автоматического добавления префиксов
    spritesmith = require('gulp.spritesmith'), // Подключение библиотеки для создания спрайтов
    merge = require('merge-stream');

```