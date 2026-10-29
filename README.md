# ABOGARED — sitio corporativo

Sitio estático multipágina, responsive y sin dependencias de compilación. Puede abrirse directamente o servirse desde cualquier hosting estático.

## Arquitectura

- `index.html`: hero, métricas, especialidades, propuesta de transparencia y CTA.
- `nosotros.html`: historia, misión, visión, valores y equipo directivo.
- `areas.html`: acordeones para Corporativo, Civil y Familiar, Laboral, Penal y Fiscal.
- `transparencia.html`: proceso, modalidades de honorarios y compromisos de confidencialidad.
- `blog.html`: portada editorial y seis contenidos SEO demostrativos.
- `contacto.html`: datos directos, formulario confidencial, mapa y acceso a WhatsApp.
- `styles.css`: sistema visual, layout, estados, animaciones y breakpoints.
- `components.js`: navbar/footer compartidos, menú móvil, acordeones, revelado y confirmación del formulario.

## Sistema visual

- Azul noche: `#071426`
- Azul institucional: `#082A52`
- Azul eléctrico: `#129FE0`
- Azul de acción: `#0069AD`
- Rojo de acento: `#E20722`
- Fondo tenue: `#F3F7FA`
- Titulares: Libre Caslon Display
- Cuerpo: DM Sans

## Antes de publicar

1. Sustituir cifras ilustrativas por métricas comprobables.
2. Reemplazar perfiles, LinkedIn y retratos de muestra por los del equipo real.
3. Cambiar teléfono, correo, dirección y vínculo de WhatsApp.
4. Conectar el formulario a un backend seguro con protección antispam y aviso de privacidad definitivo.
5. Confirmar cédulas, denominación social, jurisdicciones atendidas y textos regulatorios aplicables.
6. Publicar artículos completos detrás de las portadas del blog y añadir datos estructurados.

## Vista local

```bash
python3 -m http.server 4173
```

Después abre `http://localhost:4173`.

## Activos

- `assets/abogared-logo.jpeg`: imagen proporcionada por el cliente.
- `assets/equipo-triptych.png`: retratos ficticios generados para la maqueta; no representan al equipo real.

