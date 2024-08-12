# Supermercado-Excel
Objetivo 3: cálculos complejos y lógica 
1)	El precio de venta varía en función de ciertos factores. Agregar una columna que se llame “PrecioVentaUnitarioFinal” que cumpla las siguientes condiciones:
a.	Si el vendedor fue un Director, Gerente o CEO, se le hará un descuento del 10%
b.	Si la venta no fue de un Director, Gerente o CEO, y la venta se realizó un domingo, se cobra un recargo de un 20%
c.	Si no, el “PrecioVentaUnitarioFinal” será igual al “PrecioVentaUnitario”
2)	El costo de algunos productos depende de la temporada, por lo que vamos a agregar tres columnas nuevas:
a.	“CostoUnitarioVerano”: si se realizó una venta de los productos A, B, C o D y la venta se realizó durante el verano, entonces se aplica un recargo del 5% sobre el “CostoUnitario”. Sino se mantiene el costo.
b.	“CostoUnitarioInvierno”: si se realizó una venta de los productos E, F, G o H y la venta se realizó durante el invierno, entonces se aplica un recargo del 7% sobre el “CostoUnitario”. Si la venta fue de los productos J o I H y la venta se realizó durante el invierno, entonces se aplica un recargo del 10% sobre el “CostoUnitario”. Sino se mantiene el costo.
c.	Unificar en la columna “CostoUnitarioFinal” las condiciones realizadas en las dos columnas anteriores.
3)	Agregar una columna que sea “ComisionPorcentaje” en la tabla “Ventas” que traiga la comisión correspondiente para el vendedor y mes de la tabla “Comisiones”. (este punto puede ser un poco complicado, posiblemente necesiten anidar dos funciones de búsqueda)

Objetivo 6: Tablas dinámicas 

1)	Calcular mediante tabla dinámicas el monto facturado por cada empleado.
2)	Calcular en una tabla dinámica, para cada cargo, el salario promedio, el salario máximo, el salario mínimo, el valor total de los salarios y cuanto representa el total de los salario de ese cargo frente al total de los salarios.
3)	Calcular el total facturado por cada producto sin contar las ventas del CEO y directores.
4)	Calcular la Utilidad generada por mes y por producto (producto en fila y mes en columnas). Descartando las ventas realizada los fines de semana.
5)	Calcular la comisión generada por Cargo y Vendedor (ambos en nivel fila). Esta tabla tiene que poder filtrarse por un Timeline (filtro de fecha). La tabla tiene que mostrar los totales y subtotales.
