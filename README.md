# **PROYECTO_CH_DS**
## Coder House - Data Science - Comisión 29.765
**Profesor:** *César Millán Castillo*

**Tutor:** *Andres Cervantes*

**Equipo:**
 :woman:*Agustina Clissa*
 :woman:*Agustina Mel*
 :man:*Alejo Carballo*

### Empresa
La base de datos elegida para realizar el proyecto final está compuesta por un set de personas aseguradas de una de las principales compañía de banca-seguros con sede en Argentina. 
Se cuenta con un total de 570.379 registros que corresponden a la contratación de un seguro para tres tipos de productos disponibles: Autos, Accidentes Personales y Vivienda. 
Debido a la cantidad de registros, es imprescindible organizar y gestionar los datos para hacer un estudio de predicción y, de esta forma, poder tomar las mejores decisiones que aporten ventaja competitiva a mediano y largo plazo.

### Fuente de información
El dataset se compone de una base de pólizas vigentes en el mes de junio-2022 de 3 productos diferentes que ofrece la compañía de seguros de la Argentina, en donde trabaja uno de los integrantes del equipo. 
Se han seleccionado esos productos ya que son los mas relevantes dentro de la compañia. La base de datos se encuentra en hoja de cálculo de Microsoft Excel (.xlsx) Generación del primer Data Wrangling y EDA, apuntado a sus datos (insights) univariado, bivariado y multivariado.
Asimismo, se consideraron 3 subdatasets, para poder analizar las características y la relación de las variables (edades, segmento, score interno, canal, etc.), para cada uno de los productos.

### Objetivo
Con el dataset propuesto en este Proyecto, vamos a tratar de predecir cual es el mejor producto que le podemos ofrecer a un nuevo cliente, dadas sus características. Esto permite personalizar al máximo el trato con el cliente y captar su atención para asegurar las ventas . Además, hacer un análisis cross selling entre los clientes existentes para predecir qué otro producto se le puede ofrecer. Por ejemplo: a un cliente que adquirió el producto Autos qué otro producto le puedo ofrecer, dadas sus características.

### Hipotesis
Mediante los datos de la base del presente proyecto  se pueden elaborar hipótesis de comportamiento futuro de los riesgos y, en función de la situación del cliente, hacer una recomendación oportuna y relevante al asegurado y/o su agente. 
Asimismo, dicho riesgo se puede ver inducido por otra serie de factores subyacentes o tendencias del tipo de clientes que contratan un seguro (edad, género, geografía)
Gracias a estas hipótesis se pueden elaborar estrategias de comercialización que permitan el incremento del volumen de ventas en la empresa


### Descripción de columnas
A continuación se describen la variables utilizadas en el DataSet
|	VARIABLE	|	DESCRIPCION VARIABLE	|
|	------------	|	------------	|
|	CLIENTE	|	Numero de identificacion del cliente	|
|	EDAD	|	Edad actual	|
|	ANTIGUEDAD_CLIENTE	|	Diferencias entre la fecha actual y la primera contracion de cualquier producto	|
|	GENERO	|	Sexo indicado por cliente	|
|	SEGMENTO	|	Indica el segmento de renta. Siendo 1 el segmento mas alto ingresos y el 9 el segmento mas bajo	|
|	ACTIVIDAD_ECONOMICA_TX	|	Actividad economica a la que se dedica el clientes	|
|	CODIGO_POSTAL	|	Codigo postal de la vivienda del cliente	|
|	LOCALIDAD_TX	|	Codigo postal de la vivienda del cliente	|
|	PROVINCIA_COMERCIAL	|	Localidad de la vivienda del cliente	|
|	TIPO_VIVIENDA	|	Indica el tipo de vivienda del cliente	|
|	RAMO_PROP_TX	|	Indica el producto contrato: Autos, Vivienda o Accidentes Personales	|
|	Q	|	Cantidad de Polizas	|
|	ANTIGUEDAD_POLIZA	|	Diferencias entre las fecha actual y fecha de contratacion de la poliza vigente	|
|	EDAD_CONTRATACION	|	Diferencias entre EDAD - ANTIGÜEDAD_POLIZA	|
|	TIPO_MEDIO_PAGO_TX	|	Indica el medio de pago con el cual contrato	|
|	PUNTO_VENTA_TX	|	Punto de venta donde se genero la contratacion	|
|	SUBCANAL	|	Subcanal donde se genero la contratacion	|
|	CANAL	|	Canal donde se genero la contratacion	|
|	POINT_RENTABLE	|	Indica si el clientes es rentable en relacion al historial Prima-Siniestros. 10 Muy - 1 Poco	|
|	BLACK_LIST_BOOL	|	Indica si el clientes esta en la lista de fraude	|
|	CLAIMS_COUNT	|	Cantidad de siniestros que tuvo el cliente a lo largo de la historia	|
|	EARLY_CLAIM_FLAG	|	Cantidad de siniestros producidos dentro de los 3 meses d ela fecha de contratacion	|
|	PROBLEMATIC_BOOL	|	Siniestros que estan en jucio, desistidos, rechazados	|
|	POINT_CONFIABLE	|	Indica si el clientes es confiable en relacion al historial siniestral. 10 Muy - 1 Poco	|
|	POINT_DIGITAL	|	Indica si el clientes es digital  en relacion al uso de los canales digitales para la contratacion, cotizacion, siniestros	|
|	ESTADO_CIVIL_TX	|	Estado civil indicado por el cliente	|
|	ESTADO_CLIENTE_TX	|	Indica el estado actual del cliente	|
|	SCORE_INTERNO	|	Variable que indica el riesgo previsto por variables interna de la organizacion. A mayor riesgo, mayor probabilidad de cancelacion	|
|	SCORE_EXTERNO	|	Variable que indica el riesgo previsto por variables externas de la organizacion. A mayor riesgo, mayor probabilidad de cancelacion	|

