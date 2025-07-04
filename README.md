# Trivify
## Sistema para transformar tus preguntas docentes en un juego tipo trivial


El presente Trabajo Fin de Grado se centra en el desarrollo de un videojuego educativo de preguntas y respuestas orientado a su uso como herramienta docente adaptable por cada profesor a su asignatura, fomentando el aprendizaje activo y la participación del alumnado mediante la gamificación. 

El juego estará basado en una mecánica tipo trivial, donde se presentan preguntas clasificadas por categorías temáticas. Contará con dos modos principales: un modo para un jugador, pensado para repaso autónomo, y un modo multijugador competitivo, para dinamizar sesiones en clase. Los jugadores responderán preguntas dentro de un tiempo limitado, obteniendo puntuaciones según sus aciertos. Habrá un sistema de clasificación online para fomentar la motivación. Se incluirá además un editor que permitirá a los profesores crear y gestionar sus propios paquetes de preguntas y categorías, para adaptarlo a los objetivos específicos de su asignatura. El diseño de la interfaz será accesible y pensado para contextos educativos, con elementos visuales claros y opciones de configuración ajustadas a las necesidades del aula.

Desde el punto de vista técnico, el desarrollo se llevará a cabo con el motor Unity, aprovechando sus capacidades para exportación multiplataforma a través de WebGL, permitiendo así el acceso al juego desde navegadores web tanto en dispositivos de escritorio como móviles. El lenguaje principal de desarrollo será C# y se utilizarán servicios externos para la gestión de rankings. Se empleará Git como sistema de control de versiones.




# ToDo list


## Primer prototipo
Juego individual con tablero, movimiento básico y varias preguntas de ejemplo.
- tablero, casillas, tirada de dado, movimiento de ficha, selección de casilla destino dentro de las posibles,
- presentación de pregunta, elección de respuesta, indicación de si es correcta o no
- puntuación
- fichero con varias preguntas, elegir formato, json ?
- selección aleatoria de pregunta
- concepto de categoría y selección de pregunta de esa categoría
- concepto de quesito, pregunta de quesito, visualización de los quesitos que tienes y condición de victoria al conseguir todos


## Añadir estas funcionalidades en el orden que queramos, generando un prototipo a probar después de cada una
- Multijugador local
- Editor de preguntas
- Clasificaciones
mirar opciones https://dreamlo.com es muy fácil, servicios de unity, de google play.


## Funcionalidades extra según vayamos de tiempo
- Multijugador online
- Importar preguntas de moodle
Los bancos de preguntas de moodle se pueden exportar en varios formatos, alguno xml, que se pueden parsear y sería interesante "vender" que puedes reutilizar lo que ya tienes en moodle para hacerlo más atractivo con este trivial
- Usar open trivia database https://opentdb.com/
- etc.