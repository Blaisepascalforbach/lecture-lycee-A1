LIRE AU LYCÉE — FRANÇAIS A1

Mise en ligne simple avec GitHub Pages

1. Décompresse ce fichier ZIP.
2. Crée un dépôt GitHub public vide.
3. Ajoute à la racine du dépôt les fichiers index.html, manifest.webmanifest, sw.js et README.txt, ainsi que le dossier icons.
4. Dans le dépôt, ouvre Settings > Pages. Choisis “Deploy from a branch”, puis la branche main et le dossier /(root). Enregistre.
5. Quand GitHub affiche l’adresse du site, ouvre-la sur le téléphone. Dans le menu du navigateur, choisis “Ajouter à l’écran d’accueil” ou “Installer”.

L’application peut fonctionner hors connexion après le premier chargement. Le navigateur doit prendre en charge les applications web progressives. La synthèse vocale du téléphone sert de solution de base.

Voix Google : le point d’intégration window.OEPRE_GOOGLE_TTS est prévu. Cette fonction doit retourner une Promise qui se termine à la fin de la lecture audio, afin que la phrase reste surlignée pendant toute sa lecture. Fais appeler un serveur ou un service intermédiaire qui protège la clé API ; ne place pas de clé Google dans le fichier HTML public.
