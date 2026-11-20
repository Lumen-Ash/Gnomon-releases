# Gnomon: descargas / downloads

Este repositorio **solo contiene instaladores, notas de versión y el archivo de versión** de [Gnomon](https://github.com/Lumen-Ash), el conversor de medidas y calculadora de obra de **Lumen & Ash**. No hay código fuente aquí.

*This repository only holds installers, release notes and the version file of Gnomon, the measurement converter and job-site calculator by **Lumen & Ash**. There is no source code here.*

## Descargar / Download

**Última versión / Latest:** [Releases](../../releases/latest)

**Microsoft Store (próximamente / coming soon):** [Gnomon – Construction Calculator](https://apps.microsoft.com/detail/9NGBFPTQ4RF9)

- Windows 10/11, 64 bits. No hace falta instalar .NET. / Windows 10/11 x64; .NET is bundled.
- Se instala por usuario, sin permisos de administrador (el asistente permite instalar para todos). / Installs per user without administrator rights (the wizard can install for all users).

### Aviso de SmartScreen / SmartScreen notice

Los instaladores aún no llevan firma digital de Windows, así que SmartScreen puede mostrar «Windows protegió su PC». Pulsa **Más información → Ejecutar de todas formas**. Para estar seguro de que el archivo es el original, compara su SHA-256 con la tabla de abajo.

*The installers are not yet signed with a Windows code-signing certificate, so SmartScreen may show "Windows protected your PC". Choose **More info → Run anyway**. To make sure the file is the original, compare its SHA-256 with the table below.*

**Privacidad / Privacy:** [PRIVACY.md](PRIVACY.md) — Gnomon no envía ningún dato / Gnomon sends no data.

En PowerShell / In PowerShell: `Get-FileHash .\Gnomon_Setup_<version>.exe -Algorithm SHA256`

## Actualizaciones / Updates

Gnomon comprueba `latest.json` de este repositorio (como mucho una vez cada 24 horas, y se puede desactivar en Ajustes). Solo se descarga ese archivo: no se envía ningún dato. Cada actualización se verifica con una firma ECDSA P-256 (`latest.json.sig`) y con el SHA-256 del instalador antes de instalarse. Las versiones `-rc` son pre-releases y no se ofrecen como actualización.

*Gnomon reads `latest.json` from this repository (at most once every 24 hours; it can be turned off in Settings). Only that file is downloaded: no data is sent. Every update is verified with an ECDSA P-256 signature (`latest.json.sig`) and the installer's SHA-256 before it is installed. `-rc` versions are pre-releases and are not offered as updates.*

## SHA-256 de cada versión / SHA-256 of each version

| Versión / Version | Fecha / Date | SHA-256 |
|---|---|---|
<!-- SHA256-ROWS -->
