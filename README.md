# project

1. pour connecter a ce projet
git clone https://github.com/randrianrivelo/project
cd project

2. pour verifier si dans ce branche
git branch
*doit afficher : *main


3. Se mettre sur la même branche :
git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

4. Si n'existe pas en locale
git fetch
git checkout main

5. TOUJOURS METTRE A JOURS AVANT DE TRAVAILLER POUR EVITER CONFLIT*
git pull origin main

6. TRAVAILLER ET ENVOYER SES MODIFICATION
git add . #POUR APPLIQUER LES CHANGES
git commit -m "Ajout fonctionnalite X" #POUR MODIFIER MD.TXT TSY TADIDIKO ITO
git push origin main #pour push
