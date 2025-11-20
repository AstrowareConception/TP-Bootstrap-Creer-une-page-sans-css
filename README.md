
# 🧪 **TP Bootstrap – Créer une page d’accueil moderne sans écrire de CSS**

### ⏱ Durée : environ 2 heures

### 🎓 Niveau : étudiants de 1ère année BTS SIO

### 🎯 Objectif : pratiquer Bootstrap en autonomie, sans écrire une seule ligne de CSS

---

## 🔒 **Contraintes du TP**

* **AUCUN CSS autorisé**
  👉 Pas de `<style>`
  👉 Pas de `.css` externes
  👉 Pas de style inline (`style="…"`)
  ➜ **Tout le style doit venir de Bootstrap + éventuellement un thème Bootswatch**

* **Bootstrap obligatoire**
  (via CDN, pas d’installation locale)

* **HTML propre, indenté, et lisible**

---

# 📘 **Contexte**

Le lycée fictif **Tech&Co** souhaite une petite page web propre et moderne pour présenter son **Service Informatique**.

Vous devez créer une **page d’accueil responsive**, esthétique, professionnelle, en vous appuyant **uniquement sur Bootstrap ou un thème Bootswatch**.

---

# 🎨 **Étape 1 — Mise en place**

1. Créez un dossier :
   **`tp-bootstrap-service-info`**

2. Créez un fichier :
   **`index.html`**

3. Ajoutez le **starter template** Bootstrap depuis la documentation officielle :

   * Le `<link>` du CSS Bootstrap dans le `<head>`
   * Le script JS Bootstrap juste avant `</body>`

4. (Optionnel mais recommandé) Choisissez un **thème Bootswatch** :
   👉 [https://bootswatch.com/](https://bootswatch.com/)
   Cliquez sur un thème, puis remplacez le lien CSS de Bootstrap par celui du thème.

> 🎯 À la fin de cette étape :
> Vous devez avoir une page blanche mais stylée grâce à Bootstrap ou au thème choisi.

---

# 🧱 **Étape 2 — Créer une navbar responsive**

La page doit commencer par une **navbar** Bootstrap avec :

* Le nom du service :
  **Tech&Co — Service Informatique**
* Trois liens (sans destination) :

  * Accueil
  * Services
  * Contact
* Une version **responsive** (burger menu sur mobile)

---

# 🌟 **Étape 3 — Créer un “hero” de présentation**

Sous la navbar, créez un bloc principal avec :

* Un grand titre (ex. : **Support informatique du lycée Tech&Co**)
* Un sous-titre de présentation (1 à 2 phrases)
* Un bouton Bootstrap (ex : `btn btn-primary`) :
  **Nous contacter** ou **Ouvrir un ticket**

Pour le style, utilisez uniquement :

* `container`
* `text-center`
* `py-5`
* ou tout autre utilitaire Bootstrap

AUCUN CSS personnalisé.

---

# 🧰 **Étape 4 — Section “Nos services”**

Créez une section avec un titre **H2** :
👉 *Nos services*

Puis, alignez **3 cartes Bootstrap (`card`)** dans une grille responsive :

* `row` + `col-md-4`
* Chaque carte doit contenir :

  * Un titre (ex : “Assistance PC”)
  * Une petite description
  * Un bouton “En savoir plus” (optionnel)

Exemples de services :

* Assistance aux postes (PC, imprimante…)
* Gestion des comptes ENT / messagerie
* Support réseau / Wi-Fi

---

# 🕒 **Étape 5 — Infos pratiques**

Ajoutez une section avec :

* Une **alert** Bootstrap (ex : “Nous sommes fermés le week-end”)
* Une liste d’informations pratiques utilisant :

  * `list-group`
  * ou un petit `table.table.table-striped`

Informations à mettre :

* Horaires d’ouverture
* Salle / bâtiment
* Adresse mail de contact

Toujours sans CSS.

---

# 🦶 **Étape 6 — Footer**

En bas de la page, ajoutez un footer simple :

* Texte centré :
  **© 2025 Lycée Tech&Co – Service Informatique**
* Utilisez par exemple :
  `bg-light`, `py-3`, `text-center`


---

# ⭐ **Bonus (optionnel)**

Si vous finissez avant :

* Ajouter un **accordion** FAQ
* Ajouter une **section Équipe** (cartes avec photos placeholder)
* Utiliser différents composants (badge, progress bar…)
* Ajouter un **mode sombre** via un thème Bootswatch

---

