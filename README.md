# ASISTEMAS_A2025
AUDITORIA DE SISTEMAS 2025
INSTRUCCIONES DE ENTREGA – ASISTEMAS A2025

Estimado estudiante:

Siga cuidadosamente los siguientes pasos para entregar su actividad del curso ASISTEMAS A2025. Esta guía ha sido diseñada para personas que no tienen experiencia previa con GitHub. 

PASO 1: Crear una cuenta en GitHub (si no tiene una)

1. Ingrese a https://github.com y haga clic en “Sign up”.
2. Complete sus datos y confirme su correo electrónico.

PASO 2: Fork del repositorio base del curso

1. Ingrese al siguiente enlace: https://github.com/fabiansmsecu/ASISTEMAS_A2025
2. En la parte superior derecha, haga clic en el botón “Fork”.
3. Se creará una copia del repositorio en su cuenta personal.

PASO 3: Clonar su fork en su computadora

1. Ingrese a su cuenta de GitHub y abra su copia del repositorio ASISTEMAS_A2025.
2. Haga clic en el botón verde “Code” y copie el enlace que aparece (HTTPS).
3. Abra su terminal (Git Bash, PowerShell o Terminal según su sistema) y escriba:


git clone https://github.com/SuUsuario/ASISTEMAS_A2025.git
cd ASISTEMAS_A2025

Reemplace 'SuUsuario' por su nombre de usuario real de GitHub.
PASO 4: Crear una rama para su actividad

1. Una vez dentro de la carpeta del proyecto, cree una nueva rama con su apellido y nombre:


git checkout -b actividad1-ApellidoNombre

PASO 5: Escribir y guardar su solución

1. Edite los archivos requeridos con su solución.
2. Asegúrese de guardar correctamente todos los cambios.

PASO 6: Subir su trabajo a GitHub

1. Guarde y prepare sus cambios para subir:


git add .
git commit -m "Actividad 1 – Apellido Nombre"
git push origin actividad1-ApellidoNombre

PASO 7: Crear un Pull Request (PR)

1. Ingrese a su repositorio en GitHub.
2. Aparecerá un mensaje que dice “Compare & pull request”. Haga clic ahí.
3. Verifique lo siguiente:
   - Base repository: fabiansmsecu/ASISTEMAS_A2025
   - Head repository: SuUsuario/ASISTEMAS_A2025
   - Título: Actividad 1 – Apellido Nombre
4. Haga clic en “Create pull request”.

¿CÓMO VERÁ SU PROFESOR SU ENTREGA?

El profesor verá su Pull Request en: https://github.com/fabiansmsecu/ASISTEMAS_A2025/pulls
Desde allí podrá revisar, ejecutar y calificar su código.

RECOMENDACIONES FINALES

- No cierre su Pull Request.
- No edite ramas que no sean suyas.
- Asegúrese de que el código funcione antes de entregarlo.
- Si tiene dudas, consulte al profesor.

