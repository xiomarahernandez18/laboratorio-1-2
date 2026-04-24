ESTUDIANTE: CARMEN XIOMARA HERNANDEZ CASTILLO 
CODIGO SMSS107724


SISTEMA DE REGISTRO DE ESTUDIANTES PARA TUTORIAS 

SITUACION PROBLEMATICA 
 
En muchos institutos y academias de la zona, el registro de estudiantes para tutorías se realiza de forma manual, lo que genera desorden, pérdida de información y dificultad para llevar control de asistencia.

Este problema afecta al sector educativo, especialmente a centros de estudio que no cuentan con sistemas digitales.

 SOLUCION DE PROBLEMA 

Se desarrolló una aplicación web con Vue.js que permite:

Registrar estudiantes en tutorías
Validar los datos ingresados
Mostrar una lista organizada de estudiantes
Marcar asistencia y eliminar registros

Esto mejora la organización y reduce errores humanos.

PREGUNTAS 

. ¿Qué es Vue.js y cuál es su función en la página web?

Vue.js es un framework de JavaScript que se utiliza para crear interfaces web dinámicas e interactivas. En este proyecto su función principal es permitir que los datos que el usuario ingresa se reflejen automáticamente en la pantalla sin necesidad de recargar la página. Gracias a Vue, la aplicación puede actualizar la lista de estudiantes en tiempo real y manejar la interacción del usuario de manera sencilla.

. Variables reactivas utilizadas y su función

En la aplicación se utilizaron las siguientes variables reactivas:

nombre: almacena el nombre del estudiante ingresado en el input.
edad: guarda la edad del estudiante.
materia: almacena la materia seleccionada en el menú desplegable.
estudiantes: es un arreglo donde se guardan todos los estudiantes registrados.
error: se utiliza para mostrar mensajes cuando hay datos incorrectos o incompletos.

Estas variables son importantes porque Vue las actualiza automáticamente en la interfaz cuando cambian.

. Diferencia entre v-bind y v-model

La directiva v-model se utiliza para enlazar los datos de los inputs con las variables del sistema, permitiendo que lo que el usuario escribe se guarde automáticamente.

Por otro lado, v-bind se usa para asignar valores dinámicos a atributos HTML. En este proyecto se utilizó para mostrar información adicional en los elementos de la tabla.

. Ejemplo de evento utilizado

Un ejemplo de evento utilizado es @click, que se usa en el botón de registrar estudiante. Cuando el usuario hace clic, se ejecuta la función agregarEstudiante, que guarda los datos en el sistema.

. Uso de v-for

La directiva v-for se utilizó para recorrer la lista de estudiantes y mostrar cada uno en una fila de la tabla. Esto permite que cada vez que se agregue un nuevo estudiante, se muestre automáticamente en pantalla.

. Uso de v-if

La directiva v-if se utilizó para mostrar mensajes de error cuando los campos están vacíos o tienen datos incorrectos. También se usa para mostrar la tabla solo cuando existen registros. Esto ayuda a mejorar la experiencia del usuario y evita mostrar información innecesaria.

. Validación de datos

La validación de datos se realiza dentro del método agregarEstudiante, donde se verifica que todos los campos estén llenos y que la edad sea un número válido mayor que cero.

Esto es importante porque evita que se guarden datos incorrectos en el sistema, lo que podría causar errores o afectar el funcionamiento de la aplicación.












