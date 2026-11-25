# Как просто сгенерировать конфиг Cloudflare WARP
Не стоит выполнять скрипты локально, так как РКН заблокировал запросы для получения конфигурации. Вместо этого лучше запускать их на удалённых серверах. Ниже приведен подходящий сервис, который предоставляет бесплатный временный сервер.

### GitHub Codespaces
1. Перейдите по ссылке: https://github.com/marktorin/WarpGenerator/codespaces
2. Войдите в GitHub.
3. Нажмите **`Create codespace on main`**
4. Дождитесь, пока среда загрузится. Это может занять 10-30 секунд.
5. Если внизу экрана не появился терминал, нажмите в верхнем меню Терминал -> Создать терминал. Затем вставьте в терминал команду (Shift + Insert):
```bash
bash warp_generator.sh
```
6. После того как конфиг сгенерируется, он будет сохранён в `warp.conf`. В левом меню с файлами нажмите правой кнопкой мыши на `warp.conf` и выберите "Скачивание".
Также вы можете скопировать конфиг из терминала и вставить его в новый текстовый файл. Либо, чтобы скачать его файлом, выделите ссылку и нажмите Ctrl + Shift + C, затем вставьте её в адресную строку браузера. Импортируйте файл в [AmneziaWG](https://github.com/amnezia-vpn/amneziawg-windows-client/releases) или [AmneziaVPN ПК](https://github.com/amnezia-vpn/amnezia-client/releases/download/4.8.9.2/AmneziaVPN_4.8.9.2_windows_x64.exe) / [AmneziaVPN Смартфон](https://github.com/amnezia-vpn/amnezia-client/releases/download/4.8.9.2/AmneziaVPN_4.8.9.2_android8+_arm64-v8a.apk).

