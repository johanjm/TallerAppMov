# Dibujar Rectángulos
Para implementar una aplicación con fondo blanco y con la opción de graficar triángulos se lo realiza mediante Android Studio, herramienta por el cual alvergará el desarrollo de la misma. A continuación, se muestra los pasos que fueron implementados y la manera en la que se verá desarrollado.

**1. Creación de Proyecto**
   - Al momento en el que se crea un nuevo proyecto se comenzará a editar el archivo *MainActivity.kt*, debido a que en este archivo poseerá el desarrollo de la aplicación
**2. Codificación del proyecto**
   - Como se mencionó en el apartado anterior, el contenido principal que se presentará en pantalla se verá como se indica a continuación, en donde la clase con nombre *Lienzo* tendrá como valores pirncipales el ancho y el pincel, este ultimo será el encargado de realizar el trazado de la figura.
     - ![imagen](https://user-images.githubusercontent.com/66731201/222044058-6dfbc3a9-9de5-45eb-931d-1910d3c59937.png)
   - Además de obtener el ancho del dispositivo en el que se esté instalando, se tendrá el color rojo que característico(255,255,0,0)

**3. Dibujar Rectángulo**
   - La siguiente porción de código se encarga de dibujar el rectángulo desde la columna 10 y fila 10 (ambas siendo coordenadas para el trazado del rectángulo). De la misma manera que estará coincidiendo con el ancho de la pantalla en la fila 40 y restando 10 pixeles del dispositivo.
     -![imagen](https://user-images.githubusercontent.com/66731201/222044745-545616b7-ff51-43c9-8a97-c8e398b56985.png)
     
**4. Otros Rectángulos**
   - Así como ya se declararon las coordenadas de trazado de los rectángulos, entonces se lo hará unas 2 veces más:
     - ![imagen](https://user-images.githubusercontent.com/66731201/222045057-41e49ace-4925-485a-a5c7-cc20113e43ee.png)

**5. Vista**
   - Finalmente se muestra en pantalla de un dispositivo Samsung su correcto trazado de rectángulos
     - Creación de aplicación Android
       - ![imagen](https://user-images.githubusercontent.com/66731201/222046403-fda824b2-736f-4688-b889-2fa692de654f.png)

     - Aplicación Android desplegada
       - ![imagen](https://user-images.githubusercontent.com/66731201/222046491-8882873d-3750-4b94-8cec-f3bf77ee9109.png)
 
