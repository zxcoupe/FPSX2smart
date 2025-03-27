# FPSX2smart

Для кого эта утилита? Пригодится для владельцев смартфонов за 100~200$. С бюджетом ниже позволяет "хоть как-то" играть в 3Д игры. С указанным бюджетом позволит выставлять графику на "ультра" настройки.

Для скептиков записал "пруф" на Unisoc T618+ MALI-G52 (по мнению Gaijin, MALI-G52 считается бомж-GPU, поэтому настроить выше "средних" нельзя):
https://youtu.be/HYZ1hMC9-vQ
https://rutube.ru/video/c6916a0c4f376b2d3332bda095f3dcb6/
https://vkvideo.ru/video3931506_456240585

Новости по версиям тут
https://github.com/zxcoupe/FPSX2smart/blob/main/Versions.txt

Ускоритель FPS на ведрофонах в два раза! (Кроме Poco C40- тут дебильный процессор и оно не работает).
Проверял на Rockchip, MTK, Snapdragon.
В Warthunder на GameMT E6+ (RK3566+Mali G52) и Balmuda Phone FPS увеличивается практически в два раза!
Идеально подходит "еще" выкрутить FPS в PSP эмуляторе PPSSPP.

Как пользоваться?

Смартфон подключить к ПК на Windows через USB. Включить отладку по USB через раздел разработчика.
Как активировать пункт "Отладка по USB" на смартфоне? Для этого заходим в настройки смартфона, внизу списка открываем "Параметры разработчика", включаем режим "Параметры разработчика" и "отладка по USB". Если у вас нет пункта "для разработчика", в настройках зайдите в меню "Об устройстве" --> "Сведения о ПО" и на строке "Номер сборки" быстро тапайте 7 раз, пока не появится надпись "Теперь вы стали разработчиком!".
ВАЖНО! Файлы запускать скопировав их в каталог с ADB. 
ADB КАЧАТЬ ОТДЕЛЬНО! В Архиве ADB есть, работает. Но не ручаюсь за этот ADB. Можно скачать самостоятельно с гугла.
https://developer.android.com/tools/releases/platform-tools?hl=ru

Недостатки:

Если с этого же девайса, в режиме повышения FPS есть необходимость подключкться по RDP к серверам, то будет "пикселястость". Хотя как показала практика, все равно мы "увеличиваем" нужную область в RDP. Утилита же для игр в основном нужна.

Пример "буста" применения утилиты:
На RK3566 в Warthunder
https://www.youtube.com/watch?v=HGW33d4e2sw

Остались вопросы?
Telegram-канал @FPSX2smart

p.s. Год назад задумал написать такую "лентяйку" и вот свершилось чудо. Раньше задавался вопросом- а как на планшете отобразить НОРМАЛЬНО страницу с Zabbix чтоб все поместилось.
Вторая плюшка- смотреть Youtube/Rutube/VK чтоб меньше заикалось. Третья и основная плюшка- ускорение FPS до двух раз в играх. Там где например в Warthunder невозможно было играть, с этой штукой более-менее стало нормально (без нее ~12FPS, с ней ~17-25fps на одном девайсе и ~25 до нее и ~45 при включении на ультра настройках!)

Отдельная благодарность всем участникам ТГ канала t.me/atarist и каналу t.me/electro_kot "ЭлектроКот - ТехноБлог" (Андрею Смирнову, за публикацию в новостях)
