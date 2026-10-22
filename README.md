''''bash
git init : pour crer un repository local
git add . : pour preparer les modifications
git commit -m "" : pour enregistrer les modifications
git remote — Configurer un dépôt distant : gerer les connexion vers le depot distant
git push -u origin main : Envoi le commit local vers le depot distant
git log
git show
''''

## Rediger un commit

'''
git restaore --staged fichier : pour restaurer le fichier avant le commit suis a l'execution de la commande git add .

'''

## Gestion des branches

'''bash
git branch : pour lister les branches
git ckeckout -b nom_branch pour créer une branche
git status
git add .
git commit -m "Enregistrement de la branche"
git push origin new_branch : pour publier cette branche sur mon depot github en ligne
git checkout main : pour revenir a la branche main
git marge branch : pour merger la branche créer vers la branche main
git push origin main : pour envoyer le depot local vers le depot en ligne
Utilisation d'un puul request
'''
