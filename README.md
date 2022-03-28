# capstone_diagnose
En este repositorio se está haciendo entrega de la evaluación diagnóstica del uso de git, github y gitflow.
Por lo tanto habrá un flujo de git que se dará en este repositorio, el cuál se podrá revisar públicamente.


Primero se clonó el repo en el computador local con git clone link

Luego se creó y pusheó una branch: git branch evaluacion
git push -u origin evaluacion

Luego de ello se entró con el comando checkout a la branch: git checkout evaluacion
Para crear una feature_branch: git checkout -b feature_branch

En ella se creó el archivo de jupyter notebook, haciendo git add . & git commit -m "mensaje"
Después volví a la rama de evaluacion con git checkout evaluacion, y luego sumar los cambios de la feature_branch con: git merge feature_branch
Eliminamos la branch con: git branch -d feature_branch
Y luego hice git push

Como no hice más cambios, entré en la rama main con el comando checkout, para hacer merge y de ahí un git push, dando por finalizado el flujo de git
