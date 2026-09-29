# HIKE+ V2.42 — Randonnée à plusieurs : randonnée de l'hôte synchronisée

Correction : lorsqu'un participant est sur une randonnée différente de celle de l'hôte, le départ de groupe remplace maintenant réellement sa randonnée par celle choisie par l'hôte.

- L'hôte reste le seul à choisir la randonnée.
- Le GPX de la randonnée choisie est embarqué dans les données du groupe lorsque nécessaire, notamment pour les fichiers locaux/blob.
- Chaque participant reconstruit un fichier GPX local à partir des données reçues.
- Le participant n'a donc plus besoin d'avoir sélectionné la même randonnée avant le départ.
- Le départ synchronisé, le chrono, le partage GPS et la limite de 6 personnes sont conservés.
