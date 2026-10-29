# Black-jack

Jeu de blackjack au style « casino crypto » (thème sombre, gros bouton vert « Parier », cartes animées, multiplicateur affiché en cas de gain), avec un portefeuille (dépôt, retrait, transactions) et un solde de départ que tu choisis.

## Jouer

Ouvre simplement `index.html` dans ton navigateur (aucune installation nécessaire).

- Au premier lancement, tu choisis ton solde de départ.
- Bouton **Portefeuille** : dépôts, retraits et historique des transactions.
- La mise est retirée du solde à chaque pari et les gains sont crédités, comme sur un vrai site.
- Solde, historique « Mes paris » et statistiques sont sauvegardés dans le navigateur.

## Règles

- Blackjack paie 3 contre 2 (2.50×), victoire 2.00×, égalité 1.00×.
- Le croupier reste sur tous les 17 et vérifie le blackjack (As ou figure visible).
- Assurance proposée si le croupier montre un As (paie 2 contre 1).
- Doubler sur les 2 premières cartes, séparer une fois (As séparés : une seule carte).
- Sabot infini : chaque carte est tirée avec `crypto.getRandomValues`.

## Raccourcis clavier

`Espace` parier · `Q` tirer · `W` rester · `E` séparer · `R` doubler · `S` mise ÷2 · `A` mise ×2
