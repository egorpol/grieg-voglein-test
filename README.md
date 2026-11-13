# Grieg, *Vöglein*, Op. 43 No. 4: a facsimile-linked edition

A student edition from the seminar [From Digital Edition to Computational Music Analysis](https://egorpol.github.io/camat_lectures/)
(winter 2026/27). Every bar of the MEI file is linked to its place on two page images of the printed source.

- `mei/work.mei`: the edition, by (your names). It starts from the encoding by Maja Hartwig and Kristina Richts in the
  [MEI Sample Collection](https://github.com/music-encoding/sample-encodings) (ECL-2.0, see `LICENSE-encoding.txt`;
  the file declares itself public domain). Its header records what was changed, by whom and when.
- `pages/`: printed pages 42 and 43 of Edvard Grieg, *Klavierwerke*, vol. 1, ed. Hermann Kretzschmar, Leipzig:
  C. F. Peters, plate 8800, from [IMSLP file 28165](https://imslp.org/wiki/Special:ImagefromIndex/28165)
  (public domain), drawn at 300 dpi. `pages/boxes/` holds the box of each bar; `pages/pages.json` and
  `alignment.json` are CAMAT's records of the pages and boxes.
- `reviews/`: the peer-review sheet, once it is written.
