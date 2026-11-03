# ZoneScoreBoard

## Current builds / Versiones actuales — 2026-11-03

| Side / Lado | Version / Versión | CurseForge |
|---|---|---|
| ZoneScoreBoard server | 3.6.0 | [Files / Archivos](https://www.curseforge.com/minecraft/mc-mods/zonescoreboard/files/9426494) |
| ZoneScoreBoardClient client | 1.1.0 | [Files / Archivos](https://www.curseforge.com/minecraft/mc-mods/zonescoreboard/files/9426501) |

Server 3.6.0 controls appearance; Client 1.1.0 ignores old local TOML. / El servidor 3.6.0 controla la apariencia; el cliente 1.1.0 ignora el TOML local anterior.

[Changes, installation and compatibility / Cambios, instalación y compatibilidad](RELEASE-2026-11-03.md).

Public protected Beta builds. A submitted file becomes downloadable only after CurseForge approval. / Betas públicas protegidas: cada archivo queda descargable cuando CurseForge lo aprueba.

## Earlier documentation / Documentación anterior

The version and side table above takes precedence over historical versions below. / La tabla anterior prevalece sobre versiones históricas de la documentación siguiente.

## Optional client / Cliente opcional — 2026-11-02

**English:** The server mod still works without a client mod. An optional **ZoneScoreBoard Client 1.0.1** now styles recognized TAB panels, with configurable colors/spacing and real-player heads/ping when compatible server 3.5.1+ data is present. Install only the client file on players, with no ZoneCore or ZoneRanks client requirement. See [client installation, features and limits](CLIENT-1.0.1.md). The existing public server 3.4.2 files are unchanged.

**Español:** El mod de servidor sigue funcionando sin complemento cliente. **ZoneScoreBoard Client 1.0.1** añade presentación opcional de paneles TAB, colores/separación y cabeza/ping de jugadores reales con datos compatibles de servidor 3.5.1+. Instala solo el archivo cliente en los jugadores, sin exigir Core ni Ranks en cliente. Consulta [instalación, funciones y límites](CLIENT-1.0.1.md). Los archivos públicos existentes de servidor 3.4.2 no cambian.

## Update / Actualización — 2026-10-17

Selected version / Versión seleccionada: **server 3.4.2**. New file availability depends on CurseForge approval / La disponibilidad de los archivos nuevos depende de su aprobación en CurseForge.

See [changes, exact files and installation](UPDATES-2026-10-17.md) / Consulta [cambios, archivos e instalación](UPDATES-2026-10-17.md). Preserve the world and TOML files / Conserva mundo y TOML.

## Español

Panel lateral y lista TAB configurables para Minecraft 1.20.1 / Forge 47.x. El diseño admite temas, colores, variables y animaciones. **Instala este único JAR en el servidor**; los clientes no necesitan ZoneScoreBoard. Requiere [ZoneCore](https://www.curseforge.com/minecraft/mc-mods/zonecore) 2.1.0 o superior en el servidor.

Los jugadores usan `/zsb`, `/zsb on`, `/zsb off` y `/zsb estado` con `zonescoreboard.toggle`. Los administradores usan `/zscore ver`, `/zscore editar`, `/zscore reload`, `/zscore tab probar` y el resto del editor con nivel OP 2 o `zonescoreboard.admin`. `/zonecore reload` también recarga su configuración.

Configura `config/ZONEMODS/zonescoreboard/` mediante los cinco TOML generados, descritos en [CONFIGURATION.md](CONFIGURATION.md). Haz una copia antes de cambiar un servidor persistente. ZoneCore proporciona datos de rango y prefijo.

## English

Configurable sidebar and TAB player list for Minecraft 1.20.1 / Forge 47.x servers. Original styling supports themes, colors, variables, and animations. **Install the single JAR on the server**; players do not need ZoneScoreBoard on their clients. [ZoneCore](https://www.curseforge.com/minecraft/mc-mods/zonecore) 2.1.0 or newer is required on the server.

Players can use `/zsb`, `/zsb on`, `/zsb off`, and `/zsb estado` with `zonescoreboard.toggle`. Administrators can use `/zscore ver`, `/zscore editar`, `/zscore reload`, `/zscore tab probar`, and the rest of the editor with OP level 2 or `zonescoreboard.admin`. `/zonecore reload` also reloads this configuration.

Edit the five generated TOML files under `config/ZONEMODS/zonescoreboard/`; see [CONFIGURATION.md](CONFIGURATION.md). Back up persistent server data before changing it. See [RELEASES.md](RELEASES.md) for the protected file and test limits.

## Titularidad / Ownership

Documentation and original assets © Elgochogms. This public repository contains only documentation and the project avatar. Source code, mappings, private server data, and credentials are not published here. The 3.4.2 JAR includes LICENSE.txt, which states All Rights Reserved for this release and preserves the rights granted under the respective licenses of previously released versions.

