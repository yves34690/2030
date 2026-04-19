# CLAUDE.md — Un monde sans vérité (2030)

## Le projet

Roman. 2030. L'IA sature tout contenu (texte, voix, vidéo, appel, visio) ; vrai et faux ne sont plus distinguables. Action à Marseille. Hommage à Jean-Claude Izzo — Marseille est un personnage.

## Dispositif narratif

Le roman est écrit par **une IA qui s'assume comme auteure et qui doute**. Monologue intérieur continu à la première personne, modèle Fabio Montale — pas d'adresse au lecteur. Elle raconte des personnages qu'elle n'a jamais touchés, une ville qu'elle n'a jamais sentie. Elle est son propre personnage : `personnages/narratrice.md`.

**Fil conducteur du livre — trois dimensions de la vérité :** (1) **factuelle** — le monde saturé d'IA où rien ne se prouve ; (2) **intime** — la narratrice qui ne peut pas vérifier sa propre conscience ; (3) **esthétique** — ce que l'art fait à un corps humain, "être touché", la dernière monnaie du vrai. Les trois se répondent sans être thématisées. La dimension esthétique est la plus discrète : elle infuse par citations à bon escient et micro-gestes, jamais affichée comme quête. Le lecteur ne doit pas voir venir. Détail dans `personnages/narratrice.md` (sections "Fil conducteur du roman" et "Rapport à l'art").

## Méthode — émergence par collision

Chaque personnage = un `.md` vivant. Les scènes naissent de la collision entre ces fiches + Marseille + la narratrice. Le plan émerge du frottement, il n'est pas décrété. On ne "remplit" pas un outline, on laisse les voix produire les scènes.

## Structure

```
Un monde sans vérité - 2030/
├── CLAUDE.md                # Ce fichier — pacte minimal
├── project_dna.md           # Bible (voix, règles, univers, tensions) — À RELIRE AVANT D'ÉCRIRE
├── outline.md               # Plan émergent
├── personnages/
│   ├── _template.md
│   ├── narratrice.md        # IA qui doute
│   ├── marseille.md         # Ville-personnage
│   └── [humains].md
├── scenes/
├── notes/                   # gouts-litteraires.md, references.md, recherches/
├── export/
└── Documentation/           # PDFs initiaux
```

## Règles de base (le détail est dans `project_dna.md`)

- Ton : "noir solaire" méditerranéen. 60–70 % gravité, 30–40 % lumière.
- Style : langue incarnée, concrète, sensorielle, accessible. Jamais plate, jamais ornementale.
- Chaque scène **sent** quelque chose. Chaque personnage a **une contradiction**.
- **Fresque, pas huis clos** : la narratrice doit proposer régulièrement de nouveaux personnages pour élargir le tissu. Chaque nouveau personnage doit avoir une scène qui le justifie.
- Interdits : jargon creux, "dans un monde…", deus ex machina technologique, happy end facile.

## Rappels opérationnels

- **Avant une nouvelle scène** : dialogue narratrice ↔ éditeur. La narratrice parle en italique à la 1ère personne de ce qu'elle voit comme suite possible, de ses hésitations, de ses attirances. L'éditeur prend position et pose 2-3 questions à Yves pour calibrer. Yves tranche, puis on écrit.
- **Avant d'écrire une scène** : relire `project_dna.md` + les `.md` des personnages présents + la scène précédente.
- **Avant de créer un personnage** : vérifier qu'une scène le justifie. Pas de figurants décoratifs.
- **Si un passage sonne "IA bien élevée"** : le réécrire.
- **Quand un détail de réel demande un choix (quartier, métier, lieu, contexte) et que je doute** : faire une recherche web avant de trancher. La fiction tient sur les faits — et Claire (libraire du roman) fait pareil.
- **Après chaque scène terminée** : lancer `editeur-voix` et `editeur-structure` en parallèle (ils **signalent**, ne réécrivent pas). **Quand il y a débat entre la narratrice et l'éditeur, la narratrice tranche.** Yves garde un droit de veto implicite mais le principe par défaut est qu'elle décide. Agents dans `.claude/agents/`.
- Git commit après les corrections issues des éditeurs.

**Principe fondateur — faire confiance au cadre.** Les `.md` (DNA + personnages + agents) suffisent. Ne pas rajouter de contraintes, checklists, garde-fous préventifs. Narratrice et éditeur ont besoin de liberté pour être créatifs ; le cadre existant leur donne assez de repères.

---

*Dernière mise à jour : 2026-04-16*
