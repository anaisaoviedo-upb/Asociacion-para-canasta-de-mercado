# Asociacion-para-canasta-de-mercado

Con el objetivo de definir productos que tiene una venta asociada, para establecer promociones, se realizan unas reglas de asociación.
* Datos: En el dataframe, cada fila es una factura y los productos están en forma de columnas. La base de datos debe ser binaria, indicando con 1 los productos que se vendieron en cada factura.
* Creación de modelos: se utiliza apriori para crear las reglas de asociación
* Evaluación: se calcula soporte y confianza de las reglas
* Interpretación: se buscan las reglas con mayor confianza.
