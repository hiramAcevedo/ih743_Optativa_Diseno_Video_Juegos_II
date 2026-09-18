# IH743 Optativa Abierta III: Diseño de videojuegos II

Índice de los proyectos de Optativa Abierta III, Diseño de videojuegos II (clave IH743), Licenciatura en Desarrollo de Sistemas Web, Universidad de Guadalajara, ciclo 2026-B.

- Asesor: Oscar Gregorio Silva Mares.
- Alumno: Hiram Agustín Acevedo López.
- Versión de Unity utilizada: 6000.5.9f1 (Unity 6.5).

Repositorios de la materia:

- Este repositorio: índice de las entregas y proyecto "Hola mundo" de la unidad 1.
- [Aplicación interactiva 2D, "Una noche junto al fuego"](https://github.com/hiramAcevedo/ih743_Aplicacion_Interactiva_2D): proyecto de la unidad 2, actividades 2.1 a 2.6, con una etiqueta por entrega.

## Proyectos y entregas

Este repositorio conserva el proyecto de la actividad 1.4 y funciona como índice de la materia. Los enunciados de las actividades 2.1, 3.1 y 4.1 piden proyectos nuevos con sus respectivos repositorios públicos.

Por eso, los siguientes proyectos tendrán repositorios independientes. Dentro de cada uno, las actividades continúan el mismo proyecto y cada entrega se identifica con una etiqueta de Git. Las actividades ya entregadas se consultan mediante su etiqueta correspondiente.

| Actividad | Proyecto | Ubicación | Entrega |
|---|---|---|---|
| 1.4. Inicio del proyecto | Hola mundo (Universal 3D) | [u01-act4-hola-mundo](u01-act4-hola-mundo/) en este repositorio | [act-1.4](https://github.com/hiramAcevedo/ih743_Optativa_Diseno_Video_Juegos_II/tree/act-1.4) |
| 2.1. La primera ventana | Aplicación interactiva 2D (Universal 2D) | [Repositorio de la unidad 2](https://github.com/hiramAcevedo/ih743_Aplicacion_Interactiva_2D) | [act-2.1](https://github.com/hiramAcevedo/ih743_Aplicacion_Interactiva_2D/tree/act-2.1) |
| 2.2. El primer escenario | Aplicación interactiva 2D: Una noche junto al fuego | [Repositorio de la unidad 2](https://github.com/hiramAcevedo/ih743_Aplicacion_Interactiva_2D) | [act-2.2](https://github.com/hiramAcevedo/ih743_Aplicacion_Interactiva_2D/tree/act-2.2) |
| 2.3. Programación de botones | Aplicación interactiva 2D: Una noche junto al fuego | [Repositorio de la unidad 2](https://github.com/hiramAcevedo/ih743_Aplicacion_Interactiva_2D) | [act-2.3](https://github.com/hiramAcevedo/ih743_Aplicacion_Interactiva_2D/tree/act-2.3) |
| 2.4. El bucle de juego y la animación | Aplicación interactiva 2D: Una noche junto al fuego | [Repositorio de la unidad 2](https://github.com/hiramAcevedo/ih743_Aplicacion_Interactiva_2D) | [act-2.4](https://github.com/hiramAcevedo/ih743_Aplicacion_Interactiva_2D/tree/act-2.4) |

El proyecto de la unidad 2 continúa hasta la actividad 2.6. Las unidades 3 y 4 tendrán sus propios proyectos conforme a sus enunciados; se añadirán al índice cuando se inicien.

## Abrir el hola mundo

1. Clona este repositorio:

   ```bash
   git clone https://github.com/hiramAcevedo/ih743_Optativa_Diseno_Video_Juegos_II.git
   ```

2. En Unity Hub, ve a Projects > Add > Add project from disk.
3. Selecciona `u01-act4-hola-mundo`, donde están las carpetas del proyecto Unity.
4. Ábrelo con el editor 6000.5.9f1. La primera importación genera `Library` y puede tardar varios minutos.
5. Abre `Assets/Scenes/SampleScene.unity` con doble clic y presiona Play. La consola debe mostrar "Hola mundo".

Para los demás proyectos, sigue el README de su propio repositorio.

## Archivos versionados

Se incluyen `Assets`, `Packages` y `ProjectSettings` de cada proyecto. Los `.meta` de los recursos conservan sus identificadores y referencias.

Se excluyen `Library`, `Temp`, `Logs` y `UserSettings`, que Unity regenera. El `.gitignore` de Unity se coloca junto a esas carpetas: en este repositorio está dentro de `u01-act4-hola-mundo`; en un repositorio cuya raíz sea directamente un proyecto Unity, estará en la raíz.
