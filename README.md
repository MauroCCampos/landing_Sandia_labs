# Trabajar con ramas

### ¿Cuándo crear una rama?
Debes crear una rama cuando comiences a trabajar en algún feature nuevo/vista nueva/ etc. <br/>
Tomando en cuenta que por ahora solo estás trabajando con HTML, te recomiendo crear una rama por vista. <br/>
Enfocarte en trabajar en una vista por vez, evita que te pierdas en tremendo chorizo. <br/>
<br/>
### Como nombrar ramas
feature/ para codear un nuevo feature > `feature/home-screen` <br/>
fix/ para arreglar algo > `fix/home-UI` <br/>
bug/ para solucionar un bug > `bug/home-navbar-not-showing` <br/>
<br/>
### Como crear una rama
En la terminal de tu proyecto debes correr <br/>
git checkout -b nombredeturama -> `git checkout -b feature/home-screen` <br/>
Esto creará una nueva rama en tu repositorio y automáticamente te llevará a ella. La rama no aparecerá en github hasta que hagas un push de tu código<br/>
<br/>
### Como cambiar de ramas 
git checkout ramadondevas -> `git checkout main` <br/>
<br/>
### Como hacer un commit
Cuando termines de codear algo, por ejemplo, tienes listo el navbar, te recomiendo hacer un commit<br/>
Primero añades los archivos que quieras comitear. Si estás trabajando solo en una funcionalidad, por ejemplo el navbar, agrega todos los archivo usando
`git add .` <br/>
Luego que tienes todos los archivos agregados, vas a crear un commit que describa lo que hiciste <br/>
git commit -m "titulo de lo que hiciste" -> `git commit -m "navbar added"` <br/>
Lo siguiente es subir tu código a GitHub haciendo un push<br/>
git push origin ramadondeestastrabajando -> `git push origin feature/home-screen` <br/>
Cuando la terminal te avise que se subió el código, ve al proyecto en GitHub y comprueba que se subió el commit.<br/>
Sigue haciendo lo mismo, codea una funcionalidad y cuando la termines haz un commit.<br/>
Usualmente cuando se termina todo lo que debías hacer en la rama (en este caso, cuando termines la primera vista), vas a GitHub y abres un pull request. <br/>
Como en este caso estás aprendiendo, puedes subir el código aunque no esté listo, así te puedo revisar más fácil y dejar comentarios.<br/>
Cuando hagas un pull request, debes explicar brevemente que hiciste y si es una estructura HTML, agrega una foto del diseño original que estás trabajando<br/>
<br/>
Eso es todo por ahora. Cualquier duda recurrir a catita codiguitos.<br/>
<br/>
Happy coding! 😊
