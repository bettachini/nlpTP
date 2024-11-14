# Diario del proyecto

## 2024-08-28

### Posibles proyectos
- Asesor legislativo en el sector de la regulación de la actividad nuclear.
    - Qué está xxx asesor de amrara el xxx
        - NORMAS: fuerza de ley
        - GUÍAS: dan números que se aplican a casos específicos
- Extensión a múltiples jurisdicciones

### Grafo
Knowledge graph: utilizarlo para linkear las normas.

Objetivo final: verificar que estamos cumpliendo las normas.

### Primer Paso
Armar el Knowledge Graphs

Cuando tengamos eso hecho, podemos usar el KG en un RAG. Podemos buscar y leer articulo de Microsoft (reciente) al respecto.

Si todo sale bien y rapido, podemos meternos a hacer Knowledge Graph Completion.


### Datasets 
https://www.argentina.gob.ar/anmat/normativa-general

### Compendio leyes nacionales > 1997
https://datos.gob.ar/dataset/justicia-base-infoleg-normativa-nacional

### Próximos pasos
1. Obtener links (idealmente ya las normas/leyes/etc) del sitio de ANMAT para generar conjunto de documentos.
   a. html: parsear el texto de la ley
   b. pdf: buscar libreria que genere texto plano.
2. Buscar conexiones entre normas para armar grafos.

Otra posibilidad:
Mirar la base de datos de leyes y tratar de armar un grafo con conexiones entre ellas. Seleccionar usando criterios de densidad y analizar alguna partecita.


## 
Chunks pues toda la normativa no entra.

