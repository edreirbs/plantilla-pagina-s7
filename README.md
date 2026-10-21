# Mi página

Una página pública con un formulario que guarda lo que la gente aparta, y una
lista que muestra lo guardado.

Construida en la **Sesión 7 del curso Claude for Business**, sin escribir código:
todo se le pidió a Claude en español.

## Cómo está armado

| Pieza | Qué hace |
|---|---|
| **GitHub** | Guarda este proyecto y su historial |
| **GitHub Pages** | Publica en internet lo que hay en `main` |
| **Supabase** | Guarda lo que la gente escribe en el formulario |

## Cómo se cambia

1. Se abre una sesión de Claude Code en la nube sobre este repositorio.
2. Se le pide el cambio **en una rama**, no en `main`.
3. Claude abre un **Pull Request**: ahí se revisa qué cambió.
4. Cuando está bien, se fusiona. Eso, y solo eso, publica.

## Qué NO va en este repositorio

La llave `sb_publishable_` sí puede estar aquí: está hecha para andar a la vista.
La que empieza con `sb_secret_` o dice `service_role`, **nunca**.
