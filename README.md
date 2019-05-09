# SERVER

## Primero crear una base de datos llamada ng_games_db

`mysql -u root -p` </br>
`CREATE DATABASE ng_games_db;`</br>
`ctrl + D`

## Importar estructura de la base de datos

`mysql -u root -p ng_games_db < database/database.sql`

## Modificar server/src/keys.ts con la contraseña correcta

`cd server`</br>
`nano src/keys.ts `

## Instalar dependencias

`npm i package.json`

## Compilar

`tsc`

## Iniciar Servidor 

`nodejs build/index.js`
