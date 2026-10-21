# CLAUDE.md

Este archivo lo lee Claude cada vez que trabaja en este repositorio, sin que se lo pidas.

---

## 1. Qué es este proyecto

La página pública de Boutique El Girasol para apartar prendas. La usan clientes desde su celular. Es material de práctica del curso Claude for Business.

## 2. De dónde sale cada cosa

- Las tres prendas y sus precios van escritos en la página: Vestido Casual $1,500, Pantalón Formal $1,200 y Blusa Estampada $700. Solo cambian cuando yo lo pida.
- Los apartados (prenda, talla y sucursal) se guardan en la tabla `apartados` de Supabase, y la lista de la página sale de esa tabla.
- No inventes apartados. Si la tabla está vacía, que la lista diga que todavía no hay apartados.

## 3. Cómo quiero que trabajes aquí

- Trabaja siempre en una rama, nunca directo sobre `main`.
- Al terminar, sube la rama, abre un Pull Request y dame su liga. Revisar el Pull Request es mi visto bueno.
- Antes de correr cualquier instrucción sobre la base de datos, enséñamela y espera a que te diga que sí.
- No fusiones nada: fusionar es una decisión mía, y es lo único que publica.

## 4. Lo que nunca debes hacer

- **Nunca escribas una llave que empiece con `sb_secret_` o que diga `service_role`.** La única llave que puede estar aquí es la que empieza con `sb_publishable_`, que está hecha para andar a la vista.
- No pidas ni guardes datos personales: ni nombre, ni teléfono, ni correo.
- No borres el historial ni fuerces cambios sobre lo ya publicado.

## 5. Cómo vuelvo a abrir esto

- El proyecto vive en este repositorio de GitHub. Se abre con una sesión de Claude Code en la nube sobre este repositorio.
- La página publicada está en `usuario.github.io/mi-pagina`: GitHub Pages publica lo que hay en `main`.
- La base de datos está en supabase.com, en el proyecto `curso-claude`.

> **Si la página deja de mostrar datos después de una semana sin usarla**, casi siempre es que el proyecto gratuito de Supabase se pausó. Se reanuda desde su página en supabase.com.
