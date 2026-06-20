# OSRS_CN_Data_Runelite

Simplified Chinese translation data for the [OSRSCN Chinese](https://github.com/Aoldbald/OSRS_CN_Runelite)
RuneLite plugin.

The plugin downloads the TSV files under `public/zh/` on first run and caches them
locally in `~/.runelite/osrscn/zh/`.

## Credits

The Simplified Chinese transcript and translation work is by
[lck3141592654](https://github.com/lck3141592654), derived from the community OSRS
transcript effort (see [RuneLingual](https://github.com/YS-jack/RuneLingual-Plugin)).

## Notes

Files are plain UTF-8 TSV (English key, Chinese value). Do not track them with Git LFS —
the plugin fetches them via `raw.githubusercontent.com`, which would otherwise serve LFS
pointers instead of the file contents.
