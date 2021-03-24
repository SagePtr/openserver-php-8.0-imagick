# PHP-8.0-imagick for OpenServer

## Инструкция по установке (English version below)
1. Распаковать содержимое папки `PHP_8.0` в папку `<OpenServer>\modules\php\PHP_8.0\`.
2. Нажать на иконку OpenServer в трее правой кнопкой мыши и выбрать: `Дополнительно -> Конфигурация -> PHP_8.0`.
3. Найти в файле конфигурации блок `Extensions`, добавить туда следующую строку:
`extension  = imagick`
4. Сохранить файл конфигурации, перезапустить OpenServer.

## Installation
1. Unpack content of `PHP_8.0` directory into the  `<OpenServer>\modules\php\PHP_8.0\` directory.
2. Right-click the OpenServer icon in the system tray and click: `Advanced -> Configuration -> PHP_8.0`
3. Find the `Extensions` block and add the line below:
`extension  = imagick`
4. Save configuration and restart OpenServer.

Thank you this guy: https://jite.eu/2021/2/21/imagick-on-php8/ for a good manual how-to build PHP+Imagick easy.
