
# Explications

Utilisation de 5 Describes dans ('Test Voting Contract'):

describe('Initialisation') => Vérification du déploiement du smart contract

describe('Workflow') => Vérification des différentes étapes du statut du Workflow

1 beforeEach pour déployer le contrat avant chaque "it".

describe('Add and Get Voter') => Vérification des fonctions AddVoter() et GetVoter()

1 beforeEach pour déployer le contrat avant chaque "it".

describe('Add and Get Proposal') => Vérification des fonctions AddProposal() et GetOneProposal()

1 beforeEach pour déployer le contrat et créer 2 voters avant chaque "it".

describe('Set and Tally Vote') => Vérification des fonctions SetVote() et Tallyvotes()

1 beforeEach pour déployer le contrat, créer 3 voters et 1 proposal avant chaque "it".

# Résultats

yarn hardhat test => 42 passing

yarn hardhat coverage => 100% statements, 100% branch, 100% functions, 100% lines


## Screenshots

![App Screenshot](https://github.com/ThibautBaudry/Projet_2_Alyra/blob/main/Capture%20d%E2%80%99%C3%A9cran%202024-02-26%20%C3%A0%2020.48.48.png)


![App Screenshot](https://github.com/ThibautBaudry/Projet_2_Alyra/blob/main/Capture%20d%E2%80%99%C3%A9cran%202024-02-26%20%C3%A0%2020.49.05.png)


## Authors

- [@ThibautBaudry](https://github.com/ThibautBaudry)
