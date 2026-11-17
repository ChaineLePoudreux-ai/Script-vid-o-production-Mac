# Production vidéo — HMS Vengeance, record de 217 jours en mer

## Récapitulatif
- **Source** : article Opex360 / Zone Militaire du 16 novembre 2026 (URL fournie par l'utilisateur via déclencheur `vid=`)
- **Format** : vertical 9:16, 1080×1920, H.264 + AAC, 79,22 s, 25 fps
- **Voix off** : edge-tts `fr-FR-HenriNeural` (voix homme mature), débit −12 %, MP3 puis AAC 48 kHz
- **Script** : 194 mots (≤ 200), dernière phrase exacte : « Abonnez-vous, c'est gratuit et ça informe gros ! »
- **Titre viral** (15 mots, sans « : ») : Ce sous-marin britannique est resté 217 jours sous la mer et voici pourquoi c'est inquiétant

## Fichiers
- `video/hms_vengeance_9x16.mp4` — vidéo finale 1080×1920 (26,3 Mo)
- `video/hms_vengeance_720x1280.mp4` — version compressée pour Drive (2,71 Mo)
- `voix_off.mp3` — voix off seule (79,22 s)
- `script.txt` — script voix off
- `titre.txt` — titre viral
- `images/` — visuels sources (web crédité + IA)
- `frames/`, `clips/` — intermédiaires de montage

## Découpage des scènes (~10,3 s chacune, fondu 0,5 s, Ken Burns alterné)
| # | Fichier | Contenu | Origine |
|---|---------|---------|---------|
| 1 | s1_vengeance.jpg | HMS Vengeance rentrant à Faslane | Web — Wikimedia Commons, OGL v1.0 (crédité à l'écran) |
| 2 | s2_faslane.jpg | Base navale sous la pluie | IA — style Enki Bilal |
| 3 | s3_vanguard.jpg | SNLE en mer gris acier | IA — style Enki Bilal |
| 4 | s4_trident.jpg | Missile Trident perçant la surface | IA — style Enki Bilal |
| 5 | s5_equipage.jpg | Poste de commande, marins fatigués | IA — style Enki Bilal |
| 6 | s6_coque.jpg | Coque couverte d'organismes marins | IA — style Enki Bilal |
| 7 | s7_dreadnought.jpg | SNLE futuriste (classe Dreadnought) | IA — style Enki Bilal |
| 8 | s8_final.jpg | Sous-marin solitaire en plongée | IA — style Enki Bilal |

## Notes de production
- L'API Wikimedia Commons a renvoyé des erreurs 429 persistantes depuis le sandbox ; une seule image web a pu être récupérée (scène 1). Les scènes 2 à 8 ont été générées en IA style Enki Bilal, conformément au plan de secours prévu par la compétence.
- Montage : zoompan (zoom avant/arrière alterné) sur sources 2160×3840, xfade fondu 0,5 s entre scènes, fade in/out global, mux audio AAC, `+faststart`.
