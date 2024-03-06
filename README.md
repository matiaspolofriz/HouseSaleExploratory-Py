Resumen de mi analisis

1- Importe Pandas

2- Almacene mi base de datos de Excel en una variable

3- Utilice diferentes metodos para observar datos:

      .head --> para visalizar una parte de la tabla
      .shape --> para ver la cantidad de filas y columnas en total
      .mean --> para mostrarme todos los promedios de cada columna
      .describe --> para describir los datos estadisticos principales (cantidad, promedio, desvio estandar, minimo, maximos y quartiles)
      [] --> para unir dos o mas columnas de la tabla

4- Importe diferentes librerias --> matplotlib | seaborn | numpy

5- Analisis de la columna "Precio de ventas" (SalePrice)

      ° Grafica de DISPLOT --> vizualiza si hay distribucion normal, como se desvia
      ° .skew --> positivo (oblicuidad)
      ° .kurt --> kurtosis (grado de la punta de la grafica y si hay muchos datos dispersos en los costados)

6- Grafica SCATTER PLOT entre "Precio de ventas" y "Area vivienda"

      ° Creo la variable
      ° Uno columnas con metodo CONCAT
      ° Grafica de SCATTER PLOT --> hay relacion, pero no lineal, tiene outliers.

7- Grafica BOX PLOT entre ["Precio de ventas" y "Calidad" || "Precio de ventas" y "Año construida"]

      ° Creo la variable
      ° Uno columnas con metodo CONCAT
      ° Grafica de BOX PLOT

8- Grafica HEATMAP (Matriz de correlacion) --> para ver que variables estan mas correlacionadas

9- Grafica HEATMAP --> ahora con numeros

Podemos ver que:

* Calidad, AreaVivienda y area Sotano estan muy fuertemente correlacionadas con PrecioVenta
* Las variables de garage están super correlacionadas
* Sotano y 1er piso son basicamente hermanos gemelos
* AñoConstruccion esta ligeramente correlacionada con PrecioVenta, parece que en un futuro habra que hacer un analisis de serie de tiempo más serio.

10- Grafica SCATTER PLOT entre "Precio de ventas" y TODAS LAS VARIABLES MAS CORRELACIONADAS



Gracias por leer, que tengas un buen dia! 
