Запуск:
1) npm install
2) gulp

в package.json в dependencies добавлено:
  "fullpage.js": "^2.9.6"
  
скрипт fullpage.js подключен в foundation.js (gulp/path/js.foundation.js)
стили fullpage.сss подключен в foundation.css (gulp/path/css.foundation.js)

также в foundation.js (gulp/path/js.foundation.js) подключается scrolloverflow.min.js, обязательно перед fullpage.js. Сам скрипт scrolloverflow.min.js находится в /source
