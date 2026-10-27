# NOVA — Simulador empresarial (prototipo)

Prototipo web de un simulador de gestión empresarial chileno.

## Cómo probarlo
1. Descarga `index.html`.
2. Ábrelo en un navegador moderno.
3. Crea una empresa y empieza a jugar.

## Cómo publicarlo en GitHub Pages
1. En GitHub, crea un repositorio nuevo, por ejemplo `nova-simulador`.
2. Sube `index.html` a la raíz del repositorio.
3. En el repositorio, entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera a que GitHub publique el sitio. La URL aparecerá en esa misma sección.

## Qué incluye
- Creación de empresa por rubro y dificultad.
- Creación de productos físicos.
- Fabricación e inventario.
- Ventas simuladas con precio, calidad, reputación, publicidad y eventos.
- Pedidos especiales.
- Cobros inmediatos y diferidos.
- Panel financiero e IVA educativo simplificado.
- Guardado local de la partida en el mismo navegador.

## Límites actuales
- No tiene cuentas reales ni confirmación por correo.
- El guardado usa `localStorage`: se queda en ese navegador/dispositivo.
- No hay pagos, integración con el SII ni declaraciones reales.
- Los cálculos tributarios son educativos y simplificados.
- El modo continuo aún avanza manualmente al pulsar el botón.
