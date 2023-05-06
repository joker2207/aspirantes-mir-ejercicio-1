pwd
cd desktop
mkdir ejercicios
cd ejercicios
code .
git config --global user.name "tu_nombre" ya estos los tenia configurado en mi visuaal
git config --global user.email "tu_email" ya estos los tenia configurado en mi visuaal
cd ..
git init ejercicios
cd ejercicios
git add
git commit -m "version inicial"
pwd
cd ejercicio1
git add README.md
git commit -m "Agrega solución primer ejercicio"
cd ..
git remote add origin https://github.com/joker2207/aspirantes-mir-ejercicio-1.git
git branch -M main
git push -u origin main