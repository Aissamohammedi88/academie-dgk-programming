# academie-dgk-programming
Complete 50-module programming curriculum. From binary foundations to complex systems (AI, multi-agent swarms). Hands-on projects. Sovereign code. By Aissa Mohammedi (DGK).
 🎓 Academie-DGK — Stack Programmation & Sécurité
# Déployez instantanément votre espace d'apprentissage/immersion

> Cette section est **interactive** : copiez-collez dans votre terminal Linux/MacOS (PowerShell avec ajustements pour Windows).

---
## ⚡ Installation en 3 étapes

### 1️⃣ Clone ou Initialise
```bash
cd ~/academie-dgk-programming

    Créez le dossier si nécessaire : mkdir -p ~/academie-dgk-programming && cd "$_" {.card}

2️⃣ Init & Git
git init -b main
git add README.md .gitignore modules/
git commit -m "feat: initialisation de l'académie DGK avec 50 modules"

    Aucune étape perdue.

3️⃣ Liens & Push
git remote add origin https://github.com/<YOUR-GITHUB-USER>/academie-dgk-programming.git
git push -u origin main

    🔑 Personnalise le URL origin: remplace <YOUR-GITHUB-USER> par ton identifiant GitHub.

📦 Structure proposée (à personnaliser)
academie-dgk-programming/
├─ modules/
│   ├─ intro-python/
│   ├─ algos/
│   ├─ web-dev/
│   ├─ crypto-basics/
│   ├─ docker/ 
│   └─ rust/
└─ docs/
    ├─ notes.md
    └─ licence.txt

    💡 Chaque sous-dossier devient un module complet : README + exercices + tests + solutions (optionnel).
