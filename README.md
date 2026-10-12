# Título Proyecto

## Miembros del grupo LX-XXX-X (sustituir)

1. Morales Márquez, Diego
2. Cabeza Curado, Hugo
3. Muñoz Pereira, Jesús
4. Morrondo Silva, Alejandro

## 1. Introducción al problema
El principal inconveniente a día de hoy en el ámbito de la arqueología se centra en la descentralización e inconsistencia en los formatos y criterios de registro de datos entre las distintas expediciones arqueológicas. La mayoría de expediciones no siguen una estructura definida debido a que muchas veces los datos se registran en cuadernos, ordenadores locales u hojas de cálculo resultando en derivaciones además del problema principal:

- Pérdida de seguimiento de los hallazgos: es complicado manejar y rastrear todo el recorrido que sufre una pieza desde su extracción hasta su destino final como puede ser un instituto público (museos o universidades) o almacenes.

- Desconexión entre personal y actividades: no existe un registro que dicte los diferentes tipos de trabajadores que participaron así como el  rol que desempeñaron en la expedición y las hazañas específicas logradas.

- Ineficiencia en el análisis: los restos óseos que se descubren requieren una descripción y clasificación detallada que la mayoría de las veces se resumen de forma excesiva y estas se pierden.
 
- Falta de información en museos: los museos reciben piezas con falta de información que no se ofrece ni es consultable haciendo esa información “invisible” al resto de los visitantes interesados.

Por ello, diversas empresas y museos necesitan centralizar sus datos para comprender mejor los hallazgos y profundizar en nuestro pasado. Con el objetivo de dar respuesta a esta necesidad, planteamos una base de datos accesible para clientes y usuarios que garantice la consistencia de la información y evite la pérdida del trabajo invertido.

- Falta de información en el museo: Las cartelas solo muestran datos básicos como la fecha o el material. Al no haber un registro digital desde la excavación, se pierde la historia completa de la pieza: quién la descubrió, cómo se halló y su contexto original.

- Cuadernos y códigos propios: Usar notas a mano y nomenclaturas personales hace que los datos solo los entienda quien los escribió. Sin un sistema común, es casi imposible cruzar esa información con el trabajo del resto del equipo.


## 2. Glosario de términos


- Términos específicos del dominio del problema, ordenados alfabéticamente. Se valorará la presencia de información multimedia.

## 3. Visión general del sistema

### 3.1. Requisitos generales

### 3.2. Usuarios del sistema

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

#### R.F.01. Título requisito funcional

Como [tipo de usuario]
quiero [servicio]
para [razón]

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### 4.1.1. Requisitos de información

##### R.I.01. Título requisito de información

Como [tipo de usuario]
quiero [servicio]
para [razón]

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- ...

#### 4.1.2. Reglas de negocio

##### R.N.01. Título regla negocio

Descripción de la regla de negocio.

### 4.2. Mapa de historias de usuario (opcional)

### 4.3. Requisitos no funcionales (opcional)

**R.N.F. 01. Título requisito no funcional**
Como [tipo de usuario]
quiero [servicio]
para [razón]

-- fin entregable 1 --

## 5. Modelo conceptual

### 5.1. Diagramas de clases UML

- con restricciones.

### 5.2. Escenarios de prueba

- con descripción textual y diagrama de objetos UML.

## 6. Matrices de trazabilidad

- Matriz de trazabilidad entre los elementos del modelo conceptual y los requisitos.

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:------|:-----------|:-----------|:-----------|:-----------|
| RI-1  | X          | X          | X          | X          |
| RI-2  |            | X          |            | X          |
| RF-1  |            | X          |            | X          |
| RF-2  | X          |            | X          | X          |
| RN-1  |            | X          |            |            |
| RN-2  | X          | X          | X          |            |
| ...   |            |            |            |            |

-- fin entregable 2 --

## 7. Modelo relacional en 3FN

- Relaciones obtenidas al aplicar la transformación del modelo conceptual.

### 7.1.  Justificación de la estrategia de transformación de jerarquías

- si se identificaron jerarquías en el MC.


### 8. Matriz de trazabilidad MC/SQL (opcional):

- Restricciones sobre el MC / Elementos del modelo tecnológico (SQL) (Triggers, checks, etc.)
- Incluir Reglas de negocio — Constraints/Triggers en las matrices de trazabilidad para el entregable 3

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:-------|:-------|:-------|:-------|:-------|
| TABLA-1 |        |        |        |        |
| TABLA-2 |        |        |        |        |
| TABLA-3 |        |        |        |        |
| TABLA-4 |        |        |        |        |
| TRIG-1 |        |        |        |        |
| TRIG-2 | X      | X      |        | X      |
| TRIG-3 |        | X      |        | X      |
| TRIG-4 |        |        | X      |        |
| CONST-1 |        |        |        |        |
| CONST-2 | X      | X      |        | X      |
| CONST-3 |        | X      |        | X      |
| CONST-4 |        |        | X      |        |

Se consideran todo tipo de constraints declarativas (aquellas definidas durante el CREATE TABLE).
-- fin entregable 3 --

## Referencias


