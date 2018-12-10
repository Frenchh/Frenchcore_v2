Franc Core integration/staging repository
=================================================
[![Build Status](https://travis-ci.org/franc/franc.svg?branch=master)](https://travis-ci.org/franc/franc) ![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)

Franc (FRC) est une crypto-monnaie durable inspirée de la vision de Satoshi Nakamoto pour Bitcoin. Il s'agit d'une devise transactionnelle peer-to-peer décentralisée, conçue pour offrir une solution au problème posé par l'augmentation exponentielle de l'énergie consommée par Bitcoin et d'autres monnaies de preuve du travail. L'extraction minière avec preuve de travail n'est pas durable du point de vue de l'environnement du fait de l'électricité utilisée par le matériel minier de grande puissance. Franc utilise le protocole vert, un algorithme de preuve d’enjeu économe en énergie inspiré de PIVX / DASH, qui peut être extrait sur n’importe quel ordinateur et n’exigera jamais d’équipement minier spécialisé. Le protocole vert offre une solution simple aux problèmes de durabilité Bitcoin et fournit une blockchain plus rapide et plus évolutive, mieux adaptée à une utilisation transactionnelle quotidienne.

- Les transactions rapides comportant des transactions de confirmation zéro garanties, nous l'appelons _SiftTX_.
- Vote décentralisé sur la blockchain permettant un avancement par consensus du Masternode actuel
  La technologie utilisée pour sécuriser le réseau et fournir les fonctionnalités ci-dessus, chaque Masternode est sécurisé
  with a collateral of 2,500 FRC.

More information at [franc-blockchain.com](http://www.franc-blockchain.com)


### Coin Specs
|-----------------------------|----------------|
| Temps par bloc              | 120 Seconds    |
| Max Coin Supply (PoW Phase) | 500,000 FRC    |
| Max Coin Supply (PoS Phase) | 20,500,000 FRC |
| Premine                     | 500,000 FRC    |

### Reward Distribution

| **Hauteur du bloc** | **Frenchnodes**  |     **PoS**      |
|---------------------|------------------|------------------|
| 201-5000            | 85% (0.85 FRC)   | 15% (0.15 FRC)   | 
| 5001-25000          | 85% (25.5 FRC)   | 15% (4.5 FRC)    |
| 25001-100000        | 85% (17 FRC)     | 15% (3 FRC)      | 
| 100001-1050000      | 85% (8.5 FRC)    | 15% (1.5 FRC)    |
| 1050001-2100000     | 85% (4.25 FRC)   | 15% (0.75 FRC)   | 
| 2100001-3150000     | 85% (2.13 FRC)   | 15% (0.375 FRC)  | 
| 3150001-Infinite    | 85% (1.06 FRC)   | 15% (0.195 FRC)  | 
