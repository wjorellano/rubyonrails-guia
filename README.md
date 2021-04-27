# Guia de Ruby on rails 

- Instalación
  - [Windows10](so/windows.md)
  - [Ubuntu](so/ubuntu.md)

### Comandos basicos

generar proyecto en ruby on rails
```
rails new nombre-de-la-app
```
otras opciones de generar un proyecto
```
rails new nombre de la app --database=db-que-quieran-implementar
```
crear base datos
```
rails db:create
```
iniciar el servidor
```
rails server
```
consola de rails
```
rails console
```
generar una API
```
rails new --api nombre-de-la-api
```
cambiar de base de datos
```
rails db:system:change --to=postresql
```
ejecutar migraciones
```
rails db:migrate
```
rollback a las migraciones
```
rails db:rollback o rails db:migrate STEP=numero-de-migraciones
```
