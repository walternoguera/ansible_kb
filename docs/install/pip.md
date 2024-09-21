# Instalar Ansible con PIP

## Paso 1: Comprobar la versión de Python

Antes de instalar PIP, comprobamos que tenemos la versión correcta de Python. Para verificarlo, ejecuta el siguiente comando:

```bash
python3 --version
```

Debe mostrar una versión de Python 3.8 o superior.

## Paso 2: Instalar PIP

Si no tienes PIP instalado, lo instalas con el siguiente comando:

```bash
sudo apt install python3-pip
```

## Paso 3: Verificar la instalación de PIP

Una vez instalado, asegúrate de que PIP se instaló correctamente ejecutando:

```bash
python3 -m pip -V
```

Este comando muestra la versión de PIP y la ruta de instalación.

## Paso 4: Instalar Ansible a nivel global

Con PIP instalado, instalamos Ansible a nivel global, lo que significa que estará disponible para todos los usuarios del sistema. Usa el siguiente comando:

```bash
sudo python3 -m pip install ansible
```

> **Importante:** Cuando instalas a nivel global, Ansible se instala en `/usr/local/bin/ansible`. Si se instala a nivel de usuario, se instalará en `~/.local/bin/ansible`.

## Paso 5: Verificar la instalación de Ansible

Verificamos que Ansible se instaló correctamente ejecutando:

```bash
ansible --version
```

Imagen de referencia:
![ansible install_pip](https://github.com/user-attachments/assets/3f811dcd-a58e-4b73-9c7d-8307b8e67bd0)
