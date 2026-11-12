# R-organise
Application web autonome (mono-fichier HTML) permettant de convertir des fichiers texte en PDF, de fusionner plusieurs documents, de réorganiser ou pivoter leurs pages visuellement, et de les redécouper en plusieurs fichiers PDF — 100 % localement dans le navigateur.

✨ Fonctionnalités

Import multi-formats :

Fichiers texte brut et code source : .txt, .md, .csv, .json, .log, .js, .py, .html, etc. (détection automatique des fichiers binaires non lisibles).

Fichiers .pdf existants (importation multiple possible).

Mise en page personnalisable (pour les textes) :

Choix de la police standard PDF (Helvetica, Times, Courier).

Format de page (A4 ou Letter), taille de police (6 à 30 pt) et marges (5 à 50 mm).

Numérotation automatique des pages en pied de page et retour à la ligne intelligent (word-wrapping).

Édition visuelle des pages :

Réorganisation par glisser-déposer (drag & drop) ou via les flèches ← / →.

Rotation par pas de 90° (⟲ / ⟳) et suppression individuelle (×).

Aperçu plein écran (Lightbox) haute définition avec navigation au clavier (←, →, Échap).

Découpage multi-PDF :

Boutons ciseaux (✂) placés entre chaque page pour définir les points de rupture.

Identification visuelle par couleur et badge (PDF 1, PDF 2, etc.).

Exportation flexible :

Export en 1 seul PDF fusionné.

Export découpé : téléchargement direct s'il n'y a qu'un bloc, ou archive .zip contenant tous les PDF numérotés (nom-partie-01.pdf, nom-partie-02.pdf, etc.).

Confidentialité & Design :

Traitement 100 % côté client : aucun fichier n'est envoyé sur un serveur.

Thème clair et sombre automatique avec bouton de bascule manuelle.

🚀 Installation et utilisation

Aucune installation, compilation ni serveur backend n'est requis :

Téléchargez le fichier texte-en-pdf.html.

Ouvrez-le directement par double-clic dans n'importe quel navigateur moderne (Chrome, Firefox, Edge, Safari).

Glissez-déposez vos fichiers texte ou PDF dans la zone prévue.

(Une connexion Internet est uniquement requise au chargement initial pour récupérer les 3 bibliothèques JavaScript depuis cdnjs.cloudflare.com.)

🛠️ Dépendances techniques

Toutes les dépendances sont chargées avec des versions épinglées depuis cdnjs.cloudflare.com :

PDF.js (3.11.174) : rendu des pages PDF sur <canvas> pour les miniatures et l'aperçu plein écran.

pdf-lib (1.17.1) : génération vectorielle des PDF depuis du texte, copie de pages et application des rotations.

JSZip (3.10.1) : création d'archives .zip lors de l'exportation de plusieurs PDF découpés.
