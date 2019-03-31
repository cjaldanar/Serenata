# SERENATA

 # Desarrollado por:
   * Andrés Felipe Martinez Ramírez - Código: 20191099030
   * Juan Carlos Cruz Fajardo       - Código: 20191099027
   * Carmen Aldana                  - Código: 20191099023      

 # Solicitud inicial:

“El docente Alejandro Daza tiene una parranda de amigos que tienen diferentes profesiones, pero en común tienen que todos son músicos. De repente, esta uno desparchado, un fin de semana, lo llama a uno una persona y dice, mire necesitamos dar una serenata a tal persona o a tal pareja, necesito que llegue con unos músicos allá. Pero los amigos del docente Alejandro Daza son muy irresponsables, entonces uno nunca sabe con quién cuenta, chévere que uno pudiera contar con la misma gente siempre, pero no. De repente a veces sale, dos guitarristas, un flautista y tocó armar la serenata con eso. A veces sale toda la patota de amigos y se van con bajos, chelos, violines y todos el mundo, pero a veces no. Entonces, yo quiero que ustedes modelen ese ejercicio aleatorio, esa simulación de ir a unas chisgas, con los que salgan para tocar en un caso de esos. Entonces, a veces saldrá el trio de cuerdas, a veces saldrá la banda de mariachis completa, a veces se irá con el de las maracas nada más. Vamos a hacer el modelo y vamos a hacer una implementación muy sencilla a consola de eso, es una simulación, de repente me dicen miren por allá, generar toque y salieron dos guitarristas y salió el vocalista, no más, entonces cuando eso está corriendo, allá dirá, guitarra uno afinando, guitarra dos afinando,  vocalistas afinando y luego guitarra uno tocando, guitarra dos tocando, vocalista tocando pero tenemos que soportar o tener la flexibilidad de que pueda representarse a través de cualquier tipo de instrumento , de repente mañana salió solo el cantante con un man de un arpa y otro con un triángulo y el programa pueda funcionar. En el modelo se debe reflejar esa flexibilidad y en la implementación un prototipo con no se 4 o 5 instrumentos, aleatorio, de repente en un toque van 5 personas, en otro toque van 20, digamos que el número máximo de personas que irán al toque son 20, puede ser que vaya 1 solo o los 20 completos, se pueden repetir instrumentos, uno de cada uno, es una implementación muy aleatoria y que permita la extensión. Si por ejemplo, se presenta un prototipo con guitarras permita meterle unas maracas, si está bien modelado e implementado, esa extensión es sencilla y no va a requerir una modificación fuerte.”

# 1. IDENTIFICACIÓN DE REQUISITOS:

En este numeral se pretende realizar la identificación, análisis y descripción de los requerimientos asociados con:

* La interfaz.
* Simulación de la aleatoriedad de músicos e instrumentos.
* Reportar al usuario, los músicos e instrumentos que realizan la serenata.

  # a. Identificación del requerimiento:
  
  Para el caso de estudio, se propone realizar el modelado y la implementación de una simulación aleatoria de una serenata, donde se       refleje la flexibilidad de representar la serenata a través de cualquier tipo de instrumento y músico. 
  
  # b. Interfaz
  
   * La interfaz utilizada será una ventana.
   * El color estimado para la ventana es gris claro.
   * Contendrá un botón para dar inicio a la generación de la serenata.
   * Contendrá un cuadro de texto para mostrar músicos e instrumentos que generan la serenata. 
   
   # c. Simulación de la aleatoriedad
   
   * La aleatoriedad será originada por el sistema.
   * La aleatoriedad estará asociada al inicio de la serenata que activará cuando ésta sea iniciada con el botón "Generar Serenata".
   
   # d. Reportar al usuario, la serenata 
   
   * Mediante un cuadro de texto se reportará al usuario el inicio de la serenata.

# 2. IDENTIFICACIÓN DE REQUISITOS:

   # a. Interfaz:
   
   * Se construira en Netbeans un formulario en Java.
   * El diseño (Relleno y trazado de la ventana ) y comportamiento (Acciones sobre la ventana) serán elaborados a través de sentencias        de Java.
   * Graficamente, la ventana se visualizará de la siguiente manera:
   
   ![Imagen Pantalla proyectada.png](https://github.com/cjaldanar/Serenata/blob/master/Pantalla%20proyectada.png) 
   
   
   # b. Simulación de la aleatoriedad
   
   * A través de un metodo Random, se realizará la simulacion de aleatoriedad de los músicos e instrumentos, cuando se de clic en el          botón "Generar Serenata".
   
   # c.	Reporte al usuario, la serenata:
   
   * Mediante un cuadro de texto, se reportará al usuario el inicio de la serenata cuando se visualice el nombre del cantante y del         instrumento que toca.
    
# 3. MODELADO:

   # a. Diagrama UML: Identificación de Casos de Uso

![Imagen Caso de Uso Principal.png](https://github.com/cjaldanar/Serenata/blob/master/Caso%20de%20Uso%20Principal.png)

   # b. Diagrama de Clases
   
   # c. Diagrama de Secuencia
