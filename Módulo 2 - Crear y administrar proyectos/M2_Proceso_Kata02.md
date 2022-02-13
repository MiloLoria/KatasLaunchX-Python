# Ejercicio - Crear un paquete


## Crear un entorno virtual

 Ejecutar en su terminal: ``python3 -m venv LaunchX-env``

 ![](../imagesresult/m2-k2-1.png)

 Se activa el entorno virtual: ``Launchx-env\Scripts\activate``

  ![](../imagesresult/m2-k2-2.png)

 Se ejecuta el comando ``pip freeze`` para ver las bibliotecas instaladas en tu entorno: (Se devuelve vacio ya que no se encuentra bibliotecas instaladas)
 
![](../imagesresult/m2-k2-3.png)

Se instala la bilioteca python-dateutil con el comando: ``pip install python-dateutil``

![](../imagesresult/m2-k2-4.png)

 Se ejecuta nuevamente el comando ``pip freeze`` para ver las bibliotecas instaladas en tu entorno: (Retorna las bibliotecas instaladas en este caso observamos la biliote de ``python-dateutil``)

![](../imagesresult/m2-k2-5.png)

Ejecuta el comando ``deactivate`` (Observa cómo cambia el mensaje de tu terminal ``(Launchx-env)`` a cómo se veía antes. ):

![](../imagesresult/m2-k2-6.png)
