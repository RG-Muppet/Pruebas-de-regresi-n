<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Proyecto 1: Pruebas de Regresión Manuales de Urban Routes</title>
</head>
<body>

<h1>Proyecto 1: Pruebas de Regresión Manuales de Urban Routes</h1>

<h2>Descripción del Proyecto</h2>
<p>
  Este proyecto consiste en la realización de pruebas de regresión manuales para la aplicación de transporte <strong>Urban Routes</strong>.
  Urban Routes permite a los usuarios crear rutas, calcular la duración y el costo del viaje, y seleccionar entre diversas opciones de transporte,
  como automóvil, a pie, taxi, bicicleta, scooter y autos compartidos.
</p>
<p>
  La aplicación tiene una interfaz sencilla que incluye dos campos de dirección ("Desde" y "Hasta"), así como tres modos de viaje:
  "Óptimo", "Flash" y "Personal". Al establecer estas ubicaciones, la aplicación calcula el tiempo y costo total de viaje entre los puntos
  "A" y "B" utilizando un algoritmo específico.
</p>

<h2>Objetivo de las Pruebas</h2>
<p>
  El objetivo de las pruebas de regresión es asegurar que las funcionalidades principales de Urban Routes operen sin errores tras cualquier cambio en el sistema.
  Al encontrar y reportar los errores, el equipo de QA contribuye a mejorar la experiencia del usuario y a mantener la competitividad de la aplicación en el mercado.
</p>

<h2>Alcance de las Pruebas Manuales</h2>
<p>
  El equipo de QA ha preparado casos de prueba específicos que abarcan las principales funcionalidades de la aplicación. Estos casos de prueba incluyen los siguientes elementos:
</p>

<ol>
  <li><strong>Establecimiento de direcciones</strong>:
    <ul>
      <li>Verificación de que los campos "Desde" y "Hasta" permiten introducir direcciones válidas.</li>
      <li>Confirmación de que la aplicación interpreta las direcciones correctamente y establece puntos "A" y "B" para la ruta.</li>
    </ul>
  </li>
  <li><strong>Selección de modo de viaje</strong>:
    <ul>
      <li>Verificación de que el usuario puede seleccionar entre los modos "Óptimo", "Flash" y "Personal".</li>
      <li>Confirmación de que cada modo afecta los cálculos de duración y costo según lo esperado.</li>
    </ul>
  </li>
  <li><strong>Opciones de transporte</strong>:
    <ul>
      <li>Pruebas de selección de distintos tipos de transporte (automóvil propio, a pie, taxi, bicicleta, scooter y autos compartidos).</li>
      <li>Verificación de que el tipo de transporte seleccionado afecta el cálculo de precio y tiempo de manera correcta.</li>
    </ul>
  </li>
  <li><strong>Cálculo de duración y costo del viaje</strong>:
    <ul>
      <li>Asegurarse de que la aplicación calcula la duración y el costo del viaje entre los puntos A y B en función del modo de viaje y el tipo de transporte.</li>
    </ul>
  </li>
  <li><strong>Comportamiento del servidor</strong>:
    <ul>
      <li>Confirmación de que el servidor de la aplicación se inicia correctamente y la aplicación es accesible desde la URL proporcionada.</li>
    </ul>
  </li>
</ol>

<h2>Ejecución de las Pruebas Manuales</h2>
<ol>
  <li><strong>Iniciar el servidor</strong>:
    <ul>
      <li>Abre la aplicación y asegúrate de que el servidor esté activo antes de comenzar las pruebas. El servidor puede tardar hasta 2 minutos en iniciarse.</li>
    </ul>
  </li>
  <li><strong>Seguir los casos de prueba</strong>:
    <ul>
      <li>Los casos de prueba detallan los pasos a seguir y los resultados esperados para cada funcionalidad en Urban Routes.</li>
      <li>Realiza cada prueba de acuerdo con los casos preparados, registrando cualquier comportamiento inesperado o error.</li>
    </ul>
  </li>
</ol>

<h2>Documentación de Errores</h2>
<p>Para cada error encontrado:</p>
<ol>
  <li><strong>Descripción</strong>: Documentar el problema, especificando el comportamiento esperado y el comportamiento actual.</li>
  <li><strong>Reproducción</strong>: Incluir los pasos necesarios para reproducir el error.</li>
  <li><strong>Prioridad</strong>: Asignar una prioridad al error (crítico, alto, medio, bajo) para facilitar la gestión del proceso de corrección.</li>
  <li><strong>Registro en Hoja de Cálculo</strong>: Los errores se documentan en una plantilla de Google Sheets, que se utiliza para hacer seguimiento de todos los problemas encontrados.</li>
</ol>

</body>
</html>
