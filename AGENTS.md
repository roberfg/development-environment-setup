# Contexto Del Proyecto

## Propósito

Scripts de automatización para instalar y configurar herramientas de desarrollo, aplicaciones y utilidades del sistema en Windows, WSL y varias distribuciones Linux.

## Scripts

- `windows.ps1`: Windows.
- `wsl-ubuntu.sh`: WSL con Ubuntu.
- `bazzite.sh`: Bazzite.
- `cachyos.sh`: CachyOS.
- `mx-linux.sh`: MX Linux.
- `nobara.sh`: Nobara.

Los scripts de este repositorio instalan dependencias, preparan el entorno y enlazan los paquetes del repositorio `.dotfiles` cuando corresponde.

## Requisitos

- Windows: Winget y PowerShell 7+.
- Linux/WSL: Bash y permisos de `sudo`.

## Ejecución

Windows:

```powershell
Set-ExecutionPolicy Unrestricted -Scope Process
.\windows.ps1
```

Linux/WSL:

```bash
bash wsl-ubuntu.sh
bash bazzite.sh
bash cachyos.sh
bash mx-linux.sh
bash nobara.sh
```

## Reglas de mantenimiento

- Mantener los scripts idempotentes cuando sea posible.
- Detectar el sistema operativo y las herramientas disponibles antes de instalar o modificar archivos.
- No eliminar configuraciones del usuario ni sobrescribir secretos sin una condición explícita.
- Probar cada script en su sistema operativo objetivo.
- Mantener documentación y comentarios en español neutro; conservar identificadores y comandos en inglés.
