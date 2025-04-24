# Módulo 2: Búsqueda Avanzada de Literatura Académica

## 2.1. Introducción
La búsqueda avanzada de literatura científica es una competencia clave para desarrollar investigaciones de calidad. Utiliza operadores booleanos y estrategias de filtrado para encontrar artículos relevantes en bases de datos académicas.

---

## 2.2. Principales bases de datos académicas
- **Google Scholar**: Búsqueda general de artículos, libros y tesis.
- **PubMed**: Literatura biomédica y ciencias de la salud.
- **Scopus**: Literatura multidisciplinaria, métricas de citación.
- **ScienceDirect**: Revistas científicas de Elsevier.
- **Redalyc**: Enfoque en ciencia abierta y acceso latinoamericano.
- **SciELO**: Biblioteca científica de acceso abierto.

---

## 2.3. Operadores y estrategias de búsqueda
- **AND**: Encuentra documentos que contengan *todos* los términos.
- **OR**: Incluye documentos que contengan *uno u otro* término.
- **NOT**: Excluye resultados que contengan ciertos términos.
- **" "**: Para búsquedas exactas por frase.
- **(*)**: Truncamiento para términos relacionados (ej. "educ*" = educación, educativo).

Ejemplo:
```text
("machine learning" OR "deep learning") AND "medical imaging" AND NOT "COVID-19"
```

---

## 2.4. Búsqueda avanzada con Google y Google Académico

A pesar de que Google es un motor de búsqueda generalista, con el uso adecuado de operadores lógicos se puede obtener información relevante para investigaciones científicas. Al realizar una búsqueda sin operadores ni filtros específicos, por ejemplo `de lo grande a lo pequeño`, puede arrojar millones de resultados, muchos de los cuales no serán pertinentes. En contraste, al utilizar comillas `"de lo grande a lo pequeño"` se delimita la búsqueda a esa frase exacta, reduciendo drásticamente el número de resultados y aumentando su precisión.

> **Principio clave**: *Entre más específica es la ecuación de búsqueda, mayor es la calidad y relevancia de los resultados.*

### 2.4.1. Conjunción lógica (AND / +)

La conjunción busca resultados que contengan **todos** los términos especificados, sin importar el orden. Por ejemplo:

```bash
"ingeniería electrónica" +"Manizales" +"Medellín"
```
<div style="text-align: center;">
    <img src="./recursos/conjuncion.png" alt="Conjuncion" style="width: 200px;"/>
</div>

Esto asegura que los resultados incluyan ambos términos geográficos junto a la frase exacta "ingeniería electrónica". Es útil para construir ecuaciones más precisas, en contraste con búsquedas amplias que ignoran relaciones clave entre los términos.

### 2.4.2. Negación (NOT / -) y Disyunción (OR / |)

- **Negación** (`-"palabra"`) elimina resultados que contengan un término no deseado:
  ```bash
  "ingeniería electrónica" -"UNAL"
  ```

- **Disyunción** (`OR`) busca resultados que incluyan cualquiera de los términos:
  ```bash
  "Carro" OR "Coche"
  ```
<div style="text-align: center;">
    <img src="./recursos/disyuncion.png" alt="Disyuncion" style="width: 200px;"/>
</div>

Estas herramientas son indispensables para filtrar ruido o ampliar la cobertura temática.

### 2.4.3. Intitle

La función `intitle:` permite encontrar páginas donde el término buscado aparece en el **título del documento**, indicando mayor relevancia:
```bash
intitle:"industria 4.0"
```

### 2.4.4. Comodín (*)

El asterisco `*` actúa como un comodín para representar cualquier palabra:
```bash
"cómo hacer * fritos"
```
Es útil cuando se desconoce un término exacto pero se quiere explorar un campo semántico específico.

### 2.4.5. Filetype

Limita la búsqueda a un tipo de archivo:
```bash
"industria 4.0" filetype:pdf
```
Ideal para investigaciones que requieren acceder a artículos completos, informes técnicos o tesis.

### 2.4.6. Google Académico

**Google Académico** es un motor de búsqueda especializado en literatura científica: artículos, tesis, libros y conferencias. A diferencia de una base de datos académica estructurada, es un motor que indexa contenidos disponibles públicamente o a través de editoriales académicas.

#### Funcionalidades clave:
- Operadores booleanos (`+`, `-`, `OR`, `" "`, `author:`) para refinar resultados.
- Filtros por fecha, idioma y ordenamiento por relevancia o fecha de publicación.
- Visualización de la cantidad de citas de cada artículo, útil para identificar estudios influyentes.
- Creación de alertas para notificar cuando se publiquen artículos relacionados con una ecuación específica.
- Opción para guardar artículos en la biblioteca personal del usuario.
- Acceso al perfil de autor donde se agrupan todos sus trabajos y estadísticas de citación.

> Para búsquedas más visuales, se puede emplear la opción de búsqueda avanzada, donde es posible seleccionar campos como título del artículo, nombre del autor o nombre de la publicación, sin necesidad de escribir manualmente operadores booleanos.

---

## 2.5. Búsqueda avanzada en bases de datos académicas

A diferencia de Google Scholar, estas bases de datos cuentan con estructuras indexadas y controladas por criterios editoriales y científicos. A continuación, se describen sus particularidades para búsquedas avanzadas:

### 2.5.1. Scopus

Scopus, desarrollada por Elsevier, es una de las bases más prestigiosas a nivel mundial. Permite realizar búsquedas avanzadas usando operadores booleanos y estructuras personalizadas como:

```bash
TITLE-ABS-KEY("machine learning" AND "medical imaging")
```

#### Características:
- Filtros por tipo de documento, autor, institución.
- Análisis por citas, área de conocimiento y geografía.
- Mayor cobertura en inglés.
- Posibilidad de exportar artículos a gestores como Mendeley o generar el DOI para localización directa.

### 2.5.2. SciELO

SciELO (Scientific Electronic Library Online) es una biblioteca científica de acceso abierto, con fuerte presencia en Latinoamérica y el Caribe. Aunque es más limitada que Scopus, permite búsquedas avanzadas mediante campos.

#### Herramientas:
- Filtros por título, autor, país, financiador.
- Orden por fecha, relevancia, citas.
- Exportación a gestores de referencia.

También permite ordenar por relevancia, fecha, idioma y número de citas. Al igual que otras plataformas, la combinación de filtros con operadores booleanos mejora significativamente la calidad de los resultados.

### 2.5.3. Redalyc

Redalyc (Red de Revistas Científicas de América Latina y el Caribe, España y Portugal) promueve el acceso abierto y la ciencia sin fines de lucro. Su plataforma no cuenta con una sección de búsqueda avanzada tan estructurada como otras bases, por lo que se recomienda utilizar:

```bash
"tema" site:redalyc.org
```
Esta estrategia, ejecutada desde Google Académico, permite limitar la búsqueda al dominio de Redalyc, accediendo a artículos directamente desde esa fuente.

### 2.5.4. PubMed

PubMed, administrada por la Biblioteca Nacional de Medicina de los EE. UU., se especializa en ciencias biomédicas y de la salud. Su sección Advanced Search permite:

- Buscar por autor, título, resumen, DOI, entre otros campos.
- Emplear el índice interno con la función "Show Index" para visualizar términos disponibles y su frecuencia.
- Guardar búsquedas y combinarlas para ecuaciones más complejas.
- Los resultados incluyen acceso a artículos en PubMed Central, muchos de ellos en acceso abierto.

> **Nota:** Es fundamental realizar búsquedas en inglés para acceder a una mayor cantidad y calidad de resultados.

### 2.5.5. ScienceDirect

ScienceDirect, también operada por Elsevier, permite acceder a artículos de alta calidad revisados por pares. Su función de búsqueda avanzada permite aplicar filtros por:

- Filtros por autor, título, tipo de documento.
- Buscador avanzado y guía de operadores en "Search Tips".

---

> **Nota:** El uso de operadores booleanos y filtros avanzados permite ajustar la estrategia de búsqueda según los objetivos del investigador. Estas técnicas son aplicables tanto en motores como en bases de datos académicas estructuradas.


## 2.6. Generación de ecuaciones de búsqueda con ChatGPT
ChatGPT puede ayudarte a crear estrategias de búsqueda según tus criterios. Por ejemplo:

**Entrada:** Quiero artículos sobre inteligencia artificial en diagnóstico médico sin incluir radiología.

**Salida sugerida por ChatGPT:**
```text
("artificial intelligence" OR "machine learning") AND "medical diagnosis" NOT "radiology"
```

Esta ecuación puede pegarse directamente en bases como Scopus o PubMed.

---

## 2.5. Recomendaciones prácticas
- Usar filtros por año, tipo de artículo, y acceso abierto.
- Guardar resultados en PDF o exportarlos a Mendeley.
- Documentar las ecuaciones utilizadas en tu investigación.

## Referencias
- Busqueda Avanzada con google - Aprende a Investigar: https://www.youtube.com/playlist?list=PLVlJEb-ZJEHGO3k3BaDszqIKGKX3Ry8AY
- Conjunción lógica: https://www.wikiwand.com/es/articles/Conjunci%C3%B3n_l%C3%B3gica
- Disyunción lógica: https://www.wikiwand.com/es/articles/Disyunci%C3%B3n_l%C3%B3gica
- Base de datos SCOPUS - Buscadores académicos confiables - Cómo buscar ARTÍCULOS CIENTÍFICOS: https://www.youtube.com/watch?v=Wu-WDSDaBXE
- Base de datos SCOPUS - BUSQUEDA AVANZADA DE ARTÍCULOS CIENTÍFICOS - Aprender a investigar: https://www.youtube.com/watch?v=ErUnP5l813s
- Búsqueda avanzada en SCIELO - Aprender a investigar: https://www.youtube.com/watch?v=WRCfpVR6IJU
- Búsqueda avanzada en REDALYC - Aprender a investigar: https://www.youtube.com/watch?v=VUz7TP3pYRI
- Búsqueda avanzada en PubMed: https://www.youtube.com/watch?v=m8aSV9QXJls
- Cómo buscar artículos científicos | PubMed | Información actualizada | Ciencias de la salud: https://www.youtube.com/watch?v=fg18CxUYym4
- ScienceDirect - Búsqueda avanzada - Operadores booleanos: https://www.youtube.com/watch?v=nAYXGYcAroo
- 
---

_Continuar con el Módulo 3: Uso de Mendeley para gestión bibliográfica._

