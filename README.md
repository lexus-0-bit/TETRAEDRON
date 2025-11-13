# TETRAEDRON
AN LITTLE GAME SURVUVAL LOW POLY

TETRAEDRON

TETRAEDRON es un juego de supervivencia en 3D totalmente desarrollado en Android, usando solo OpenGL ES 2.0 y Java puro. Está construido para funcionar directamente desde un dispositivo móvil, sin necesidad de un PC, y está pensado para jugadores que buscan una experiencia de supervivencia inmersiva con mecánicas profundas, generación procedural de mundo, ciclo día/noche, enemigos inteligentes, crafting y construcción.

"Un juego ambicioso hecho desde un teléfono."

Características principales

- Mundo abierto generado proceduralmente: una isla espectacular con montañas, playas, bosques, ríos y cumbres nevadas.
- Ciclo dinámico de día y noche: con efectos visuales y mecánicas de juego que cambian según la hora.
- Sistema de crafting y construcción: construye refugios, fogatas, vallas y mejóralos progresivamente.
- Herramientas personalizables: fabrica hachas, picos y espadas para interactuar con el entorno.
- Enemigos con IA básica: salen de nidos en la noche, te persiguen si estás cerca y huyen de la luz.
- Sistema de necesidades: hambre, energía y salud que afectan tu rendimiento y supervivencia.
- Eventos climáticos dinámicos: lluvias que oscurecen el cielo y afectan la visibilidad.
- Interacción en tiempo real: corta árboles, recolecta recursos, ataca, salta, nada y más desde una UI táctil optimizada.
- Optimizado para móviles: frustum culling, chunking del terreno y culling de objetos para rendimiento en tiempo real.

Requisitos para compilar

- Android Studio (versión recomendada: Giraffe o superior)
- SDK de Android con soporte para OpenGL ES 2.0
- Dispositivo con Android 7.0+ (recomendado Android 10+ para mejor rendimiento)
- Aproximadamente 5 MB de espacio libre en el dispositivo

El juego no requiere Google Play Services ni dependencias externas, y está diseñado para funcionar en ROMs limpias, incluso AOSP.

Cómo ejecutar

1. Clona este repositorio:
   git clone https://github.com/lexus-0-bit/TETRAEDRON.git

2. Abre el proyecto en Android Studio.

3. Conecta tu dispositivo Android o usa un emulador con soporte para OpenGL ES 2.0.

4. Compila y ejecuta el proyecto como una app normal de Android.

Nota: El juego guarda y carga mundos automáticamente en la memoria interna del dispositivo.

Recursos de audio

El juego incluye efectos de sonido para:
- Cortar árboles
- Minar rocas
- Saltar, caminar, construir, comer, atacar, etc.

Los archivos de audio deben estar en res/raw/ con los nombres:
- chop.ogg
- mine.ogg
- step.ogg
- jump.ogg
- build.ogg
- eat.ogg
- drink.ogg
- craft.ogg
- attack.ogg

Puedes reemplazarlos por tus propios efectos en formato .ogg o .wav.

Licencia

Este proyecto está licenciado bajo la GNU General Public License v3.0 (GPLv3).

Copyright (C) 2025 lexus-0-bit

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the

Puedes encontrar una copia completa de la licencia en el archivo LICENSE.

Notas del desarrollador

- Este juego fue escrito enteramente desde un teléfono Android, sin el uso de una computadora.
- Está pensado como una prueba de concepto de lo que un solo desarrollador puede lograr con persistencia, Java y OpenGL ES.
- Todo el código está organizado de forma monolítica intencionalmente para facilitar la expansión y depuración en entornos móviles limitados.
- ¡Si te gusta el proyecto, considera contribuir o compartir tu experiencia!

Capturas (próximamente)

Próximamente se agregarán capturas de gameplay y del mundo generado.

¡Gracias por jugar TETRAEDRON!
