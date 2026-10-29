# Journal des versions d'Edith

Edith est la mentore digitale conçue par Devlogy. Chaque version part de l'instance zéro (Devlogy) et rejoint les Edith des clients quand leur admin l'applique.

## 2.0.0 — Edith 2.0 : mon carnet de nouveautés

*2026-10-29 · Majeure · touche : Interface, Prompt, Base de données*

Première version numérotée d'Edith. Elle arrive avec un journal des versions dans l'admin et le canal « Actu spéciale Edith », qui annonce les nouvelles versions aux Edith installées chez les clients de Devlogy.

### Pour l'équipe

**J'ai maintenant un numéro de version : je suis Edith 2.0.** Quand j'apprends quelque chose de nouveau, je te le dis ici, dans un article « Nouveau chez Edith ».

Ce que tu as déjà dans cette version :

- **Des missions par plateforme.** Je lis la documentation officielle à ta place, je te montre le chemin en schémas, démos et quiz, et je suis tes progrès.
- **La Bibliothèque de l'équipe.** Les meilleures réponses, tutos et astuces, validés par l'admin. Le bouton « Proposer » sous mes messages y envoie les tiens.
- **Mes actus.** Ma veille du lundi et du jeudi sur tes plateformes et leur secteur.
- **Des rappels malins**, aux jours que tu choisis, qui s'adaptent à ton rythme.
- **Copier, Word et PDF** sous chaque message, pour garder ou partager une réponse.
- **Le bouton « Nouvelle réponse »**, pour revenir en bas de la conversation quand tu es remonté·e.

Rien à faire de ton côté : continue tes missions !

### Pour l'admin

- Le nouvel onglet **Versions** de l'admin affiche la version installée, son journal et l'état du canal.
- Les Edith des clients reçoivent les nouvelles versions par le canal « Actu spéciale Edith » (dépôt public `devlogy/edith-versions`). Leur admin les voit en premier, puis les applique en une phrase à Claude, avec le plugin Edith.
- Une nouvelle règle d'accès protège le journal des versions : tout le monde le lit, seul l'admin l'écrit.
- Les textes d'Edith prennent le nom de l'organisation réglé dans l'onglet Versions.
