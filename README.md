# ZabaLABS · Web

Landings de los productos de ZabaLABS. Una carpeta por producto y cada una se publica
como su propio sitio estático (HTML + CSS + JS, sin build).

```
ZabaLABS-Web/
  README.md
  bar/                          landing del sistema de gestión de bares
    index.html                  la página (HTML + CSS + JS en un solo archivo)
    assets/
      img/                      fotos de archivo (dominio público)
      video/                    video en loop de la banda "El oficio no cambia"
      credits.json              autoría y licencia de cada imagen y video
```

Cuando haya otro producto (stock, iluminación, etc.) se agrega una carpeta hermana:
`stock/index.html`.

## Configuración de la landing de bar

Arriba de todo, en `bar/index.html`, hay dos valores:

- `--wa`: número de WhatsApp con código de país, sin `+` ni espacios.
- `--pago`: link de pago de MercadoPago. Vacío = no se muestra el botón de pago.

## Publicación

La landing de bar se sirve en <https://zabalabs.tech> como archivo estático.
El paso a paso de deploy y de alta de clientes **no va en este repo** (tiene datos del
servidor): se guarda en `bar/VENDER-PASO-A-PASO.txt`, que está en `.gitignore`.

## Imágenes y créditos (landing de bar)

Las fotos (`bar/assets/img/`) y el video (`bar/assets/video/`) son de dominio público (Wikimedia Commons). Los datos
de cada una están en `bar/assets/credits.json` y el crédito visible está en el pie de la página.
