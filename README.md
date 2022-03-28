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
9. 
