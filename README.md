# KAVEL Thenics – Medien

Öffentliche Medien für die App **KAVEL Thenics** (3D-Übungsanimationen als animiertes WebP).

- `exercises/<übung>.webp` – 480 × 480, Endlosschleife
- Die App lädt einen festen Stand (Commit) über jsDelivr, ersatzweise raw.githubusercontent:
  `https://cdn.jsdelivr.net/gh/kandilyasin/kavel-media@<commit>/exercises/<übung>.webp`

Neue oder geänderte Animationen: Dateien ergänzen/committen, dann in der App
`ExerciseMedia.commit` auf den neuen Commit setzen und `ExerciseMedia.version` erhöhen.
Bestehende Dateien nie überschreiben, ohne den Commit in der App zu ändern.
