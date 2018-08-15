---
isChild: true
anchor:  windows_setup
---

## Настройка Windows {#windows_setup_title}

Вы можете скачать двоичные файлы из [windows.php.net/download][php-downloads]. После извлечения PHP рекомендуется установить [PATH][windows-path] в корневой каталога вашего PHP (где находится php.exe), чтобы вы могли выполнять PHP из любого места.

Для обучения и локальной разработки вы можете использовать встроенный веб-сервер с PHP 5.4+, поэтому вам не нужно ничего делать для его настройки. Если вы хотите использовать решения «всё в одном», включающие полномасштабный веб-сервер и MySQL, тогда такие инструменты, как [уставновщик веб-платформы][wpi], [XAMPP][xampp], [EasyPHP][easyphp], [OpenServer][openserver] и [WAMP][wamp], помогут быстро создать и использовать среду разработки под Windows. Тем не менее, использование такой среды будет немного отличаться от продакшена, поэтому будьте внимательны с различиями в окружении, если разрабатываете на Windows, а деплоите на Linux.

Если вам нужно запустить свою продакшен-систему в Windows, то IIS7 даст вам самую стабильную и лучшую производительность. Вы можете использовать [phpmanager][phpmanager] (плагин GUI для IIS7), чтобы упростить настройку и управление PHP. IIS7 поставляется со встроенным FastCGI и готовым к работе, вам просто нужно настроить PHP как обработчик. Для поддержки и получения дополнительных ресурсов посетите [специальный сайт на iis.net][php-iis] для PHP.

Как правило, запуск приложения в разных окружениях при разработке и продакшене может привести к появлению странных ошибок, которые будут всплывать при эксплуатации. Если вы разрабатываете под Windows и деплоите на Linux (или на что-то другое, кроме Windows), вам следует подумать об использовании [виртуальной машины](/#virtualization_title).

У Криса Танкерсли (Chris Tankersley) есть очень полезный пост в блоге о том, какие инструменты он использует для [разработки PHP под Windows][windows-tools].

[easyphp]: http://www.easyphp.org/
[phpmanager]: http://phpmanager.codeplex.com/
[openserver]: http://open-server.ru/
[wamp]: http://www.wampserver.com/en/
[php-downloads]: http://windows.php.net/download/
[php-iis]: http://php.iis.net/
[windows-path]: http://www.windows-commandline.com/set-path-command-line/
[windows-tools]: http://ctankersley.com/2016/11/13/developing-on-windows-2016/
[wpi]: https://www.microsoft.com/web/downloads/platform.aspx
[xampp]: http://www.apachefriends.org/en/xampp.html
