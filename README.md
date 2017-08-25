Процесс установки.

1. git clone https://github.com/dmgame/template.git
2. cd template (перейдите в склонированную папку или откройте е в редакторе кода)
3. npm up (установит все модули. У вас должен быть установлен nodejs и gulp глобально)

Запуск gulp

1. выполните комманду gulp

Структура папок


Используемые по модули

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