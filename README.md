# Orage FX v3 — Foudre Audio

## Nouveautés v13
- **Module STUTTER / BEAT REPEAT** : répétition rythmique de l'audio calée sur le tempo (BEAT REPEAT / REVERSE / GATE / OFFBEAT, divisions 1 mesure à 1/64, droit / triolet / pointé), bouton ENGAGE et 5 entrées CV au patchbay. Le rack accepte 11 modules.
- Correctif : état des tuiles de modules dans le panneau latéral.


## Nouveautés v12
- **Identité visuelle « Bel Air »** : nouveau logo ORAGE en lettres chromées (or / argent / cuivre selon le thème, éclair en barre du A, filet de vitesse, étincelle) ; modules FX avec bandeau crème, filet chromé, blason et grand pictogramme gravé sur le panneau ; teintes harmonisées pour chaque thème.
- **Rack FX** : bouton d'activation / bypass par module (comme Serum 2), glisser-déposer pour réordonner avec défilement automatique du rack, barre de défilement qui ne cache plus les modules, textes mieux dégagés.

## Nouveautés (mise à jour v8)
- **Design** : quatre thèmes (CHAMPAGNE par défaut, ARGENT, CUIVRE, ORIGINAL noir et orange), bouton LOOK ; potards et touches métalliques en relief, plus d'usure ; Roulette et Chaos retirés.
- **Oscilloscope** : un clic sur la lampe du haut bascule lampe / oscilloscope (signal de sortie).
- **Réverb plaque** (module REVERB) : SIZE, DECAY, PRE-DELAY, DAMPING, MOTION, WIDTH, LOW CUT, SHIMMER, FREEZE.
- Les modules démarrent à zéro (neutres) quand on les ajoute ; presets d'usine classés par catégories, sauvegarde utilisateur avec catégorie.

Distorsion haute tension semi-modulaire (VST3 + Standalone), rack façon Guitar Rig.

## Nouveautés v3
- Rack : ajoute / retire / réordonne les modules (poignée à gauche, ▼ replier, ✕ retirer). Patchbay à droite.
- Modules : Gate, Octaver, Distorsion, Color, Filtre MS20, Destroy Machine, Tube Comp, Spring.
- Comp : EAR 660 / Fairchild + COMP, THRESHOLD, ATTACK et VU-mètre à aiguille (gain reduction).
- Gate : THRESHOLD, RELEASE, RANGE + voyant OPEN (threshold à 0 = ouvert).
- Synchro Ableton (tempo/PPQ) pour LFO 1/2, Sample & Hold et Destroy.
- Foudre structurelle (chutes de tension, sursauts, arcs) et non plus cosmétique.
- Presets : barre en haut (précédent/suivant/menu/SAVE), stockés dans `%APPDATA%\Foudre Audio\Orage FX\Presets` (.orfx).
- Trois remises à zéro : VIDER LE RACK, VIDER LE PATCHBAY, RESET RÉGLAGES.

## Compilation (GitHub Actions)
Dans ton dépôt : remplace `CMakeLists.txt` et le dossier `Source/` par ceux de ce zip.
`.github/workflows/build.yml` ne change pas. Lance le workflow, télécharge l'artefact
`Orage-VST3-Windows` : le dossier `Orage FX.vst3` va dans `C:\Program Files\Common Files\VST3`.
Le plugin s'appelle "Orage FX" : il cohabite avec l'ancien "Orage".
