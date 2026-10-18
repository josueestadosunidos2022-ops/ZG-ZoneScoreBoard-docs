# ZoneScoreBoard — releases / entregas

## 3.4.1 protected candidate / candidato protegido

- Minecraft 1.20.1, Forge 47.x, Java 17. **Server-only JAR**. ZoneCore `[2.1.0,)` required on the server. The previous documentation that called this a client/server pair was incorrect; the source runs on the server and Forge metadata now marks its ZoneCore dependency `SERVER`.
- `zonescoreboard-3.4.1-protected.jar` SHA-256 `F7F95CCFF188D06A8007F747CE25D9BCF2DFCCC3D36B9EAF5FBFA8B873D001A9`.
- The new 3.4.1 JAR declares author Elgochogms and All Rights Reserved, with `LICENSE.txt` packaged. Older MIT version rights persist. The stale compile dependency on Core 2.1.2 was corrected to existing Core 2.1.3.
- Gradle build and **78 regression checks passed**. ProGuard obfuscated internal classes without embedding Java source or the private mapping. The exact protected JAR started with protected Core 2.1.3 on isolated Forge 47.4.10; `/zscore ver` and `/zscore reload` responded, five live TOML files were generated, and shutdown was clean.
- No player joined that server. Sidebar/TAB display, permissions with real players, the full modpack, and production hosting have not been tested with this protected JAR. Uploaded as CurseForge **Beta** [file 9124664](https://authors.curseforge.com/#/projects/1738059/files/9124664), server only; analysis, moderation and public availability are pending.

## Español

Un solo JAR de servidor, sin instalación en clientes. Compiló, pasó 78 comprobaciones y arrancó con Core protegido en Forge aislado; los comandos de consulta y recarga funcionaron. Aún faltan pruebas con jugadores reales, el modpack completo y hosting. Verifica el SHA-256 antes de instalar y respalda los datos persistentes.

