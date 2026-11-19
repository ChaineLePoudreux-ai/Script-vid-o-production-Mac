# Production vidéo — La fin du disque (GTA VI, Steam, licences)

## Récapitulatif
- **Source** : texte utilisateur (aucune URL dans le message ; texte utilisé tel quel, reformulé à 200 mots max)
- **Format** : vertical 9:16, 1080×1920, H.264 yuv420p + AAC 48 kHz, 85,5 s, 25 fps
- **Voix off** : edge-tts `fr-FR-HenriNeural` (voix homme mature), débit −10 %, MP3 puis AAC
- **Script** : 199 mots (≤ 200), dernière phrase exacte : « Abonnez-vous, c'est gratuit et ça informe gros ! »
- **Titre viral** (15 mots, sans « : ») : GTA VI sans disque ce que Rockstar et Steam ne veulent pas que vous sachiez

## Fichiers
- `video/fin_du_disque_9x16.mp4` — vidéo finale 1080×1920 (27,3 Mo)
- `video/fin_du_disque_720x1280.mp4` — version compressée (2,8 Mo)
- `audio/voixoff.mp3` — voix off seule (85,5 s)
- `script.txt` — script voix off
- `titre.txt` — titre viral
- `images/` — visuels sources (web crédité + IA)

## Découpage des scènes (~11,1 s chacune, fondu 0,5 s, Ken Burns alterné)
| # | Fichier | Contenu | Origine |
|---|---------|---------|---------|
| 1 | s1_blockbuster.jpg | Magasin Blockbuster, l'ère du disque physique | Web — Wikimedia Commons, CC BY-SA 4.0 (crédité à l'écran) |
| 2 | s2_steam.jpg | Téléchargement d'un jeu dans Steam | Web — Wikimedia Commons (screenshot Steam), domaine public (crédité à l'écran) |
| 3 | s3_editeurs.jpg | Dirigeants d'éditeurs comptant l'argent | IA — style Enki Bilal |
| 4 | s4_code.jpg | Boîte vide avec simple code d'activation | IA — style Enki Bilal |
| 5 | s5_neon.jpg | Mégapole néon, l'univers type GTA VI | IA — style Enki Bilal |
| 6 | s6_contrat.jpg | Contrat de licence, petites lignes | IA — style Enki Bilal |
| 7 | s7_californie.jpg | Capitole de Californie (loi 2025) | Web — Wikimedia Commons, CC BY-SA 4.0 (crédité à l'écran) |
| 8 | s8_cadenas.jpg | Cadenas, la licence verrouillée | Web — Wikimedia Commons, CC BY-SA 4.0 (crédité à l'écran) |

## Notes de production
- Montage : zoompan (zoom avant/arrière alterné) sur frames 2160×3840, xfade fondu 0,5 s, fade in/out global, mux audio AAC, `+faststart`.
- L'image Steam (très large, 1280×325) a été composée sur fond flou plutôt que recadrée en pillarbox agressive.
- Les crédits web sont incrustés en bas à droite (fond noir semi-transparent, texte blanc, DejaVu).
