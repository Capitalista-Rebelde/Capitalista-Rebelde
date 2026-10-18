# ADR 0006 — Apache-2.0 para código, CC BY-SA 4.0 para documentación

**Fecha** 2026-10 · **Estado** Aceptada · **Área** Gobernanza

## Contexto
La intención inicial era AGPL-3.0 para todo el código. AGPL obliga a que quien use el código abra el suyo, incluso ofreciéndolo como servicio.

## Decisión
Apache-2.0 para el código y CC BY-SA 4.0 para la documentación.

Queremos que las herramientas de curación y las calculadoras se adopten e integren en otros productos. AGPL lo impide en la práctica: nadie integra una dependencia que le obliga a abrir su propio código. La ventaja competitiva del proyecto no está en el código, sino en la calibración de MCC-1 (que no es pública) y en la red de ejecutores y verificadores (que no se puede copiar).

La documentación sí lleva cláusula de compartir igual: copiar la tesis citando la fuente está bien, apropiársela no.

## Alternativas descartadas
- AGPL-3.0 para todo: protege algo que no necesita protección y bloquea la adopción, que es lo que sí necesitamos.
- MIT: no incluye concesión expresa de patentes. Apache sí, y en este sector importa.
