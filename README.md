# 🚀 Atelier JS — Initiation à JavaScript avec Style

![Banner](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Atelier%20JS&fontSize=40&fontAlign=center)

Bienvenue dans ce mini-atelier JavaScript 🔥 conçu pour apprendre, expérimenter, et rigoler un peu avec du code JS moderne !

---

## 💡 À propos du projet

🎯 Ce dépôt contient des exercices pratiques et des scripts éducatifs pour apprendre les bases de JavaScript de manière concrète.

🧠 Pensé pour les débutants ambitieux qui veulent maîtriser la logique derrière les scripts, DOM, événements, boucles, fonctions et bien plus.

---

## 📁 Contenu du dépôt

- `index.html` – base pour tester tes scripts  
- `exercices/` – dossiers classés par thème  
- `scripts/` – tous les fichiers JavaScript associés  
- `README.md` – t'es dessus là mec  

---

## 🧰 Technologies utilisées

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/VSCode-%23007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## 🛠️ Installation

```bash
git clone https://github.com/Fadi-AICH/atelier-js.git
cd atelier-js
npm install
npm run dev
```
---

## 📘 Aperçu des Exercices

### 🧪 Exercice 1 — Variables & Types

> Apprendre à déclarer des variables et manipuler des types primitifs

```js
let prenom = "Fadi";
let age = 26;
const isHacker = true;

console.log(`Je m'appelle ${prenom}, j'ai ${age} ans et je suis ${isHacker ? "un hacker" : "normal"} 😎`);
```

---

### 🧠 Exercice 2 — Conditions & Logique

> Comprendre les instructions conditionnelles `if`, `else`, et les opérateurs logiques

```js
const password = "azerty007";

if (password.length > 8 && password.includes("007")) {
  console.log("🔓 Accès autorisé");
} else {
  console.log("🚫 Mot de passe faible");
}
```

---

### 🔁 Exercice 3 — Boucles & Tableaux

> Manipuler les boucles `for`, `while` et parcourir un tableau

```js
const outils = ["Burp Suite", "Nmap", "Wireshark"];

for (let outil of outils) {
  console.log(`🔍 Analyse avec ${outil}`);
}
```

---

### 🧰 Exercice 4 — Fonctions

> Créer des fonctions simples et utiliser la portée locale/globale

```js
function scanPort(port) {
  return port === 22 ? "SSH détecté" : `Port ${port} analysé`;
}

console.log(scanPort(22)); // 🔐 SSH détecté
```

---

### 🖱️ Exercice 5 — Manipulation du DOM

> Interagir avec la page HTML via le DOM

```js
document.querySelector("#hackButton").addEventListener("click", () => {
  document.body.style.backgroundColor = "#000";
  alert("Mode Hacker activé 👨‍💻");
});
```

---

## ✍️ Auteur

**👤 Fadi AICH**  
🎓 Étudiant ingénieur en cybersécurité | 🧠 Passionné d’ethical hacking 
🔗 [GitHub](https://github.com/Fadi-AICH) 

---

## ✨ Citation Dev du jour

![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)
```


