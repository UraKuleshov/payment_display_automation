Скрипт, который позволяет автоматизировать отображение платежей в складском сервисе "МойСклад". Ежедневно на баланс компании может
приходить больше 80 платежей. Чтобы разнести в ручную такое количество платежей потребуется не мало времени, поэтому было решено
автоматизировать этот процесс. 

Взаимодействие с API МойСклад осуществляется по протоколу Basic Auth, вместе с запросом 
передается заголовок Authorization со значением пары логин:пароль, закодированным в RFC2045-MIME стандарта Base64.

Взаимодействие с API Приорбанк осуществляется по протоколу OAuth 2.0, который позволяет выдать приложению определнные 
права на доступ к ресурсам пользователя.

