# linux-image-5.2.11_X86_64_zstd_versia_12_griggorii_config
linux-image-5.2.11_X86_64_zstd_versia_12_griggorii_config

Внимание ядро ломает систему в плане загрузки так что почему надо еще разбираться в последствии придется переключаться по tty

и загружается после тыканий f5 f6 f7 f8 и далее методом перебора повторить пока не загрузится на f7 , но что странное это начинает происходить даже на соседних ядрах , но есть стабильное ядро которое не ломает v11 тут https://github.com/Griggorii/linux-image-5.2.11_X86_64_zstd_versia_9_10_griggorii_config/blob/master/README.md

Ядро маленького размера ваифай возможно придется включить аппаратной кнопкой  в окружении cinnamon на ноутбуке если при нажатии он не захочет ставить галочку скачать ядро deb пакетами полностью с headers и dev https://drive.google.com/open?id=1GfTKFqqgJSR4FWS_eniia8o-GGYvMsNb

Ядро после установки возможно не сразу загрузится и побегут цифры до 100 и следующей перезагрузкой уже будет точно работать.

Сразу предупреждаю zram не работает ядро может оказаться не стабильным так как модуль не вкомпилен oss , alsa , wire audio , sandbox и всякие другие модули , но есть конфиг который я назвал больше модулей и всё такое по нему запускаем компиляцию make -j16 bindeb-pkg и жмём все время enter получаем ядро в котором есть вся эта поддержка. Просто многие думают что ядро это груб и нифига в нём трудного нет и ошибаются получая что то не рабочим из устройств или программ по этому сразу отсеиваем таких персоонажей и смотрим что работает и нет.

Адрес для помощи над разработками яндекс кошелек https://money.yandex.ru/to/410014999913799
