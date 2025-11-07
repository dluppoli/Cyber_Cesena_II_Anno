Realizzare regole snort che lanciano un alert nel caso in cui:
- Ci sia un collegamento ad un url che contiene la parola "login"
- Ci sia la stringa "password" all'interno del body di una richiesta in POST (ovviamente in chiaro)
- Ci sia un tentativo di conessione ssh verso il server 10.2.2.9 
- Ci sia un tentativo di SQL Injection tramite inserimento del carattere '
