# BRIXEQ — Manual de Usuario en Español

Guía completa de BRIXEQ en español, en un único archivo HTML autocontenido (sin dependencias externas, sin CDN).

**Leer online:** https://alejandroid80.github.io/brixeq-manual/

## Contenido

1. Filosofía y flujo de trabajo
2. Estructura de un proyecto
3. Tu primer sonido
4. La pantalla principal (Editor)
5. Navegación y reproducción
6. Edición, selección y Randomize
7. Parámetros de cada paso
8. Los 8 motores de síntesis
9. Patrones, escalas y transposición
10. Escenas y Master Bus
11. Moduladores (LFOs)
12. Modo canción (Song Mode)
13. Grabación y guardado
14. Chuleta rápida de controles
15. Solución de problemas rápidos

## Uso local

Descarga `index.html` y ábrelo con doble clic en cualquier navegador, o:

```bash
python3 -m http.server 8000
# luego abre http://localhost:8000
```

## Estructura del repositorio

```
index.html   # El manual completo (HTML + CSS embebido)
README.md    # Este archivo
guia-lofi.html  # Guía rápida de loop LoFi en español (HTML embebido)
```

## Guía LoFi

Una guía paso a paso para crear un loop LoFi en BRIXEQ en un solo compás:

- **BPM:** 72–78 (lento, para que respire)
- **Shuffle:** 56–60% (groove humano)
- **Escala:** Re menor natural o Dórico
- **Patrón:** Bombo en pasos 0·6·10, caja con Snap, charles en pasos pares, acordes Re m9 (paso 0) / Sol m9 (paso 8), bajo Re3/Sol3
- **Filtro:** Hacia abajo (LP) en bombo y acordes; apertura media en charles
- **Efectos (R3):** Delay ping-pong 1/8 + Reverb sala media, Sidechain desde T1 (bombo)
- **Variaciones:** Copiar patrón a otra ranura (`R1+A`, `R1+B`) y crear variación B en escena distinta (`B` en la tira inferior)

Verla online: https://alejandroid80.github.io/brixeq-manual/guia-lofi.html

## Créditos

Manual creado a partir del proyecto **BRIXEQ** para TrimUI Brick. El diseño y la documentación originales provienen del repositorio [https://github.com/boorch/brixeq-pak](https://github.com/boorch/brixeq-pak) por **boorch**. Esta adaptación al español y la guía LoFi son obra de **alejandroid80**.

## Aviso sobre el uso de IA

La traducción del manual al español y la guía LoFi se han elaborado con **asistencia de un modelo de lenguaje** (OpenCode), partiendo de la documentación original de boorch y con revisión manual.

Aunque cada sección se ha comprobado, un texto generado con IA puede contener imprecisiones, erratas o parámetros que no coincidan exactamente con lo que muestra tu unidad. Si algo no encaja con tu TrimUI Brick, fíate de la máquina y del material original antes que de esta documentación. Las correcciones son bienvenidas.

> *Disclaimer: the Spanish translation and the LoFi guide were produced with AI assistance and manually reviewed. They may contain inaccuracies; always verify against the device.*

## Notas

- No usa JavaScript ni recursos remotos: funciona offline.
- Tema oscuro, diseño responsive y navegación por secciones.
