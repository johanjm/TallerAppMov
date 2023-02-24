# EJERCICIO-42: Internacionalización y archivo strings.xml

Este proyecto consiste en una calculadora básica que permite realizar operaciones de suma y resta. El objetivo principal es aprender cómo utilizar la internacionalización y el archivo strings.xml para mejorar la accesibilidad de la aplicación.

## Instalación

1. Clona el repositorio en tu máquina local
2. Abre el proyecto en Android Studio
3. Ejecuta el proyecto en un emulador o dispositivo Android conectado

## Uso

1. Abre la aplicación en tu dispositivo Android
2. Ingresa dos números en los campos de texto
3. Selecciona la operación que deseas realizar (suma o resta) presionando el botón correspondiente
4. El resultado de la operación se mostrará en el campo de texto de la parte inferior de la pantalla

## Internacionalización y archivo strings.xml

La internacionalización es el proceso de adaptar una aplicación para que pueda funcionar en diferentes idiomas y regiones. Esto incluye la traducción del texto en la aplicación, así como el uso de diferentes formatos de fecha, hora, moneda y otros elementos culturales.

En Android, la internacionalización se logra a través del archivo strings.xml. Este archivo contiene todos los textos que se utilizan en la aplicación y se almacena en diferentes carpetas de valores para cada idioma o región.

En este proyecto, se ha utilizado el archivo strings.xml para traducir los textos de la aplicación al español e inglés. Además, se han utilizado los recursos de la cadena para mejorar la accesibilidad de la aplicación.

## Código

El siguiente código muestra cómo se han implementado las operaciones de suma y resta en la aplicación:

```java
public void operar(View v)
{
    String valor1 = et1.getText().toString();
    String valor2 = et2.getText().toString();
    int nro1 = Integer.parseInt(valor1);
    int nro2 = Integer.parseInt(valor2);
    
    if (r1.isChecked() == true) {
        int suma = nro1 + nro2;
        String resu = String.valueOf(suma);
        tv1.setText(resu);
    } else if (r2.isChecked() == true) {
        int resta = nro1 - nro2;
        String resu = String.valueOf(resta);
        tv1.setText(resu);
    }
}
```
## Interfaz de usuario

La interfaz de usuario de la aplicación consta de dos campos de texto para ingresar los números y dos botones de radio para seleccionar la operación. El resultado de la operación se muestra en un campo de texto en la parte inferior de la pantalla.

![image](https://user-images.githubusercontent.com/74844624/221088589-5c62e20c-6a46-45f2-a0d8-a8a0cf25a7e2.png)

Después de ingresar los números y seleccionar la operación, el resultado de la operación se mostrará en el campo de texto inferior.

![image](https://user-images.githubusercontent.com/74844624/221088838-b9de7d2f-8b42-47c2-9c10-5d9057264434.png)

## Conclusión
En este proyecto se ha utilizado el archivo strings.xml para mejorar la accesibilidad de la aplicación y permitir su uso en diferentes idiomas y regiones. También se ha implementado la funcionalidad de suma y resta en la aplicación de manera eficiente y sencilla.
