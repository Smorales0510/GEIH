# GEIH · Observatorio del mercado laboral colombiano

Dashboard interactivo del mercado laboral de Colombia (2008–2026) a partir de los
microdatos de la Gran Encuesta Integrada de Hogares (GEIH) del DANE: empleo,
informalidad, demografía, educación, trabajo no remunerado y migración, a nivel
nacional, urbano/rural y por departamento (con mapa).

Es un **único archivo `index.html` autocontenido** (datos, estilos, fuente y
gráficos incrustados; sin dependencias ni internet).

## Ver en línea (GitHub Pages)

1. Subí **el contenido de esta carpeta** (`index.html` y `.nojekyll`) a la raíz de tu repositorio.
2. En el repo: **Settings → Pages**.
3. En *Build and deployment*, *Source* = **Deploy from a branch**.
4. *Branch* = **main** y carpeta **/ (root)** → **Save**.
5. Esperá 1–2 minutos. El sitio queda en `https://TU-USUARIO.github.io/TU-REPO/`.

> El 404 aparece cuando el archivo no se llama `index.html`: GitHub Pages sirve
> `index.html` en la raíz. Con este nombre se resuelve.

## Ver sin internet

Abrí `index.html` con doble clic; funciona igual en el navegador.

## Fuente de datos

GEIH — DANE, microdatos a nivel de persona, ponderados con el factor de expansión
oficial. Tasas según metodología DANE (TGP, TO, TD). La informalidad se calcula con
la definición propia de cada marco (2005: tamaño de empresa; 2018: protección social);
el cambio de marco 2018 (2022) se señala en las series.
