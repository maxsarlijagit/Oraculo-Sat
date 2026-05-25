# Contributing to ORÁCULO SAT

Thanks for your interest in improving ORÁCULO SAT! This is an open project and contributions of all kinds are welcome — code, ideas, bug reports, translations, or new data layers.

*Versión en español más abajo.*

---

## How to contribute

1. **Fork** the repository.
2. **Create a branch** for your change: `git checkout -b my-improvement`
3. **Make your edit.** The whole app is a single file: `oraculo-sat.html`. No build step, no dependencies to install — just open it in a browser to test.
4. **Test it** by opening the file locally and checking your feature works (and that existing ones still do).
5. **Open a Pull Request** with a clear description of what you changed and why.

## Ideas that would help

- New data layers (other open APIs, additional satellite sources)
- Better detection (more robust anomaly/edge algorithms, satellite-specific models)
- UI/UX improvements and accessibility
- More languages (the `T` object near the top of the script holds all interface strings)
- Performance optimizations for the 3D terrain and change detection
- Bug fixes and documentation

## Guidelines

- Keep it **single-file and dependency-free** where possible (libraries load from CDN).
- All image processing should stay **client-side** — no sending user data to servers.
- Be honest about capabilities in any user-facing text. This tool surfaces *candidates and anomalies*, it doesn't *confirm* findings.
- Test in a current browser before submitting.

## Reporting issues

Open an issue describing the problem, what you expected, and steps to reproduce. Screenshots help.

---
---

# Contribuir a ORÁCULO SAT

¡Gracias por tu interés en mejorar ORÁCULO SAT! Es un proyecto abierto y toda contribución es bienvenida — código, ideas, reportes de bugs, traducciones o nuevas capas de datos.

## Cómo contribuir

1. **Forkeá** el repositorio.
2. **Creá una rama** para tu cambio: `git checkout -b mi-mejora`
3. **Hacé tu edición.** Toda la app es un solo archivo: `oraculo-sat.html`. Sin paso de compilación, sin dependencias para instalar — abrilo en el navegador para probar.
4. **Probalo** abriendo el archivo localmente y verificando que tu función ande (y que las existentes sigan andando).
5. **Abrí un Pull Request** con una descripción clara de qué cambiaste y por qué.

## Ideas que ayudarían

- Nuevas capas de datos (otras APIs abiertas, fuentes satelitales adicionales)
- Mejor detección (algoritmos de anomalías/bordes más robustos, modelos específicos para satélite)
- Mejoras de UI/UX y accesibilidad
- Más idiomas (el objeto `T` cerca del inicio del script tiene todos los textos de la interfaz)
- Optimizaciones de rendimiento para el terreno 3D y la detección de cambios
- Correcciones de bugs y documentación

## Pautas

- Mantenelo **de un solo archivo y sin dependencias** donde sea posible (las librerías cargan desde CDN).
- Todo el procesamiento de imagen debe quedar **del lado del cliente** — no enviar datos del usuario a servidores.
- Sé honesto sobre las capacidades en cualquier texto visible. Esta herramienta resalta *candidatos y anomalías*, no *confirma* hallazgos.
- Probá en un navegador actual antes de enviar.

## Reportar problemas

Abrí un issue describiendo el problema, qué esperabas y los pasos para reproducirlo. Las capturas ayudan.
