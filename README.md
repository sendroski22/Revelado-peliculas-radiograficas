# Simulador revelado de películas radiográficas tradicionales

Web interactiva para aprender, paso a paso, cómo se revela a mano una película radiográfica: desde la entrada al cuarto oscuro hasta la película seca en el negatoscopio.

**CFGS Imagen para el diagnóstico y medicina nuclear** · Módulo 1346 - Fundamentos físicos y equipos

🔗 **Acceso a la web:** `https://sendroski22.github.io/Revelado-peliculas-radiograficas/`

---

## ¿Para qué sirve?

Hoy en día casi toda la radiología es digital, pero el revelado de películas todavía se usa en algunos servicios y es la base para entender cómo se forma una imagen radiográfica. Este simulador permite que el alumnado haga el proceso completo en el papel del técnico y vea qué le ocurre a la película en cada fase.

## Relación curricular

| | |
|---|---|
| **Ciclo** | CFGS Imagen para el diagnóstico y medicina nuclear |
| **Módulo** | 1346 - Fundamentos físicos y equipos |
| **Resultado de aprendizaje** | RA3. Procesa y trata imágenes radiográficas, describiendo las características de los receptores y sus aplicaciones. |
| **Criterio de evaluación** | 3.d) Se han revelado películas radiográficas. |

## Contenido

1. **Cuarto oscuro:** cerrar la puerta, trabajar con luz de seguridad (inactínica) y sacar la película del chasis.
2. **Revelado:** la imagen latente se hace visible.
3. **Aclarado intermedio:** se detiene el revelado.
4. **Fijado:** se eliminan los haluros de plata no expuestos y la imagen queda permanente.
5. **Lavado:** se eliminan los restos de productos químicos.
6. **Secado:** la película queda lista para el negatoscopio.
7. **Resultado:** radiografía final de una mano, tabla resumen del proceso y cuestionario de 4 preguntas con corrección inmediata.

En cada paso hay una animación interactiva y dos explicaciones: **qué hace el técnico** y **qué le pasa a la película**. Los tiempos están acelerados.

### Modo con errores

Con el interruptor **«Activar modo con errores»**, el alumnado decide el orden y cuándo sacar la película de cada baño, y aparecen acciones que un técnico no debería hacer. Los fallos se ven en la película (velo, manchas, poca o excesiva densidad, aspecto lechoso, amarilleo, huellas) y se explican al final.

## Uso

- **En línea:** abre el enlace de GitHub Pages.
- **Sin conexión:** descarga `index.html` y ábrelo con cualquier navegador. Funciona en ordenador, tablet y móvil. Sin conexión se ven las fuentes del sistema en lugar de las tipográficas de la web, pero todo funciona igual.

### Publicar en GitHub Pages

1. Sube `index.html` a la raíz del repositorio.
2. Ve a **Settings → Pages**.
3. En *Source*, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. Guarda: en uno o dos minutos la web estará disponible en `https://<usuario>.github.io/<repositorio>/`.

## Estructura del repositorio

```
├── index.html   # La web completa (HTML, CSS y JavaScript en un solo archivo)
├── README.md
└── LICENSE
```

No necesita instalación, ni dependencias, ni servidor.

## Personalización

La radiografía de la mano es un dibujo esquemático original hecho con SVG, dentro de `index.html`. Los textos de cada paso (`TEXTS`), los fallos del modo con errores (`DEFECTS`) y las preguntas del cuestionario (`QUIZ`) están al principio del bloque `<script>` y se pueden editar fácilmente.

## Autoría y licencia

“Web interactiva Simulador revelado de películas radiográficas tradicionales” por **Pablo A. Sendra Lleó** (2026), disponible bajo licencia [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es).

Puedes compartir y adaptar este material siempre que cites la autoría, no lo uses con fines comerciales y compartas las obras derivadas con la misma licencia. El texto legal completo está en el archivo [`LICENSE`](LICENSE).

Este material fue desarrollado con la asistencia del modelo de inteligencia artificial [Claude (Anthropic)](https://claude.ai/).
