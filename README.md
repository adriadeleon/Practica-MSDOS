# **Practica MS-DOS**
___
### **Introducción a la Práctica de MS-DOS**
___

- ¿Qué es MS-DOS?

<br> MS-DOS son las siglas de **MicroSoft Disk Operating System (Sistema Operativo de Disco de MicroSoft)** y es el nombre de uno de los sistemas operativos para sistemas informáticos basados en una arquitectura x86 y diseñados por la empresa norteamericana de software Microsoft. **Se le conocía popularmente como DOS.**

<br> Existían dos series de comandos del **MS-DOS**: internos y externos. Los primeros, llamados también residentes, se cargaban automáticamente al inicio del sistema operativo del computador, a partir de un archivo almacenado de nombre command.com; por eso era posible activarlos sin tener el DOS entero en la unidad desde la cual se ejecutan.

___

### **Ejercicio 1**
___

1. El primer paso es crear la siguiente estructura de carpetas dentro de una carpeta raíz. (En mi caso he decidido crear un propia carpeta raíz para no modificar ninguna otra)

![image](https://user-images.githubusercontent.com/98842240/160415251-70d23087-fb2d-4394-be51-e59461e581c6.png)

<br> Como vemos en la siguiente imagen, he creado la estructura con el siguiente comando: "**mkdir** *nombre de la nueva carpeta*".

![image](https://user-images.githubusercontent.com/98842240/160417077-9d90fbff-5f97-458d-8b81-aa18694314fa.png)

- NOTA: Para crear más de una carpeta en un directorio, podemos utilizar el comando "**mkdir** *nombre de la nueva carpeta* + *nombre de otra nueva carpeta*".
___
2. Una vez creada la estructura de carpetas debemos acceder con el comando "cd *nombre de directorio*" a la carpeta llamada **TABLAS**

Podemos acceder con el comando que hemos especificado con anterioridad, el comando "**cd**".

![image](https://user-images.githubusercontent.com/98842240/160418629-8c0a499f-1572-4745-bc75-e3701ac36dea.png)

Podemos ver que hemos accedido a la carpeta **TABLAS**.
___
3. Ahora debemos acceder a la carpeta raíz del ordenador, este ccomando es más fácil de lo que parece. Debemos ejecutar el comando "**cd /**".

![image](https://user-images.githubusercontent.com/98842240/160419548-1b5afa6a-97f3-4c56-846d-31a13d080631.png)

Si observamos, veremos que hemos accedido a la carpeta raíz del ordenador.
___
4. El cuarto paso es visualizar el contenido de la carpeta **PROG**, para esto debemos ejecutar el siguiente comando: "**dir *ruta del directorio***".

![image](https://user-images.githubusercontent.com/98842240/160420679-09fae9c5-d3bc-45e2-ada3-cdafe299c9b3.png)

Veremos que por pantalla se nos imprime el contenido del directorio **PROG**.
___
5. Para este punto debemos borrar la carpeta **PASCAL** para borrarla lo haremos con un comando "**rmdir** *nombre del directorio*".

![image](https://user-images.githubusercontent.com/98842240/160432745-ffb90e4c-1bee-4fbf-b596-8e7c191bddbc.png)

Si queremos comprobar los pasos que vamos haciendo al crear o eliminar un directorio, lo podemos ir visualizando con el comando "**dir**".
___
6. Sitúate en la carpeta **VARIOS** y desde allí crea una nueva carpeta dentro de **WORD** llamado **PRACT**.

Para este ejercicio debemos ir a la carpeta **VARIOS** y ejecutar el comando "**mkdir** *nombre del archivo* + *ruta final*".
<br>
![image](https://user-images.githubusercontent.com/98842240/160435111-983a9045-31e6-463c-848d-7828148f4722.png)

Al final de la imagen podemos observar que he realizado un **dir** para poder visualizar que el trabajo se ha realizado con exito.
___
7. Para este paso debemos situarnos en **PRACT** y desde allí mostrar el contenido de la carpeta **EXCEL**, para ello utilizaremos el comando **dir**.

Al ejecutarlo podemos ver el contenido de la carpeta que hemos seleccionado, hay varias formas de ejecutar el comando, podemos ejecutarlo trambién para poder ver el contenido de sus subcarpetas.
<br>
![image](https://user-images.githubusercontent.com/98842240/160451110-581912ce-65ca-48fc-99c3-a00e06437189.png)

___
8. Desde el directorio **TABLAS** muestra el listado de archivos y directorios del directio raíz.

![image](https://user-images.githubusercontent.com/98842240/160455722-d8f0173f-7ce4-47d5-803c-c9dc3edcc89f.png)

- NOTA: también podemos visualizarlo con el comando "**tree** *ruta*" y veriamos la estructura de la ruta especificada.
___
9. Sitúate en la carpeta APLI y desde allí crea una subcarpeta llamada AGENDA dentro de **VARIOS**

![image](https://user-images.githubusercontent.com/98842240/160636915-1cf453bd-07fb-487b-a444-e8bead29702e.png)

Podemos ver que lo creamos con el comando "**mkdir** *ruta donde lo queremos*".
___

10. Borrar la carpeta **EXCEL**.

Para ello debemos borrar el directorio con el comando **rmdir**.

![image](https://user-images.githubusercontent.com/98842240/160637652-407ac6d6-56fc-4f11-be29-faa2fc69399e.png)

___
11. Desde la carpeta raíz debemos crear una carpeta nueva que se llame **NUEVO**.

Con el comando **mkdir** *ruta donde la queremos crear**.

![image](https://user-images.githubusercontent.com/98842240/160639075-247bc784-73b3-4bae-a049-cee10cbf9d9c.png)

___
12. Desde **PRACT** muestra el contenido de **WORD**.

Con el comando "**dir** *ruta donde queremos ver*"

![image](https://user-images.githubusercontent.com/98842240/160641779-2acd1021-1dfc-404b-b98f-49420956b2b8.png)

___

### **Ejericio 2**
___
1. Utilizando el editor de textos de MS-DOS, crea un archivo de texto denominado EJER.TXT, con el siguiente contenido, y almacénalo dentro de la carpeta TEXTOS (dentro de la estructura del ejercicio anterior)

Podemos ver en la imagen el comando utilizado "**copy con** *nombre.txt*".

![image](https://user-images.githubusercontent.com/98842240/160646162-1fc8493a-6acc-4844-b576-176f24f6454e.png)

___
2. Copiar el archivo *.txt* anterior en la carpeta **AGENDA**.

![image](https://user-images.githubusercontent.com/98842240/160659064-04915292-0a7e-4729-8678-b9f31b52f48c.png)

Para copiarlo usaremos el comando "**copy**".
___
3. Borrar el archivo almacenado en la carpeta **TEXTOS**.

Lo haremos con el comando "**del /F /A**".

![image](https://user-images.githubusercontent.com/98842240/160659563-1358765a-78da-4633-ac67-b9e4acdfc056.png)

![image](https://user-images.githubusercontent.com/98842240/160659613-56a538ef-cfdd-422a-bc89-24d01c0c2dd8.png)
___
4. Añade texto en el archivo *.txt* creado con anterioridad.

Lo haremos con el comando "**notepad**"

![image](https://user-images.githubusercontent.com/98842240/160661917-dcddaae9-dd1d-4009-bd69-613798d19ecb.png)

![image](https://user-images.githubusercontent.com/98842240/160661858-e304726f-dbbe-46df-a3fd-511ec1b8dd7a.png)
___
5. Copiamos el archivo *.txt* a la carpeta **BASIC**.

Lo haremos con el comando **COPY**.

![image](https://user-images.githubusercontent.com/98842240/160662656-1c2ef3bf-23f7-4e29-8a09-f991180a6879.png)

___
6. Cambiar el nombre del archivo de la carpeta *.txt* por *FICHERO.txt*.

Para ello usaremos el comando **rename** para poder ponerle un nuevo nombre al archivo.

![image](https://user-images.githubusercontent.com/98842240/160663379-b8d2d83c-3469-43f7-b79b-28d6dd5be4a3.png)

___
7. Mover el archivo *FICHERO.txt* a la carpeta **BASIC**.

Lo realizaremos con el comando **move**.

![image](https://user-images.githubusercontent.com/98842240/160663622-75a20227-d074-41c4-91dc-74dfa7ca3750.png)

___
8. Abrir el archivo *EJER.txt* y borrar la primera frase.

Eso lo haremos con el comando **notepad**.

![image](https://user-images.githubusercontent.com/98842240/160663802-d9a72015-ae3c-49f3-9f1f-e1e3d8b72cae.png)

___
9. Copia el archivo *NUEVO.txt* en la carpeta **NOTAS**.

Con el comando **copy**.

![image](https://user-images.githubusercontent.com/98842240/160664032-65bcad3d-5560-4052-a410-0b1b286afb50.png)

___
10. ¿Cuántos archivos hay en la carpeta **BASIC**? ¿Y en **NOTAS**?

- NOTAS
![image](https://user-images.githubusercontent.com/98842240/160664173-0491a179-77b4-406e-bb11-f19366732d8d.png)

- BASIC

![image](https://user-images.githubusercontent.com/98842240/160664300-b5402eb1-d820-4319-b902-8bc9a041a529.png)

___
- Ejercicio 3
___
1. Borra la **ACCESS** y en su lugar crea una nueva carpeta llamada **ASTRO**.

![image](https://user-images.githubusercontent.com/98842240/160807123-1f47cd3c-99f3-4835-a426-78132f456d2a.png)

La acción la completaremos con el comando **rmdir** *nombre de la carpeta*.
___
2. Crea la siguiente estructura de directorios y subdirectorios dentro de la carpeta **ASTRO**.

![image](https://user-images.githubusercontent.com/98842240/160807498-d1ec129f-b449-41b5-9414-811b743569fa.png)

![image](https://user-images.githubusercontent.com/98842240/160807558-f80fd520-73fa-4d6b-802f-ac9af97f2178.png)

___
3. Sitúate en la carpeta **CIENCIA** y desde allí muestra el listado de archivos y su carpeta **HISTORIA**.

![image](https://user-images.githubusercontent.com/98842240/160808033-45a59638-2f59-4189-a47c-03a60d11fb94.png)

- NOTA: con un **dir -r** la extensión el *-r* significa *recursividad*, es decir, que imprimirá por pantalla la carpeta y sus subcarpetas.

___
4. Utilizando el editor de MS-DOS crea el siguiente archivo de texto y guárdalo con el nombre *TYCHO.txt* dentro de la carpeta **DATOS1**.

![image](https://user-images.githubusercontent.com/98842240/160811082-fe2b6842-e60f-4b62-97cb-74dad1ddc9c9.png)

Usaremos el comando **notepad** para poder crear el archivo *.txt*.
___
5. Utilizando de nuevo el editor de textos de MS-DOS crea el siguiente archivo de texto, y guárdalo con el nombre *KEPLER.TXT* dentro de la carpeta **DATOS2**.

![image](https://user-images.githubusercontent.com/98842240/160811661-295dc44b-f22f-4d75-945a-005804f66ef2.png)

___
6.  Copia los archivos *TYCHO.TXT* y *KEPLER.TXT* en la carpeta **CIENCIA**.

![image](https://user-images.githubusercontent.com/98842240/160812032-174a29e7-a52b-4616-baf3-120220f1e5ea.png)

Esto lo haremos con el comando **copy**.
___
7. Cambia de lugar los archivos almacenados en **DATOS1** y **DATOS2** de forma que *TYCHO.TXT* quede guardado dentro **DATOS2** y *KEPLER.TXT* en **DATOS1**.

![image](https://user-images.githubusercontent.com/98842240/160812425-7522822d-6661-4164-8364-6918df14f8eb.png)

___
8. Crea un nuevo archivo formado por la unión de los dos anteriores (sin volver a escribir el texto) y guárdalo dentro de la carpeta **HISTORIA** con el nombre *TOTAL.TXT*.

![image](https://user-images.githubusercontent.com/98842240/160812635-27925e68-dfc1-4eb1-9531-ba8c5e718b83.png)

- NOTA: Cuando escribimos *.txt* significa que cogemos todos los archivos de esa extensión.
___
9. Abre el archivo KEPLER.TXT almacenado en la carpeta **CIENCIA** y añade el siguiente texto:

  *“Kepler aplicó sus teorías a los satélites de Júpiter, descubiertos por
Galileo a través de un pequeño telescopio, cuya introducción en la
observación astronómica constituye uno de los hitos de la astronomía.”*

Esta acción la realizaremos con el comando **notepad** *nombre del archivo*.
___
- Ejercicio 4
___
1. Crea en la carpeta raíz de la unidad A: una carpeta denominada **TECINFO**.

![image](https://user-images.githubusercontent.com/98842240/160814151-fbd3a942-cabc-4b5e-9781-bd617844f30f.png)

___
2. Crea dentro de **TECINFO** el siguiente archivo de texto y llámalo *HARD.TXT*.

*"El HARDWARE está constituido por los elementos físicos del ordenador.
Consta esencialmente de componentes electrónicos que proporcionan el
soporte necesario para la interpretación y ejecución de las operaciones
elementales que realiza el ordenador"*

3. Y crearemos otro archivo llamado *SOFT.txt*.

*"El SOFTWARE es el conjunto de elementos lógicos necesarios para que el
ordenador realice las funciones que se le encomiendan. Está formado por
los programas, es decir, por un conjunto ordenado de instrucciones,
comprensibles por la máquina, que permiten desarrollar tareas concretas"*

![image](https://user-images.githubusercontent.com/98842240/160851597-59defc1e-0ce0-43a9-9353-9dda0d3713b4.png)

Los crearemos con el comando *notepad*.

___
4. Mueve el contenido de **TECINFO** a la carpeta **APLI** del disquete A utilizado para realizar los ejercicios anteriores


![image](https://user-images.githubusercontent.com/98842240/160860444-9e93bda6-688a-40dd-914c-8fa9de159dbc.png)

Lo realizaremos con el comando **move** ***.txt** *ruta del directorio donde queremos moverlo todo*.
___
6. Eliminar la carpeta **TECINFO**.

Para ello debemos eliminarlo con el comando **rmdir** *ruta del directorio o nombre de este*.

![image](https://user-images.githubusercontent.com/98842240/160861942-87ddfabe-22e3-49c1-8066-593df104182a.png)

___
7.  Copia a la vez los archivos *HARD.TXT* y *SOFT.TXT* en la carpeta **VARIOS**.

Este punto será ejecutado con el comando **copy** *nombre de los archivos separados por un espacio* + *ruta donde queremos copiarlos*.
___
8. Cambia la extensión de los archivos contenidos en **AGENDA** por *.TYP*.

![image](https://user-images.githubusercontent.com/98842240/160863340-8d4a2d2e-3b77-46f4-8912-55d486a30e23.png)

Para ello debemos utilizar el comando **ren** y darle una nueva extensión al archivo.
___
9. Cambia la primera letra del nombre de todos los archivos del directorio **APLI** que empiecen por la letra C y tengan extensión DOC de forma que empiecen con la letra S

![image](https://user-images.githubusercontent.com/98842240/160863775-af1bec95-468c-4e4f-8460-0cd0fefa063a.png)

___
10. Copia los archivos contenidos en la carpeta **APLI** que tengan extensión DOC en la carpeta **AGENDA**.

Utilizaremos el comando **copy**.

![image](https://user-images.githubusercontent.com/98842240/160864284-744f47e7-7d56-4fee-ae16-dfad5c821b92.png)

___
### **Final del trabajo de MS-DOS**




