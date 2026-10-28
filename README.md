# ZabaLABS · Web

Landings de los productos de ZabaLABS. Una carpeta por producto y cada una se publica
como su propio sitio estático (HTML + CSS + JS, sin build).

```
ZabaLABS-Web/
  bar/
    index.html              landing del sistema de gestión de bares
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
