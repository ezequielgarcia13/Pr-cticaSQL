# PrácticaSQL

#### 1. Crear las siguientes tablas sin PKs y FKs en el siguiente orden:

A. Cliente:
- IDCliente: int.
- RazonSocial: varchar (50).
- Domicilio: varchar (50).
- Mail: varchar (50). Admite nulos.
- Rubro: int. Admite nulos.
- CantEmpleados: int.

B. Rubro:
- IDRubro: int.
- Descripcion: varchar (50).

c. ClienteSucursal:
- IDClienteSucursal: int.
- CantSucursalesCapital: int.
- CantSucursalesInterior: int.

#### 2. Actualizar las tablas de la consigna anterior, agregando las siguientes PKs y FKs en el orden adecuado:

A. Cliente: En dos instrucciones.
- PK: IDCliente.
- FK: Rubro. Hace referencia a IDRubro en la tabla Rubro.

B. Rubro:
- PK: IDRubro.
