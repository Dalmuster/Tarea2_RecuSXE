# Tarea2_RecuSXE

## Apartado 1

Como mencionamos en clase, aunque no es recomendable, en ocasiones puede ser
necesario crear tablas ajenas a Odoo dentro de su base de datos (integración con
sistemas externos, almacenamiento de históricos, datos temporales…). Mediante la
herramienta PgAdmin u otro método que estimes oportuno, elabora y ejecuta una
sentencia que cree una tabla llamada “Pokemons“ con los siguientes campos:

● idPokemon: autonumérico. Este campo será la clave primaria.

● nombre: Texto con tamaño máximo de 40 caracteres.

● capturado: Booleano.

● tipoPokemon: Texto con tamaño máximo de 120 caracteres.

● numeroPokemon: Numérico tipo entero..

● fechaCaptura: tipo fecha

Creación de la tabla
![imagen](https://github.com/user-attachments/assets/86868063-f2e1-43a0-a92c-db49181780d6)

## Apartado 2

Inserta 3 registros inventados en la tabla a través de una sentencia SQL.

Inserción de los datos

![imagen](https://github.com/user-attachments/assets/a4f99b24-8f88-43e7-8c8e-cb3e414c4ba3)

## Apartado 3

Realiza una consulta donde se muestren todos los datos de la tabla Pokemons
ordenados por fechaCaptura, de modo que en la primera fila salga el que tenga la
fecha más reciente.

![imagen](https://github.com/user-attachments/assets/ae39b602-c15f-42cb-b0f4-4159e7d86d8b)

## Apartado 4

Realiza una consulta que permita obtener un listado de todos los contactos de
Odoo (no empresas) con la siguiente información:
- Nombre
- Cuya ciudad NO sea Tracy
- Nombre comercial de la empresa
ordenados alfabéticamente por el nombre comercial de la empresa,

![imagen](https://github.com/user-attachments/assets/f9714da5-c649-441a-bda0-c15410156360)

## Apartado 5

Utilizando las tablas de odoo, obtén un listado de clientes a los que se les ha emitido
algún reembolso (facturas rectificativas de cliente)
- Nombre de la empresa
- Número de factura
- Fecha de la factura
- Total factura SIN impuestos
Ordenadas por fecha de factura de modo que la primera sea la más reciente.

![imagen](https://github.com/user-attachments/assets/aa53a2b4-229b-4cdc-bfb6-df923f50e318)

## Apartado 6

Utilizando las tablas de odoo, obtén un listado de empresas proveedoras, que
hayan emitido más de una facturas de compra confirmadas, mostrando los
siguientes datos:
- Nombre de la empresa
- Número de facturas
- Total facturado SIN IMPUESTOS

  ![imagen](https://github.com/user-attachments/assets/1a8e077f-fd06-491a-b7a4-b913d04da6db)

## Apartado 7

Crea una sentencia que actualice el correo de los contactos cuyo dominio es
@bilbao.example.com a @bilbao.euskadi.neus

![imagen](https://github.com/user-attachments/assets/268ed8b3-6111-419f-8963-8ba3312b140a)

## Apartado 8

La empresa Wood Corner ha hecho un ERE y ha despedido a todos los empleados
que tenías como contacto. Crea una sentencia que elimine todos los contactos
pertenecientes a la empresa “Wood Corner”, pero mantén la empresa.

Query

![imagen](https://github.com/user-attachments/assets/94a1b81c-6b10-4474-9b59-b3a14a060100)

Contactos antes del borrado

![imagen](https://github.com/user-attachments/assets/3ad33c7c-ed42-4c25-9a42-2df1ad44d78d)

Contactos despues del borrado

![imagen](https://github.com/user-attachments/assets/3309c680-5ce8-4e1b-8060-28075c35ffb3)

