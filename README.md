# 🔐 Chiffrement de Vigenère

## 📌 Description

Ce projet consiste en l’implémentation en Python de l’algorithme de chiffrement et de déchiffrement de Vigenère, une méthode de cryptographie classique basée sur un chiffrement par substitution polyalphabétique.

L’objectif est de comprendre les principes fondamentaux du chiffrement symétrique ainsi que les limites de sécurité de ce type d’algorithme.

---

## ⚙️ Fonctionnalités

* 🔑 Chiffrement d’un message à l’aide d’une clé
* 🔓 Déchiffrement du message
* Normalisation du texte (majuscules/minuscules)
* Traitement automatique de la clé (répétition)

---

## 🛠️ Technologies utilisées

* Python 3

---

## 🚀 Utilisation

### 1. Cloner le projet

```bash
git clone https://github.com/dalisadi/vigenere-cipher.git
cd vigenere-cipher
```

### 2. Lancer le programme

```bash
python main.py
```

### 3. Exemple

```python
message = "HELLO WORLD"
key = "KEY"

encrypted = encrypt(message, key)
print(encrypted)

decrypted = decrypt(encrypted, key)
print(decrypted)
```

---

## 📚 Concepts abordés

* Cryptographie classique
* Chiffrement symétrique
* Algorithme de Vigenère
* Manipulation de chaînes de caractères en Python

---

## ⚠️ Limites de sécurité

Le chiffrement de Vigenère n’est pas sécurisé face aux attaques modernes :

* Vulnérable aux attaques par analyse fréquentielle
* Faible face aux attaques par clé répétée

Ce projet est donc à but pédagogique.

---

## 🎯 Objectifs du projet

* Comprendre les bases de la cryptographie
* Implémenter un algorithme de chiffrement
* Manipuler des chaînes et structures en Python
* Développer une logique algorithmique

---

## 👩‍💻 Auteur

Dalia SADI
Étudiante en informatique – Cybersécurité & Réseaux

---
