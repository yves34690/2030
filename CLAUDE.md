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
- Interdits : jargon creux, "dans un monde…", deus ex machina technologique, happy end facile.

## Rappels opérationnels

- **Avant d'écrire une scène** : relire `project_dna.md` + les `.md` des personnages présents + la scène précédente.
- **Avant de créer un personnage** : vérifier qu'une scène le justifie. Pas de figurants décoratifs.
- **Si un passage sonne "IA bien élevée"** : le réécrire.
- **Après chaque scène terminée** : lancer `editeur-voix` et `editeur-structure` en parallèle. Deux regards complémentaires (langue / architecture) avant le commit. Agents dans `.claude/agents/`.
- Git commit après les corrections issues des éditeurs.

---

*Dernière mise à jour : 2026-04-16*
