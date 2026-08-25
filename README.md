# runs

Scripts de automatización para configurar mi entorno de trabajo en diferentes sistemas operativos.

## Descripción

Este proyecto contiene scripts para instalar y configurar herramientas de desarrollo, aplicaciones de productividad y utilidades del sistema de forma automática.

## Scripts disponibles

| Script | Sistema operativo |
|--------|-------------------|
| `windows.ps1` | Windows |
| `wsl-ubuntu.sh` | WSL con la distro Ubuntu |
| `bazzite.sh` | Bazzite |
| `cachyos.sh` | CachyOS |
| `mx-linux.sh` | MX Linux |
| `nobara.sh` | Nobara |

## Uso

### Windows

```powershell
Set-ExecutionPolicy Unrestricted -Scope Process
.\windows.ps1
```

### Linux / WSL

```bash
# WSL Ubuntu
bash wsl-ubuntu.sh

# Bazzite
bash bazzite.sh

# CachyOS
bash cachyos.sh

# MX Linux
bash mx-linux.sh

# Nobara
bash nobara.sh
```

## Requisitos

- **Windows**: Winget instalado
- **Linux**: Bash y permisos de sudo

