# Ansible KB

Este repositorio contiene documentación y ejemplos para la instalación y configuración de Ansible en varios entornos Linux.

## Índice
- [Requisitos previos](#requisitos-previos)
- [Instalar Ansible](#instalar-ansible)
  - [Instalar Ansible con PIP](docs/install/pip.md)
  - [Instalar Ansible en Ubuntu](docs/install/ubuntu.md)
  - [Instalar Ansible en Fedora](docs/install/fedora.md)
- [Solución de Problemas](docs/troubleshooting.md)
- [Ejemplos](examples/)

## Requisitos previos

### Control Nodes:
El **Control Node** es la máquina donde se ejecuta Ansible. Debe cumplir con los siguientes requisitos:
- **Servidor Linux**: Preferiblemente Ubuntu, CentOS, Fedora o Debian.
- **WSL (Windows Subsystem for Linux)**: Si prefieres usar un servidor con Windows, deberás tener instalado **WSL** para ejecutar comandos Linux.
- **Python 3.8 o superior**: Ansible requiere al menos Python 3.8 para funcionar.
- **PIP instalado**: PIP es el gestor de paquetes de Python que te permitirá instalar Ansible.
- **Módulo SSH instalado**: El módulo `openssh-client` debe estar disponible para conectarse a los nodos gestionados.

### Managed Nodes:
Los **Managed Nodes** son los servidores que serán administrados por Ansible. Deben cumplir con los siguientes requisitos:
- **SSH**: Debe estar instalado en los servidores Linux que serán gestionados.
- **WinRM (Windows Remote Management)**: Para administrar servidores Windows, se debe configurar WinRM.
- **Python**: Python debe estar instalado en los servidores Linux gestionados para que Ansible pueda ejecutar scripts.

### Opciones para instalar Ansible:
Existen varias opciones para instalar Ansible, dependiendo de tus necesidades:
- **Ansible-core**: La distribución mínima que incluye las funcionalidades básicas de Ansible.
- **Distribución completa**: Incluye un conjunto de módulos, plugins, playbooks, y otras herramientas adicionales.

## Instalar Ansible

Para guías específicas de instalación en diferentes entornos, consulta los siguientes enlaces:

- **[Instalar Ansible con PIP](docs/install/pip.md)**
- **[Instalar Ansible en Ubuntu](docs/install/ubuntu.md)**
- **[Instalar Ansible en Fedora](docs/install/fedora.md)**

## Solución de Problemas
Si encuentras problemas durante la instalación, consulta la sección de [Solución de Problemas](docs/troubleshooting.md).

## Ejemplos de Playbooks
- [Playbooks básicos](examples/)
