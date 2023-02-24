# Ejercicio 12
Confeccionar un programa que solicite el ingrese de una dirección de un sitio web y seguidamente abrir una segunda ventana que muestre dicha página.

# Desarrollo

1.- En el archivo MainActivity asignamos dos parámetros de tipo String, en el primero indicamos el nombre del dato y en el segundo el valor del dato:

![image](https://user-images.githubusercontent.com/38448479/221083891-d80b4d81-df97-4055-bc00-947d658e0435.png)

2.- Creamos otra clase denominada Actividad2 en esta definimos una variable de tipo Bundle y la inicializamos llamando al método getExtras() de la clase Intent (esto lo hacemos para recuperar el o los parámetros que envió la otra actividad (Activity)):

![image](https://user-images.githubusercontent.com/38448479/221084087-f9d860ab-7677-4bcd-acc1-40cfe9dba12d.png)

5.- Posterior creamos dos interfaces en la primera se encuentra un EditText donde se ingresara la url y un Button que al precionar nos redirecciona a la página.

![image](https://user-images.githubusercontent.com/38448479/221084493-3e1c9dcc-b7b5-441a-9dbe-bbea65bfffd6.png)

6.- Y en la otra interaz agregamos un WebView para vizualizar ahi la pagina y tambien un Button para finalizar la vista.

![image](https://user-images.githubusercontent.com/38448479/221084635-2bc1d6cf-6264-4f61-b59d-1aa0a3099d1d.png)

7.- Por utlimo se vizualiza los resultados

![image](https://user-images.githubusercontent.com/38448479/221084672-ff8d91dc-adb0-4ee3-8ca4-56c5db820369.png)

![image](https://user-images.githubusercontent.com/38448479/221084688-9c346a18-8db7-4261-a267-a922af9d20f5.png)



