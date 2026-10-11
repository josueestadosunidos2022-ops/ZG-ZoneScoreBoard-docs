# ZG ZoneScoreBoard 3.4.1 — TOML / configuración

The protected server JAR generated these files under `config/ZONEMODS/zonescoreboard/` in an isolated Forge 47.4.10 launch. / El JAR protegido de servidor generó estos archivos en esa ruta durante un arranque aislado.

| File / Archivo | Options / Opciones |
|---|---|
| `sidebar/diseno.toml` | `[sidebar] activo`, `titulo`, `color_titulo`, `degradado_inicio`, `degradado_fin`, `negrita`, `subrayado`: enable and style the sidebar title / activar y diseñar el título lateral. |
| `sidebar/lineas.toml` | `lineas = [...]`: up to 15 sidebar rows; empty strings are allowed / hasta 15 líneas; se admiten líneas vacías. |
| `sidebar/pie.toml` | `[pie_panel] activo`, `subtitulo`: optional footer under sidebar rows; when enabled, only 14 main rows fit / pie opcional; al activarlo quedan 14 líneas principales. |
| `tabulador/diseno.toml` | `[tabulador] activo`, `encabezado`, `pie`, `nombre_jugador`: standard TAB layout, newline `\\n` / diseño TAB clásico, salto de línea `\\n`. |
| `tabulador/visual.toml` | `[visual] activo`, `tema`, `efectos`, `actualizacion_ticks`; `[espacios] antes_jugadores`, `despues_jugadores`, `entre_lineas`; `[paleta]`, `[temas.<nombre>]`, `[animaciones.<nombre>]`: custom themes, spacing, colors and frames / temas, espacios, colores y fotogramas. Visual mode starts disabled to preserve the standard TAB layout / empieza desactivado para conservar el diseño anterior. |

Built-in themes / temas incluidos: `godieland`, `minimal`, `fuego`, `hielo`; additional themes can be defined in the TOML. `actualizacion_ticks` accepts 5–100; animation `intervalo_ticks` accepts 5–12000. Player spacing accepts 0–6, line spacing 0–3. Invalid values reject reload while keeping the prior active configuration (regression tested). / Los valores inválidos rechazan la recarga y conservan la configuración activa anterior.

Available text placeholders / variables: `%player%`, `%rank%`, `%prefix%`, `%world%`, `%playtime%`, `%online%`, `%tps%`, `%time%`. The visual TAB adds `%color:nombre%` and `%anim:nombre%`. Color formats include legacy `&6`, expanded hex and Birdflop `&#FFAA00`. Use `/zscore reload` or `/zonecore reload` after edits; `/zscore tab probar` previews the visual layout. / Recarga tras editar y usa la vista previa antes de dejar el diseño activo.

`zonescoreboard-visual.toml` inside the JAR is a bundled template, not a sixth live config file. / `zonescoreboard-visual.toml` dentro del JAR es una plantilla integrada, no un sexto archivo de configuración en vivo.

