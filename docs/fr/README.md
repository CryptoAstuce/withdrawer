# Parcours francais : withdrawer (preuve et finalisation des retraits L2 vers L1)

Lecture commentee du depot base/withdrawer : un utilitaire Go en ligne de commande qui prouve puis finalise un retrait d ETH depuis une chaine op-stack (Base ou Optimism) vers Ethereum L1, avec ou sans fault proofs.

Sommaire :

1. [Presentation de withdrawer](01-presentation.md)
2. [Deux chemins pour un meme retrait](02-deux-chemins.md)
3. [Le flux en deux passages, prouver puis finaliser](03-flux-principal.md)
4. [Le retrait classique, L2OutputOracle et OptimismPortal](04-withdrawer-classique.md)
5. [Le retrait avec fault proofs, DisputeGameFactory et parties invalidees](05-withdrawer-fault-proofs.md)
6. [Le signataire, cle privee, mnemonique ou Ledger](06-signer.md)
7. [Configuration du gas, simulation et dry-run](07-gas-et-dry-run.md)
8. [Limites et perimetre de ce parcours](08-limites-perimetre.md)

Ce parcours est une lecture pedagogique du code source et de la documentation du depot, sans installation ni execution du projet.
