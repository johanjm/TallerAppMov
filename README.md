#  EJERCICIO-46
##  Componente ActionBar (Ocultarlo y mostrarlo)

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

![image](https://user-images.githubusercontent.com/74844624/221085072-4923afa6-4808-4d63-bc10-b4e7de3d905a.png)

4. Ejecutar la aplicación en un emulador o dispositivo físico para ver el ActionBar en acción:

![image](https://user-images.githubusercontent.com/74844624/221083780-9c9faa2a-befe-4174-8d29-bc1539c1bd19.png)

¡Y eso es todo! Finalmente con los pasos anteriores se debería tener éxito en la creación de una aplicación con un ActionBar que se puede ocultar y mostrar, y que utiliza la internacionalización y el archivo string.xml.
