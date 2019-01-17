# Analysis of fNIR data

Explanation of the method, the task and the analysis

### Introduction

Si bien ya se ha tratado el correlato neuronal de efectos de magia con imagen por resonancia magnética funcional
[Danek et al., 2015](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4316608/), 
[Parris et al., 2009](https://www.sciencedirect.com/science/article/pii/S1053811908012949)
en este proyecto se considera que es una técnica que no preserva las condiciones de una sesión de magia, por lo que para registrar la 
respuesta neurológica se utilizó la espectroscopia funcional de infrarrojo cercano (fNIR). 
Esta técnica es ideal para montajes ecológicos al no ser invasiva y permitir cierta movilidad de los sujetos. 
La tecnología fNIR registra los cambios relativos de las concentraciones de hemoglobina oxigenada y desoxigenada en la corteza prefrontal,
estimando de esta manera el nivel de oxigenación de la zona con una resolución temporal de segundos y una resolución espacial de 
centímetros (Biopac Systems, 2009). Debido al acoplamiento neurovascular (Dirnagl, 1997), una mayor oxigenación conlleva una 
mayor actividad cerebral que, de acuerdo con la información de la que se dispone hasta la fecha, puede traducirse 
como una mayor sorpresa o asombro -violación de expectativas.


#### fNIR

La espectroscopia funcional de infrarrojo
cercano se basa en LEDs que emiten luz a longitudes de onda del infrarrojo cercano (740 y 860nm) y 
fotodetectores a dos distancias distintas de los LEDs (distancia corta y distancia larga). 
La tecnología fNIR reporta información sobre dos capas relacionadas con la corteza prefrontal; 
la capa superficial, que se asocia a la vascularización de piel y meninges (cuando los LEDs y los fotodetectores 
se encuentren a la distancia corta) y la capa profunda, asociada a la actividad de la corteza prefrontal
(cuando los LEDs y los fotodetectores se encuentren a la distancia larga).

Mas información sobre el fNIR y su análisis [aqui](https://en.wikipedia.org/wiki/Functional_near-infrared_spectroscopy)

Características del fNIR diseñado en el Instituto de Neurociencias de Alicante (INA):
+ 1. Dimensiones: longitud: 20 cm; altura: 6cm
+ 2. LEDs y fotodetectores: Consta de 4 LEDs y de 10 fotodetectores. La primera distancia, que reporta información de la capa superficial,
es de 1,4cm y la segunda distancia, que reporta información de la capa profunda, es de 3,2cm. De acuerdo con la disposición de los LEDs y los fotodetectores se dispone de 16 canales de adquisición de datos en la capa superficial y de 12 en la profunda.
+ 3. Longitudes de onda utilizadas: 740nm para la desoxihemoglobina y a 860nm para la oxihemoglobina.


#### Naturalidad condicionada

De acuerdo con la información que se dispone, en este proyecto se analiza por primera vez el principio de teoría mágica llamado
“naturalidad condicionada”. Este concepto, acuñado por el mago español Arturo de Ascanio a principios de los sesenta enuncia que:

“Cuando en un juego se hace un determinado movimiento (coger una carta, o dejarla…) inocuo en sí mismo, hay que hacerlo exactamente
igual que cuando el movimiento es imprescindible, necesario para el juego. Se debe acostumbrar desde el principio al público a 
que dicha acción siempre se hace de idéntica forma, sea o no necesaria para el juego, de modo que en ninguno de los casos llame
la atención”
Arturo de Ascanio, Análisis de un juego. II jornadas cartomágicas de El Escorial, 1975


En términos más aplicados al proyecto, este principio hace referencia a que el hecho de repetir una acción con un determinado 
gesto sin hacer la trampa hace que, cuando esta acción se repita con el mismo gesto pero de manera tramposa (“haciendo el truco”),
la acción tramposa pasará desapercibida para los integrantes del público, ya que estarán condicionados en relación a ese gesto.
Este principio, plenamente arraigado en la teoría mágica, pasa a ser analizado desde un enfoque científico-técnico, ya que se 
intenta observar si la ausencia o presencia de maniobras de condicionamiento repercute en la respuesta neurofisiológica.

#### Procedimiento

(1) El sujeto se sentó en el asiento situado delante de la mesa. 
(2) Se le puso el fNIR al sujeto y se le ajustó. 
(3) Se dieron las instrucciones del experimento. 
(4) Se inició la presentación con un efecto mágico a modo de control para cerciorarse de que se habían entendido las instrucciones. 
(5) Se tomaron las constantes en reposo (baseline del run 1). 
(6) Se visionó el efecto de magia con cartas.
(7) Se marcó como inicio del estímulo del primer run al momento previo a producirse el efecto mágico. Los espectadores reportaron, 
mediante el pulsador, el tiempo en el que ellos consideraron que se producía el efecto mágico (tiempo 1). 
(8) Se esperaron 60 segundos después del efecto mágico para aislar la respuesta del cuestionario (fin del run 1). 
(9) Se pasó el cuestionario posterior al efecto mágico.
Se repitieron los pasos 5, 6, 7, 8 y 9 con el efecto de monedas y el efecto de cubiletes.

Después de la sesión de magia, se contaba con 3 runs de cada sujeto (uno por cada efecto de magia). 
Los tiempos 1 de cada efecto, que eran los reportados por los sujetos cuando experimentaban la sensación de magia,
fueron los que se usaron para el análisis. El inicio del estímulo servía como referencia para aquellos sujetos que olvidaban pulsar.


#### Condidiones

12 condiciones
3 materiales (cartas, monedas, cubiletes) x 2 naturalidad (condicionado, no-condicionado) x 2 visionados (directo, vídeo)

#### Subjects N=53
Visionado en directo
+ 1 d_c_c, d_m_nc, d_c_c: 18 sujetos
+2 d_c_nc, d_m_c, d_c_nc: 18 sujetos

Visionado en vídeo
+ 1 v_c_c, v_m_nc, v_c_c: 9 sujetos
+ 2 v_c_nc, v_m_c, v_c_nc: 8 sujetos






