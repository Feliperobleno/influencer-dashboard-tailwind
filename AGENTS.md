# Instrucciones del proyecto

## Alcance y autorización
- Sigue los requisitos explícitos del usuario y las instrucciones del README.
- No inventes requisitos de producto ni supongas comportamientos no especificados; aclara las ambigüedades relevantes antes de implementarlas.
- No añadas archivos, carpetas, dependencias ni tecnologías sin autorización explícita.
- Respeta las restricciones técnicas de cada tarea. Para el dashboard actual, usa HTML5 y Tailwind CSS v4 mediante el CDN oficial; no añadas JavaScript ni CSS personalizado salvo que se solicite.
- No hagas commits ni pushes sin autorización explícita del usuario.

## HTML y Tailwind
- Usa elementos HTML semánticos y conserva una jerarquía de encabezados coherente.
- Mantén el marcado conciso y legible; sigue el formato existente y evita reformatear áreas no relacionadas.
- Usa clases de utilidad de Tailwind para estilos. No introduzcas hojas de estilo, atributos `style` ni dependencias adicionales sin autorización.
- Añade comentarios HTML breves solo para explicar decisiones estructurales o responsive que no sean evidentes.

## Diseño responsive
- Aplica un enfoque mobile-first y los breakpoints `sm:`, `md:` y `lg:` cuando correspondan al diseño solicitado.
- Evita que el contenido provoque desplazamiento horizontal de la página. Si una tabla necesita desplazamiento, confínalo a su propio contenedor.
- Cuando una tabla resulte difícil de leer en móvil, presenta los mismos datos en un formato móvil adecuado, como tarjetas, y conserva la tabla en pantallas mayores si así se requiere.

## Accesibilidad
- Usa landmarks, listas, tablas y encabezados nativos según el tipo de contenido.
- Asocia etiquetas y valores con elementos semánticos; en tablas, incluye `caption` y encabezados con `scope` cuando correspondan.
- Proporciona nombres accesibles a los controles y referencias ARIA válidas; no añadas ARIA redundante si HTML nativo basta.
- Comprueba que las variantes responsive no oculten información a las tecnologías de asistencia ni creen identificadores duplicados.

## Datos y consistencia
- Mantén coherentes los datos repetidos entre KPI, tarjetas, tablas y listados.
- Verifica los cálculos derivados con las fórmulas del dominio; para comisiones, aplica el porcentaje indicado al importe correspondiente.
- Identifica claramente los datos ficticios y no presentes cifras estimadas como datos reales.

## Verificación
- Revisa el diff y confirma que solo cambien los archivos autorizados.
- Ejecuta `git diff --check` y las comprobaciones disponibles del editor o del proyecto.
- Si existe un servidor configurado, úsalo para verificar la página. Comprueba distintos anchos de pantalla cuando haya un navegador disponible y comunica cualquier validación que no se haya podido realizar.
- No añadas herramientas ni archivos de prueba sin autorización.
