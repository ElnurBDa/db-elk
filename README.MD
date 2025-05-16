# Why

- in case if you are lazy to write a Dashboard Frontend
- in case if you want the best Visualizations
- in case if you like ELK very much

# How to?
After you setup some backend and PG DB, download a driver for Logstash and compose this up.

```bash
wget https://jdbc.postgresql.org/download/postgresql-42.7.1.jar
docker compose up -d
```

# Suggestion
- Modify the configurations files for your need
- Try to have ordinary data types in the table. Logstash gets freak out when it sees JSON format in the DB.
