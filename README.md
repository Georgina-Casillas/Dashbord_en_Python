# Visualización de Datos (Dashbord de Python)

## La Participación de Hombres y Mujeres en la Economía de México. Un análisis comparativo entre México y el promedio mundial (2005-2021).



## Autor ✒️
**Georgina Casillas Rosano**

* [LinkedIn](https://www.linkedin.com/in/georgina-casillas-rosano-data-science)
* [Portafolio]()

* Instalación 💻: Este proyecto requiere de instalar Python.

## Objetivos del proyecto: 🎯
* Desarrollar un Dashboard para visualizar y analizar las diferencias en la participación económica de hombres y mujeres en México y contrastarlas con los datos promedio obtenidos en el resto del mundo.


* Crear un Dashboard con Plotly y Dash que compare los porcentajes de participación por género en los sectores agrícola, industrial y de servicios entre México y el mundo, se necesita cargar los datos en Python y estructurar los gráficos en el dashboard. Al final con Dash, se construyen los gráficos y se muestran en una interfaz web interactiva.

## Dataset 🧾
* El conjunto de datos se obtiene de la página Web de Naciones Unidas (http://data.un.org) en el periodo de 2005 a 2021. Consiste en 8036 valores y 7 variables correspondientes a datos sobre la participación de hombres y mujeres en los sectores económicos de Agricultura, Industria y Servicios en las distintas Regiones, Países y Áreas del Mundo.


Region/Country/Area: int64
Unnamed: Categorical 
Year: int64
Series: Categorical (Agricultura, Industria, Servicios)
Value: float64
Footnotes: object
Source: object


## Estructura del Proyecto y Metodología 📈


1. **Carga de datos y Preprocesamiento:**
    * La base de datos se carga usando la librería Pandas. 
    * Se codifican apropiadamente las variables categóricas (Agricultura, Industria, Servicios ) para tener una identificación más clara de las variables.
    * La variable edad se deja como una variable numérica ya que el modelo puede encontrar los mejores puntos de corte por sí mismo sin necesidad de agrupar manualmente.


2. **Preprocesamiento de datos:**
   * Se filtra el dataset, separando los países por Sector, Año y Valor para tener una mejor visualización de los datos para México y la suma de los Países.


3. **Generación de los Gráficos:**
   * En esta sección se generan las gráficas para analizar las diferencias en la participación económica de hombres y mujeres en México y contrastarlas con los datos promedio obtenidos en el resto de los países.


4. **Creación del Dashboard:**
Para crear un dashboard con Plotly y Dash que compare los porcentajes de participación por género en los sectores agrícola, industrial y de servicios entre México y el mundo, se necesita cargar los datos en Python y estructurar los gráficos en el dashboard. Al final con Dash, se construyen los gráficos y se muestran en una interfaz web interactiva.


## Hallazgos Clave 🔎
* La participación laboral por género refleja las dinámicas económicas y sociales de México.
* La tendencia mundial y en México en la disminución de participación en el sector agrícola, se debe a la falta de acceso a recursos económicos en el campo.
* Desde 2005, la participación femenina en el sector Industrial en México no ha tenido grandes avances.
* En los últimos 20 años, la participación femenina en el sector de servicios en México creció un 20%, reflejando avances en políticas de igualdad


