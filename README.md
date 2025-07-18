# Тестирование мобильных приложений

Я протестировала мобильное приложение на реальном устройстве Android и подготовила различные виды тестовой документации. Помимо этого в рамках работы с Charles и Proxyman я перехватила и изменила трафик для этого же приложения

[Чек-лист](https://docs.google.com/spreadsheets/d/1xhv7-ysJcsianPBW_yTrd4Or2eHZYR2b2TMsMWgp37M/edit?usp=sharing) на основе требований, без макета  

[Тест-кейсы](https://drive.google.com/file/d/1R0f8Mr1oJVSPKJo5-Emx-5nrC8y-EV7d/view?usp=drive_link), созданные в Qase

[Тестовый прогон](https://drive.google.com/file/d/1qVgrshD6NczHbu6XXpFb531YGDPqJSmM/view?usp=drive_link)

[Отчёты о дефектах](https://docs.google.com/spreadsheets/d/1ejzKna42t7p8i9dBdrLJAXaVpfoIH5ll/edit?usp=drive_link&ouid=116268271765014270767&rtpof=true&sd=true), оформленные через YouTrack 

[Перехват](https://drive.google.com/file/d/1X5ApajBm0mFL2KfJ6ABU20Kp_zDWG9rG/view?usp=drive_link) и [изменение](https://drive.google.com/file/d/1xzXDT_r9bPwMPFiPZoIGf0YMOYaWSbsA/view?usp=drive_link) трафика выполнены на основе заданных условий:отправить запрос на удаление любого из товаров в корзине, но видоизменить его так, чтобы он удалил другой товар, на ресурсе https://demoshopping.ru; смоделировать ситуацию при которой при обращении к https://demoshopping.ru пользователь увидит в браузере любую картинку

[Скриншот](https://drive.google.com/file/d/1eXDJZmBUlKvnljuwGv-wxVLTJyszFkKT/view?usp=drive_link) перехваченного HTTPS-запроса с мобильного устройства. В header user-agent содержится информация о моем устройстве


