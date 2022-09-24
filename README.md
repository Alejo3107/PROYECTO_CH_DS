# **PROYECTO_CH_DS**
## Coder House - Data Science - Comisión 29.765
**Profesor:** *César Millán Castillo*

**Tutor:** *Andres Cervantes*

**Equipo:**
 :woman:*Agustina Clissa*
 :woman:*Agustina Mel*
 :man:*Alejo Carballo*

### Empresa
Una de las principales compañia de banca-seguros con sede en Argentina.

### Fuente de información
El dataset elegido para realizar el proyecto final esta compuesto por las polizas vigentes al mes de junio 2022 de los 3 principales productos de la compañia.

### Objetivo
Predecir cuales son los clientes mas rentables (POINT_RENTABLE entre 8 y 10) para cada producto, con el objetivo de ofrecerle a los clientes rentables  actuales otro producto o ir a buscar nuevos clientes rentables.

### Hipotesis
La idea de ir a buscar los clientes mas rentables es porque son lo que mas prima y resultado genera a la compañia.

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

