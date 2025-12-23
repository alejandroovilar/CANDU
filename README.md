Modelización de un Reactor Nuclear tipo CANDU
Este repositorio contiene los archivos de configuración y datos necesarios para la simulación de un reactor nuclear de tipo CANDU, desarrollados como parte del trabajo de modelización del núcleo. El proyecto se estructura a través de diferentes escenarios que permiten analizar el comportamiento del reactor bajo distintas condiciones de operación y diseño.

-Descripción del Modelo Principal:
El archivo CANDU-Principal.txt representa la base fundamental del proyecto. En este documento se detalla la modelización integral del reactor siguiendo los parámetros técnicos requeridos en el enunciado del trabajo. Incluye la definición geométrica de la calandria, la disposición de los canales de combustible y las propiedades de los materiales moderadores y refrigerantes que caracterizan a este sistema.

-Análisis de Sensibilidad y Configuraciones Específicas:
Para profundizar en el comportamiento del reactor, se han desarrollado tres variantes adicionales que modifican aspectos críticos de la reactividad y la eficiencia de la simulación:

-Configuración de Barras de Control:
En el archivo CANDU-barras-parcialmente-insertadas.txt, se estudia el efecto del sistema de regulación sobre el flujo neutrónico. En esta versión, las barras de control situadas en la zona central del núcleo han sido desplazadas hacia arriba hasta alcanzar el 25% de su longitud total. Este ajuste permite evaluar la distorsión del flujo y la ganancia de reactividad asociada a la extracción parcial de los venenos neutrónicos.

-Variación del Enriquecimiento del Combustible:
El archivo CANDU-concentracion-uranio-5%.txt se centra en el estudio del ciclo de combustible. A diferencia del diseño estándar de los reactores CANDU, que utilizan uranio natural, en este escenario se ha incrementado el enriquecimiento de uranio de manera progresiva desde un 0,7% hasta un 5%. El objetivo de este modelo es determinar cómo influye el aumento de la concentración de U 235 en la criticidad y en la distribución de potencia del núcleo.

-Optimización de Fuentes y Eficiencia Computacional:
El archivo CANDU-fuente-ciclos.txt introduce modificaciones orientadas a la metodología de cálculo. Se han integrado fuentes de neutrones específicas para estabilizar el proceso de arranque de la simulación. Paralelamente, se ha realizado un ajuste en los parámetros de ejecución reduciendo el número de ciclos. Esta modificación busca optimizar la eficiencia computacional, permitiendo obtener resultados convergentes en un tiempo de proceso significativamente menor sin sacrificar la precisión necesaria para el análisis académico. NOTA: Este código no fue considerado para el trabajo
