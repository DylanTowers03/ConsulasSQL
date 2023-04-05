# ConsulasSQL
BD Tienda con las consultas pedidas por el profesor Jaider
---

### Consulta con el join 
```` sql
select clientes.nombre, ventas.clientes_id, ventas.total
from clientes
inner join ventas on (clientes_id=clientes.id);
````
![Consulta sql](Images/consultaJoin.PNG)

---
### Consulta con el where
```` sql
select *
from clientes,ventas
where (clientes_id=clientes.id);
````
![Consulta sql#2](Images/cunsultaWhere.PNG)