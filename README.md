# Vaya Baya

Bowls de avena, yogurt griego y fruta, más café. Dark kitchen en la Colonia Obrera, CDMX.
Este repo guarda la identidad de la marca y las fotos del menú.

Calculadora de costos y precios: https://hackerjj.github.io/proyectobowl/

## Estructura

```
logos/
  frambuesa/   fondo frambuesa, letras vainilla
  vainilla/    fondo vainilla, letras frambuesa
  favicon/     íconos para web (16, 32, 512 px) y apple-touch-icon (180 px)
fotos/
  originales/  fotos del menú en 2048 x 2048, sin tocar
  web/         las mismas en 1200 x 1200, comprimidas (~200 KB) para Uber, Rappi y redes
```

## Logos

Cada color viene en tres formatos:

| Archivo | Formato | Para qué |
|---|---|---|
| `*-2-lineas.png` | Cuadrado, "VAYA / BAYA" en dos renglones | Foto de perfil en Uber Eats, Rappi, Instagram y WhatsApp; stickers |
| `*-1-linea.png` | Cuadrado, una sola línea | Publicaciones cuadradas, etiquetas anchas |
| `*-horizontal.png` | Banner 4296 x 1256 | Portada de la tienda, encabezados, menú impreso |

La versión principal es **frambuesa**. Vainilla es para fondos oscuros o para variar en redes.

## Colores

| Color | HEX | RGB |
|---|---|---|
| Frambuesa | `#7A1F37` | 122, 31, 55 |
| Vainilla | `#EDE3B2` | 237, 227, 178 |

## Fotos del menú

| Archivo | Producto |
|---|---|
| `bowl-apple.jpg` | Apple Bowl |
| `bowl-baby.jpg` | Baby Bowl |
| `bowl-baya.jpg` | Baya Bowl |
| `bowl-choco.jpg` | Choco Bowl |
| `bowl-monkey.jpg` | Monkey Bowl |
| `bowl-tropi.jpg` | Tropi Bowl (temporada) |

Para subir a las apps usa las de `fotos/web/`. Antes de subirlas, revisa en el panel de
cada app el tamaño y la proporción que piden; si piden otro formato, recorta desde
`fotos/originales/`.

## Documentos fiscales

Los documentos del SAT (constancia de situación fiscal, etc.) **no van en este repo**
mientras sea público. Se guardan aparte, en una carpeta privada.
