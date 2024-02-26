# Explications

# Utilisation de 5 Describe:
# _ Vérification du déploiement du smart contract
# _ Vérification des différentes étapes du statut du Workflow
1 beforeEach pour déployer le contrat avant chaque "it".
# _ Vérification des fonctions AddVoter() et GetVoter()
# 1 beforeEach pour déployer le contrat avant chaque "it".
# _ Vérification des fonctions AddProposal() et GetOneProposal()
# 1 beforeEach pour déployer le contrat avant chaque "it" et créer 2 voters.
# _ Vérification des fonctions SetVote() et Tallyvotes()
# 1 beforeEach pour déployer le contrat avant chaque "it", créer 3 voters et 1 proposal.

# Résultats

yarn hardhat test => 42 passing
yarn hardhat coverage => 100% statements, 100% branch, 100% functions, 100% lines
