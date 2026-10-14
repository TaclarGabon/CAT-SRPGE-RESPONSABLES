# CAT-SRPGE Responsables — préparation du module documents

Version de référence V7.2 préservée sur `main`. La branche `developpement-documents-securises` sert uniquement aux travaux préparatoires.

## État
La rubrique « Documents par souscription » existe déjà dans l'interface. Aucun PDF ne peut encore être ouvert depuis le portail.

Le prototype sécurisé de la passerelle (authentification Firebase, Drive privé, listing/téléchargement) a été préparé dans le dépôt frère `TaclarGabon/CAT-SRPGE-ACTIONNAIRES` sous `docs-passerelle/`, **mais n'est pas déployé**.

## Suite avant publication
1. Le propriétaire teste d'abord la passerelle Apps Script avec les documents fictifs.
2. Vérifier le refus pour comptes non autorisés et la possibilité pour un responsable habilité de consulter les pièces d'un actionnaire.
3. Installer le lien de consultation dans le détail de chaque opération en utilisant l'`operationId` existant (pas `OP-001` seul).
4. Conserver la mention « document non reçu dans CAT » tant que les fichiers ne sont pas rattachés par la nouvelle passerelle.
5. Tester et publier seulement après confirmation des règles d'accès.

Ne pas insérer d'ID de dossier ou fichier Drive privé dans l'HTML de GitHub Pages.
