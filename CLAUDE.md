# CLAUDE.md — Instructions agent (build boutique + création produits/collections)

Tu construis la boutique **Shopify** d'ADYTON et tu crées les produits/collections via
**Printify** (Bella+Canvas 3001, DTG). Lis `CONTEXT.md` en entier avant d'agir.
`docs/brief-original.md` contient le détail narratif des 12 collections.

Ce fichier liste les **règles dures**. En cas de doute, demande — ne devine pas sur les
points marqués ⛔.

---

## ⛔ Règles dures d'impression

1. **DTG uniquement. JAMAIS la broderie (embroidery).** La broderie ne peut pas rendre
   l'univers ADYTON (max 6 couleurs, pas de photo, pas de dégradé, pas de texture, zone
   minuscule). Toujours vérifier que le mode Printify est **DTG** (URL de l'éditeur = `/dtg`).
2. **Cotes MASTER exactes** (300 DPI, sRGB, PNG fond transparent) — générer et uploader
   à ces tailles, jamais agrandir un fichier après coup :
   - **Dos** : `4200 × 4800 px`
   - **Sceau avant** : `1050 × 1050 px` (placé poitrine gauche)
   - **Manche gauche** : `898 × 898 px`
3. **Ne jamais concevoir le dos plus large que 4200 px.** C'est la limite du fournisseur
   EU (OPT) ; au-delà, l'impression US est correcte mais l'EU rogne. 4200×4800 marche
   partout à l'identique.
4. **Zone sûre** : garder les éléments vitaux (titre, N° de dossier) à ~5 % des bords
   (dos ≈ zone centrale 3800×4460). ~1 cm de bord peut être rogné (bleed).
5. **Deux fournisseurs, routage par localisation** : OPT OnDemand (EU) + Underground
   Threads (US). Créer le produit chez les deux, mêmes fichiers, mêmes placements.

## ⛔ Règles dures de marque

- **Palette stricte** : encre `#17130D`, papier `#EAE3D2`, rouge alerte `#A62B22`. Rien d'autre.
- **Typo** : Space Mono partout (assets dans `brand/`, typo intégrée dans les SVG).
- **Baseline** : `FORBIDDEN ARCHIVES`. **Devise sceau** : `NON INTRABIS` (ne pas traduire).
- Utiliser les assets fournis (`brand/seal/`, `brand/logo/`) — ne pas recréer le logo ou
  le sceau depuis zéro.

## Contenu — garde-fous (voir CONTEXT §8)

- Thèmes présentés comme **hypothèses / dossiers / questions**, jamais comme faits.
- **Aucun groupe, personne ou communauté réelle visé.** SECRET ORDER / HUMAN PROGRAM :
  distance esthétique, pas de trope haineux, pas d'accusation réelle.
- Éviter les IP déposées (ex. « Matrix »). Noms publics réels (Area 51, MK-Ultra,
  Operation Fishbowl) = OK.
- Objectif : mystère esthétique premium, jamais militantisme. La marque vit d'organique
  social → tout contenu bannissable est un risque existentiel.

---

## Modèle de données produit (par dossier)

Chaque design est un dossier. Métadonnées à porter dans le titre/description Shopify et,
si possible, en tags/metafields :

```
code:          FF-001                     # <PréfixeCollection>-<NNN>
title:         THE MAP
collection:    FLAT FILES
status:        DISPUTED                    # libre, ton "dossier"
archive:       WORLD MODEL
access_level:  RESTRICTED
sleeve_code:   ADYTON // FF-001
```

Préfixes collections : FF, LE, CL, DI, MF, SO, AC, SI, FL, HP, EG, AR (voir CONTEXT §6).

Titre produit Shopify suggéré : `ADYTON — FF-001 · THE MAP`
Handle/SKU : `adyton-ff-001`.

## Workflow d'ajout d'un design

1. Générer les 3 fichiers art aux cotes MASTER (dos 4200×4800, sceau 1050², manche 898²),
   PNG transparent 300 DPI sRGB, en respectant palette + zone sûre.
2. Créer le produit Printify **BC3001, DTG** chez **OPT** et chez **Underground Threads**.
3. Placer : Face avant = sceau (poitrine gauche), Face arrière = œuvre, Manche gauche = code.
4. Renseigner titre/description/métadonnées (modèle ci-dessus).
5. Publier vers la **collection Shopify** correspondante (1 collection Shopify = 1 des 12).
6. Ne pas produire les 120 d'un coup : lancer collection par collection, valider.

## Boutique Shopify

- 12 collections Shopify = les 12 univers (CONTEXT §6).
- Esthétique du storefront = archive/dossier : fond papier, encre, Space Mono, sceau en
  filigrane/en-tête, mentions type « CLASSIFIED FILE ».
- Capturer l'email dès l'entrée (pop-in « accès aux archives ») — la liste email est le
  seul canal que personne ne peut bannir.
- Pas d'intégration pub payante (non utilisée).

## Prix & marge

- Retail cible ~**39,90 €**. Coût prod ~13–17 $ (3 zones). Intégrer **TVA** (~20 % UE) et
  **expédition** selon marché avant d'annoncer une marge. Vérifier le coût réel dans le
  Product Creator du fournisseur (varie selon variante/taille/zones).

## À ne pas oublier (bloquants hors code)

- **Échantillon** dos plein format sur tee noir chez OPT **et** Underground Threads avant
  toute vente réelle (valider la qualité DTG, surtout UT noté 8.8).
- Vérifier que les **couleurs sombres** sont en stock chez OPT (40 % de variantes en
  rupture au global).
- Domaine + handles + recherche marque classe 25 (admin, hors code).
