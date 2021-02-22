# Ensayo sobre Git
![imagen](https://www.bing.com/images/search?view=detailV2&ccid=XFYOE5%2b2&id=FC09ED315168FB33A6C2B84A247F17E39E617146&thid=OIP.XFYOE5-2A5WMHhBDPLgQiwHaHa&mediaurl=https%3a%2f%2fth.bing.com%2fth%2fid%2fR5c560e139fb603958c1e10433cb8108b%3frik%3dRnFhnuMXfyRKuA%26riu%3dhttp%253a%252f%252fwww.knowledge7.com%252fwp-content%252fuploads%252f2014%252f06%252f20140619-git-logo.jpg%26ehk%3d4mIvRS2%252fcrHmk4%252bXcgnsPLiPrnfkpIZCXBWOrG6Ww6Q%253d%26risl%3d%26pid%3dImgRaw&exph=300&expw=300&q=git+image&simid=607990795144400448&ck=8146FC568B1154EBA1ED4185CA90AF34&selectedIndex=0&FORM=IRPRST&ajaxhist=0)
## Git
**Git** es un software que permite mantener el control de las versiones de un poryecto, manteniendo el control de versiones de aplicaciones, cuando estás dependen de una gran cantidad de código fuente. Su función principal es llevar el registro de los cambios y hacer del trabajo colaborativo más eficiente, dado que permite que *varias personas realicen cambios sobre los archivos compartidos en un repositorio de código*. 

### Principales características de Git
- Es un modelo que facilita las interacciones entre las personas que trabajan en un mismo proyecto
- Permite revisar el historial de las modificaicones y quien la realizó.
- Fusionar cambios de otras personas 
- Rapidez en la gestión de ramas y mezclado de diferentes versiones
- Los almacenes de información pueden publicarse por HTTP, FTP, rsync o mediante un protocolo nativo. 

### Estructura de datos de Git
- Archivos = Grupo de bites
- Arbol = Carpetas asignadas desde el nombre de archivo o directorio al nombre real 
- Confirmaciones = Son una serie de confirmaciones y metadatos 

### Trabajo Colaborativo
Git permite fusionar el conflicto de un proyecto para que desde diferentes dispositivos se intente corregir cualquier error, para que el programador pueda combinar cambios simultaneos en un mismo archivo o archivos según sea el caso.
Para coordinar el trabajo colaborativo de un grupo de peresonas en torno a un proyecto es necessario acordar trabajar con **Git**, estos acuerdos se llaman *Flujo de trabajo*, que es una formula o una recomendación acerca del uso de Git para realizar el trabajo colaborativo de forma uniforme y productiva. Los *flujos de trabajo* más conocidos son git-flow, GitHub-flow, GitLab Flow y One Flow.

### Comandos Git
A continuación se detallan algunos de las órdnes básicas más utilizadas:
1. git init = Se utiliza para inicalizar y crea un respositorio vacio .git
2. ls = Sirve para visualizar el archivo oculto .git
3. help = informará sobre el comando git init, y tambien a averiguar que esta pasando con un repositorio de git en el estado de git a un nivel alto
4. git fetch = Descarga los cambios realizados en el repositorio remoto
5. git merch = Impacta en la rama en la se encuentra, los cambios realizados en la rama especifica
5. fit pull = Unifica comandos fetch y merche en un único comando
6. fit commit -m = Confirma los cambios realizados 
7. git status = Muestra el estado actual de la rama y los cambios que ha sin commitear
8. git add = Comienza a trackear el archivo llamado
9. git branch = Lista todas las ramas locales
10. git branch -a= Lista todas las ramas locales y remotas
11. git branch -d <nombre_rama> = Elimina la rama local con el nombre "nombre rama"
12. git push origin = Commitea los cambios desde el branch local origen al branch "nombre rama"
13. git remote origin = Actualiza el repositorio remoto en caso que algún desarrollador haya eliminado alguna rama remota
14. git reset -- hard HEAD = Elimina los cambios que aún no se han hayan hecho *commit*
15. git revert <hash_commit> = Revierte el *commit* realizado, identificado por el "hash_commit".

### Ventajas y Desventajas
Dentro de las principales ventajas que se pueden resaltar se encuentran:
1. Es de fácil acceso
2. Fácilita el trabajo colaborativo de grandes cantidades de código
3. Controla las versiones y los cambios de las diferentes versiones de un proyecto.

Dentro de las principales desventajas se pueden mencionar:
1. Posee una interfaz muy poco amigable.
2. Se require conocimiento de programación y códigos utilizados en Git

Ensayo elaborado por: **Wilson Barrientos**

Carné: *20004315*


Curso: **Ciencia de Datos en Pyton**

### Universidad Galieo


Fuente: [fuente](https://missing.csail.mit.edu/2020/version-control/)
