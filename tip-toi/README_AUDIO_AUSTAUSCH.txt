Audio-Austausch vom 25.06.2026

Die neuen Schatzsuche-Audios aus Schule/schatzsuche wurden als Ogg Vorbis, mono, 22050 Hz in Audio/ eingebaut.
Die YAML verweist mit `media-path: Audio/%s` auf diese Dateien.
Die passenden alten Schatzsuche-Eintraege im tts-cache wurden ebenfalls ersetzt.

Hinweis: Die vorhandene open_pc.gme ist nicht neu assembliert. Falls du die GME direkt auf den Stift kopieren willst, muss sie mit tttool aus open_pc.yaml neu gebaut werden:
  tttool assemble open_pc.yaml open_pc.gme
