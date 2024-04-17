
Este análisis exploratorio de datos en Python es bastante detallado y abarca varias etapas importantes.

Carga y baselines pre-limpieza de datos:

-Se importaron las bibliotecas necesarias.
-Se cargaron los datos en un DataFrame de Pandas.
-Se observaron los primeros registros para familiarizarse con los datos.
-Se establecieron los nombres de las columnas.
-Se visualizó la distribución de las categorías de la variable objetivo.
-Se calculó el baseline global y baselines por ciudad.

Análisis de los problemas de calidad de los datos:

-Se verificaron los tipos de datos y se observaron inconsistencias.
-Se realizó una descripción estadística de las variables para detectar problemas.
-Se identificaron valores inválidos y tipos de columnas incorrectos.
-Se convirtieron las variables numéricas incorrectas a categóricas.
-Se detectaron y manejarons los valores faltantes, eliminando registros o imputando valores.
-Se buscaron excepciones o valores atípicos en algunas variables utilizando gráficos de caja y diagramas de densidad.

 Para el dataset

-Cleveland Clinic Foundation
-Hungarian Institute of Cardiology, Budapest
-University Hospital, Zurich, & University Hospital, Basel, Switzerland
-Los campos del dataset son los siguientes:

-ciudad: ciudad del paciente (Cleveland, Hungria, Suiza)
-edad: en años
-sexo: "1"=hombre, "0"=mujer
-tipo_dolor: tipo de dolor de pecho ("1"=angina típico, "2"=angina atípico, "3"=dolor no de angina, "4"=sin síntoma de dolor)
-presion: presión de la sangre en reposo (en mm/Hg, en el momento de admisión al hospital)
-colesterol: en densidad del colesterol (en mg/dl)
-azucar: indica si el nivel de azucar en la sangre en ayunas es superior a 120 mg/dl ("1") o no ("0")
-ecg: resultado el electro cardiograma ("0"=normal, "1"=anormalidad del nivel de ST, "2"=hipertrofía ventricular probable)
-pulso: frecuencia cardiaca máxima alcanzada
-angina: si se induce a una angina a través del ejercicio ("1") o no ("0")
-st: diferencia relativa entre el nivel de ST inducido por el ejercicio comparado con el nivel del reposo.
-pendiente: la pendiente de llegada al máximo del nivel ST durante el ejercicio ("1"creciente, "2"=plana, "3"=decreciente)
-venas: número de venas coloreadas a partir de la fluorescopia (0 a 3)
-thal: tipo de defecto (valores aceptados 3=normal, 4=defecto arreglado, 7=defecto reversible)
-target: indica si en efecto el paciente presenta una enfermedad cardiaca ("1", "2", "3", "4") o no ("0")