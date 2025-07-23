# Data-Clean

Carga de datos en R con datas de instituciones publicas de México

En este repositorio se encuentran cargados dos Data; uno desde el .csv descargado previamente y otro desde la web. El primero correponde a la Proporción de mujeres de 15 años y más que han sufrido violencia física y/o sexual por parte de su actual o última pareja y que han acudido al menos a una institución o autoridad en busca de ayuda. Datos de INEGI-ENDIREH. El data se categoriza por estados y tenemos el porcentaje que ha reportado estas actividades de violencia por estado.

En el segundo corresponde a Alumnas del Sistema CONALEP que continúan sus estudios aún embarazadas. Registro de febrero a julio, 2024. El data se divide por estado y el periodo de febrero - julio del 2024 con el numero de chicas que continuaron en ese periodo sus estudios estando embarazadas.

#Actualización 
Para ambos dataset se limpiaron los datos:
  1. Detectar y tratar valores faltantes
  2. Detectar y tratar duplicados y variables masl tipificadas
  3. Estandarizar nombre de columnas y contenido de variables
  4. Limpiar espacios
Y posteriormente se guardo el nuevo .csv en ./data/processed con el la terminacion ....-limpios.csv, de igual forma se guardaron los srcipts en ./scripts/ con la terminacion ...-cleaning.R
