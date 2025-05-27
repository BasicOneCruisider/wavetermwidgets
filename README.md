# Configuration de Terminals et Liens Utiles

Ce fichier JSON définit la configuration pour une série de terminaux et de liens utiles, permettant de personnaliser l'interface de votre application terminal. Il inclut des entrées pour des shells de commande, des services web comme YouTube et GitHub, ainsi que Windows PowerShell.

## Structure du Fichier

Le fichier se compose de sections distinctes pour chaque terminal et lien, chaque section étant identifiée par une clé unique. Voici un aperçu des sections incluses :

### 1. Terminal : Command Prompt (`cmd`)

- **Clé** : `cmd`
- **Icône** : `rectangle-terminal`
- **Couleur** : `#fc8803`
- **Label** : `cmd`
- **Type** : Terminal
- **Chemin d'accès** : Utilise l'application Command Prompt de Windows.

### 2. Terminal : PowerShell Core (`pwsh`)

- **Clé** : `pwsh`
- **Icône** : `rectangle-terminal`
- **Couleur** : `#03fc49`
- **Label** : `pwsh`
- **Type** : Terminal
- **Chemin d'accès** : Utilise l'application PowerShell Core.

### 3. Lien vers YouTube

- **Clé** : `youtube`
- **Icône** : `play`
- **Label** : `youtube`
- **Couleur** : `red`
- **Type** : Web
- **URL** : [YouTube](https://www.youtube.com/feed/subscriptions)
- **Pinned URL** : Lien direct vers les abonnements YouTube.

### 4. Lien vers GitHub

- **Clé** : `github`
- **Icône** : `brands@github`
- **Label** : `github`
- **Type** : Web
- **URL** : [GitHub](https://github.com)
- **Pinned URL** : Lien vers GitHub.

### 5. Terminal : Windows PowerShell

- **Clé** : `windows-powershell`
- **Icône** : `rectangle-terminal`
- **Couleur** : `#0078d7`
- **Label** : `Windows PowerShell`
- **Type** : Terminal
- **Chemin d'accès** : Utilise l'application Windows PowerShell.

## Utilisation

Ce fichier doit être inclus dans votre application terminal pour permettre aux utilisateurs d'accéder facilement à différents shells de commande et à des ressources en ligne. Chaque entrée est conçue pour être facilement personnalisable, permettant d'ajouter ou de modifier des terminaux et des liens selon les besoins.

## Personnalisation

1. Pour ajouter un nouveau terminal ou un lien, créez une nouvelle clé unique et suivez le format des autres entrées.
2. Assurez-vous que les icônes, couleurs et chemins sont corrects et disponibles dans votre application.

## Conclusion

Cette configuration vise à améliorer l'expérience utilisateur en offrant un accès rapide aux outils nécessaires et aux ressources de développement en ligne. N'hésitez pas à personnaliser ce fichier selon vos besoins et vos préférences !
