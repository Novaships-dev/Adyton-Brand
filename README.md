# ADYTON — Forbidden Archives

> *Adyton* (grec ancien, ἄδυτον) : le sanctuaire le plus secret d'un temple,
> la salle interdite « où l'on ne pénètre pas ».

Marque de streetwear print-on-demand construite comme une **archive interdite** :
chaque t-shirt est un dossier classifié numéroté. Vente via **Shopify**, production
**print-on-demand** via **Printify** (DTG sur Bella+Canvas 3001).

---

## À quoi sert ce repo

Ce dépôt réunit **toute la fondation de la marque** (identité, système d'impression,
contexte stratégique) pour permettre de construire la boutique et de créer les
collections de façon cohérente — y compris par un agent de code (voir `CLAUDE.md`).

## Structure

```
adyton-brand/
├── README.md            ← ce fichier
├── CONTEXT.md           ← contexte complet marque + business (à lire en premier)
├── CLAUDE.md            ← instructions pour l'agent qui code la boutique / crée les produits
├── brand/
│   ├── logo/            ← logotype + planche d'identité (SVG + PNG)
│   ├── seal/            ← sceau (3 encres), icône, monogramme
│   └── declinations.png ← aperçu de toutes les variantes
├── print-system/        ← gabarits d'impression + fiche technique (cotes exactes)
└── docs/
    └── brief-original.md ← brief maître d'origine (détail des 12 collections)
```

## Repères express

| | |
|---|---|
| **Nom** | ADYTON |
| **Baseline** | FORBIDDEN ARCHIVES |
| **Devise du sceau** | NON INTRABIS (latin — « tu n'entreras pas ») |
| **Typo** | Space Mono |
| **Palette** | encre `#17130D` · papier `#EAE3D2` · rouge alerte `#A62B22` |
| **Produit** | Bella+Canvas 3001, DTG |
| **Fournisseurs** | OPT OnDemand (Europe) + Underground Threads (USA) |
| **Master dos** | 4200 × 4800 px · **Sceau** 1050² · **Manche** 898² (300 DPI) |
| **Structure** | 12 collections × 10 dossiers = 120 designs |

## Statut

- ✅ Nom, identité visuelle complète, système d'impression, fournisseurs
- ⏳ À faire : domaine + handles, recherche marque classe 25, échantillons, **création des collections**
