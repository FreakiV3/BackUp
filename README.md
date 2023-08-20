# Script de Sauvegarde Automatique

Ce script Python vous permet de créer automatiquement une sauvegarde de tous les fichiers et dossiers présents dans un répertoire source vers un répertoire de sauvegarde. Il est utile pour maintenir une copie de vos fichiers importants en cas de besoin.

## Fonctionnalités

- Crée un dossier de sauvegarde s'il n'existe pas.
- Supprime les fichiers et dossiers dans la sauvegarde qui ne sont plus présents dans le répertoire source.
- Copie les fichiers et dossiers actuels du répertoire source vers le répertoire de sauvegarde.

## Utilisation

1. Assurez-vous que vous avez Python installé sur votre système.

2. Pour lancer la sauvegarde, appuyez sur `Ctrl + F8`. Le script créera un dossier "Backup" (s'il n'existe pas) dans le même répertoire que le script et y copiera les fichiers du répertoire actuel.

3. Pour fermer le script, appuyez sur `Ctrl + F9`.

## Configuration

Vous pouvez personnaliser les répertoires source et de sauvegarde en modifiant les variables `source_directory` et `backup_directory` dans le script.

## Remarques

- Assurez-vous d'utiliser "F8" et "F9" avec la touche "Ctrl" pour déclencher les actions dans le script.

- Si le répertoire de sauvegarde est identique au répertoire source, le script affichera un message indiquant qu'aucune sauvegarde n'est nécessaire.

- Le script n'effectue pas de compression des fichiers sauvegardés. Vous pouvez ajouter cette fonctionnalité si nécessaire.

- Assurez-vous d'adapter ce script à vos besoins spécifiques avant de l'utiliser en production.

## Licence

Ce script est sous licence MIT. Consultez le fichier [LICENSE](LICENSE) pour plus de détails.
