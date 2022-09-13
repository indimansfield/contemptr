Run database
`docker-compose -f docker-compose.yaml up -d`

Run Migrations - in infrastructure referencing gaspode main project
`cd gaspode/infrastructure && dotnet ef migrations add InitialCreate -s ../gaspode`