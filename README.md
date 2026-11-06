# OL DING — terres et immobilier propre

Site vitrine statique (HTML / CSS / JS, sans build) hébergé sur GitHub Pages,
domaine `olding.shop`.

> Généré depuis `C:\Users\souha\coaching-sites-factory` (fichier `sites/olding.mjs`).
> Pour une modification de contenu, éditez ce fichier puis relancez `node build.mjs olding` :
> une modification faite directement ici serait écrasée à la prochaine génération.

## À compléter avant de communiquer sur le site

| Priorité | Quoi | Où |
|---|---|---|
| 🔴 Bloquant | Mentions légales : identité de l’éditeur, SIREN, adresse, médiateur. Obligatoire en France. | `mentions-legales.html` |
| 🟠 Important | Adresse `contact@olding.shop` : créer une redirection e-mail chez Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Formulaire : remplacer `VOTRE_ID_FORMSPREE` (sinon repli automatique en `mailto:`). | `contact.html` |
| 🟠 Important | Présentation de la personne qui coache (nom, parcours réel, photo). | `a-propos.html` |
| 🟡 Plus tard | Tarifs (Selon plafond / Selon le bien / Non €) et contenu des formules à ajuster à votre offre réelle. | `index.html` `#tarifs` |
| 🟡 Plus tard | Témoignages : n’en ajoutez que des vrais, avec l’accord des personnes. | — |

## Description de l’activité (Stripe, annuaires…)

```
We are OL DING, a property-holding company based in Hannut in the province of Liège, formed in February 2022. We let land, housing and non-residential premises that we own ourselves, and we hold participations in other companies. One point governs everything we do and most landlords learn it too late: in Belgium the legal regime of a lease follows the use that is actually made of the property, not the title written at the top of the contract. Where land is let for agricultural use, the farm lease regime applies even if the document calls itself a precarious occupancy agreement. That regime is mandatory. It brings a minimum term of nine years, a rent capped by coefficients set province by province, with any excess recoverable by the tenant, notice restricted to grounds the law lists, and a right of pre-emption for the tenant if the land is sold. We put the applicable regime in writing before anyone signs, in the tenant's interest as much as our own, because a lease wrongly labelled is not a lease avoided. Site: olding.shop
```

## Structure

```
index.html            Accueil : hero, programmes, méthode, tarifs, approche, FAQ
programmes.html       Détail des 4 programmes
a-propos.html         Notre approche et principes
contact.html          Formulaire de prise de contact
mentions-legales.html Mentions légales, confidentialité, CGV
404.html              Page d’erreur (chemins absolus)
assets/css/style.css  Couleurs de la marque en tête de fichier, puis styles communs
assets/js/main.js     Menu, thème, animations, formulaire
```

## DNS (Namecheap → Advanced DNS)

Supprimer les enregistrements de parking, puis :

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
