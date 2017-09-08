# module-wordpress-woocommerce

#### Работа модуля протестирована на WordPress версии 4.3.1 с модулем WooCommerce версии 2.4.7.

Модуль интеграции платформы [WordPress](https://wordpress.org/) с платежной системой [PayBox](http://paybox.kz) для магазина [WooCommerce](http://www.woothemes.com/woocommerce/).

### Инструкция

Для работы модуля необходимо выполнить следующие шаги:

##### 1. Заключить договор с PayBox

Заполнить форму заявки на сайте [PayBox](http://paybox.kz) для получения доступа к личному кабинету PayBox.

##### 2. Установить и настроить модуль модуль

**Важно!** *Следуюшие шаги предполагают, что у вас уже установлен модуль магазина WooCommerce*.

1. Установка модуля. В консоли администратора WordPress выбрать *Плагины &rarr; Добавить новый*, нажать кнопку *Загрузить плагин*, выбрать zip-архив с плагином и нажать на кнопку *Установить*.
После сообщения об успешной установке перейти на страницу *Плагины &rarr; Установленные*, найти в списке **Paybox Payment Gateway** и нажать на кнопку *Активировать*.
2. Настройка. В консоли администратора WordPress выбрать *WooCommerce &rarr; Настройки* и перейти на вкладку *Оплата*. В списке *Платежные шлюзы* найти **Paybox** и перейти к настройкам (кликнуть по ссылке на названии).
На странице настройки модуля ввести **Номер магазина** и **Секретный ключ** &mdash; эти данные берутся из [личного кабинета PayBox](https://www.paybox.kz/admin/merchants.php). Остальные настройки можно оставить по умолчанию.
3. После того, как все настройки будут сохранены, вам будет доступен метод оплаты через систему PayBox.