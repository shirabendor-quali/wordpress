FROM mysql:5.7
COPY docker-entrypoint.sh /usr/local/bin/
ENTRYPOINT [ "docker-entrypoint.sh" ]
CMD ["mysqld"]
ENV MYSQL_DATABASE=demo_db
ENV MYSQL_USER=wordpress
ENV MYSQL_ROOT_PASSWORD=Colony!123
ENV MYSQL_PASSWORD=Colony!123