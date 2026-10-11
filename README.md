# 🧀 Quesos de Italia

Mapa interactivo de quince quesos italianos, desarrollado a partir de un trabajo práctico de la materia **Pastas Artesanales** (CFL 405, docente Joel Sosa).

**🔗 Ver la página:** https://marcelodvpm.github.io/Quesos-de-Italia/

<img width="740" height="740" alt="QR_Quesos_de_Italia" src="https://github.com/user-attachments/assets/2e30ab1c-8bec-489b-ac97-822189cf3589" />
[Código QR de la página](QR_Quesos_de_Italia.png)

## ¿Qué es?

Una página web de un solo archivo que muestra un mapa ilustrado de las regiones de Italia con sus quesos representativos. Cada queso es un punto numerado: al hacer clic aparece una ficha con:

- el **tipo de queso** y su **región de origen**;
- una **breve descripción**, tomada del trabajo escrito;
- los datos de su **denominación** (DOP, IGP o STG) y de su **consorcio**;
- un **enlace al sitio oficial del consorcio**, cuando existe.

Debajo del mapa hay una botonera con los nombres de los quesos, pensada para usar la página cómodamente desde el celular.

## Los quince quesos

| # | Queso | Tipo | Región |
|---|-------|------|--------|
| 1 | Parmigiano Reggiano | Duro de largo estacionamiento | Emilia-Romaña |
| 2 | Grana Padano | Duro de largo estacionamiento | Llanura del Po |
| 3 | Pecorino Romano | Duro de largo estacionamiento | Lacio / Cerdeña |
| 4 | Provolone | Duro / semiduro de pasta hilada | Lombardía y Véneto |
| 5 | Asiago | Semiduro | Véneto y Trentino |
| 6 | Fontina | Semiduro | Valle de Aosta |
| 7 | Montasio | Semiduro | Friuli-Venecia Julia |
| 8 | Scamorza | Semiduro de pasta hilada | Abruzzo y Molise |
| 9 | Taleggio | Blando de corteza lavada | Lombardía |
| 10 | Gorgonzola | Blando / semiblando azul | Piamonte y Lombardía |
| 11 | Mozzarella di Bufala Campana | Pasta hilada fresca | Campania |
| 12 | Mozzarella fior di latte | Pasta hilada fresca | Campania y sur del Lacio |
| 13 | Burrata | Pasta hilada fresca rellena | Puglia |
| 14 | Ricotta | Derivado del suero | Toda Italia (Sicilia) |
| 15 | Mascarpone | Derivado de la crema | Lombardía |

## Contenido del repositorio

| Archivo | Descripción |
|---------|-------------|
| `index.html` | La página completa (HTML, CSS y JavaScript en un solo archivo; el mapa va incrustado). |
| `QR_Quesos_de_Italia.png` | Código QR que apunta a la página. Se imprime al final del trabajo escrito. |
| `README.md` | Este archivo. |

## Cómo funciona

- No necesita instalación, servidor ni dependencias: es HTML, CSS y JavaScript puro.
- El mapa es una imagen incrustada en el propio `index.html`; los puntos se ubican encima con coordenadas en porcentaje, así que se adaptan al tamaño de la pantalla.
- Los datos de los quince quesos están en un arreglo `D` dentro del script, al final de `index.html`. Para corregir un texto, cambiar un enlace o mover un punto, se edita ese arreglo (`d` = descripción, `e` = denominación y consorcio, `u` = enlace, `x` e `y` = posición en el mapa).
- Se adapta al modo claro y oscuro del dispositivo.

Para verla en tu computadora, alcanza con abrir `index.html` en el navegador.

## Cómo publicarla con GitHub Pages

1. Subí `index.html` y `QR_Quesos_de_Italia.png` a la raíz del repositorio.
2. Entrá a **Settings → Pages**.
3. En **Source** elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guardá.
4. Pasado un minuto o dos, la página queda disponible en la dirección de arriba.

## Fuentes

- Los textos descriptivos provienen del trabajo práctico escrito.
- Los datos de denominaciones y consorcios corresponden a los consorcios de tutela citados en la bibliografía del trabajo: Parmigiano Reggiano, Grana Padano, Pecorino Romano, Gorgonzola, Taleggio, Asiago, Montasio, Provolone Valpadana y Mozzarella di Bufala Campana.
- Fontina cuenta con su propio consorcio de tutela; Scamorza, fior di latte, ricotta y mascarpone no tienen consorcio propio, y para la burrata (IGP Burrata di Andria) no se incluye enlace.

> ⚠️ Los datos de cada ficha son de carácter informativo y educativo. Se recomienda contrastarlos con los sitios oficiales de cada consorcio.

## Créditos

- **Trabajo práctico:** Latina Hernán — Pastas Artesanales, CFL 405. Docente: Joel Sosa.
- **Mapa ilustrado:** imagen aportada por el autor del trabajo. Si se reutiliza fuera de este proyecto, conviene verificar su origen y derechos de uso.
- **Página web:** desarrollada con la asistencia de Claude (Anthropic).

## Licencia

Proyecto con fines educativos. Si querés que otras personas puedan reutilizarlo, agregá un archivo `LICENSE` con la licencia que prefieras.
