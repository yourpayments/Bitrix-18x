# «Твои платежи», модуль для CMS Bitrix-18x

![](https://repository-images.githubusercontent.com/638835276/ff494b04-d65b-4843-8759-e85c689a7e80)

[НКО «Твои Платежи»](https://YPMN.ru/ "Платёжная система для сайтов, платформ и приложений") - платёжная система для сайтов, платформ, игр и приложений.

«Твои платежи» для Bitrix 18 v.
Модуль «Твои платежи» для 1C Bitrix начиная с версии 18.х. Для старых версий Bitrix модуль можно взять тут 
https://github.com/yourpayments/Bitrix , 
https://github.com/yourpayments/Bitrix_14.x 
или в маркетплейсе http://marketplace.1c-bitrix.ru/solutions/payu.payment2/.

Данный модуль подходит для версий Малый бизнес, Бизнес и Бизнес Веб-кластер.

#Инструкция по установке модуля оплаты «Твои платежи» под 1C Битрикс

Папку payu нужно разместить в {Корневой каталог сайта}/bitrix/php_interface/include/sale_payment/
Содержимое папки tools нужно скопировать в {Корневой каталог сайта}/bitrix/tools/
#После этого необходимо :
https://prnt.sc/n6c1n4
https://prnt.sc/n6bw0u
Зайти в административную часть интернет магазина.
Перейти на страницу "Платежные системы" ( "Магазин" -> "Настройки магазина" -> "Платежные системы" )
Нажать на кнопку "Добавить платежную систему"
Заполнить общие данные о платежной системе.
Перейти на нужную вкладку ( "Физические лица" или "Юридические лица" ) и заполнить всю необходимую информацию ( Пример заполнения есть на скриншоте )
Сделать платежную систему активной и нажать "Сохранить"

В настройках вашего мерчанта на «Твои платежи» необходимо указать ссылку возврата(IPN) информации о статусе платежа на страницу http://yoursite.com/bitrix/payu_ipn.php
