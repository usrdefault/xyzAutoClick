# v3.9.6 - 22.08.2026 (j.m.a)
## Nouveautés
- Points de clic : plusieurs positions à l'écran cliquées l'une après l'autre, avec un rayon d'aléatoire par point et un arrêt automatique après un passage complet.
- Zones d'arrêt personnalisées : on peut en tracer plusieurs, chacune pouvant arrêter, mettre en pause ou démarrer le clic.
- Liste blanche / liste noire de processus : le clic s'arrête selon l'application au premier plan.
- Arrêt automatique sur Alt+Tab et Win+Tab.
- Interrupteur principal : une touche qui autorise ou bloque globalement le clicker, avec « DÉSACTIVÉ » affiché en rouge dans le titre.
- Raccourcis clavier pour changer de page et pour basculer chaque réglage important.
- Barre d'état en bas de la fenêtre : préréglage actif, version, raison du dernier arrêt.
- Clic clavier en plus du clic souris, avec choix de la casse.
- Mode Maintien pour le rapport cyclique, qui garde le bouton enfoncé en continu.
- Apparence : image de fond, opacité de la fenêtre et du panneau, flou réglable, et personnalisation page par page.
- Icône de la barre des tâches personnalisable, qui suit le thème et la couleur d'accent.
- Nouveau sélecteur de couleur d'accent : palette intégrée et champ hexadécimal, à la place de la fenêtre de couleur de Windows.
- Nouvelle icône de l'application, en version claire et sombre.
- Mémorisation de la position de la fenêtre au démarrage.
- Journaux et rapports de plantage, consultables et exportables depuis Maintenance.
- Bouton « Vérifier les mises à jour » et aperçu des nouveautés avant d'installer.
- Version portable, qui garde toutes ses données dans son propre dossier.
## Modifié
- L'application s'appelle xyzAutoClick, avec son propre installeur, ses propres dossiers de données et son propre canal de mise à jour.
- Panneau Avancé entièrement refait, et panneau Paramètres réorganisé avec un menu latéral.
- Nouvelle police, pour que les chiffres ne bougent plus quand les valeurs changent.
- Consommation mémoire réduite quand aucun réglage n'a été touché depuis un moment.
- L'installeur embarque les bibliothèques Windows nécessaires, pour éviter les échecs de démarrage sur certains PC.
- Le défilement sur les champs numériques accepte Maj, Ctrl et Maj+Ctrl pour des pas plus grands.
## Corrigé
- La vitesse de clic demandée est réellement atteinte, y compris à haute vitesse.
- Le curseur ne devient plus erratique pendant que le clicker tourne.
- Plusieurs plantages au démarrage et à l'ouverture du panneau Zones.
- Le raccourci ne se déclenche plus tout seul à cause des clics générés par l'application.
- La fenêtre ne s'affiche plus brièvement à la mauvaise taille ou au mauvais endroit au lancement.
- Le double clic utilise la cadence de Windows et fonctionne correctement avec la durée de clic.
