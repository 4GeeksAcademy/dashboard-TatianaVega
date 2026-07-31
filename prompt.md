Restricciones tecnicas: usa solo HTML y tailwind css v4, el CDN correcto es https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4, nada de React/Vue/otros frameworks
No uses cdn.tailwindcss.com ni sintaxis de Tailwind v3.
Que es el proyecto : Construir un dashboard que muestre al menos tres KPIs, tres drivers y detalles operacionales (tablas o listados) en los tres bloques bloque superior (KPIs), bloque intermedio (Drivers) y bloque inferior (detalle operacional) .
Contexto del negocio: Este es un dashboard para una influencer que promociona 3 productos por comisión en redes sociales.

- Producto A: precio 50€, 150 ventas
- Producto B: precio 120€, 60 ventas
- Producto C: precio 80€, 90 ventas
- Comisión: 15% sobre cada venta
- Instagram: alcance 60,000, engagement 4.2%
- TikTok: alcance 90,000, engagement 6.1%
- YouTube: alcance 40,000, engagement 3.5%

Funnel de ventas (ejemplo):
- Impresiones totales: 200,000
- Clics al link: 15,000
- Ventas generadas: 300

Estructura visual esperada: 

-primero explícame la estructura de secciones del dashboard que vas a usar, y espera mi confirmación antes de generar el HTML completo.

-Haz tres bloques de esta  manera: 
    -bloque superior (KPIs): quiero que muestres comisión total, tasa de conversión, engagement rate promedio.
    -bloque intermedio (Drivers): factores que quiero comparar rendimiento por plataforma, rendimiento por producto, funnel de conversión.
    -bloque inferior (detalle operacional): 
    tabla de productos : precio, unidades vendidas, comisión generada, conversión (sin columna de ROI, no se incluyen datos de coste en este ejercicio).
    -tabla de plataformas, 
    -top productos.

-Criterios de calidad 
    HTML semántico (<header>, <nav>, <main>, <section>, <table>, etc.)
    Solo clases utility de Tailwind, sin CSS personalizado adicional
    Diseño mobile-first con breakpoints sm:, md:, lg:
    Componentes reutilizables (que las "cards" de KPI compartan la misma estructura visual entre sí)

diseño visual del dashboard : se inspire en este estilo:

- Fondo general gris muy claro, tarjetas blancas con esquinas redondeadas y sombra suave
- El bloque de KPIs debe verse como una tarjeta grande con el valor principal, 
  un indicador de variación en una etiqueta de color (verde/rojo), y opcionalmente 
  un mini gráfico de línea o barras dentro de la misma tarjeta
- Para el driver "rendimiento por plataforma", usa un diseño de lista con ícono 
  de cada red social a la izquierda, nombre, cifra principal y una etiqueta de 
  variación en color a la derecha (como una fila de tabla simplificada)
- Puedes usar un donut/pie chart para visualizar alguna proporción si aplica 
  (por ejemplo, distribución de comisión por producto)
- Mantén exactamente los mismos 3 bloques, los mismos KPIs/drivers/tablas 
  y los mismos datos que ya definimos — solo cambia el estilo visual, 
  no el contenido ni la estructura de información.
 