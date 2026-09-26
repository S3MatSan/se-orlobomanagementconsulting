# Señor Lobo — Management Consulting

Landing page corporativa para **Señor Lobo (Management Consulting)**, firma boutique
ficticia de asesoramiento en M&A, desinversiones, OPAs y situaciones especiales.
Eslogan: **We Fix Problems**.

Inspirada en la estética del personaje "The Wolf" de *Pulp Fiction* (traje impecable,
discreción absoluta, resolución rápida de problemas) combinada con un tono profesional
tipo consultora boutique (referencia estructural: la web de Accuracy España).

## Estructura

- `index.html` — página única con todas las secciones (hero, filosofía, servicios,
  expedientes/casos, quiénes somos, contacto).
- `css/style.css` — estilos (paleta noir: negro, rojo sangre, dorado maletín).
- `js/main.js` — menú móvil, animaciones al hacer scroll, validación del formulario.
- `assets/` — iconos SVG (maletín, favicon).

## Sobre los "Expedientes" (casos)

Los casos mostrados (`GASLAMP`, `GOLD WATCH`, `ROYALE`, `BONNIE`) son situaciones
**anonimizadas y representativas** del tipo de operación que la práctica cubre
(OPAs, carve-outs de infraestructura de telecomunicaciones, venta de redes de cobre,
desinversiones logísticas). No corresponden a clientes reales de Señor Lobo ni citan
compañías reales: son ejemplos ilustrativos del expertise, con nombres en clave al
estilo de un dossier confidencial.

## Contacto del formulario

El formulario de contacto es funcional en el frontend (validación + mensaje de
confirmación) pero **no envía datos a ningún backend**. Para producción, conectar a
un servicio de envío de formularios (p.ej. Formspree, un endpoint propio, o email
transaccional) en `js/main.js`.

## Cómo verlo en local

```bash
python3 -m http.server 8000
# abrir http://localhost:8000
```
