Wapp Service

Este pequeño servicio API es un scheduler que utiliza node-cron para, cada 24 horas, llamar a otra API (propia) que lee un Google Sheat y toma los vencimientos que serán a los 3 días (del dia en cuestion) y mediante la API https://waapi.app/ envía el aviso a esos destinatarios.
Meidante dicha API tambien recibo mensajes y los proceso, en caso de ser necesario.