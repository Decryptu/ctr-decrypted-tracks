# CTR Decrypted tracks

Custom tracks for [CTR Decrypted](https://github.com/Decryptu/ctr-decrypted). The game's Mods screen lists them on its Tracks tab, next to the tracks from [Project Saphi](https://www.projectsaphi.com), and installs them on request.

`index.json` is what the game reads. Each folder under `tracks/` is one package with a `listing.json`, and `CREDITS.md` names everyone's work. All three are managed by `tools/tracks/build_index.py` in the game's repository; see [docs/CUSTOM_TRACKS.md](https://github.com/Decryptu/ctr-decrypted/blob/main/docs/CUSTOM_TRACKS.md).

A track that Saphi lists too shows once in the game. Put its Saphi track id in the track's `listing.json` as `saphi_track_id` and rebuild the index; byte-identical uploads are also recognised without it.
