# ADYTON — Contexte complet

Document de référence pour toute décision de marque, de design ou de code.
Pour le détail narratif des collections, voir `docs/brief-original.md`.

---

## 1. Essence & positionnement

ADYTON n'est pas une boutique de t-shirts imprimés — c'est une **archive interdite**.
Chaque pièce doit donner l'impression d'être un **fragment de dossier classifié**, une
pièce d'archive, un document interdit. L'univers : mystères, histoire alternative,
dossiers censurés, questions interdites.

Le porteur ne porte pas un motif : il porte **un dossier**. Le système pousse à la
collection (posséder plusieurs pièces), à la rareté et à la continuité narrative.

Positionnement : **premium**, sobre, intriguant. La retenue fait le haut de gamme
(peu de couleurs, typo unique, texture maîtrisée).

## 2. Décisions stratégiques (cadre fixé par le fondateur)

- **Lancement des 12 collections** simultanément (120 designs potentiels), mais **pas
  produits au hasard ni tous d'un coup sans validation**.
- **Aucune publicité payante.** Acquisition **100 % organique**, **mondiale**
  (TikTok / YouTube / Pinterest). → conséquence : la distribution repose sur des comptes
  sociaux ; un bannissement de compte est le risque n°1 → ne jamais dépendre d'un seul
  canal, capturer l'audience en **email + site** dès le jour 1.
- **Marché mondial dès le départ** (d'où deux fournisseurs, EU + US).
- **Langue : anglais** pour la portée internationale (baseline FORBIDDEN ARCHIVES,
  codes de collection en anglais).
- **Tous les angles thématiques sont conservés.**

## 3. Identité visuelle

- **Logotype** : `ADYTON` en Space Mono Bold, largement espacé.
- **Sceau** : emblème circulaire — fronton de temple + serrure en négatif (la chambre
  interdite verrouillée), anneau « ADYTON » / « NON INTRABIS », « ΑΔΥΤΟΝ » sous le glyphe.
  Décliné en 3 encres : noir, blanc (knock-out, tee sombre), rouge (tampon).
- **Icône** : temple + serrure dans un cercle, sans texte (petits formats).
- **Monogramme** : « A » dans un cercle (favicon, étiquette, bouton).
- **Baseline** : FORBIDDEN ARCHIVES.
- **Devise du sceau** : NON INTRABIS (latin). Ne pas traduire.
- **Typographie** : Space Mono (tout le système — c'est la signature « document tapé »).
- **Palette** : encre `#17130D` · papier `#EAE3D2` · rouge alerte `#A62B22`. Rien d'autre.
- **Texture** (sur les designs) : grain toner/photocopie, repères d'impression, trame —
  c'est ce qui sépare l'archive premium du t-shirt mème.

Fichiers dans `brand/` (SVG vectoriels, typo Space Mono intégrée).

## 4. Système de dossiers

Chaque design = un **dossier numéroté**. En-tête type :

```
FILE 001 — THE MAP
STATUS: DISPUTED
ARCHIVE: WORLD MODEL
ACCESS LEVEL: RESTRICTED
```

Codification par collection : `FF-001`, `FF-002`, … (préfixe = collection).
Chaque collection a : nom, symbole, code, traitement typo, palette, règles graphiques,
et ses 10 dossiers de lancement.

## 5. Architecture d'un t-shirt

- **Avant** : petit sceau discret, poitrine gauche.
- **Dos** : l'œuvre principale, pleine surface — la raison d'achat. Pensé comme une
  affiche / couverture de dossier (titre, N°, composition, symbole).
- **Manche gauche** : le code court du dossier (ex. `ADYTON // FF-001`).

## 6. Les 12 collections

| Code | Collection | Univers (résumé) |
|---|---|---|
| FF | **FLAT FILES** | Terre plate, firmament, cartes azimutales, Antarctique, mur de glace, Polaris, modèles anciens du monde |
| LE | **LOST EMPIRES** | Tartarie, civilisations effacées, mud flood, villes enfouies, chronologies alternatives |
| CL | **CLASSIFIED** | Dossiers déclassifiés, programmes secrets, MK-Ultra, black projects, niveaux d'accès |
| DI | **DISCLOSURE** | OVNI / UAP, Area 51, crashs, témoignages, récupération de technologies |
| MF | **MOON FILES** | Missions Apollo, anomalies lunaires, face cachée, transmissions |
| SO | **SECRET ORDER** | Sociétés secrètes, symboles codés, pyramides, ordres cachés *(voir §8 sensibilités)* |
| AC | **ANCIENT CODE** | Égypte, Sumer, Anunnaki, géométrie sacrée, textes anciens |
| SI | **SIMULATION** | Réalité simulée, glitchs, NPC, code de la réalité, perception |
| FL | **FORBIDDEN LANDS** | Antarctique, zones interdites, terres inconnues, expéditions |
| HP | **HUMAN PROGRAM** | Médias, surveillance, ingénierie sociale, fabrication du consentement *(voir §8)* |
| EG | **ENDGAME** | Dystopie, transhumanisme, identité numérique, fusion homme-machine |
| AR | **THE ARCHIVE** | Collection spéciale : pièces les plus mystérieuses, éditions limitées, méta-lore |

Objectif : 12 × 10 = **120 designs**. Méthode recommandée : lancer collection par
collection, valider, étendre — ne pas tout produire d'un coup.

## 7. Production & impression

- **Produit** : Bella+Canvas 3001, **DTG uniquement** (jamais broderie — voir CLAUDE.md).
- **Fournisseurs** (routage par localisation client) :
  - **OPT OnDemand** — Europe (note 9.1). EU : ~4,49 $ 1er article.
  - **Underground Threads** — USA (note 8.8, tout en stock, ~10,08 $).
  - *Print Geek (9.4) gardé en réserve US si l'échantillon UT déçoit.*
- **Cotes MASTER (300 DPI, sRGB, PNG transparent)** — concevoir à la plus petite zone
  commune aux deux fournisseurs :
  - **Dos / Avant** : **4200 × 4800 px** (14 × 16 in / 35,6 × 40,6 cm)
  - **Sceau avant** : **1050 × 1050 px** (poitrine gauche)
  - **Manche gauche** : **898 × 898 px** (~7,6 cm)
- **3 réalités POD** : zone d'impression = rectangle fixe (ne suit pas la taille du tee) ;
  pas de vrai bord-à-bord en DTG ; tee sombre = sous-couche blanche (rendu moins vif,
  risque craquelage → **échantillon obligatoire** avant de lancer une collection).
- **Prix cible** : retail ~39,90 € ; coût prod ~13–17 $ (3 zones). Attention **TVA** (~20 %
  en UE) + coût d'expédition selon marché → vérifier la marge réelle.

Détail complet et gabarits : `print-system/`.

## 8. Sensibilités & garde-fous (protègent la marque autant que l'éthique)

La distribution est 100 % organique sur des plateformes qui **déplateforment** vite. Donc :

- Présenter les thèmes comme des **hypothèses / questions / dossiers**, jamais comme des
  faits établis. C'est le ton « archive », pas le ton « accusation ».
- **SECRET ORDER** et **HUMAN PROGRAM** touchent à des tropes (sociétés secrètes qui
  « contrôlent le monde », fabrication du consentement) qui recoupent des récits
  antisémites/complotistes. Traiter avec **distance esthétique**, **ne jamais viser un
  groupe réel**, aucune personne ni communauté réelle nommée ou visée.
- Éviter tout ce qui déclenche bannissement / bad press : pas de contenu haineux, pas
  d'appel à la défiance ciblée. L'univers reste **mystère esthétique**, pas militantisme.
- IP : éviter les marques déposées (ex. « Matrix » dans SIMULATION → évoquer l'idée, pas
  la franchise). Area 51, MK-Ultra, Operation Fishbowl = noms réels/publics, OK.

## 9. Admin à finaliser (hors code)

- Réserver domaine (**adyton.co** ou **theadyton.com** — `adyton.com` pris) + handles brandés.
- **Recherche marque classe 25** (INPI/EUIPO) par un conseil en PI avant dépôt
  (ADYTON libre dans le vêtement ; autres « Adyton » existent dans des secteurs sans rapport).
- **Échantillons** dos plein format sur tee noir chez OPT **et** Underground Threads.
