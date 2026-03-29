# my-skills

Repositorio de skills reutilizables para usar con Claude u otras IAs.

Una skill es un archivo `SKILL.md` que contiene metodología, reglas y contexto
sobre un tema concreto. Al pasárselo a Claude al inicio de una conversación,
puede responder con mucha más precisión sin necesidad de explicar el contexto desde cero.

## Cómo usar una skill

1. Abre una conversación nueva con Claude
2. Sube el archivo `SKILL.md` correspondiente como adjunto
3. Indica qué quieres hacer: "Usando esta skill, ayúdame a..."

## Skills disponibles

| Skill | Descripción | Versión |
|-------|-------------|---------|
| [running](./running/SKILL.md) | Planificación de entrenamiento de running. Metodología MAF + 80/20. | v4.0 |
| [nutrition](./nutrition/SKILL.md) | Próximamente | — |
| [productivity](./productivity/SKILL.md) | Próximamente | — |

## Cómo contribuir / actualizar

Cuando una skill mejore o se aprenda algo nuevo, actualizar el `SKILL.md`
correspondiente con la nueva versión y hacer commit con el número de versión.

Ejemplo de commit: `running skill v4.1 — añadir sección de nutrición deportiva`
