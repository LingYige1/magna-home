# Magna · Home v3 en código

Réplica del frame "Home — Desktop 1440 · v3" (Figma, página 04 · UI — Home).
HTML + CSS + JS sin dependencias. Abre `index.html` en el navegador.

## Fotos
Ya vienen incluidas y optimizadas en `assets/img/`.

## Animaciones e interacciones
- Hero: la foto se asienta con un zoom lento, el titular entra por líneas y luego bajada, botones y navbar.
- Navbar adaptativa: detecta el fondo que tiene debajo. Sobre fotos (hero y cierre) usa vidrio con tinte verde y texto Luz; sobre secciones claras pasa a Luz 94 % con texto Tierra. Transición de 240 ms. El texto nunca baja de 4,5:1.
- Nav links: subrayado crece de izquierda a derecha (220 ms).
- Botón primario: invierte color en hover. Secundario vidrio: sube al 24 %. Las flechas no se mueven.
- Enlaces: la flecha se separa del texto (estado hover del componente Enlace).
- Pilares: la línea superior se dibuja y aparece el contenido.
- Test: los tres anillos se completan en barrido.
- Proceso: la línea avanza y los pasos aparecen en orden.
- Manifiesto: las ondas se expanden desde el centro, luego puntos, conectores y anotaciones; después una onda pulsa en bucle lento.
- Cierre: el wordmark sube desde el borde inferior.
- Testimonios: carrusel funcional (flechas, contador y barra de progreso).
- Mobile: menú desplegable y layouts apilados.
- Respeta "reducir movimiento" del sistema.

## Para Shopify
Los enlaces apuntan a anclas del home. Cambia los `href` por las URLs reales
(/pages/agenda, /pages/sobre-magna, etc.) al pasar al tema.
