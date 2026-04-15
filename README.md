⚔️ Unreal Engine: Basic Combat & Animation System

Este proyecto es una demostración técnica de sistemas fundamentales en Unreal Engine, enfocado en la integración de animaciones complejas y lógica de combate interactiva. El objetivo es mostrar un flujo de trabajo sólido entre el Animation Blueprint y la comunicación entre actores (Player vs Enemy).

🚀 Características Principales
1. Sistema de Animación (State Machine)
El personaje cuenta con un Animation Blueprint configurado para transiciones fluidas entre estados, utilizando Blends Spaces para el movimiento y Montages para acciones rápidas:

Locomoción: Idle, Walk y Jump (con Blend Spaces de velocidad).

Acciones de Combate: Attack y Shield (Bloqueo).

Estados de Salud: Reacción a daño y animación de Death (Muerte).

2. Sistemas Interactivos y Lógica
Se implementó una arquitectura basada en Blueprints para manejar la interactividad:

Sistema de Daño: Comunicación mediante Interface para que tanto el jugador como el enemigo puedan enviarse y recibir daño de forma genérica.

Mecánica de Bloqueo (Shield): Lógica que verifica si el escudo está activo antes de restar puntos de vida al recibir un ataque.

IA Básica de Enemigo: Un sistema simple que detecta al jugador, ataca en intervalos y reacciona al daño hasta morir.

🛠️ Tecnologías Utilizadas
Motor: Unreal Engine 5.x

Lenguaje: Blueprints (Visual Scripting)

Assets: Mixamo

Control de Versiones: Git + Git LFS


📁 Estructura del Proyecto
/Content/Characters: Modelos y esqueletos.

/Content/Animations: Animation Blueprints, Montages y Blend Spaces.

/Content/Blueprints: Lógica del Player, Enemy y GameMode.
