# git_basico

## 1- Crear un nuevo repositorio en en [github.com](https://github.com)  

## 2- Clonar el repositorio en VSCode

```bash
git clone https://github.com/ec4lab/git_basico.git
````

## Entornos virtuales

### Crear

```Bash
python3 -m venv .venv # En Ubuntu  
```

```Powershell
python -m venv .venv # En Windows
```

### Activar

```Bash
source .venv/bin/activate # En Ubuntu 
```

```Powershell
.venv\Scripts\Activate # En Windows
```

## Seleccionar interprete

```bash
/NOMBRE_DEL_PROYECTO/.venv/bin/python3 # En Ubuntu
```

```powershell
NOMBRE_DEL_PROYECTO\.venv\Scripts\python.exe # En Windows
```

## Instalar librerías

```bash
pip install requests numpy plotly matplotlib Tkinter
```

Crear o actualizar requirements.txt

```bash
pip freeze > requirements.txt
```

Instalar todas las librerías detalladas en `requirements.txt`

```bash
pip install -r requirements.txt
```

### Otros comandos relacionados con librerías

```bash
pip show requests # Verificar la versión de un paquete instalado
pip list # Listar las librerías instaladas
pip uninstall requests # Eliminar librería instalado
pip uninstall -r requirements.txt -y # Desinstalar todas las librerías
```

## 4- Añadir archivos al stage (tracking)

```bash
git status
```

Agregar al `stage` los archivos `M` y `U`:

Agregar al stage todos los archivos de la carpeta actual y subs

```bash
git add .
```

Agregar todos los archivos, sin importar el directorio donde se ejecuta el comando:

```bash
git add --all
git add -A  # Versión corta
```

Agregar solo un archivo:

```bash
git add main.py
```

Quitar los archivos del stage:

```bash
git reset
```

Quitar solo un archivo:

```bash
git restore --staged LICENSE
```

## git commit

```bash
git commit -m "Versión 0.1.0"
```

## git push

```bash
git push
```

## git fetch

Verificar si la copia local está actualizada

```bash
git fetch
```

Verificar actualizaciones

```bash
git status
```

para actualizar la copia local:

```bash
git pull
```
