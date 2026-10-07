# MCTranslator

MCTranslator es una herramienta diseñada para hacerte la vida más fácil. Extrae los archivos de idioma de tus mods de Minecraft (`.jar`), los traduce automáticamente y genera un Resource Pack en español listo para usar directamente en el juego.

## ✨ Características

- **Traducción Automática**: Extrae los textos del inglés y los traduce al español en cuestión de segundos.
- **Múltiples Motores**: 
  - *Google Translate*: Gratis, rápido y masivo (menos recomendado).
  - *DeepL API*: Ideal para traducciones de mayor calidad y más naturales (el más recomendado).
  - *Inteligencia Artificial (Gemini)*: Traducciones con contexto, perfectas para Minecraft.
- **Fácil de Usar**: Selecciona tu carpeta de mods o simplemente arrastra los archivos `.jar` a la aplicación, elige tu versión de Minecraft y dale a "Iniciar".
- **Historial Integrado**: Revisa todas tus traducciones pasadas, ve qué mods se procesaron y vuelve a generar los Resource Packs cuando lo necesites.
- **Protección de Código**: Evita crasheos protegiendo automáticamente las variables internas del juego y los códigos de color (`§c`, `%s`, etc.).

## 💡 Recomendaciones de Uso

1. **Elegir el mejor motor para ti**:
   - Para traducir un modpack gigante rápidamente y sin configurar nada, usa **Google Translate**.
   - Para traducciones más precisas, prueba la **IA Experimental**. Te recomendamos usar una clave de API gratuita de Google Gemini. ¡Si pones más de una clave, el programa rotará automáticamente entre ellas si alcanzas el límite de uso!
2. **Mods individuales**: Si no quieres traducir toda una carpeta entera, puedes arrastrar uno o varios mods (archivos `.jar`) directamente desde tu explorador hacia la ventana del programa.
3. **Versión de Minecraft**: Antes de traducir, asegúrate de seleccionar la versión correcta del juego en la lista desplegable. Esto garantiza que el Resource Pack no te muestre alertas rojas de "incompatibilidad" al activarlo en Minecraft.

## 🛠️ Solución de problemas

Si el programa se cierra repentinamente o se interrumpe sin mostrar un error en pantalla, puedes revisar este archivo de registro oculto para ver qué salió mal:

`%APPDATA%\MCTranslator\debug.log`

*(Puedes copiar y pegar esa ruta en tu Explorador de Archivos). El registro te mostrará paso a paso en qué mod o en qué texto exacto se detuvo la traducción.*

![Descargas Totales](https://img.shields.io/github/downloads/d0ce3/McTranslator-Feedback/total?color=8707ff&style=for-the-badge&label=DESCARGAS)


**⚠️ Windows puede mostrar una advertencia al instalar o actualizar**

Es normal y esperable. No es un virus.

**MCTranslator es una aplicación gratuita y sin fines de lucro**, hecha por una sola persona. Para que Windows deje de mostrar estas advertencias hace falta un "certificado de firma de código", que cuesta varios cientos de dólares por año — un gasto que no tiene sentido para un proyecto gratuito como este.

Sin ese certificado, Windows (y algunos antivirus) desconfían automáticamente de cualquier programa nuevo y poco descargado, sin importar si es seguro o no. Es lo mismo que le pasa a la mayoría de las apps chicas e independientes cuando recién salen.

Si Windows te muestra "Windows protegió tu PC", hacé click en Más información → Ejecutar de todas formas.
Si tu antivirus lo bloquea directamente, agregalo como excepción.

<img width="1360" height="720" alt="image" src="https://github.com/user-attachments/assets/7b3b34e3-2d6f-41cb-83fb-eb40a3c0ce0b" />
Tambien desactiven el control inteligente de Aplicaciones si es que utilizan solamente Windows Defender.

Con el tiempo, a medida que más gente lo descarga y lo usa sin problemas, estas advertencias van a ir apareciendo cada vez menos.


## 📄 Licencia

Copyright © 2026 d0ce3. Todos los derechos reservados.
