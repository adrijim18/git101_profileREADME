#  Profile README

Aprende Git y GitHub contribuyendo a un proyecto real. Agrega tu perfil y haz tu primer Pull Request.

## Parte 1: Personaliza tu Profile README

### 1. Crea tu GitHub Profile README
* Ve a [github.com](https://github.com/) e inicia sesión
* Haz clic en New repository
* En el nombre escribe exactamente tu nombre de usuario de GitHub

  (por ejemplo, si tu usuario es monalisa-octocat, escribe monalisa-octocat)
  
* Márcalo como Public
* Activa la opción Add a README file
* Haz clic en Create repository

### 2. Edita tu README
* Dentro del repositorio, haz clic en el ícono del lápiz para editar el README.md
* Personalízalo con lo que quieras, puedes agregar:
  
  Una presentación tuya
  
  Las tecnologías que conoces
  
  Tus redes sociales

> ¿Necesitas inspiración? Revisa este [repositorio](https://github.com/abhisheknaiidu/awesome-github-profile-readme?tab=readme-ov-file) con ideas y ejemplos.

## Parte 2: Haz un Pull Request

Ahora vas a contribuir a este repositorio agregando tu nombre y GitHub profile README a la lista de participantes.

### 1. Haz fork al repositorio.
* En este repositorio
* Haz clic en el botón Fork (arriba a la derecha)
* Haz clic en Create fork

> Un fork es tu propia copia del repositorio en tu cuenta de GitHub.

### 2. Clona tu fork
```
git clone <url>
cd git101_profileREADME
```

### 3. Crea una rama nueva
```
git checkout -b Add-Profile/<tu-usuario-de-github>
```
Por ejemplo: `git checkout -b Add-Profile/monalisa-octocat`

> No trabajes directo en `main`, crea  una rama para tus cambios.

### 4. Agrega tu nombre a profiles.md
* Abre el archivo profiles.md
* Agrega tu nombre al final de la lista con este formato:
```
[<tu-usuario-de-github>](https://github.com/<tu-usuario-de-github>)
```
Por ejemplo: `[monalisa-octocat](https://github.com/monalisa-octocat)`

### 5. Guarda tus cambios con Git
```
git add .
git commit -m "feat: Add my profile to profiles.md"
git push origin Add-Profile/<tu-usuario-de-github>
```
Por ejemplo: `git push origin Add-Profile/monalisa-octocat` 

> Estás subiendo tu rama Add-Profile/monalisa-octocat y todos sus commits a *TU* fork.

### 6. Abre tu Pull Request
* Ve a tu fork en GitHub
* Verás un botón que dice Compare & pull request. Haz clic en él
* Agrega un título descriptivo, por ejemplo: Add <tu-usuario-de-github> GitHub profile
* Haz clic en Create pull request

> ¡Listo! Tu Pull Request será revisado y una vez aceptado, tu nombre aparecerá en el repositorio.
