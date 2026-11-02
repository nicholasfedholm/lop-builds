# LoP builds

Two kinds of Vintage Story 1.22.7 dinosaur family builds live in this repo.

## Perf builds of laughinggas's families

Unofficial performance variants of four Legacy of the Phanerozoic family mods.

All credit for the original mods goes to laughinggas. The models, textures, and everything creative in these zips started as his work. These are my own expanded builds of his mods: ported to game version 1.22.7, with textures upscaled and extra variants and species added over months of work. The Perf step takes my full build and downscales its entity texture sheets by half (a plain deterministic BOX downscale, no repainting and no new art) so it uses less VRAM, then runs the result through a checker that verifies dimensions, eye details, and that every non-texture file is byte identical to my full build.

| Family | laughinggas's original release | My full build | This Perf build |
|---|---|---|---|
| Hadrosauridae (Hadro) | 5.4 MB | 211.5 MB | 52.3 MB |
| Ceratops | 5.7 MB | 109.1 MB | 32.0 MB |
| Carcharodontosauridae (Carchar) | 4.8 MB | 88.9 MB | 22.5 MB |
| Mosasaurs (Mosa) | 2.4 MB | 82.0 MB | 20.2 MB |

Read the table honestly: the Perf builds are about a quarter of my full builds, but they are still several times larger than laughinggas's originals, because my builds carry the upscaled textures, extra variants, and added species. If the smallest possible file is what you want, his originals win. They just do not run on game version 1.22, which is the whole reason these builds exist.

Known imperfection, stated plainly: in the Hadro build, 13 sheets lose the darkest pixels of the small Eye Slits element in the downscale. The eyes themselves survive on every sheet. The checker flagged it, I am not hiding it, and a fix is on the list.

## Our own new families

Allosauridae (Jurassic Giants) and Iguanodontia have no release from laughinggas. He never made these two families, so we built them ourselves in the style of Legacy of the Phanerozoic. The credit line is different for these two: the idea and the design language come from LoP by laughinggas, the packs themselves are our own work.

They are not downscales of anything. The textures are upscaled, with sheets up to about 2,600 to 2,700 pixels wide, and species ship with more variants than the original packs carry: up to 6 sheets per species, adult male and female, plain, striped, and spotted skins, plus babies. 9 species in each pack. The zips in the release for these two families are the full builds: Allosauridae 83.2 MB, Iguanodontia 61.2 MB.

## Use

For the Perf builds, download the zip for a family from the Releases page and use it instead of the original family zip in your Mods folder. Do not run both, they are the same modid. You still need LoP Behaviors and the rest of the set from the original pages. For the two new families, just drop the zip in your Mods folder.

## Takedown

The four Perf builds are unofficial and not affiliated with laughinggas. If you are laughinggas, or you hold the rights to this work, and you want them taken down, message me here on GitHub or on the Vintage Story ModDB (Ellimist) and I will take them down immediately. No hassle, no argument, no questions asked. The same offer stands for the two new families if you feel they step on your work.
