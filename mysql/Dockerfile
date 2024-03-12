# Usa l'immagine MySQL ufficiale
FROM mysql:latest

# Imposta le variabili di ambiente per la password di root
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=jeecorso
ENV MYSQL_USER=root
ENV MYSQL_PASSWORD=root

# Esponi la porta su cui MySQL eseguirà le connessioni
EXPOSE 3306

# Opzionalmente, puoi montare un file di configurazione personalizzato
# COPY ./my-custom.cnf /etc/mysql/conf.d/

# Opzionalmente, puoi inizializzare il database con uno script SQL
# COPY ./init.sql /docker-entrypoint-initdb.d/
