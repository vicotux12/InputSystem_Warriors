# Unity Input System - 'Warriors' Example Project

![warriors.png](https://i.imgur.com/m4cuul3.png)


## Overview


Descripción

-Este proyecto de ejemplo de Unity se ha creado para demostrar una variedad de herramientas y funcionalidades con el nuevo sistema de entrada.

-Puede obtener más información sobre el nuevo sistema de entrada aquí: https://unity.com/features/input-system

Escena de prueba del sistema de entrada

-Esquema de control de acción de entrada para controles básicos del jugador (eje direccional para movimiento, pulsación de botón para ataque)

-Configuración de las vinculaciones del teclado y del gamepad genérico al esquema de control

-Probado con los siguientes controladores: PlayStation Dualshock 4, Xbox One y Nintendo Switch Pro

-Creación de instancias de varios controladores de jugador para una configuración multijugador local

-Entrada de UI (Joystick virtual y botón virtual) para controles de pantalla táctil

-Cambio de tiempo de ejecución entre los mapas de acciones de control del jugador y del menú

-Interfaz de usuario para reasignar controles de acción a nuevos botones y joysticks

-Visualización de datos del dispositivo conectado tanto en la interfaz de usuario de Screen Space como en la de World Space

-Devoluciones de llamadas para la desconexión y reconexión del tiempo de ejecución de un dispositivo de entrada Otros escenarios demostrados

Apilamiento de cámaras de Universal Render Pipeline para la interfaz de usuario superpuesta
Pase de renderizado programable de Universal Render Pipeline para superposición de interfaz de usuario con desenfoque de escena
Posprocesamiento integrado de Universal Render Pipeline para mapeo de tonos
Prefabricado de interfaz de usuario anidada para mostrar información del dispositivo de entrada
Gráfico de sombreado para filtrar un mapa de máscara para los colores del equipo
TextMesh Pro para renderizar texto de interfaz de usuario del espacio de pantalla y del espacio mundial
Objeto programable para almacenar colores y nombres de visualización del dispositivo
Requisitos
Versión de Unity

Actual: 2019.4.6f1
Paquetes

com.unity.inputsystem: 1.0.0
com.unity.textmeshpro: 2.0.1
com.unity.render-pipelines.universal: 7.3.1
Hardware

Este proyecto de ejemplo se ha desarrollado y probado con los siguientes dispositivos de entrada:

Teclado
Mando Dualshock de PlayStation 4
Mando Xbox One
Mando Pro de Nintendo Switch
Android Samsung Galaxy S9 (pantalla táctil para joystick virtual y botón virtual)
Ratón (para simular la entrada de pantalla táctil en el Editor de Unity)
Software

Este proyecto de ejemplo se desarrolló y probó en Windows 10.

Uso

Este proyecto de ejemplo está disponible públicamente para que usted:

-Úselo como recurso de aprendizaje para el nuevo sistema de entrada o cualquier otra función y herramienta implementada
-Úselo como base para construir sus propios proyectos.
-Extrae código, activos e información para tus propios proyectos

Créditos y comentarios
Este proyecto de ejemplo es desarrollado por Unity Technologies y cuenta con participación de I+D, gestión de productos, marketing de productos y evangelización.


Descargos de responsabilidad técnica y problemas conocidos: 

-El script GameManager tiene un botón para generar un grupo de guerreros en tiempo de ejecución.

-La cantidad de guerreros que se generan se basa en una variable entera fija (establecida manualmente en el Inspector) y no en la cantidad de dispositivos de entrada conectados y detectados.
-Al abrir el proyecto por primera vez, es posible que el efecto de desenfoque de pantalla del menú de pausa no se represente.

Para solucionar esto, ubique el recurso UniversalRenderPipeline_Renderer_MenuBlur y agregue el Kawase Blur Render Pass a las Características del Renderizador.
