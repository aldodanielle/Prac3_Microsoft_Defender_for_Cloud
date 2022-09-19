# Practica 3
## Microsoft Defender for Cloud
### Paso 1:
Ingresamos a portal Azure y buscamos el servicio que lleva por nombre Microsoft Defender for Cloud y notamos que tiene las dos versiones (Gratis y Estándar) e iniciamos el servicio.

![Imagen 1](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P1.png)
![Imagen 1.1](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P2.png)
------------------------------------------------------------------------------------------------------
### Paso 2:
Una vez que iniciamos y actualizamos observamos que ya contamos con los diferentes recursos activos como por ejemplo la protección para las otras nubes que son Azure como AWS, GCP y también nos da nuestra puntación de seguridad como se muestra en la segunda imagen.

![Imagen 2](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P3.png)
![Imagen 2.1](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P4.png)
![Imagen 2.2](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P5.png)
------------------------------------------------------------------------------------------------------
### Paso 3:
Agregamos una directiva buscamos el recurso de Directiva (la directiva nos ayuda para saber que está en concordancia con las reglas que colocamos) y una vez que estamos en el recurso nos vamos a Definiciones para crear una nueva directiva es decir una regla de cómo proteger nuestra nube.

![Imagen 3](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P6.png)
![Imagen 3.1](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P7.png)
------------------------------------------------------------------------------------------------------
### Paso 4:
Para definir una directiva necesitamos primero la definición de la misma es decir la ubicación en este ejemplo la colocamos en nuestra suscripción de Azure for Students y un nombre para la directiva así como una descripción si así lo deseamos también podemos observar que nos sale la regla en forma de código JSON el cual es el lenguaje en el que función Azure y por último la aguardamos.

![Imagen 4](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P8.png)
![Imagen 4.1](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P9.png)
------------------------------------------------------------------------------------------------------
### Paso 5:
Asignar una directiva, una vez creada es momento de asignarla para ello dentro de Directiva nos vamos a Asignación y una vez dentro de ahí presionamos Asignar directiva y nos manda a otra ventana como la que a continuación se muestra y para asignar la directiva primero elegimos el ámbito (Exclusiones), y elegimos nuestro grupo de recursos a la cual se le va asignar la directiva, después colocamos la definición de la directiva y para el ejemplo colocamos que solamente se puedan crear los recursos en ciertas ubicaciones permitidas y elegimos esta definición de las muchas que tiene Azure.

![Imagen 5](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P10.png)
------------------------------------------------------------------------------------------------------
### Paso 6:
Paso a la siguiente pestaña Parámetros en donde podemos elegir nada más en donde se pueden crear los recursos y para este caso solo elegimos que se puedan crear nada más en Estados Unidos.

![Imagen 6](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P11.png)
------------------------------------------------------------------------------------------------------
### Paso 7:
También asignamos un mensaje por si se incumpla con la directiva y ya por últimos la revisamos y creamos, esto normalmente se tardan entre 5 y 10 minutos en crearse. 

![Imagen 7](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P12.png)
![Imagen 7.1](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P13.png)
------------------------------------------------------------------------------------------------------
### Paso 8:
Creamos una nueva Máquina Virtual

![Imagen 8](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P16.png)
------------------------------------------------------------------------------------------------------
### Paso 9:
Cremo otro recurso llamado Microsoft Sentinel y dentro de ahí elegimos el área de trabajo, si no tenemos un área de trabajo creamos una nueva área de trabajo de Log Analytics solo agregando los datos que nos pida, una vez creada la agregamos y entramos nos sale una ventana como la de la segunda imagen.

![Imagen 9](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P14.png)
![Imagen 9.1](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P15.png)
------------------------------------------------------------------------------------------------------
### Paso 10:
Dentro de aquí podemos conectar nuestros orígenes de datos Maquina Virtuales, AWS, GCP, entre otros. Para este ejemplo no conectamos a la actividad de Azure y de aquí nos vamos a abrir la página del conector y nos abre una ventana como se muestra en la imagen dos en donde solo tenemos que los pasos que nos dicen la misma página para conectarnos 

![Imagen 10](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P17.png)
![Imagen 10.1](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P18.png)
------------------------------------------------------------------------------------------------------
### Paso 11:
Como vamos a seguir los pasos solo es cuestión de oprimir el botón de Asistente para configuraciones de Azure Policy, y nos abre una nueva ventana y de ahí llenamos todos los campos que nos pida por ejemplo el ámbito en esta caso elegimos en donde queremos que se aplique para el caso lo elegimos que se aplique en toda nuestra suscripción e igual elegimos que parámetros el cual es el área de trabajo de Log Analytics que creamos anteriormente y solo faltaría revisarla y crearla para ver si todo está correcto y marcha de la misma manera.

![Imagen 11](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P19.png)
![Imagen 11](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P20.png)
------------------------------------------------------------------------------------------------------
### Paso 12:
Una vez creada podemos ver los registros y la actividad de Azure como se muestra a continuación y también podemos ver el Log Analytics como se muestra en la segunda imagen.

![Imagen 12](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P21.png)
![Imagen 12.1](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P22.png)
------------------------------------------------------------------------------------------------------
### Paso 13:
Vamos a Azure Sentinel y de ahí nos movemos a los libros (que son las plantillas de consulta asia Log Analytics) del mismo en donde se recaba toda la información de nuestros recursos y también podemos guardar y crear nuestros propios libros.

![Imagen 13](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P23.png)
------------------------------------------------------------------------------------------------------
### Paso 14:
Nos vamos a Microsoft Defender for Cloud y una vez dentro de ahí nos dirigimos a Protección de Cargas de Trabajo para activar el Just-In-Time para ello primero tenemos que irnos a el recurso de nuestra máquina virtual y le damos conectar por RDP

![Imagen 14](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P24.png)
------------------------------------------------------------------------------------------------------
### Paso 15:
Una vez seleccionado conectado por RDP nos sale un mensaje como el que a continuación se muestra solo es cuestión de dar clic en él y habilitarlo el Just-In-Time

![Imagen 15](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P25.png)
![Imagen 15](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P26.png)
------------------------------------------------------------------------------------------------------
### Paso 16:
Una vez activado volvemos a entrar a entrar a Microsoft Defender for Cloud y podemos notar que nuestra maquina ya se encuentra activa.

![Imagen 16](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P27.png)
------------------------------------------------------------------------------------------------------
### Paso 17:
Solicitamos el acceso 

![Imagen 17](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P28.png)
------------------------------------------------------------------------------------------------------
### Paso 18:
Una vez solicitado el acceso podemos activarlos y desactivarlo así también como las direcciones IP permitidas y el tiempo que este puede estar dentro de la máquina siendo una hora como mínimo y 3 como máximo.

![Imagen 18](https://github.com/aldodanielle/Prac3_Microsoft_Defender_for_Cloud/blob/main/Imgenes/P29.png)
------------------------------------------------------------------------------------------------------
