# 📝 ChainNotes - Un Mur de Messages Décentralisé sur Base

ChainNotes est un smart contract déployé sur **Base Mainnet** qui permet à quiconque de poster des messages sur la blockchain de manière transparente et immuable.

---

## 📌 **Smart Contract**
- **Adresse du contrat** : `0xcd35eee173111a50f2cabdda8c039035e636b61a`
- **Réseau** : Base Mainnet (`https://mainnet.base.org`)
- **Langage** : Solidity (`^0.8.19`)
- **Fonctionnalités** :
  - Permet à tout utilisateur d'ajouter un message on-chain.
  - Stocke les messages de manière **publique** et **immutable**.
  - Limite chaque message à **200 caractères** pour éviter le spam.

---

## 🛠️ **Comment Interagir avec le Contrat ?**

### 1️⃣ **Via Remix**
1. Ouvrir **[Remix Ethereum](https://remix.ethereum.org/)**
2. Aller dans **Deploy & Run Transactions**.
3. Sélectionner **"Injected Provider - MetaMask"** et choisir le réseau **Base Mainnet**.
4. Copier l'adresse du contrat (`0xcd35eee173111a50f2cabdda8c039035e636b61a`).
5. Interagir avec les fonctions `postNote(string message)` et `getAllNotes()`.

### 2️⃣ **Via Etherscan (BaseScan)**
1. Aller sur **[BaseScan](https://basescan.org/address/0xcd35eee173111a50f2cabdda8c039035e636b61a)**
2. Naviguer vers l'onglet **"Write Contract"** pour ajouter un message.
3. Aller dans **"Read Contract"** pour voir tous les messages stockés.
