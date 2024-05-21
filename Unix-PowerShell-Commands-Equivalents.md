# Voici la liste des commandes **UNIX** courantes et leurs équivalents en **PowerShell** :

1. cp (copy, copier):
- **Unix** : La commande copie des fichiers ou des répertoires.
- **PowerShell** : L'équivalent PowerShell est Copy-Item.

2. rm (remove, supprimer) :
- **Unix** : La commande supprime des ou des répertoires.
- **PowerShell** : L'équivalent PowerShell est Remove-Item.

3. cd (change directory, changer de répertoire)
- **Unix** : La commande cd permet de changer de répertoire.
-**PowerShell** : L’équivalent PowerShell est Set-Location.

4. mkdir (make directory, créer un répertoire) :
- **Unix** : La commande mkdir crée un nouveau répertoire.
- **PowerShell** : L’équivalent PowerShell est New-Item -ItemType Directory. 
Voici un exemple : `New-Item -Path .\TestFolder -ItemType Directory`

5. man (manual,manuel) :
- **Unix** : La commande man affiche le manuel d’une commande.
-**PowerShell** : L’équivalent PowerShell est Get-Help pour obtenir des informations sur les cmdlets.

6. (history, historique des commandes) :
- **Unix** : La commande history affiche l’historique des commandes.
- **PowerShell** : L’équivalent PowerShell est Get-History pour afficher l’historique des commandes.

7. alias :
- **Unix** : La commande alias crée ou affiche des alias pour d’autres commandes.
- **PowerShell** : L’équivalent PowerShell est New-Alias.

8. cat :
- **Unix** : La commande cat affiche le contenu d’un fichier.
- **PowerShell** : L’équivalent PowerShell est Get-Content.

# Voici les lignes de commandes que j’ai utilisées pour trouver ces équivalents :

`Get-Alias` ou `Alias` ou `alias`
On obtient une liste de tous les alias car certaines commandes diffèrent légèrement de Unix et peuvent être difficiles à trouver (exemple mkdir doit être remplacé par md) 
1. `Get-Alias cp | Get-Help`
2. `Get-Alias rm | Get-Help`
3. `Get-Alias chdir | Get-Help`
4. `Get-Alias md | Get-Help`
5. `Get-Alias man | Get-Help`
6. `Get-Alias history | Get-Help`
7. `Get-Help Alias | Get-Help`
8. `Get-Alias cat | Get-Help`
