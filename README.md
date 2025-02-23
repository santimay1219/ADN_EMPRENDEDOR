ADN_EMPRENDEDOR es una aplicación de consola desarrollada en Java que implementa la técnica Pomodoro para la gestión del tiempo. Con esta herramienta, podrás configurar sesiones de trabajo y descanso, realizar múltiples ciclos de Pomodoros y llevar un registro de los pomodoros completados.

Características
-Configuración de Sesiones: Permite ingresar el número de pomodoros, así como definir la duración de las sesiones de trabajo y los descansos.
-Cuenta Regresiva: Muestra en la consola el tiempo restante durante cada sesión de trabajo y descanso.
-Registro de Pomodoros: Lleva un registro global de todos los pomodoros completados.
-Menú Interactivo: Ofrece un menú con opciones para iniciar sesiones, visualizar el registro y reiniciarlo según se requiera.

Requisitos
-Java JDK 8 o superior.
-Consola o terminal para ejecutar la aplicación.

1. Instalación
Clonar el repositorio o descargar el código fuente:
git clone https://github.com/santimay1219/ADN_EMPRENDEDOR.git
cd ADN_EMPRENDEDOR

2. Compilar la aplicación:
Utiliza el siguiente comando en la terminal:
javac PomodoroApp.java

3. Ejecutar la aplicación:
Una vez compilado, ejecuta:
java PomodoroApp

Uso
Al ejecutar la aplicación, se mostrará un menú interactivo con las siguientes opciones:
1. Iniciar sesión de Pomodoro:
Permite configurar el número de pomodoros a realizar, la duración de cada sesión de trabajo y el tiempo de descanso. Cada ciclo iniciará una cuenta regresiva y, al finalizar, se actualizará el registro global de pomodoros completados.

2. Mostrar registro de Pomodoros completados:
Muestra en consola el número total de pomodoros que has completado en todas las sesiones.

3. Reiniciar registro:
Permite reiniciar el contador global de pomodoros completados. Se solicitará confirmación antes de proceder.

4. Salir:
Cierra la aplicación.

Estructura del Código
PomodoroApp.java:
Contiene la lógica principal de la aplicación, incluyendo el menú interactivo, la función para iniciar sesiones de Pomodoro, la cuenta regresiva y las funciones para manejar el registro de pomodoros.

Mejoras Futuras
- Interfaz Gráfica: Implementar una GUI utilizando Swing o JavaFX para una mejor experiencia de usuario.
- Notificaciones: Añadir notificaciones sonoras o visuales para indicar el inicio y fin de las sesiones.
- Persistencia de Datos: Integrar una base de datos o sistema de archivos para almacenar el registro de pomodoros de manera persistente.

Contribuciones
¡Las contribuciones son bienvenidas! Si deseas mejorar la aplicación o agregar nuevas funcionalidades, sigue estos pasos:

1. Haz un fork del repositorio.
1.Crea una rama con una descripción de la mejora o corrección.
1.Realiza tus cambios y envía un pull request.
