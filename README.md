# CamaraJavascriptHTML5
Existen varias maneras de lograr capturar una imagen con JavaScript, en este caso mostraré solo una de ellas y para mí sin duda una de las mejores debido a la calidad de la imagen. 

Para ello necesitaremos usar un recurso llamado "MediaDevices" el cual nos proporciona a los dispositivos de entrada (micrófono, video y compartir pantalla) y con estos recursos podemos usar y mediante estados (iniciar, pausar, detener) podremos manipular dicho recurso de estos dispositivos integrados en el celular y web.

El flujo constará de la siguiente manera: cargamos la interfaz MediaDevices, indicando el tamaño mínimo y máximo a capturar de la resolución, seguidamente una vez iniciado la grabación de video, al capturar con un botón, ese instante capturado lo guardaremos en una etiqueta canva, luego obtenemos el dato "base64" de esa etiqueta canva y lo almacenamos en una imagen.
