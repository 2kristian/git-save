# Comandos Utiles de git

1. git init 
2. git add .
3. git reset .
4. git commit -m " poner mensaje aqui "
5. git checkout -- .  "Sirve para recuperar cosas que hemos borrado despues del ultimo commit"
6. git log  
7. git commit --amend "Sirve para arreglar mensaje de commit erronio"
8. git checkout -b rama-heroes
9. git checkout master
10. git merge " es para incluir las ramas creadas al master " 
11. git branch  -d nombre de rama " 
12. git git push
13. git commit -am "mensaje para enviar"

echo "# exemple" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/2kristian/exemple.git
git push -u origin main
