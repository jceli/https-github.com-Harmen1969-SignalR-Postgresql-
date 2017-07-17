# SignalR-Postgresql
Real time push notification using SignalR  and PostgreSQL

An implementation of real time notification using SignalR and the PostgreSQL listen/notify feature.

When changes (insert/delete/update) are made in a PostgreSQL database table, the changed content is pushed to the webpage.

# Npgsql
The Npgsql NET data provider for PostgreSQL is not included in this repo.
Execute <b>Install-Package Npgsql</b> in the Package Manager Console.
