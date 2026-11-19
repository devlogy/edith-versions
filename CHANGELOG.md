# Journal des versions d'Edith

Edith est la mentore digitale conçue par Devlogy. Chaque version part de l'instance zéro (Devlogy) et rejoint les Edith des clients quand leur admin l'applique.

## 2.3.0 — On fête tes réussites !

*2026-11-19 · Recommandée · touche : Interface, Base de données*

Edith célèbre les grands moments (niveau, mission terminée, badge, défi, quiz sans faute) avec confettis et fanfare. Trois réactions en un clic, et un mur « Les succès de l'équipe » où l'on partage et applaudit.

### Pour l'équipe

**On fête tes réussites !** Quand tu passes un niveau, termines une mission, gagnes un badge, réussis un défi ou un quiz sans faute, je sors les confettis.

- **Petite pluie** pour un défi, un badge ou un quiz parfait ; **grande explosion** pour un niveau gagné ou une mission terminée.
- **Dis-moi ce que tu ressens** : 🎉 « Trop fier·e ! », 💪 « Au suivant ! » ou 🙏 « Merci Edith ». Je te réponds, et ta réaction reste dans la conversation.
- **Partage à l'équipe** : un clic et ton succès arrive sur la page Équipe, où les collègues peuvent t'applaudir 👏. Rien n'est partagé sans ton clic.
- **Une petite fanfare** accompagne la fête : tu peux la couper dans Réglages → Célébrations.

### Pour l'admin

- Une nouvelle règle d'accès protège les succès partagés : chacun écrit les siens, toute l'équipe les lit. Les applaudissements utilisent les votes existants.
- Si l'appareil demande de réduire les animations, la carte s'affiche sans confettis.

## 2.2.0 — Mettre une mission en pause

*2026-11-18 · Recommandée · touche : Interface*

Les missions peuvent se mettre en pause : elles quittent la liste active, les rappels n'en parlent plus, et elles reprennent telles quelles. Edith propose la pause après 30 jours sans activité.

### Pour l'équipe

**Tu peux mettre une mission en pause.** Un outil qui n'est plus prioritaire pour toi ? Ouvre sa carte (« Ma carte » sur téléphone) et clique sur « Mettre en pause ».

- **Rien n'est effacé** : conversation, compétences, XP et badges restent intacts.
- **Elle se range en bas de ta liste**, dans « En pause ». Un clic sur « Reprendre », ou simplement un message, et on continue là où tu t'étais arrêté·e.
- **Je n'en parle plus** dans tes rappels, et mes actus mettent en avant tes missions actives.
- **Je te la propose** quand une mission n'a pas bougé depuis un mois. Tu peux toujours refuser.

### Pour l'admin

- Le tableau de bord compte les missions en pause de chaque collègue (un nombre, jamais leur nom), dans la colonne Plateformes et dans l'export CSV.
- Le message des rappels change : chaque collègue qui a activé ses rappels voit une fois « Mettre à jour mes rappels » sur l'accueil.

## 2.1.0 — Des sources discrètes

*2026-11-11 · Mineure · touche : Interface*

Les sources consultées se replient en une ligne discrète, « 5 sources consultées », toujours en bas de la réponse. Un clic les déplie en une liste de liens. Même présentation dans les articles des Actualités.

### Pour l'équipe

**Mes sources se font discrètes.** Elles tiennent sur une ligne en bas de ma réponse, « 5 sources consultées » : un clic la déplie pour voir les liens.

- **Plus de confusion** avec les réponses d'un quiz ou les suggestions à cliquer.
- **Même présentation dans les articles** des Actualités.

### Pour l'admin

Rien à faire : la mise à jour ne touche que l'affichage. Les exports Word et PDF gardent la liste complète des sources.

## 2.0.2 — Edith 2.0.2 : les rappels s'activent de nouveau

*2026-11-11 · Correctif · touche : aucun*

Correctif : « Activer mes rappels » était refusé par Claude depuis un changement des tâches planifiées. Les rappels se créent de nouveau.

### Pour l'admin

- « Activer mes rappels » fonctionne de nouveau : chaque rappel ouvre sa propre session, ce que Claude exige désormais pour envoyer la notification et l'e-mail.
- Si Claude demande dans quel environnement créer la tâche, Edith reprend celui qu'il propose.
- Un rappel supprimé depuis Claude est recréé au lieu de provoquer une erreur.
- Les rappels déjà actifs ne changent pas.

## 2.0.1 — Edith 2.0.1 : l'écran « Nouvelle mission » corrigé

*2026-10-30 · Correctif · touche : Interface*

Correctif : l'écran qui vérifie une nouvelle mission ne déborde plus, et une phrase tapée à la place du nom de la plateforme ne devient plus un faux domaine.

### Pour l'admin

- L'écran « Vérifie la mission » s'élargit et ne déborde plus, même avec un nom de domaine très long. Les menus de rôle restent visibles, sur ordinateur comme sur téléphone.
- Une phrase tapée dans le champ « Plateforme » (« la plateforme est Resend, je voudrais… ») ne produit plus de faux domaine. Si la phrase contient un vrai site (resend.com), Edith le reprend.
- « Ajouter » refuse ce qui n'est pas un nom de domaine, avec un message.
- Les faux domaines déjà enregistrés dans une mission sont écartés à l'ouverture.

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
