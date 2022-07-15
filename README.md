# Piloto

## Requerimientos
| Aplicación | Version    |
| ---------- | ---------- |
| Composer   | X          |
## Generar .env
#### ejecutar las siguientes lineas en la shell
Copia el el archivo de ejemplo de .env
`cp .env.example .env`
Genera nueva llave
`php artisan key:generate`
-------------------------------------------------------------------------------------------------
##### Uso de variables de Ambiente
 ------------------------------------------------------------------------------------------------
| Variable      | Descripción                                       | Ejemplo                   |
| ------------- |-------------------------------------------------- | ------------------------- | 
| IP_PERMITIDAS | IPs separadas por comas para acceder al monitoreo | "192.168.0.2,192.168.0.3" | 
                                                            

