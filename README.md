# Decantadores circulares: modelo 3D y memoria de cálculo

Aplicación web de una sola página (sin login, sin servidor) que:

- Modela en 3D decantadores circulares **primario** y **secundario**.
- Muestra la **memoria de cálculo** con fórmulas y resultados.
- Permite cambiar de vista (planta, frontal, perfil, isométrica).
- Exporta un **DXF para AutoCAD** (R2000, metros): el espacio modelo trae planta, cortes y modelo 3D, y además **3 layouts** («01 PLANTA», «02 CORTES», «03 ISOMETRICA») con hoja ISO A1/A2/A3 *full bleed*, viewports a escala y membrete.
- Pestaña **Planos y membrete**: elige el tamaño de hoja, sube tu logo y escribe los datos del membrete (institución, proyecto, ubicación, código, dibujó/revisó/aprobó, fecha).
- Exporta la **memoria de cálculo a PDF** con ese membrete en el encabezado y pie de cada página (se abre el cuadro de impresión: «Guardar como PDF»).

## Uso

Abrir la URL publicada, elegir el modo (primario/secundario), ajustar los parámetros y revisar las pestañas. Para uso local basta abrir `index.html` (Three.js r128 va incluido en `vendor/`, no requiere internet).

## Créditos

UPeU – Ingeniería Ambiental, curso *Tratamiento de Aguas Residuales*.
Método de cálculo: Cap. 12 «Decantadores», R. Isla de Juana.
Three.js r128 (MIT) – https://threejs.org
