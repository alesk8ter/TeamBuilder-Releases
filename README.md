# TeamBuilder-Releases

Repositorio privado que **sólo contiene las versiones compiladas** de TeamBuilder, en la pestaña Releases.
El código fuente está en el repositorio privado `TeamBuilder` y nunca se publica aquí.

- Cada release `vX.Y.Z` trae `TeamBuilder_Rev<N>_win-x64.zip` y su `.sha256`. El ZIP contiene la carpeta
  `TeamBuilder/`: `TeamBuilder.exe` self-contained para Windows 10/11 de 64 bits (no hace falta instalar .NET),
  `Datos/`, `Reglamentos/`, `LEEME.txt`, `LICENSE.txt`, `AVISO_LEGAL.md` y los avisos del runtime de .NET
  en `licencias-dotnet/`.
- Comprueba el ZIP con su `.sha256` antes de usarlo.
- Se publica a petición del usuario siguiendo `CONTEXTO_IA.md` §25 del repositorio `TeamBuilder`.
