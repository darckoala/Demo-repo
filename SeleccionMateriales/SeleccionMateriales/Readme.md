## Selección de Materiales[^1]

Se establece el procedimiento básico de selección, estableciendo el vínculo entre el material y la función. Un material tiene atributos: su densidad, resistencia, coste, resistencia a la corrosión, etc. Un diseño exige un cierto perfil de estos: una baja densidad, una alta resistencia, un coste modesto y resistencia al agua de mar, tal vez. Es importante comenzar con el menú completo de materiales en mente; el no hacerlo puede significar una oportunidad perdida. Si un se debe tomar una decisión innovadora, que debe ser identificada en las primeras etapas del proceso de diseño. Más tarde, se han tomado demasiadas decisiones y se han asumido
demasiados compromisos para permitir cambio radical: es ahora o nunca.

La tarea, replanteada en dos líneas, es la de 
1. Identificar el perfil de atributo deseado y, a continuación
2. Compararlo con los materiales de ingeniería reales para encontrar la mejor
combinación.

El primer paso para abordarlo es el de la traducción, examinando el diseño. Requisitos para identificar las restricciones que imponen a la elección de materiales. La inmensa variedad de opciones se reduce, en primer lugar, mediante el cribado de los materiales que no pueden cumplir con las restricciones. Se logra un mayor estrechamiento mediante la clasificación de los candidatos por su capacidad de maximizar el rendimiento.

Criterios de selección y se derivan de los requisitos de diseño de un componente mediante un análisis de funciones, restricciones, objetivos y variables libres. Las cartas de propiedades de los materiales están diseñadas para su uso con estos criterios. Las restricciones de propiedad y los índices de materiales pueden ser graficados en ellos, aislando el subconjunto de materiales que son la mejor opción para el diseño.

<div align="center">
  <br><img src=https://github.com/darckoala/Demo-repo/blob/main/SeleccionMateriales/SeleccionMateriales/Imagenes/SeleccionMaterialesProcesoFormaFunción.JPG width=40%"></br>
</div>

<div align="center">
  <sub>
      La selección de material se determina por la función. La forma a veces influye en la selección.
</div>

### Estrategia de selección

<div align="center">
  <br><img src=https://github.com/darckoala/Demo-repo/blob/main/SeleccionMateriales/SeleccionMateriales/Imagenes/Taxonomía%20de%20materiales.JPG width=60%"></br>
</div>

<div align="center">
  <sub>
      La taxonomía del reino de los materiales y sus atributos. Selección por ordenador almacena los datos en una estructura jerárquica como ésta.
</div>

En el gráfico se muestra cómo se divide el reino de los materiales en familias, clases, subclases y miembros. Cada miembro se caracteriza por un conjunto de atributos: sus propiedades. Como ejemplo, el reino material contiene en la familia "metales", que a su vez contiene la clase "aleaciones de aluminio", la subclase "Serie 6000" y finalmente el miembro particular "Aleación 6061". Cualquier otro miembro del reino, se caracteriza por un conjunto de atributos que incluyen sus propiedades mecánicas, térmicas, eléctricas, ópticas y químicas, sus características de procesamiento, su costo y disponibilidad, y la protección del medio ambiente, consecuencias de su uso. Llamamos a esto su perfil de propiedad. La selección implica buscar la mejor correspondencia entre los perfiles de propiedades de los materiales en el y el requerido por el diseño.

Hay cuatro pasos principales, que aquí llamamos traducción, selección y clasificación, e información de apoyo. Los pasos se pueden comparar con los de seleccionando a un candidato para un trabajo. El trabajo es primero analizado y anunciado, identificando las competencias y la experiencia esenciales que se exigen al candidato. Algunos de estos son simples criterios de ir o no ir como el requisito de que el solicitante "debe tener un permiso de conducir válido" o "un título en informática“ eliminar a cualquiera que no lo haga ('‘Proyección'').  Otros implican un criterio de excelencia, como "la velocidad y la exactitud de la mecanografía son prioritarias", o "se dará preferencia a los candidatos con
una lista de publicación importante", lo que implica que los solicitantes serán clasificados según estos criterios ("clasificación"). Finalmente, se buscan referencias y entrevistas para los candidatos mejor clasificados, creando un archivo de información de apoyo, una oportunidad para indagar profundamente en el carácter y el potencial.

<div align="center">
  <br><img src=https://github.com/darckoala/Demo-repo/blob/main/SeleccionMateriales/SeleccionMateriales/Imagenes/Proceso%20de%20seleccion.JPG width=30%"></br>
</div>

<div align="center">
  <sub>
      Estrategia de selección de materiales. Los cuatro pasos principales: traducción, selección, y la información de apoyo.
</div>
  
### Traducción

¿Cómo se traducen los requisitos de diseño de un componente (definiendo lo que debe hacer) en una prescripción para un material? Cualquier componente de ingeniería tiene una o más funciones:
    
- Soportar una carga.
- Contener una presión.
- Transmitir calor, etc.

Esto debe lograrse sin perjuicio de las siguientes condiciones:

- que determinadas dimensiones seran fijas,
- que el componente soporta las cargas de diseño o que presiones sin fallo.
- que aísla o conduce.
- que puede funcionar en un cierto rango de temperatura y en un
ambiente dado, y muchos más.

El diseñador tiene un objetivo: hacerlo tan barato como posible, tal vez, o como ligero, o como seguro, o tal vez alguna combinación de estos. Ciertos parámetros pueden ser ajustados para optimizar el objetivo el diseñador es libre de variar las dimensiones que no han sido restringidas por el diseño y, lo que es más importante, libre de elegir el material para el proyecto y/o componente. Nos referimos a estas variables como variables libres. Función y limitaciones, variables objetivas y libres (Tabla ) definen las condiciones de contorno para selección de un material y, en el caso de los elementos portante, de una forma por su sección transversal. El primer paso para relacionar los requisitos de diseño con el material es una declaración clara de la función, las restricciones, el objetivo y la libertad.

<div align="center">
  <sup>
      Tabla .1. Función, limitaciones, objetivos y variables libres
  </sup>
</div>
    
| Paso  | Descripción |
| ------------- | ------------- |
| Función  | ¿Qué hace el componente?  |
| Restricciones*  | ¿Qué condiciones no negociables deben cumplirse? - ¿Qué condiciones son negociables pero deseables? |
| Objetivo  | ¿Qué se debe maximizar o minimizar?  |
| Variables libres  | ¿Qué parámetros del problema puede cambiar el diseñador?  |
    
<div align="center">
  <sub>
     * A veces es útil distinguir entre restricciones "duras" y “suaves". La rigidez y la resistencia pueden ser requisitos absolutos (restricciones duras); el costo puede ser negociable (una restricción suave).
  </sub>
</div>
    
### Límites de atributos: Filtro de selección

La selección imparcial requiere que todos los materiales sean considerados candidatos; hasta que se demuestre lo contrario, utilizando los pasos de las casillas. El primero de ellos, la selección, elimina a los candidatos que no pueden hacer el trabajo en absoluto porque uno o más de sus atributos se encuentra fuera de los límites establecidos por las limitaciones. A modo de ejemplo, el requisito de que ''el componente debe funcionar con agua hirviendo", o que "el componente debe ser transparente". Impone límites obvios a los atributos de la temperatura máxima de servicio y transparencia óptica que deben cumplir los candidatos seleccionados. Nos referimos a ellos como límites de atributos.

### Índices de material

Sin embargo, los límites de atributo no ayudan a ordenar a los candidatos que permanecer. Para ello necesitamos criterios de optimización. Se encuentran en en los índices de materiales, desarrollados a continuación, que miden qué tan bien un candidato que ha pasado el paso de selección puede hacer el trabajo. El rendimiento es a veces limitado por una sola propiedad, a veces por una combinación de ellas. Por lo tanto, el mejor los materiales para la flotabilidad son los que tienen la densidad más baja, ρ; los mejores para aislamiento térmico los que tienen los valores más bajos de conductividad térmica, λ. Aquí, maximizar o minimizar una sola propiedad maximiza el rendimiento. Pero, como veremos, los mejores materiales para una ligera rigidez de la varilla. son aquellos con el mayor valor de la rigidez específica, E/ ρ, donde E es el módulo de Young.

  Los mejores materiales para un resorte son aquellos con los mejores valores de σ <sup>2</sup> <sub>f</sub> /E donde σ<sub>f</sub> es el fallo por tensión. La propiedad o grupo de propiedades que maximiza el rendimiento para un diseño dado se llama su índice de material. Existen muchos índices de este tipo, cada uno asociado con la maximización de algún aspecto de desempeño. Proporcionan criterios de excelencia que permiten la clasificación de materiales por su capacidad de rendir bien en la aplicación dada. Para resumir: seleccionar a candidatos aislados que sean capaces de hacer el trabajo; identifica a aquellos entre ellos que pueden hacer mejor el trabajo.

### Información de apoyo

El resultado de las medidas adoptadas hasta la fecha es una lista restringida de candidatos que cumplen los siguientes requisitos las limitaciones y que maximizan o minimizan el criterio de excelencia, lo que sea necesario. Podrías elegir al candidato de mayor rango, ¿pero qué malos secretos podría esconder? ¿Cuáles son sus fortalezas y debilidades?¿Tiene buena reputación? ¿Cuál es, en una palabra, su calificación crediticia? Para más adelante buscamos un perfil detallado de cada uno de ellos: su información de apoyo. La información de apoyo típicamente es descriptivo, gráfico o pictórico: caso estudios de usos previos del material, detalles de su comportamiento a la corrosión en entornos particulares, información de disponibilidad y precio, experiencia de su impacto ambiental.
  
Esta información se encuentra en los manuales, en los manuales de los proveedores. hojas de datos, bases de datos y la red mundial. ¿Por qué son necesarios todos estos pasos? Sin selección y clasificación, el grupo de candidatos es enorme y el volumen de información de apoyo es abrumador. Sumergirse en él, con la esperanza de tropezar con un buen material, no lleva a ninguna parte. Pero una vez que un pequeño número de candidatos potenciales han sido identificados por los pasos de selección, se puede buscar información de apoyo detallada sólo para estos pocos, y la tarea se vuelve viable.
  
### Condiciones locales
  
La elección final entre los candidatos que compiten entre sí dependerá a menudo de las condiciones locales: de los conocimientos especializados o el equipo interno, de la disponibilidad de proveedores locales, etc. Un procedimiento sistemático no puede ayudar en este sentido, sino que la decisión debe basarse en el conocimiento local. Esto no significa que el resultado del procedimiento sistemático sea irrelevante. Siempre es importante saber qué material es el mejor, incluso si, por razones locales, decide no utilizarlo.

### Selección de material para disipadores de calor para microchips
  
Las restricciones establecen límites de propiedad. Los objetivos definen los índices de materiales, para los que buscamos valores extremos. Cuando el objetivo no está acoplado a una restricción, el índice de material es una simple propiedad material. Cuando, en cambio, están acoplados, el índice se convierte en un grupo de propiedades como las citadas anteriormente. Ambos se explican a continuación.
  
Comenzamos con ejemplos sencillos de los primeros objetivos desacoplados:
  
1. Disipadores de calor para microchips.

Un microchip sólo puede consumir miliwatts, pero la energía se disipa en un pequeño volumen. La potencia es baja pero la densidad de potencia es alta. A medida que los chips se encogen y las velocidades de reloj crecen, el calentamiento se convierte en un problema. El chip Pentium de los PCs actuales ya alcanza los 85Cº, lo que requiere refrigeración forzada. Los módulos de múltiples chips (MCM) empaquetan hasta 130 chips en a un solo sustrato. La calefacción se mantiene bajo control mediante la conexión del chip a un disipador de calor, tomando precauciones para asegurar un buen contacto térmico entre el chip y disipador.
 
El disipador de calor se convierte ahora en un componente crítico, limitando un mayor desarrollo de la electrónica. ¿Cómo puede ser su desempeño maximizado?
  
<div align="center">
  <br><img src=https://github.com/darckoala/Demo-repo/blob/main/SeleccionMateriales/SeleccionMateriales/Imagenes/Esquema%20de%20disipadores.JPG width=40%"></br>
</div>
    
<div align="center">
  <sub>
      Un disipador de calor para la microelectrónica de potencia. El material debe aislar eléctricamente, pero conducir el calor lo mejor posible.
</div>  
  
Para prevenir el acoplamiento eléctrico y la capacitancia perdida entre el chip y el disipador de calor, el disipador de calor debe ser un buen aislante eléctrico, lo que significa una resistividad, ρ<sub>e</sub> ⩾ 10<sup>19</sup> μΩ.cm. Pero para drenar el calor de chip tan rápido como sea posible, también debe tener la conductividad térmica más alta posible. La traducción se resume en la Tabla 2, donde se supone que todas las dimensiones son limitadas por otros aspectos del diseño.
    
<div align="center">
  <sup>
      Tabla .2. Función, limitaciones, objetivos y variables libres
  </sup>
</div>
    
| Paso  | Descripción |
| ------------- | ------------- |
| Función  | Dispipador de calor  |
| Restricciones  | Material debe ser "buen aislante" - Se especifícan todas las dimensiones |
| Objetivo  | Maximizar la conductividad térmica  |
| Variables libres  | Libre elección del material  |

Para explicar: la resistividad es tratada como una restricción, un criterio de ir/no ir. Materiales que no califican como ''buen aislante'', o que tienen una resistividad mayor que el valor indicado en la tabla, se excluyen. La conductividad térmica es como un objetivo: de los materiales que cumplen con la restricción, buscamos aquellos con los valores más grandes y clasificarlos de esta manera:

- Se convierte en el material para el diseño.
- Si suponemos que todas las dimensiones están fijadas por el diseño.

Sólo queda una variable libre en la búsqueda de maximizar el flujo de calor: la elección del material. El procedimiento, entonces, es evaluar la resistividad, y luego clasificarla en conductividad.
    
Los pasos pueden ser implementados usando la carta ρ<sub>e</sub> λ, reproducido en la siguiente figura. 
  
  
<div align="center">
  <br><img src=https://github.com/darckoala/Demo-repo/blob/main/SeleccionMateriales/SeleccionMateriales/Imagenes/Carta%20de%20seleccion%20disipadores.JPG width=40%"></br>
</div>
    
<div align="center">
  <sub>
      Carta λ-ρ<sub>e</sub> cuando el atributo limite es ρ<sub>e</sub> ⩾ 10<sup>19</sup> μΩ.cm. La selección se refina aumentando la posición de la línea de selección λ.
</div>  
    
Dibuje una línea vertical en ρ<sub>e</sub> ⩾ 10<sup>19</sup> μΩ.cm; luego elija de los materiales que se encuentran por encima de esta línea, y tienen los más altos El resultado:
    
- nitruro de aluminio.
- AlN.
- Al2O3.
    
El paso final es buscar apoyo información para estos dos materiales. Una búsqueda en base de datos sobre “Nitruro de aluminio” conduce inmediatamente a hojas de datos detalladas con la información que buscamos. 

[^1]: M. F. Ashby, Materials selection in mechanical design, 3a ed. Amsterdam: Elsevier Butterworth-Heinemann, 2005. 
  
##
  <div align="center"><a href="http://www.escuelaing.edu.co" target="_blank"><img src=https://github.com/darckoala/Demo-repo/blob/main/Imagenes/Logo_Escuela.png alt="Support by" width="25%" border="0" /></a><sub><br>Este curso guía ha sido desarrollado con el apoyo de la Escuela Colombiana de Ingeniería - Julio Garavito. Encuentra más contenidos en https://github.com/uescuelaing</sub><br><br></div>
