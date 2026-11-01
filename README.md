# Vaya Baya

Bowls de overnight avena cremosa con yogurt griego natural, fruta y toppings, más café.
Dark kitchen en la Colonia Obrera, CDMX. Este repo guarda la identidad de la marca, las fotos
y los textos del menú.

| Sitio | Link |
|---|---|
| Menú para clientes | http://vayabaya.foo.ng/ |
| Material para Uber Eats | https://vayabaya.foo.ng/uber.html |
| Menú en PDF | https://github.com/andvelasco/vayabaya/blob/main/menu/vaya-baya-menu.pdf |
| Calculadora de costos y precios | https://hackerjj.github.io/proyectobowl/ |

## Estructura

```
menu/
  descripciones.md    texto oficial de cada bowl (para leer y editar)
  descripciones.json  el mismo texto en formato que leen el menú y la página de Uber
  vaya-baya-menu.pdf  menú completo en PDF (A4): para Uber Eats, imprimir o compartir
logos/
  frambuesa/          fondo frambuesa, letras vainilla
  vainilla/           fondo vainilla, letras frambuesa
  favicon/            íconos para web (16, 32, 512 px) y apple-touch-icon (180 px)
fotos/
  originales/         fotos del menú en 2048 x 2048, sin tocar
  web/                las mismas en 1200 x 1200, comprimidas (~200 KB)
```

## Menú

Las descripciones viven en `menu/`. Cada bowl tiene tres partes: **base**, **fruta** y
**topping**. Para cambiar una descripción:

1. Edita `menu/descripciones.json` (es el que usan los sitios). Respeta las comillas y las
   comas; si algo se rompe, el menú vuelve a mostrar la lista de ingredientes automática.
2. Copia el mismo cambio en `menu/descripciones.md`, que es la versión para leer.

El menú y la página de Uber toman el cambio solos, en un par de minutos.

Los **precios** y qué bowl está **activo o agotado** no van aquí: se manejan en la
calculadora (Insumos y recetas) y el menú los lee en vivo.

## Logos

Cada color viene en tres formatos:

| Archivo | Formato | Para qué |
|---|---|---|
| `*-2-lineas.png` | Cuadrado, "VAYA / BAYA" en dos renglones | Foto de perfil en Uber Eats, Rappi, Instagram y WhatsApp; stickers |
| `*-1-linea.png` | Cuadrado, una sola línea | Publicaciones cuadradas, etiquetas anchas |
| `*-horizontal.png` | Banner 4296 x 1256 | Portada de la tienda, encabezados, menú impreso |

La versión principal es **frambuesa**. Vainilla es para fondos oscuros o para variar en redes.

## Colores

Solo dos colores de marca:

| Color | HEX | RGB |
|---|---|---|
| Frambuesa | `#7A1F37` | 122, 31, 55 |
| Vainilla | `#EDE3B2` | 237, 227, 178 |

## Fotos

| Archivo | Producto |
|---|---|
| `bowl-apple.jpg` | Apple Pay Bowl |
| `bowl-baby.jpg` | Baby Bowl |
| `bowl-baya.jpg` | Baya Bowl |
| `bowl-choco.jpg` | Choco Bowl |
| `bowl-monkey.jpg` | Monkey Bowl |
| `bowl-tropi.jpg` | Tropi Bowl (temporada de mango) |

**Importante:** estas seis fotos están generadas con IA (Google, con etiqueta C2PA y marca
SynthID). Sirven como guía de presentación. Para Uber Eats conviene reemplazarlas por fotos
reales del bowl en el contenedor de entrega, con el mismo acomodo y fondo liso. Las fotos
nuevas van con el mismo nombre en `fotos/originales/` y se regeneran las de `fotos/web/`.

## Documentos fiscales

Los documentos del SAT **no van en este repo** mientras sea público. Se guardan aparte, en
una carpeta privada.
