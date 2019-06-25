FROM postgres:11-alpine
ENV POSTGRES_USER postgres
ENV POSTGRES_PASSWORD postgres

RUN /etc/init.d/postgresql start &&\
    psql --command "grant pg_monitor to postgres"