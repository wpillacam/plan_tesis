# Tesis de pregrado

**"Aplicación de una metodología con criterios técnicos y regulatorios para la
selección de tecnologías de interfaz de usuario en instituciones bancarias"**

Bach. Willian José Pillaca Meneses — Facultad de Ingeniería Industrial y de
Sistemas, Universidad Nacional de Ingeniería (UNI).

## Compilar

Requiere una distribución TeX Live/MacTeX con `latexmk`, `pgfplots` y
`pgf-pie`.

```bash
latexmk -pdf main.tex
```

El PDF generado (`main.pdf`) también se mantiene versionado en este
repositorio para poder consultarlo sin compilar.

## Estructura

- `0_0_PREAMBULO/` — clase, paquetes y datos generales del documento.
- `1_0_CARATULA/` … `1_7_SIMBOLOS/` — preliminares (carátula, resumen,
  abstract, prólogo, símbolos y siglas).
- `2_CAPITULO1/` … `2_CAPITULO4/` — cuerpo de la tesis.
- `3_1_CONCLUSIONES/` … `3_4_ANEXOS/` — cierre (conclusiones,
  recomendaciones, bibliografía, anexos).
- `main.tex` — documento maestro que ensambla todas las partes.
