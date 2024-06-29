### Componentes del flujo de GitHub
En esta unidad, se revisarán los siguientes componentes del flujo de GitHub:

1. Ramas / Branch
2. Confirmaciones / Commit
3. Solicitudes de incorporación de cambios / Pull Request
4. El flujo de GitHub

## Qué son las ramas
En la última sección, hemos creado un nuevo archivo y una nueva rama en los repositorios.

Las ramas son una parte esencial de la experiencia de GitHub porque en ellas es donde podemos realizar cambios sin que afecten a todo el proyecto en el que estamos trabajando.

La rama es un lugar seguro para experimentar con nuevas características o correcciones. Si comete un error, puede revertir sus cambios o insertar más cambios para subsanarlo. Los cambios no se actualizarán en la rama predeterminada hasta que combine la rama.

> Nota
> Como alternativa, puede crear una nueva rama y extraerla del repositorio simplemente usando Git en un terminal; el comando sería git checkout -b newBranchName.

## ¿Qué son las confirmaciones?
Como puede que haya observado en la unidad anterior, al agregar un nuevo archivo al repositorio, es necesario insertar una confirmación.

Revisemos brevemente qué son las confirmaciones.

Una confirmación es un cambio en uno o varios archivos de una rama. Cada vez que se crea una confirmación, se le asigna un identificador único y se realiza un seguimiento de ella, junto con la hora y el colaborador. Las confirmaciones proporcionan un registro de auditoría claro para todas las personas que revisen el historial de un archivo o un elemento vinculado, como una incidencia o una solicitud de incorporación de cambios.

![image](https://github.com/Charlybio87/hello-mundo/assets/142097962/e1ff09f2-3c8b-49ad-a1d8-9ebd469a25aa)

Dentro de un repositorio de Git, un archivo puede existir en varios estados válidos durante su paso por el proceso de control de versiones:

Los estados principales de un archivo en un repositorio Git son:

Sin seguimiento: estado inicial de un archivo cuando aún no forma parte del repositorio de Git. Git desconoce su existencia.

Con seguimiento: un archivo con seguimiento es aquel que Git supervisa activamente. Puede estar en uno de los siguientes subestados:

Sin modificar: se realiza un seguimiento del archivo, pero no se ha modificado desde la última confirmación.
Modificado: el archivo se ha cambiado desde la última confirmación, pero estos cambios aún no están almacenados provisionalmente para la siguiente confirmación.
Almacenado provisionalmente: el archivo se ha modificado y los cambios se han agregado al área de almacenamiento provisional (también conocida como índice). Estos cambios están listos para confirmarse.
Confirmado: el archivo se encuentra en la base de datos del repositorio. Representa la versión confirmada más reciente del archivo.
Estos estados y subestados son importantes para colaborar con el equipo y saber dónde se encuentra cada confirmación en el proceso del proyecto.

## Ahora vamos a pasar a las solicitudes de incorporación de cambios.

¿Qué son las solicitudes de incorporación de cambios?
Ahora que sabemos qué es una confirmación, revisemos las solicitudes de incorporación de cambios.

Una solicitud de incorporación de cambios es un mecanismo que sirve para indicar que las confirmaciones de una rama están listas para combinarse en otra.

El miembro del equipo que envía la solicitud de incorporación de cambios normalmente solicita a uno o varios revisores que comprueben el código y aprueben la combinación. Estos revisores podrán comentar los cambios, agregar otros o usar la solicitud de incorporación de cambios para realizar un análisis más exhaustivo.

Una vez que los cambios se han aprobado (si es que necesitan aprobación), la rama de origen de la solicitud de incorporación de cambios (la rama de comparación) se combina con la rama base.

![image](https://github.com/Charlybio87/hello-mundo/assets/142097962/154e1252-f8fd-42c8-9146-380d57decfcd)

Ahora que conocemos todos los ingredientes, revisemos el flujo de GitHub.

## El flujo de GitHub

![image](https://github.com/Charlybio87/hello-mundo/assets/142097962/74e6ac44-120a-493f-9756-3c6024d25c68)

El flujo de GitHub se puede definir como un flujo de trabajo ligero que permite experimentar de forma segura. Puede probar nuevas ideas y colaboraciones con su equipo mediante ramas, solicitudes de incorporación de cambios y combinaciones.

Ahora que conocemos los conceptos básicos de GitHub, podemos recorrer el flujo de GitHub y sus componentes.

El primer paso del flujo de GitHub consiste en crear una rama para que los cambios, características y correcciones que cree no afecten a la rama principal.
El segundo paso es realizar los cambios. Se recomienda implementar cambios en la rama de características antes de combinarlos en la rama principal. De esta forma, se tiene la seguridad de que los cambios son válidos en un entorno de producción.
El tercer paso consiste en crear una solicitud de incorporación de cambios para pedir comentarios a los colaboradores. La revisión de solicitude sde cambios es tan valiosa que algunos repositorios requieren una revisión aprobatoria antes de que estas se puedan fusionar.
A continuación, el cuarto paso consiste en revisar e implementar los comentarios de los colaboradores.
Una vez que se sienta a gusto con los cambios, el quinto paso es aprobar la solicitud de incorporación de cambios y combinarla en la rama principal.
El sexto y último paso es eliminar la rama. Al eliminar la rama se indica que el trabajo en la rama se ha completado y se evita que usted u otros usuarios empleen accidentalmente ramas antiguas.
Y eso es todo, acaba de recorrer el ciclo de un flujo de GitHub.

Vamos a pasar a la siguiente sección donde trataremos las diferencias entre incidencias y discusiones.

------
