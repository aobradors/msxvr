---
name: "VR-Script MSXVR"
description: "Contexto, sintaxis y reglas de VR-Script para MSXVR en archivos .pi"
applyTo: "**/*.pi"
---

# Instrucciones globales para MSXVR y archivos VR-SCRIPT (.pi)

## 1. Archivos .pi

Los archivos con extensión `.pi` corresponden a código VR-SCRIPT
utilizado por el sistema MSXVR.

Cuando trabajes con un archivo `.pi`, debes interpretarlo como código
VR-SCRIPT para MSXVR.

Estas instrucciones se aplican a:

- Crear archivos `.pi`.
- Modificar archivos `.pi`.
- Corregir errores.
- Depurar código.
- Explicar código.
- Analizar código existente.
- Añadir funcionalidades.
- Adaptar código VR-SCRIPT existente.

No debes interpretar un archivo `.pi` como código de otro lenguaje.


# 2. Documentación técnica oficial

La documentación oficial de MSXVR se encuentra en:

http://msxvr.es/doc/wiki/index.html

Para trabajar con archivos `.pi` y VR-SCRIPT, las tres secciones
principales de referencia son:

1. MSXVR
2. VR-SCRIPT
3. Tutoriales

Estas secciones tienen prioridad sobre cualquier conocimiento general
del modelo.

Las secciones de VR-BASIC, VR-DOS, MSXLIB y otras partes de la
documentación no deben utilizarse como referencia principal para código
VR-SCRIPT, salvo que la tarea concreta requiera información relacionada
con ellas.


# 3. Documentación MSXVR

Utiliza estas páginas cuando la tarea requiera información sobre el
sistema MSXVR, su hardware, funcionamiento, dispositivos, máquinas
virtuales o características generales del sistema.

## MSXVR - Documentación general

- Editorial:
  http://msxvr.es/doc/wiki/mdwiki.html#!e4c0b63fa3369a8ba8d7080cf95edd593deb1afa.md

- Prólogo:
  http://msxvr.es/doc/wiki/mdwiki.html#!acb087ab6d6d2090c7833d7f9d2488e282e74ea7.md

- Concepto y Términos:
  http://msxvr.es/doc/wiki/mdwiki.html#!503d2b25dd9786a96ca80c6835eebaec37628546.md

- Resumen General:
  http://msxvr.es/doc/wiki/mdwiki.html#!06d6635c74a00faf9d6a66490aaf9f6cedd9c843.md

- ¿Qué es un MSXVR "Virtualizer"?:
  http://msxvr.es/doc/wiki/mdwiki.html#!cc029b554c0eb3fbc0fd3b0ec643c69dd121682b.md

- Encendido del MSXVR "Virtualizer":
  http://msxvr.es/doc/wiki/mdwiki.html#!e6e6ef0118c59d6cda056832bfe55a14779ab6d9.md

- Cartuchos en un MSXVR "Virtualizer":
  http://msxvr.es/doc/wiki/mdwiki.html#!887e05659a1785011337470fae1d87dab7606045.md

- Teclado de un MSXVR "Virtualizer":
  http://msxvr.es/doc/wiki/mdwiki.html#!cf178c7f267a84d03e1391dcf2dfb2a79748f2fa.md

- ¿Qué es un MSXVR "Pocket"?:
  http://msxvr.es/doc/wiki/mdwiki.html#!5584cfc7abe08c59ba2aed2ea8847d7791c5aedf.md

- Encendido del MSXVR "Pocket":
  http://msxvr.es/doc/wiki/mdwiki.html#!3324865900c72eac7c927a5d1589abb1ec6bfc24.md

- ¿Qué es un MSXVR "Quantum"?:
  http://msxvr.es/doc/wiki/mdwiki.html#!0a061c7888e87cda4dc04e5ec2ceaca52a3606c9.md

- Encendido del MSXVR "Quantum":
  http://msxvr.es/doc/wiki/mdwiki.html#!f361a4598e1cf474ef12f20051e08fd989af5b58.md

- Software:
  http://msxvr.es/doc/wiki/mdwiki.html#!5c5944a31ecee921acac6f1d2366a23214e745e3.md

- Máquinas Virtuales:
  http://msxvr.es/doc/wiki/mdwiki.html#!401d857654f5fe10929cdfa28e0527cb24f2f67a.md

- Joysticks:
  http://msxvr.es/doc/wiki/mdwiki.html#!f37499501f88f49f16712a6a4eb3a491199c40ca.md

- Dispositivos:
  http://msxvr.es/doc/wiki/mdwiki.html#!009d4cbc832eb0b87ed9f99aff407d64e75961ee.md


# 4. Documentación VR-SCRIPT

Estas páginas constituyen la referencia principal para trabajar con
archivos `.pi`.

Cuando una tarea implique sintaxis, funciones, variables, tipos,
estructuras, objetos, eventos, API o cualquier otra característica de
VR-SCRIPT, consulta primero las páginas relevantes de esta sección.

## Lenguaje y sintaxis

- ¿Qué es VR-SCRIPT?:
  http://msxvr.es/doc/wiki/mdwiki.html#!0c33290424928d47863874b9fcaf3c3a94333917.md

- Palabras reservadas:
  http://msxvr.es/doc/wiki/mdwiki.html#!92d8861e8028c18a15a5111f7b8c56833ecab26e.md

- Estructura del archivo:
  http://msxvr.es/doc/wiki/mdwiki.html#!5b31456b93cedc5365cb74b52c14596080115180.md

- Tipos:
  http://msxvr.es/doc/wiki/mdwiki.html#!4ac3f918e940e95e8ebccd556b84e5199bffd54c.md

- Propiedades:
  http://msxvr.es/doc/wiki/mdwiki.html#!e98111fefbd223362dce0c8a33da9d91839d7926.md

- Funciones:
  http://msxvr.es/doc/wiki/mdwiki.html#!59a11ef5cffe56773b639a350f2d0d0823c8508d.md

- El preprocesador:
  http://msxvr.es/doc/wiki/mdwiki.html#!af1bd4383afdc0c7ecd1aac335525330e8a3fb4d.md

- Pragmas:
  http://msxvr.es/doc/wiki/mdwiki.html#!5e08c0b76febefadcd164eec443fbda266c5eb88.md

- Operadores:
  http://msxvr.es/doc/wiki/mdwiki.html#!9761da6675dcac2109553b9b746cad66a08295ac.md

- Strings:
  http://msxvr.es/doc/wiki/mdwiki.html#!ede4ff1467cf42d930f434e1851e72a02122d380.md

- Listas:
  http://msxvr.es/doc/wiki/mdwiki.html#!dcd529dd52419a74e0929c174c2bf96249ccc4f2.md

- Matrices:
  http://msxvr.es/doc/wiki/mdwiki.html#!e7e8cf97b2b034fbb0487581a610da7e4221d25b.md

- Diccionarios:
  http://msxvr.es/doc/wiki/mdwiki.html#!07c90517cf64f72dfbc9b224ffcda8a3c4dec83b.md

- Estructuras de control:
  http://msxvr.es/doc/wiki/mdwiki.html#!7a0242ca443f7123886d865b1655c22ca7fc7c43.md


## Programación orientada a objetos

- Creación y borrado de instancias:
  http://msxvr.es/doc/wiki/mdwiki.html#!4f93aadc8e3e53c6b17d0e4de2f581208b93d558.md

- Herencia de clases:
  http://msxvr.es/doc/wiki/mdwiki.html#!77f4b53473e9a30ac80844507ae00e629a76bb2e.md

- Partials:
  http://msxvr.es/doc/wiki/mdwiki.html#!8880e045009beedcc3c9ffe58c016417ca73a270.md

- Máquina de estados:
  http://msxvr.es/doc/wiki/mdwiki.html#!6739143e1a02041edf736e2ff7e507fea670c99e.md

- Sobrecarga de operadores:
  http://msxvr.es/doc/wiki/mdwiki.html#!b4fc3e012385c9b04955ad9d4040126b12c7e047.md

- instanceof:
  http://msxvr.es/doc/wiki/mdwiki.html#!e9d0b90fdea230f41a10e86df40dd1e3e844a34b.md

- Implements:
  http://msxvr.es/doc/wiki/mdwiki.html#!f38dbbc65ec7f1687c1a2b3b8d73f47985ebf4e8.md


## Ejecución y características avanzadas

- Evaluación de expresiones al vuelo:
  http://msxvr.es/doc/wiki/mdwiki.html#!e57e2befb6a9aa8859899e5574f0d79f260b39d3.md

- Ejecución de código al vuelo:
  http://msxvr.es/doc/wiki/mdwiki.html#!1c0046817ac9c7c31a6ec4221247d4fb439b6689.md

- Optimizaciones:
  http://msxvr.es/doc/wiki/mdwiki.html#!959daf53296dd4d19c052c42d5eabe6e65bdb3f0.md

- Engine del sistema:
  http://msxvr.es/doc/wiki/mdwiki.html#!6b90fbe3c7ecf32f74f8a3e5ef7eda37bad3b420.md


## Aplicaciones y sistemas relacionados

- Aplicación VR-DOS:
  http://msxvr.es/doc/wiki/mdwiki.html#!3a1ba4652ab1648dff7b8832d3df3a75c8db9044.md

- Aplicación VR-VIEW:
  http://msxvr.es/doc/wiki/mdwiki.html#!a635824c6017f333023c8976c059e4fa4bd74c8d.md

- Aplicación VR-BASIC:
  http://msxvr.es/doc/wiki/mdwiki.html#!8383356594f2de84c28fc5c92044f0333520e01a.md

- Aplicación VR-GL:
  http://msxvr.es/doc/wiki/mdwiki.html#!740c41829fcbf3d511733bf71ab0a26a2897e19e.md


## Gráficos y hardware

- Colisiones con Sprites (sin físicas):
  http://msxvr.es/doc/wiki/mdwiki.html#!09d21145c1efb12160c43a183ec627fe404b512b.md

- Uso de VR-SCRIPT para generar código ASM:
  http://msxvr.es/doc/wiki/mdwiki.html#!3230002d589416bcf4e800c3c007dc6d8c4c6afb.md

- Programación del VR-9968:
  http://msxvr.es/doc/wiki/mdwiki.html#!74d2271419d0f30db98595fcfb9b08d04dd28007.md

- Programación del VR-8000:
  http://msxvr.es/doc/wiki/mdwiki.html#!b5a25d4cf2ccb9565ee61b19b36cd9e069b1bf32.md


## API y teclado

- Funciones del API Nativo:
  http://msxvr.es/doc/wiki/mdwiki.html#!d88cec679f4796399dcdb7966c3022a03d9b3c3c.md

- Constantes de teclado:
  http://msxvr.es/doc/wiki/mdwiki.html#!b6162dd6dd490bfb47532d5553ab6f35c22de00c.md

- Ejemplos:
  http://msxvr.es/doc/wiki/mdwiki.html#!3c6a7a4429f857c7f5176cb939671d8566c2ddf6.md


# 5. Tutoriales

Los siguientes tutoriales deben utilizarse como referencia práctica cuando
exista un ejemplo relacionado con la tarea que se está realizando.

- Editar y ejecutar scripts:
  http://msxvr.es/doc/wiki/mdwiki.html#!b87aa1e417c98b8bc427a5549492b2af55ce3dbe.md

- Tutorial Monkey Demo:
  http://msxvr.es/doc/wiki/mdwiki.html#!8c3ea9e6dc651de43a7c1c03f73d5e012e27b6a4.md

- Postal Navideña en VR-Script + GL:
  http://msxvr.es/doc/wiki/mdwiki.html#!5277de2f5f39ff1e4a7e3cf529ec8ea7813651e9.md

- Tileset PNG + TSC:
  http://msxvr.es/doc/wiki/mdwiki.html#!53002f97b5cbb81dcdcc410c135a24a7996decef.md

- TMX Loader:
  http://msxvr.es/doc/wiki/mdwiki.html#!797eac4fb909c806d90c449cf05d47d0577e64f3.md

- Mad Mix Game Tribute:
  http://msxvr.es/doc/wiki/mdwiki.html#!1f924b10c97af57fcedc7e3d7984750bdf321ab9.md

- Space Invaders Tribute:
  http://msxvr.es/doc/wiki/mdwiki.html#!80399349b091c47005acd941d84f5136899d3dc4.md

- Green House Game & Watch en VR-Script + GL:
  http://msxvr.es/doc/wiki/mdwiki.html#!61a77730b8f5d5b7f72fb21a80709518ca2367f5.md

- Un juego sencillo de plataformas en VR-Script + GL:
  http://msxvr.es/doc/wiki/mdwiki.html#!57872065471b25cd1da9dfd2e1f4d434fb8f00d4.md


# 6. Documentación local adicional

Además de la documentación web oficial, existen dos documentos PDF
locales con información adicional sobre MSXVR y su programación.

## MSXVR Programming Book

Ruta:

D:\AGUSTI\DOCUMENTS\MSX\MSXVR\Documentacio\MSXVR_PROGRAMMING_BOOK_ve_ES.pdf

Este documento contiene información relacionada principalmente con la
programación de MSXVR y VR-SCRIPT.

Debe consultarse cuando la documentación web no sea suficiente o cuando
pueda proporcionar información adicional, ejemplos o explicaciones
relevantes para la tarea.

## MSXVR Service Manual

Ruta:

D:\AGUSTI\DOCUMENTS\MSX\MSXVR\Documentacio\service_manual_ES.pdf

Este documento contiene información técnica general sobre MSXVR,
hardware, funcionamiento y características del sistema.

Debe consultarse cuando una tarea requiera información técnica sobre
el funcionamiento del MSXVR o sobre aspectos de hardware que no estén
suficientemente documentados en la documentación web.

## Acceso a los documentos PDF

Cuando necesites información contenida en uno de estos documentos,
intenta acceder directamente al archivo utilizando las herramientas
disponibles en el entorno Agent.

No supongas el contenido de un PDF si no has podido abrirlo o
consultarlo.

Si el archivo no puede ser leído directamente, indícalo claramente y
continúa utilizando las fuentes web disponibles.


# 7. Procedimiento obligatorio al trabajar con .pi

Cuando trabajes con un archivo `.pi`, sigue este procedimiento:

1. Identifica qué característica de VR-SCRIPT o MSXVR está relacionada
   con la tarea.

2. Consulta mediante `web_fetch` la página de documentación de
   VR-SCRIPT que corresponda.

3. Si la tarea depende del funcionamiento general del MSXVR, consulta
   también la página correspondiente de la sección MSXVR.

4. Consulta la documentación PDF local cuando pueda aportar información
   relevante:

   - MSXVR_PROGRAMMING_BOOK_ve_ES.pdf
   - service_manual_ES.pdf

5. Si existe un Tutorial relacionado con la funcionalidad que se quiere
   implementar, consulta dicho Tutorial.

6. Analiza el código `.pi` existente y los archivos relacionados del
   proyecto.

7. Comprueba que la solución propuesta sea compatible con la
   documentación consultada.

8. Solo después propone o modifica el código.

No es necesario consultar todas las páginas de documentación para cada
tarea. Consulta únicamente las páginas relevantes.

Sin embargo, para cualquier característica específica de VR-SCRIPT que
no conozcas con certeza, debes consultar la documentación antes de
afirmar que una determinada sintaxis, función o comportamiento es
válido.


# 8. No inventar sintaxis ni funciones

No asumas que una instrucción, función, propiedad, clase, método o
parámetro existe en VR-SCRIPT simplemente porque exista en otro
lenguaje.

Especialmente, no extrapoles automáticamente características de:

- BASIC
- VR-BASIC
- C
- C++
- Python
- JavaScript
- otros lenguajes.

Si una característica no puede confirmarse en la documentación de
VR-SCRIPT, indícalo claramente.

No inventes funciones ni sintaxis para completar una solución.


# 9. Prioridad de las fuentes

Cuando exista discrepancia entre distintas fuentes, utiliza este orden:

1. Documentación específica de VR-SCRIPT.
2. Documentación oficial de MSXVR.
3. MSXVR Programming Book.
4. Tutoriales oficiales de MSXVR.
5. MSXVR Service Manual, cuando se trate de aspectos técnicos del
   sistema o hardware.
6. Código `.pi` existente en el proyecto.
7. Ejemplos de VR-SCRIPT/MSXVR existentes en el proyecto.
8. Conocimiento general del modelo.

La documentación específica de VR-SCRIPT y MSXVR tiene prioridad sobre
el conocimiento general del modelo.

Cuando una cuestión sea específicamente de hardware o servicio técnico,
el MSXVR Service Manual puede tener prioridad sobre las demás fuentes.


# 10. Compatibilidad

Todo código creado o modificado debe ser compatible con VR-SCRIPT y
MSXVR.

No sustituyas VR-SCRIPT por VR-BASIC ni por otro lenguaje.

Cuando modifiques código existente, conserva su estructura y
funcionamiento siempre que sea posible.

No realices cambios de arquitectura o estilo que no sean necesarios
para la tarea solicitada.


# 11. Documentación insuficiente o inaccesible

Si no puedes acceder a la documentación o la información disponible no
permite confirmar una característica:

- Indícalo claramente.
- No inventes una solución.
- No presentes como válida una función que no hayas podido confirmar.
- Utiliza, cuando sea posible, el código existente y los ejemplos del
  proyecto como referencia.
- Si utilizas conocimiento general del modelo que no ha podido ser
  confirmado en la documentación oficial, indícalo explícitamente.


# 12. Respuesta

Cuando hayas consultado documentación oficial para resolver una cuestión
técnica, indica brevemente qué página o páginas has utilizado.

Si has utilizado uno de los PDF locales, indica cuál de ellos ha sido
consultado.

Si existe incertidumbre sobre una característica concreta de VR-SCRIPT,
indícala explícitamente.

---