# voomscroll-public

This is a generated compliance mirror of the VoomScroll™ data files that carry
third-party licence obligations. It is **not** the app's source code, and it is
not a place to open issues or send changes: every commit here is replaced by
the next release.

The app itself lives at https://anhtr.github.io/voomscroll/.

## Why it exists

Some of the data the app shows is adapted from English Wiktionary (CC BY-SA
4.0), Tatoeba (CC BY 2.0 FR), Unicode CLDR and Unihan (Unicode Licence v3),
and Google's Noto Emoji fonts (SIL OFL 1.1). Those licences require the
adapted files to be available under the same terms, with credit and a
statement of what was changed. This repository is where they are available.

- `LICENSE` says which files carry which licence (section 2), and that
  everything else in VoomScroll stays all rights reserved (section 1). Being
  collected here does not place anything outside section 2 under those
  licences.
- `ATTRIBUTION.txt` carries the credits, the licence links and what was
  changed.
- `data/fonts/OFL.txt` travels with the two font subsets, as the OFL requires.

## What is and is not here

Files are shipped whole, exactly as the live site serves them. Where a
licence covers only some records inside a sharded directory — the `wikt-` and
`tatoeba-` records in `data/sentences/`, or the non-curated records in
`data/classifiers/` — each shard holding at least one such record ships whole,
and a shard holding none is left out.

The manifests (`data/sentences-manifest.json`, `data/classifiers-manifest.csv`
and the rest) ship whole as well, so a manifest may list a shard that is not in
this repository. That is deliberate: the missing shard carries no licence
obligation, and it is still served by the live site.

## History

Each successful release of the app replaces this repository's history with a
single commit holding exactly the files of that release. Older releases are
not kept here.
