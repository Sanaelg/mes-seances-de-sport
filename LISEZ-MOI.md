# Mes séances — mise en ligne avec GitHub Pages

## 1. Mettre l'appli en ligne (une seule fois, ~10 min)
1. Crée un compte gratuit sur https://github.com
2. En haut à droite : **+** → **New repository**
   - Nom : `mes-seances`
   - Coche **Public**
   - Clique **Create repository**
3. Sur la page du dépôt, clique **uploading an existing file**.
4. Glisse **le contenu** du dossier `mes-seances` (le fichier `index.html`, `manifest.webmanifest`, `sw.js` et le dossier `icons`) — pas le dossier lui-même.
   Ce fichier LISEZ-MOI peut aussi y aller, ce n'est pas gênant.
5. En bas : **Commit changes**.
6. Va dans **Settings** → **Pages** (menu de gauche).
   - Source : **Deploy from a branch**
   - Branch : **main** et **/ (root)** → **Save**
7. Attends 1 à 2 minutes et recharge la page : l'adresse s'affiche, du type
   `https://TON-PSEUDO.github.io/mes-seances/`

## 2. L'installer sur l'iPhone
1. Ouvre l'adresse dans **Safari**.
2. Bouton **Partager** → **Sur l'écran d'accueil** → **Ajouter**.
3. L'appli s'ouvre en plein écran, avec son icône, et fonctionne même hors connexion.

Sur Android : ouvre l'adresse dans Chrome → menu ⋮ → **Installer l'application**.
Sur ordinateur : dans Chrome ou Edge, l'icône d'installation apparaît dans la barre d'adresse.

## 3. La partager
Envoie simplement l'adresse. Chaque personne a ses propres données, enregistrées sur son téléphone : personne ne voit les séances des autres.

## 4. Récupérer tes données actuelles
Tes séances actuelles sont dans la version Claude. Pour les transférer :
1. Dans la version Claude : **Paramètres** → **Sauvegarde** → **Exporter mes données** (un fichier `.json` est enregistré).
2. Dans l'appli installée : **Paramètres** → **Sauvegarde** → **Importer une sauvegarde** → choisis ce fichier.

## 5. Mettre à jour l'appli plus tard
Quand une nouvelle version est prête : sur GitHub, ouvre le dépôt → **Add file** → **Upload files**, glisse les nouveaux fichiers (ils remplacent les anciens) → **Commit changes**.
Sur le téléphone, ferme et rouvre l'appli : la nouvelle version se charge (parfois au deuxième lancement).

## Bon à savoir
- Les données restent sur l'appareil. Si tu supprimes l'appli de l'écran d'accueil, elles sont effacées : exporte une sauvegarde de temps en temps.
- Pas de synchronisation iPhone ↔ ordinateur dans cette version. C'est ce qu'ajouterait Supabase.
