## 1. Preparación del proyecto Angular

Primero me aseguré de tener el proyecto funcionando correctamente de manera local. Para ello, ejecuté los siguientes comandos:




`npm install

npm start` 

Luego, generé la versión lista para producción con:



`npm run build` 

Esto creó la carpeta `dist/`, que contiene los archivos necesarios para el despliegue.

## 2. Subir el proyecto a GitHub
Inicialicé un repositorio Git en mi proyecto y lo subí a GitHub con los siguientes comandos:


``
git init
git add .
git commit -m "primer commit"
git branch -M main
git remote add origin https://github.com/Juanesptiia/Proyecto-pokedex-juan.git
git push -u origin main


## 3. Despliegue en Vercel

Con el repositorio ya en GitHub, seguí estos pasos en [Vercel](https://vercel.com):

1.  Inicié sesión con mi cuenta de GitHub.
    
2.  Hice clic en **“Add New Project”**.
    
3.  Seleccioné el repositorio `Proyecto-pokedex-juan`.
    
4.  Vercel detectó automáticamente que se trataba de un proyecto Angular.
    
5.  No realicé configuraciones adicionales.
    
6.  Hice clic en **“Deploy”**.

## 4. Resultado

La aplicación fue desplegada exitosamente. Vercel me proporcionó un enlace público para acceder a la aplicación Angular desde cualquier dispositivo.

> 🚀 ¡Proyecto desplegado con éxito usando Vercel!
