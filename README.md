La salida de LightGBM te da 3 cosas para ver si una variable es util:

- Gain: representa la mejora en la precisión que tiene el modelo al dividir una rama mediante esa variable.
- Cover: porcentaje de registros que se ven afectados por esta variable en el modelo.
- Frequency: que tan frecuente esa variable es utilizada en el modelo.

Claro que todas las variables que no sean importantes van a tener valores bajos para estas 3 categorías.
