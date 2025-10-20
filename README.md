# git_basico
Ejemplo de un código simple y su control de versiones a través de git y github

más info en: [Pro Git ebook](https://git-scm.com/book/en/v2)



# Vamos a necesitar.

## 1 - Cuenta de ``gitHub``.  
https://github.com/

## 2 Tener instalado `git` en nuestro sistema
Como instalar git en [ubuntu](https://github.com/ec4lab/ubuntu#instalar-git-en-ubuntu) o en [windows](https://github.com/ec4lab/windows#instalar-git-en-windows-11)

## 3 Tener instalado python en nuestro sistema
Como instalar python en [ubuntu](https://github.com/ec4lab/ubuntu#instalar-python-en-ubuntu) o en [windows](https://github.com/ec4lab/windows#instalar-python-en-windows-11)

## 3-Tener instalado `VSCode` en nuestro sistema
Como instalar VSCode en [ubuntu](hhttps://github.com/ec4lab/ubuntu#instalar-vscode-en-ubuntu) o en [windows](https://github.com/ec4lab/windows#instalar-vscode-en-windows-11)

### Si escribes la documentación en ``md``,
Te va a servir un corrector:  
Instala las extensiones `Code Spell Checker` y `Spanish - Code Spell Checker`

Agregar en [settings.json](https://github.com/ec4lab/ubuntu#personalizar-settingsjson):  
```json
"cSpell.language": "es,en" 
````

# Flujo de trabajo:

## En GitHub.com
en el Dashboard, nuevo.  
Colocamos nombre: git_básico

Add README,   
gitignore, puedes elegir de acuerdo al lenguaje que vas a utilizar.  
y Licencia, de acuerdo a lo que quieras hacer, en nuestro caso MIT, puedes ver más detalles sobre licencias aquí:

<kbd> Crear Repositorio </kbd> 

en le botón verde <kbd> <> Code </kbd>, vamos a copiar la url, en este caso:

https://github.com/ec4lab/git_basico.git

## en VSCode

Primero tenemos que decidir dónde vamos a clonar el repositorio, si por ejemplo yo quiero tener la estructura:  
```
ec4lab/git_basico  
```
debes ir dentro de la ec4lab.

Ojo, no crees la carpeta ``git_basico``, porque de lo contrario al clonar te va a quedar:
````
ec4lab/git_basico/git_basico
````
ya que el comando ``git clone`` ya trae la carpeta,

entonces, abrir un terminal: terminal -> nuevo terminal

en la aparte de abajo vas a ver un terminal y la ruta actual 

y ejecutar el siguiente comando:
```bash
git clone https://github.com/ec4lab/git_basico.git
```
Esto va a traer todo el repositorio tal cual está en la web, de ahí vamos a empezar a trabajar.

Primero ingresar a la carpeta del repositorio
```bash
cd git_basico
```

y empezamos a editar/agregar los archivos.




# 📝 Licencia
Este proyecto está licenciado bajo la Licencia MIT.
Podés usar, copiar, modificar y distribuir el software libremente, siempre que incluyas el aviso de derechos de autor original.  

Para más información, consultá el archivo [LICENSE](LICENSE).