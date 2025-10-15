# git_basico
Ejemplo de un código simple y su control de versiones a través de git y github

más info en: [Pro Git ebook](https://git-scm.com/book/en/v2)



# Vamos a necesitar.

## 1 - Cuenta de ``gitHub``.  
https://github.com/

## Tener instalado `git` en nuestro sistema,

### en Windows:
https://git-scm.com/downloads/win

Instalar usando las opciones por defecto.  

**IMPORTANTE** Durante la instalación:
En el paso ``Adjusting your PATH environment``, seleccionar:  
✅ Git from the command line and also from 3rd-party software  
Eso asegura que git funcione desde PowerShell, CMD o VSCode.

Reiniciar VSCode si ya estaba abierto


### en Ubuntu
```bash
sudo apt update
sudo apt install git
```

## Tener instalado `Python` en nuestro sistema 
https://www.python.org/

## Tener instalado `VSCode` en nuestro sistema

VSCode con las extensiones que requieras según el lenguaje que programes, por ejemplo:

Python  
Pylance  
ESPhome  
ESPHome Snippets

### Si escribes la documentación en ``md``,
te va a servir un corrector:  
Code Spell Checker  
Spanish - Code Spell Checker

Agregar en settings.json:  
ctrl + shift + p  
escribir "settings"  
``Open User Settings (JSON)``
Agregar abajo: (ojo las comas!)
```json
"cSpell.language": "es,en" 
````

# Flujo de trabajo:

## En GitHub.com
en el Dashboard, nuevo.  
Colocamos nombre: git_basico

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

entonces, abrir un terminal: ternimal -> nuevo terminal

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

Para más información, consultá el archivo [LICENSE]\(LICENSE).  