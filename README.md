# LoP Perf builds

Unofficial performance variants of six Legacy of the Phanerozoic family mods for Vintage Story 1.22.7.

All credit for the original mods goes to laughinggas. The models, textures, and everything creative in these zips started as his work. These are my own expanded builds of his mods: ported to game version 1.22.7, with textures upscaled and extra variants and species added over months of work. The Perf step takes my full build and downscales its entity texture sheets by half (a plain deterministic BOX downscale, no repainting and no new art) so it uses less VRAM, then runs the result through a checker that verifies dimensions, eye details, and that every non-texture file is byte identical to my full build.

## The builds

| Family | laughinggas's original release | My full build | This Perf build |
|---|---|---|---|
| Hadrosauridae (Hadro) | 5.4 MB | 211.5 MB | 52.3 MB |
| Ceratops | 5.7 MB | 109.1 MB | 32.0 MB |
| Carcharodontosauridae (Carchar) | 4.8 MB | 88.9 MB | 22.5 MB |
| Allosauridae | no standalone release | 83.2 MB | 30.0 MB |
| Mosasaurs (Mosa) | 2.4 MB | 82.0 MB | 20.2 MB |
| Iguanodontia | no standalone release | 61.2 MB | 21.8 MB |

Read the table honestly: the Perf builds are about a quarter of my full builds, but they are still several times larger than laughinggas's originals, because my builds carry the upscaled textures, extra variants, and added species. If the smallest possible file is what you want, his originals win. They just do not run on game version 1.22, which is the whole reason these builds exist. Allosauridae and Iguanodontia have no standalone release on his ModDB pages, so there is no original file to compare those two against.

## Use

Download the zip for a family from the Releases page and use it instead of the original family zip in your Mods folder. Do not run both, they are the same modid. You still need LoP Behaviors and the rest of the set from the original pages.

Known imperfection, stated plainly: in the Hadro build, 13 sheets lose the darkest pixels of the small Eye Slits element in the downscale. The eyes themselves survive on every sheet. The checker flagged it, I am not hiding it, and a fix is on the list.

## Takedown

These are unofficial and not affiliated with laughinggas. If you are laughinggas, or you hold the rights to this work, and you want these taken down, message me here on GitHub or on the Vintage Story ModDB (Ellimist) and I will take them down immediately. No hassle, no argument, no questions asked.
