En este laboratorio trabajaremos con files_for_lab/abTesting.csvarchivos. Consulte el case_study_ab_test.mdarchivo para obtener más información sobre los datos recopilados. El archivo también contiene una descripción de los diferentes campos de datos que se incluyen en el archivo CSV.

Asegúrese de guardar este cuaderno. Usaremos los resultados de este laboratorio en el próximo laboratorio (para expresiones LOD). Usaremos este laboratorio para prepararnos para la tarea del próximo laboratorio.

Instrucciones
Importe el csv a Tableau y responda las siguientes preguntas:

¿Cuál es la distribución del número de participantes en cada etapa para la variación de control y la variación de prueba? Asegúrese de que los pasos del proceso estén en orden. El gráfico final se vería así: (No importa si utiliza el eje Y para los pasos del proceso)

Haga clic para ver la imagen
Ahora, queremos comparar el número total de participantes para cada variación. Preste atención: ¿puede realizar la suma de todos los pasos del proceso o no?

Duplica el gráfico anterior en una hoja nueva. Ahora queremos encontrar el número total de participantes por género, es decir, cuál es el número de hombres y mujeres en cada variación. Puedes filtrar las otras categorías de género presentes en los datos. (Selecciona solo hombres y mujeres en tus datos) El gráfico final se vería así:

Haga clic para ver la imagen
Duplica la hoja anterior. Ahora el objetivo es representar la cantidad de participantes por género como porcentaje de los totales. Utiliza el cálculo rápido de tabla apropiado para esto. Redondea los porcentajes a un punto decimal. El gráfico final se vería así:

Haga clic para ver la imagen
Ya hemos visto cómo agrupar los datos creando un nuevo campo calculado (mediante IF...ELSEsentencia condicional). Ahora crearemos grupos utilizando la create groupopción de Tableau. Crearemos diferentes grupos de edad y analizaremos el saldo promedio de cada grupo. Siga los pasos:

Haga clic en la flecha hacia abajo clnt_ageen el panel de dimensiones del lado izquierdo. Vaya a Crear y seleccione groups:
Haga clic para ver la imagen del paso 1
Cree los siguientes grupos: de 17 a 30 años, de 31 a 40, de 40 a 55, de 55 a 70 y de 70 años o más.
Editar nombres de grupos:
Haga clic para ver las imágenes
Grafica el saldo promedio de cada grupo. ¿Observas alguna tendencia?
