# AURA AI para Windows — descargas

Descargas oficiales de **AURA AI para Windows (beta)**. Este repositorio solo contiene las versiones publicadas; el código fuente de AURA AI es privado.

**Descarga:** sección [Releases](../../releases/latest) → `AURA-AI-Windows-Setup.exe`.

> AURA AI para Windows está disponible en versión beta. El instalador aún no tiene firma digital, por lo que Windows puede mostrar una advertencia. Puedes comprobar su integridad mediante SHA-256. No desactives las protecciones de Windows.

- Comprobar la integridad en PowerShell: `Get-FileHash .\AURA-AI-Windows-Setup.exe` y comparar con `SHA256SUMS.txt` de la release.
- Requisitos: Windows 10 (1809+) u 11 de 64 bits; ~0,3 GB para AURA AI y de 1,1 a 7 GB para los modelos de IA; 8 GB de RAM (12 GB para el modelo recomendado); internet para descargar Ollama y los modelos (con tu permiso).
- Incluye la aplicación completa, su runtime y una base de datos local. Instalación por usuario, sin administrador.
- Desinstalar: Configuración de Windows › Aplicaciones › AURA AI (tus datos se conservan salvo que elijas borrarlos).
