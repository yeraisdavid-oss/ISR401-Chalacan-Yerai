# Ingeniería de Requerimientos — ISR-401

**Estudiante:** Yerai David Chalacan Toala  
**Universidad:** Universidad Técnica Estatal de Quevedo  
**Nivel y paralelo:** Cuarto nivel, paralelo A  
**Docente:** Gleiston Cicerón Guerrero Ulloa, PhD  

## FORM-TL-01 — Taller de tipos de requisitos

Análisis de los 20 enunciados del caso «Plataforma de gestión
de citas médicas» del Policlínico Ribera del Quevedo.

El documento contiene:

- Clasificación de los 20 enunciados por tipo, producto/proceso
  y sistema/software, con justificación.
- Características y subcaracterísticas de calidad
  de ISO/IEC 25010:2023.
- Reformulación de cinco requisitos vagos con métricas,
  unidades, umbrales y métodos de verificación.
- Comparación de criterios con un compañero.
- Referencias y declaración del uso de inteligencia artificial.

## Estructura

- `FORM-TL-01/main.tex`: fuente principal del documento.
- `FORM-TL-01/referencias.bib`: referencias bibliográficas.
- `FORM-TL-01/main.pdf`: documento compilado.
- `README.md`: descripción e instrucciones de compilación.

## Herramientas y dependencias

- Una distribución LaTeX: TeX Live o MiKTeX.
- Compilador pdfLaTeX / LuaLaTeX.
- Paquetes: inputenc, fontenc, babel con español, geometry,
  tabularx, booktabs, enumitem, xcolor, hyperref.
- Estilo bibliográfico IEEE.

## Compilación local

Clonar el repositorio:

```bash
git clone https://github.com/ChalacanYerai/ISR401-Chalacan-Yerai.git
cd ISR401-Chalacan-Yerai/FORM-TL-01
```

Ejecutar los comandos en este orden:

```bash
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

El resultado se genera como `main.pdf` dentro de `FORM-TL-01`.
Los comandos deben finalizar sin errores y las citas deben
aparecer resueltas.

## Compilación en Overleaf

1. Crear un proyecto en blanco.
2. Subir `main.tex` y `referencias.bib` en la misma carpeta.
3. Seleccionar `main.tex` como documento principal.
4. Seleccionar pdfLaTeX o LuaLaTeX como compilador.
5. Recompilar y comprobar que las referencias estén resueltas.
6. Descargar el resultado con el nombre `main.pdf`.

## Alcance de las propuestas

Los umbrales cuantificados son propuestas académicas para
el caso ficticio. No representan acuerdos con una organización
real ni resultados de pruebas ejecutadas.

La declaración del apoyo de inteligencia artificial se encuentra
en el documento principal.

## Entrega

El contenido del taller se encuentra en este repositorio.

En el SGA se entrega únicamente un PDF de una página con
los datos informativos y la URL completa del repositorio
en una sola línea.

Fecha límite actualizada según el SGA:
31 de octubre de 2026, a las 23:59.
