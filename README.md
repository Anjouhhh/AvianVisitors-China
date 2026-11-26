# Japanese Woodblock - China (partial)

32 common garden and city birds of eastern and southern China, each perched and in flight, in the
Japanese woodblock (kachō-e) style of the Avian Visitors default set. None of these species was in
upstream Avian Visitors or any community bundle when this set was made (checked 2026-11-16).

## How it was made

- Generated with OpenAI image generation (the built-in image tool of the Codex CLI), one fresh session
  per image.
- The text instructions are adapted from the Avian Visitors prompt template (CC BY-NC-SA 4.0), with a
  per-species list of field marks.
- Each image had two or three reference images: a Wikimedia Commons photo of the species for anatomy,
  sometimes a photo of a look-alike species marked "do not copy", and a public-domain woodblock print
  by Ohara Koson for the painting technique only.
- The cream ground was removed with rembg (BiRefNet), as in upstream `avian/scripts/cutout.py`.
- Every image was checked by eye against the species' field marks; wrong ones were regenerated.

## Species

Black Bulbul, Black Drongo, Black-naped Oriole, Black-throated Bushtit, Brown-breasted Bulbul,
Chinese Blackbird, Chinese Hwamei, Collared Crow, Common Tailorbird, Daurian Redstart,
Fork-tailed Sunbird, Grey-capped Greenfinch, Grey-capped Pygmy Woodpecker, Japanese Tit,
Large-billed Crow, Light-vented Bulbul, Masked Laughingthrush, Oriental Magpie-Robin, Plain Prinia,
Red-billed Blue Magpie, Red-billed Starling, Silver-throated Bushtit, Sooty-headed Bulbul,
Swinhoe's White-eye, Vinous-throated Parrotbill, White-breasted Waterhen, White-browed Laughingthrush,
White-cheeked Starling, White-throated Kingfisher, Yellow-bellied Tit, Asian Koel, Azure-winged Magpie.

## License

CC BY-NC-SA 4.0 (see `LICENSE`). Non-commercial use only. Creator: Anjouhhh.

## Files

- `illustrations/<scientific-name>.png` (perched) and `illustrations/<scientific-name>-2.png` (flight):
  transparent PNG cutouts.
- `manifest.json`: Avian Visitors asset-pack manifest (format version 1).
- The upload-ready ZIP is attached to the [v1.0.0 release](https://github.com/Anjouhhh/AvianVisitors-China/releases/tag/v1.0.0).
  It passes upstream `avian/scripts/bundle_validate.py`.
