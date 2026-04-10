# BonitoOS ERP - Releases

Repositorio público de artifacts para actualizaciones automáticas de **BonitoOS ERP**.

> El código fuente del proyecto es privado. Este repositorio solo contiene los instaladores compilados y el feed de actualizaciones.

## Archivos

- `appcast.xml` — Feed RSS usado por el auto-updater integrado en la app
- Releases — Instaladores `.exe` por versión

## ¿Cómo funciona?

La app consulta `appcast.xml` al iniciar. Si detecta una versión más nueva, muestra un diálogo nativo de Windows para actualizar automáticamente.
