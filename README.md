#  EJERCICIO-46
##  Componente ActionBar (Ocultarlo y mostrarlo)

## Instalación

1. Clona el repositorio en tu máquina local
2. Abre el proyecto en Android Studio
3. Ejecuta el proyecto en un emulador o dispositivo Android conectado

## Uso

1. Abre la aplicación en tu dispositivo Android
2. Se debe seleccionar las opciones presentadas en la pantalla
3. Selecciona la mostrar o ocultar
4. De igual manera se pude escojer otras opciones en la parte de menú de los tres puntos

Este proyecto consiste en crear un componente de ActionBar que se puede ocultar y mostrar, y que utiliza la internacionalización y el archivo string.xml. La estructura del proyecto se muestra a continuación:

![image](https://user-images.githubusercontent.com/74844624/221084195-497d9efb-af17-43f1-bcb9-3bd70218a7d2.png)

### Pasos para crear la aplicación:

1. Crear el método `onOptionsItemSelected` en el archivo `MainActivity.java`. Este método se encargará de manejar la selección de opciones del menú. Puede utilizar el siguiente código como punto de partida:

```js
@Override
public boolean onOptionsItemSelected(MenuItem item) {
    int id = item.getItemId();
    if (id==R.id.opcion1) {
        Toast.makeText(this,"Se seleccionó la primer opción",Toast.LENGTH_LONG).show();
    }
    if (id==R.id.opcion2) {
        Toast.makeText(this,"Se seleccionó la segunda opción",Toast.LENGTH_LONG).show();
    }
    if (id==R.id.opcion3) {
        Toast.makeText(this,"Se seleccionó la tercer opción", Toast.LENGTH_LONG).show();
    }
    return super.onOptionsItemSelected(item);
}
```

2. Crear el archivo de diseño del ActionBar.

![image](https://user-images.githubusercontent.com/74844624/221084924-afa89aa4-5d3d-4586-9267-1b94031089b8.png)

3. Crear el archivo de menú con las opciones que se deseen.

![image](https://user-images.githubusercontent.com/74844624/221089467-525bdd6b-4ea9-42c2-967d-6e4614a42ec7.png)

4. Ejecutar la aplicación en un emulador o dispositivo físico para ver el ActionBar en acción:

![image](https://user-images.githubusercontent.com/74844624/221089397-57be9ba4-a3e7-4cc2-9044-a8ccaea8da31.png)

¡Y eso es todo! Finalmente con los pasos anteriores se debería tener éxito en la creación de una aplicación con un ActionBar que se puede ocultar y mostrar.
