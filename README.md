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


