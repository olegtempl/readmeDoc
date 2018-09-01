<a name="cli_комманды"></a>

### Как подключить с помощью CLI

В своих проектах где присутствует таск раннер [GULP]() я использую следующее API.
При вводе в консоль:

```bash
## Команды для запуска проекта:


 * `npm run build`       **->**  Вызовет команду: `gulp build` - запуск проекта в режиме сборки для     деплоймент версии
 * `npm run dev`         **->**  Вызовет команду: `gulp` - запуск проекта в режиме разработки
 * `npm run server`      **->**  Вызовет команду: `gulp server`- запуск сервера в директории проекта,   директория будет доступна по ссылке другим людям
 * `npm run valid:all`   **->**  Вызовет команду: `gulp validation` - запуск валидации для всех         типов  - файлов
 * `npm run valid:html`  **->**  Вызовет команду: `gulp validation:html` - запуск валидации только      для  - ** *.html** файлов
 * `npm run valid:js`    **->**  Вызовет команду: `gulp validation:js` - запуск валидации только для    ** *.js** файлов
 * `npm run doc:all`     **->**  Вызовет команду: `gulp documentation` - запуск всех генераторов  -     документации ( сборка файла readme, jsDoc, LMG и т.д)
 * `npm run doc:js`      **->**  Вызовет команду: `gulp documentation:jsDoc`- запуск генератора  -      документации ** [jsDoc]() **
 * `npm run doc:l`       **->**  Вызовет команду: `gulp documentation:license` - запуск генератора      лицензий ** [LMG]() **
 * `npm run doc:b`       **->**  Вызовет команду: `gulp documentation:bundleReadme` - запуск            генератора  - README ** [README bundler]() **
 * `npm run test:j`      **->**  Вызовет команду: `gulp test:jasmine` - запуск тестов на фреймоворке    jasmine]
 * `npm run test:m`      **->**  Вызовет команду: `gulp test:mocha` - запуск тестов на фреймоворке      mocha
 * `npm run test:u`      **->**  Вызовет команду: `gulp test:unit`- запуск юнит тестов
 * `npm run test:e`      **->**  Вызовет команду: `gulp test:e2e` - запуск e2e тестов
 * `npm run js`          **->**  Вызовет команду: `rollup -c configs/rollup.config.js -w -m` -          запуск  - сборки с помощью rollup  и переводом  с помощью babel в es3 синтаксис.
  ```
 **[⬆ к оглавлению](#Оглавление)**