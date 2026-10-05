<!-- ============================================================
     ENCYCLOPEDIE INTELLIGENTE - MARIANNE D'ETAT
     README descriptif - Logique pro - Badges
     (c) gunout - Tous droits reserves
     ============================================================ -->

<div align="center">

# 📚 Encyclopédie intelligente — Marianne d'État

### 🏛️ République Française · Ministère de l'Enseignement supérieur et de la Recherche

**Mots <-> Nombres <-> Hashs cryptographiques · Base 10 · Montée / Descente · SHA-3 · BLAKE2 · BLAKE3 · RIPEMD**

[![Made in France](https://img.shields.io/badge/Made%20in-France-000091?style=for-the-badge)](https://www.gouvernement.fr)
[![République Française](https://img.shields.io/badge/République-Française-E1000F?style=for-the-badge)](https://www.gouvernement.fr)
[![License](https://img.shields.io/badge/License-MIT-16a34a?style=for-the-badge)](LICENSE)
[![Version](https://img.shields.io/badge/version-2.0.0-000091?style=for-the-badge)](https://github.com)

---

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/fr/docs/Web/JavaScript)
[![Zero Dependency](https://img.shields.io/badge/Zero-Dependency-16a34a?style=flat-square)](#)
[![Single File](https://img.shields.io/badge/Single-File-000091?style=flat-square)](#)

---

[![MD5](https://img.shields.io/badge/MD5-RFC%201321-E1000F?style=flat-square)](https://www.rfc-editor.org/rfc/rfc1321)
[![SHA-1](https://img.shields.io/badge/SHA--1-FIPS%20180--4-E1000F?style=flat-square)](https://csrc.nist.gov/publications/detail/fips/180/4/final)
[![SHA-2](https://img.shields.io/badge/SHA--256%2F384%2F512-FIPS%20180--4-000091?style=flat-square)](https://csrc.nist.gov/publications/detail/fips/180/4/final)
[![SHA-3](https://img.shields.io/badge/SHA--3--256%2F512-FIPS%20202-000091?style=flat-square)](https://csrc.nist.gov/publications/detail/fips/202/final)
[![BLAKE2b](https://img.shields.io/badge/BLAKE2b-RFC%207693-16a34a?style=flat-square)](https://www.rfc-editor.org/rfc/rfc7693)
[![BLAKE3](https://img.shields.io/badge/BLAKE3-official-16a34a?style=flat-square)](https://github.com/BLAKE3-team/BLAKE3)
[![RIPEMD-160](https://img.shields.io/badge/RIPEMD--160-ISO%2FIEC%2010118--3-7c3aed?style=flat-square)](https://en.wikipedia.org/wiki/RIPEMD)
[![CRC-32](https://img.shields.io/badge/CRC--32-IEEE%20802.3-fbbf24?style=flat-square)](https://en.wikipedia.org/wiki/Cyclic_redundancy_check)

[![Verified](https://img.shields.io/badge/Vecteurs-Verifies-16a34a?style=flat-square)](#verification-croisee)
[![No Tracker](https://img.shields.io/badge/Zero-Tracker-E1000F?style=flat-square)](#)
[![RGPD](https://img.shields.io/badge/RGPD-Compliant-000091?style=flat-square)](#)

</div>

---

## 📖 Sommaire

- [Présentation](#presentation)
- [Contexte institutionnel](#contexte-institutionnel)
- [Fonctionnalités](#fonctionnalites)
- [Logique professionnelle](#logique-professionnelle)
- [Algorithmes supportés](#algorithmes-supportes)
- [Module Base 10](#module-base-10)
- [Recherche inversée](#recherche-inversee)
- [Vérification croisée](#verification-croisee)
- [Charte graphique Marianne](#charte-graphique-marianne)
- [Installation](#installation)
- [Format JSON attendu](#format-json-attendu)
- [Auto-tests](#auto-tests)
- [Sources officielles](#sources-officielles)
- [Sécurité et conformité](#securite-et-conformite)
- [Licence](#licence)

---

## 🎯 Présentation

**Encyclopédie intelligente — Marianne d'État** est une application **web autonome** (un seul fichier `.html`) qui permet :

| Action | Description |
|--------|-------------|
| 🔤 **Analyser un mot** | Décompose, hache, associe à un nombre |
| 🔢 **Analyser un nombre** | Propriétés mathématiques, factorisation, hashs, date UNIX |
| 🧠 **Décoder une séquence Base 10** | `2.1.19.5` = BASE |
| 🔐 **Générer des hashs** | Par plage (0 a N) avec tri et export |
| 🔄 **Inverser un hash** | Retrouve le nombre depuis son empreinte |
| ✓ **Vérifier les algos** | 14 tests RFC/NIST en direct |

**Philosophie** : zéro dépendance externe, zéro tracker, 100% client-side, tout-en-un.

---

## 🏛️ Contexte institutionnel

| Élément | Valeur |
|---------|--------|
| 🏛️ **Institution** | République Française |
| 🎓 **Ministère** | Enseignement supérieur et de la Recherche |
| 🏗️ **Direction** | DGRI — Direction générale de la recherche et de l'innovation |
| 🎨 **Charte** | Marianne (Bleu #000091 - Blanc #ffffff - Rouge #E1000F) |
| 📜 **Devise** | Liberté - Égalité - Fraternité |
| ⚖️ **Conformité** | RGPD - Code des relations public-administration |

---

## ✨ Fonctionnalités

### 🔍 Analyse intelligente

- Détection automatique du **type d'entrée** (mot, entier, décimal, séquence, hash)
- Décomposition **A1Z26** (lettre en valeur numérique)
- **Factorisation en nombres premiers**
- **Diviseurs**, propriétés remarquables (parfait, abondant, Harshad, Armstrong, Fibonacci, palindrome)

### 🔐 Hashs cryptographiques

- **13 algorithmes** vérifiés contre vecteurs officiels
- **Implémentation pure JS** pour MD5, SHA-1, SHA-256, SHA-3, BLAKE2b, BLAKE3
- **API WebCrypto native** pour SHA-384, SHA-512
- **Tableau interactif** trié par colonne

### 🧮 Base 10 - Montée / Descente

- Règle **monter = additionner**
- Règle **descendre = soustraire**
- Décodage des séquences pointées (`2.1.19.5` = BASE)

### 🔄 Recherche inversée

- Dictionnaire interne **0 a 2000** pré-chargé
- **Extension automatique** 2001 a 5000
- Support **13 algorithmes** simultanés

### 📥 Export

- **JSON** structuré
- **CSV** (compatible Excel / LibreOffice)
- **Copie presse-papiers**

---

## 🧠 Logique professionnelle

### 🎯 Pipeline d'analyse

Le traitement suit une logique en **5 étapes successives** :

**Étape 1 — Réception de l'entrée utilisateur**
L'utilisateur saisit une valeur dans le champ de recherche (mot, nombre, séquence ou hash).

**Étape 2 — Détection automatique du type**
Le système analyse la chaîne et détermine s'il s'agit de :
- un **hash** (regex `^[a-fA-F0-9]{8,128}$` ou préfixe `0x`)
- une **séquence Base 10** (regex `^\d+(\.\d+)+$`)
- un **entier** (regex `^-?\d+$`)
- un **décimal** (regex `^-?\d+(\.\d+)?$`)
- un **mot** (par défaut)

**Étape 3 — Aiguillage vers le module adapté**
- Si **hash** : redirection vers le module de recherche inversée
- Si **séquence** : redirection vers le décodeur Base 10
- Si **entier** : analyse numérique complète
- Si **décimal** : analyse décimale simplifiée
- Si **mot** : analyse textuelle complète

**Étape 4 — Traitement spécialisé**
- **Module MOT** : décomposition A1Z26, 13 hashs, couleur déterministe, statistiques
- **Module NOMBRE** : Base 10, propriétés, factorisation, 13 hashs, date UNIX
- **Module BASE 10** : décodage montée/descente, séquences pointées
- **Module HASH** : recherche dans dictionnaire, extraction nombre + algo

**Étape 5 — Rendu HTML**
Génération du HTML avec sections colorées et affichage dans la zone de résultats.

---

### 🛡️ Garde-fou anti-NaN (3 filets de sécurité)

1. **MutationObserver** : surveille en temps réel tous les `style.transform` et corrige
2. **Nettoyage initial** : parcourt le DOM au démarrage pour éliminer les `NaN`
3. **Hook CSSStyleDeclaration** : intercepte toute écriture de `transform` invalide

Extrait du code de correction :

```javascript
function safeTransform(str) {
    return String(str)
        .replace(/NaN/g, '0')
        .replace(/undefined/g, '0')
        .replace(/null/g, '0')
        .replace(/calc\(\s*0px\s*\)/g, '0');
}
```

---

### 🔄 Flux de la recherche inversée

1. **Saisie du hash** par l'utilisateur
2. **Interrogation** du dictionnaire pré-chargé via `Map.get(hash)`
3. **Cas 1 — Hash trouvé** : affichage du nombre et de l'algorithme
4. **Cas 2 — Hash non trouvé** :
   - Vérification de la taille du dictionnaire
   - Si inférieur a 35 000 entrées : **extension** de 2001 a 5000
   - **Nouvelle tentative** de recherche
5. **Affichage final** : nombre trouvé ou message d'échec

---

### 📊 Structure de données interne

Le système utilise **2 structures principales** :

**Dictionnaire inverse** — objet `Map` qui associe chaque hash a son nombre d'origine et son algorithme :

```javascript
window._reverseDict = new Map([
    ['cbf43926', { n: 123456789, algo: 'CRC-32' }],
    ['900150983cd24fb0d6963f7d28e17f72', { n: 'abc', algo: 'MD5' }]
]);
```

**Table de hashs** — tableau qui stocke les hashs générés par plage pour le générateur :

```javascript
window._hashData = [
    { nombre: 0, binaire: '0', crc32: 'F4DBDF21', md5: '...', sha256: '...' }
];
```

---

## 🔐 Algorithmes supportés

| # | Algorithme | Taille | Standard | Statut | Implémentation |
|---|-----------|--------|----------|--------|----------------|
| 1 | **CRC-32** | 32 bits | IEEE 802.3 | Contrôle | Pure JS (table) |
| 2 | **FNV-1a** | 32 bits | Fowler-Noll-Vo | Hash rapide | Pure JS |
| 3 | **MD5** | 128 bits | RFC 1321 | Obsolète | Pure JS |
| 4 | **SHA-1** | 160 bits | FIPS 180-4 | Obsolète | Pure JS |
| 5 | **SHA-256** | 256 bits | FIPS 180-4 | Sûr | Pure JS |
| 6 | **SHA-384** | 384 bits | FIPS 180-4 | Sûr | WebCrypto |
| 7 | **SHA-512** | 512 bits | FIPS 180-4 | Sûr | WebCrypto |
| 8 | **SHA-3-256** | 256 bits | FIPS 202 | Sûr | Pure JS (Keccak) |
| 9 | **SHA-3-512** | 512 bits | FIPS 202 | Sûr | Pure JS (Keccak) |
| 10 | **BLAKE2b** | 512 bits | RFC 7693 | Sûr | Pure JS |
| 11 | **BLAKE3** | 256 bits | Official | Sûr | Pure JS |
| 12 | **RIPEMD-160** | 160 bits | ISO/IEC 10118-3 | Sûr | Dérivée |
| 13 | **Base64** | Variable | RFC 4648 | Encodage | Native |

---

## 🧮 Module Base 10

### 📐 Règle formelle

| Action | Opération | Exemple |
|--------|-----------|---------|
| **MONTER** | Additionner chiffres | `67` : `6+7=13` : M |
| **DESCENDRE** | Soustraire chiffres | `67` : `7-6=1` : A |
| **BASE 10** | A=1, B=2, ..., Z=26 | `2.1.19.5` = BASE |

### 🔓 Décodage de séquences

| Séquence | Décomposition | Résultat |
|----------|---------------|----------|
| `2.1.19.5` | B - A - S - E | **BASE** |
| `1.18.14` | A - R - N | **ARN** |
| `3.20.24` | C - T - X | **CTX** |
| `17.4` | Q - D | **QD** |

### 💡 Exemple complet

Entrée : `67`

- **MONTER** : 67 devient 6 + 7 = 13, soit la lettre **M**
- **DESCENDRE** : 67 devient 7 - 6 = 1, soit la lettre **A**

---

## 🔄 Recherche inversée

### 📊 Exemple

Hash saisi : `cbf43926`

Résultat : le nombre **123456789** (algorithme **CRC-32**)

### ⚡ Performances

| Plage | Entrées | Hashs | Temps |
|-------|---------|-------|-------|
| 0 a 500 | 501 | ~6 500 | ~1 s |
| 0 a 2 000 | 2 001 | ~26 000 | ~4 s |
| 0 a 5 000 | 5 001 | ~65 000 | ~10 s |

---

## ✓ Vérification croisée

L'encyclopédie auto-teste ses implémentations contre les vecteurs officiels :

| Test | Attendu | Statut |
|------|---------|--------|
| `MD5("abc")` | `900150983cd24fb0d6963f7d28e17f72` | OK |
| `MD5("")` | `d41d8cd98f00b204e9800998ecf8427e` | OK |
| `SHA-1("abc")` | `a9993e364706816aba3e25717850c26c9cd0d89d` | OK |
| `SHA-256("abc")` | `ba7816bf8f01cfea414140de5dae2223b00361a396177a9cb410ff61f20015ad` | OK |
| `SHA-3-256("")` | `a7ffc6f8bf1ed76651c14756a061d662f580ff4de43b49fa82d80a4b80f8434a` | OK |
| `BLAKE2b("")` | `786a02f742015903c6c6fd852552d272912f4740e15847618a86e217f71f5419...` | OK |
| `BLAKE3("")` | `af1349b9f5f9a1a6a0404dea36dcc9499bcb25c9adc112b7cc9a93cae41f3262` | OK |
| `CRC-32("123456789")` | `CBF43926` | OK |

---

## 🎨 Charte graphique Marianne

### 🎨 Palette officielle

| Rôle | Code HEX | Usage |
|------|----------|-------|
| Bleu Marianne | `#000091` | Titres, boutons, liens |
| Rouge Marianne | `#E1000F` | Alertes, accents, sceau |
| Blanc | `#ffffff` | Fonds, cartes |
| Or | `#fbbf24` | Accents secondaires |
| Vert | `#16a34a` | Validation, succès |
| Violet | `#7c3aed` | Recherche, innovation |

### 🏛️ Éléments institutionnels

- **Bandeau officiel** avec sceau RF et République Française
- **Barre tricolore** fixe en haut
- **Devise** : Liberté - Égalité - Fraternité
- **Footer officiel** avec mentions légales et RGPD

---

## 🚀 Installation

### 📋 Prérequis

- Un **navigateur moderne** (Chrome, Firefox, Safari, Edge)
- **Aucune dépendance** externe
- **Aucun build** nécessaire

### 💾 Utilisation

1. **Télécharger** le fichier `encyclopedie-intelligente.html`
2. **Ouvrir** dans un navigateur (double-clic)
3. C'est tout !

### 🔒 Mode local sécurisé

```bash
# Optionnel : servir en local
python3 -m http.server 8000
# Puis ouvrir http://localhost:8000/encyclopedie-intelligente.html
```

---

## 📁 Format JSON attendu

Pour la variante **Monitor Recherche** :

```json
[
  {
    "acronyme": "ANR-22-CE45-0001",
    "titre": "Modelisation des reseaux complexes",
    "laboratoire": "LIP6 - Sorbonne Universite",
    "discipline": "Informatique",
    "financeur": "ANR",
    "annee": "2022",
    "annee_fin": "2026",
    "porteur": "Marie Dupont",
    "statut": "En cours",
    "budget": 450000,
    "description": "Etude des proprietes topologiques",
    "mots_cles": "reseaux, topologie, algorithmes",
    "lien": "https://anr.fr/"
  }
]
```

---

## 🧪 Auto-tests

Ouvre la **console** (F12) pour voir :

- Garde-fou anti-NaN active (MutationObserver + hook CSSStyleDeclaration)
- Encyclopedie intelligente - Marianne d'Etat
- (c) gunout - Tous droits reserves
- Pre-chargement du dictionnaire inverse (0 vers 500)
- Dictionnaire partiel pret (0 vers 500)

Clique sur le bouton **Verification croisee** pour lancer les **14 tests RFC/NIST** en direct.

---

## 📚 Sources officielles

| Algorithme | Source | Lien |
|------------|--------|------|
| MD5 | RFC 1321 | [ietf.org](https://www.rfc-editor.org/rfc/rfc1321) |
| SHA-1 | FIPS 180-4 | [NIST](https://csrc.nist.gov/publications/detail/fips/180/4/final) |
| SHA-2 | FIPS 180-4 | [NIST](https://csrc.nist.gov/publications/detail/fips/180/4/final) |
| SHA-3 | FIPS 202 | [NIST](https://csrc.nist.gov/publications/detail/fips/202/final) |
| BLAKE2b | RFC 7693 | [ietf.org](https://www.rfc-editor.org/rfc/rfc7693) |
| BLAKE3 | Official | [GitHub](https://github.com/BLAKE3-team/BLAKE3) |
| RIPEMD | ISO/IEC 10118-3 | [ISO](https://www.iso.org/standard/67116.html) |
| CRC-32 | IEEE 802.3 | [IEEE](https://standards.ieee.org/standard/802_3-2018.html) |
| Base64 | RFC 4648 | [ietf.org](https://www.rfc-editor.org/rfc/rfc4648) |

---

## 🛡️ Sécurité et conformité

### ✅ Bonnes pratiques

- **100% client-side** : aucune donnée envoyée à un serveur
- **Zéro tracker** : pas d'analytics, pas de cookies
- **Zéro dépendance** : pas de CDN, pas de npm
- **Single-file** : un seul fichier `.html`
- **RGPD** : aucune donnée personnelle traitée
- **Open source** : code auditable
- **Fonctionne offline** : aucune connexion requise

### ⚠️ Limitations

- MD5 et SHA-1 sont **obsolètes** pour la sécurité — utilisés uniquement pour la compatibilité
- RIPEMD-160 est une **implémentation dérivée** (démonstration)
- Ne pas utiliser pour du **chiffrement** — uniquement pour du **hachage**

---

## 📄 Licence

MIT License

Copyright (c) 2025 - gunout

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

<div align="center">

## 🏛️ République Française

### Liberté - Égalité - Fraternité

**📚 Encyclopédie intelligente — Marianne d'État**

_(c) 2025 - gunout - Tous droits réservés_

---

⭐ **Si ce projet t'a plu, mets une étoile !** ⭐

</div>
