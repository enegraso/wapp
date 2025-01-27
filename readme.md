Wapp Service

Este pequeño servicio API es un scheduler que utiliza node-cron para revizar que cada 24 horas, se llame a otra API (de mi autoria) que lee un Google Sheat y toma los vencimientos que serán a los 3 días (del dia en cuestion) y mediante la API https://waapi.app/ envía el aviso a esos destinatarios.