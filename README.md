# auditorIA
Este repositorio contiene el Código utilizado para el desarrollo del prototipo del trabajo de grado “Diseño Y Desarrollo de Una Herramienta Basada En Procesamiento de Lenguaje Natural Mediado Por Deep Learning Para Evaluación de Registros Clínicos Electrónicos”. 

Se organiza en 4 cuadernos: 

* [Cuaderno donde se preprocesaron, anonimizaron y organizaron los registros clínicos electrónicos](PREPROCESAR_EHR.ipynb): Este muestra los pasos para convertir el archivo con los datos clínicos obtenido de la institución a un archivo que contiene ID aleatorios y datos clínicos (edad, anamnesis, formulación) organizado en dos columnas para ser usado posteriormente en el modelo.  

* [Cuaderno para ejecutar prototipo con LLM alojado en GPU](PROTOTIPO_LOCAL.ipynb): Contiene las librerías, funciones y organización del código para ejecutar un LLM en GPU local de Google Colab con interfaz gráfica, se debe tener en cuenta que para nuevas pruebas, se deben ajustar las librerías a versiones estáticas puesto que actualizaciones recientes de pandas y LangChain pueden comprometer su ejecución. 

* [Cuaderno para ejecutar prototipo con LLM alojado en proveedor](PROTOTIPO_FINAL_PROVEEDOR.ipynb): Contiene una versión que utiliza un proveedor en la nube de LLM, se debe ajustar las Keys y el Point de la librería OPENAI como variables de entorno para que funcione. 

* [Cuaderno para análisis descriptivo de registros clínicos electrónicos](ANALISIS_DESCRIPTIVO.ipynb): Contiene el código utilizado para hacer un análisis descriptivo de los registros clínicos obtenidos en el primer cuaderno. 


Es de resaltar que los cuadernos se encuentran organizados internamente conservando la estructura que permitió la ejecución funcional del prototipo en las pruebas reportadas, no necesariamente reflejan el flujo de trabajo representado de forma académica en el documento original.

Los autores de las librerías utilizadas fueron referenciados en el documento original.

