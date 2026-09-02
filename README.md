# IH745 Optativa V: Diseño de videojuegos II

Repositorio de los proyectos de Unity de la materia Optativa V (clave IH745, NRC 215267, sección D01) de la Licenciatura en Desarrollo de Sistemas Web, Universidad de Guadalajara, ciclo 2026-B.

- Asesora: Nancy Ruiz Monroy
- Alumno: Hiram Agustín Acevedo López
- Versión de Unity: 6000.5.9f1 (Unity 6.5)

## Actividades

Cada actividad vive en su propia carpeta y cada entrega queda marcada con una etiqueta de Git, para que el enlace entregado apunte a un punto fijo del historial.

| Actividad | Nombre | Carpeta | Etiqueta |
|---|---|---|---|
| 1.4 | Inicio del proyecto: script de "Hola mundo" | `u01-act4-hola-mundo/` | `act-1.4` |

## Cómo abrir un proyecto

1. Clona el repositorio:

   ```
   git clone https://github.com/hiramAcevedo/ih745_Optativa_Diseno_Video_Juegos_II.git
   ```

2. En Unity Hub, ve a Projects y elige Add > Add project from disk.
3. Selecciona la carpeta del proyecto que quieras abrir (por ejemplo `u01-act4-hola-mundo`), no la raíz del repositorio.
4. Ábrelo con el editor 6000.5.9f1. La primera apertura tarda unos minutos porque Unity genera la carpeta `Library`; las siguientes son rápidas.

## Qué se versiona

Se suben las carpetas `Assets`, `Packages` y `ProjectSettings` de cada proyecto, junto con sus archivos `.meta`, que guardan el identificador de cada recurso y son necesarios para que las referencias entre escenas, scripts y assets no se rompan al clonar.

Quedan fuera `Library`, `Temp`, `Logs` y `UserSettings`, porque Unity los regenera en cada equipo. El `.gitignore` de cada proyecto es el que mantiene GitHub para Unity.
