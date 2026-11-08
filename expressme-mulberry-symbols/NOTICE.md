# Mulberry Symbols

ExpressMe bundles a subset of the **Mulberry Symbols** AAC symbol set.

- Author: Steve Lee (Copyright 2018-2026 Steve Lee), with original designs by Garry Paxton
- Source: https://github.com/mulberrysymbols/mulberry-symbols (EN/ folder), https://mulberrysymbols.org
- License: Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)
  https://creativecommons.org/licenses/by-sa/4.0/

Verbatim text of the upstream `LICENSE.txt`:

> The Mulberry Symbol set
>
> Copyright 2018-2026 Steve Lee
>
> This work is licensed under the Creative Commons Attribution-Share Alike License.
>
> To view a copy of this license, visit https://creativecommons.org/licenses/by-sa/4.0/

Upstream commit used: `fa94a93ca1b5357c0b6e0d9f8a81c426a1dfefdf` (2026-10-27).

## Changes made

The original SVGs were copied unmodified to `assets/symbols/mulberry/<word>.svg` (renamed to the
word they represent). For bundling, `scripts/generate-mulberry-symbols.py` inlines them into
`src/assets/mulberrySymbols.ts`, folding `<style>` class rules into presentation attributes and
rounding path coordinates to one decimal place. The pictures themselves are unchanged. As required
by CC BY-SA, these derived files are shared under the same license.

## Included files (word <- upstream file)

| ExpressMe word | Upstream file (EN/) |
|---|---|
| want | want_,_to.svg |
| go | go_,_to.svg |
| like | good.svg |
| more | more.svg |
| yes | correct.svg |
| no | mistake_no_wrong.svg |
| help | help_,_to.svg |
| that | point_,_to.svg |
| what | what.svg |
| where | where.svg |
| when | when.svg |
| who | who.svg |
| how | how.svg |
| will | future.svg |
| get | get_,_to.svg |
| make | make_,_to.svg |
| see | eye.svg |
| look | look_,_to.svg |
| come | come_,_to.svg |
| up | up.svg |
| down | down.svg |
| in | in.svg |
| out | out.svg |

In-app credit: Settings > About ("Symbols: Mulberry Symbols by Steve Lee, CC BY-SA 4.0").
