# pugstarter
Комплект файлов для автоматической компиляции .pug шаблонов в html файлы.

Для начала работы необходимо иметь установленный Node.js (с его npm-менеджером) - https://nodejs.org/en/
После установки Node.js через командную строку необходимо глобально установить Gulp-менеджер командой <br>
<b>npm i gulp -g</b>

После этого можно работать со стартовым пакетом для обработки Pug-файлов, который включает в себя настроенный gulp-менеджер для компиляции pug в html. Обратите внимание, что компилироваться будут все файлы из папки <b>app/pug</b> в <b>app/html</b>, включая вложенные директории, кроме папки <b>app/pug/includes</b> (предназначена для базовых шаблонов и общих блоков страниц).

Для запуска автокомпиляции в папке проекта необходимо открыть командную строку и прописать команду:<br>
<b>gulp watch</b>

После этого gulp-менеджер будет автоматически отслеживать изменения в pug файлах и компилировать их в html. Командная строка должна оставаться открытой. Более того, в случае ошибок в коде, комплияция не произойдет, а вместо нее в командную строку выведется информация об ошибках.
