# Validador y Creador SEMOVI unificado para Vercel y GitHub

Este proyecto contiene una arquitectura limpia de archivo único (`index.html`) optimizada para **Vercel** y **GitHub**:

- **Al entrar a la URL principal por primera vez:** Muestra directamente la **Interfaz de Configuración**, donde puedes modificar la fecha de expedición, tipo de licencia, folio, validez y generar automáticamente un **Token Secret** aleatorio y seguro.
- **Al hacer clic en el botón:** La misma página transforma su vista en automático (sin necesidad de cambiar de archivo ni salir del dominio) mostrando la interfaz oficial de validación de la SEMOVI con tus datos cambiados, actualizando la URL de tu sitio web al instante para que puedas compartirla o copiarla.
- **Botón de Edición:** En la esquina superior derecha de la vista de validación hay un botón discreto de configuración que te permite regresar al panel para crear nuevas variantes en segundos.
