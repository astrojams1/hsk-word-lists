# HSK 3.0 word lists (levels 1 to 6): free CSV and Anki files

Every word of HSK 3.0 levels 1 to 6, **5,367 words**, with pinyin and English meanings, as plain CSV and as Anki
import files. Free to use, share and change under [CC BY-SA 4.0](LICENSE).

| Level | Words | CSV | Anki | Word pages |
|---|---:|---|---|---|
| HSK 1 | 509 | [hsk-1.csv](csv/hsk-1.csv) | [hsk-1.txt](anki/hsk-1.txt) | [HSK 1 word list](https://ouro-apps.vercel.app/hanzi-cards/hsk/1/) |
| HSK 2 | 750 | [hsk-2.csv](csv/hsk-2.csv) | [hsk-2.txt](anki/hsk-2.txt) | [HSK 2 word list](https://ouro-apps.vercel.app/hanzi-cards/hsk/2/) |
| HSK 3 | 953 | [hsk-3.csv](csv/hsk-3.csv) | [hsk-3.txt](anki/hsk-3.txt) | [HSK 3 word list](https://ouro-apps.vercel.app/hanzi-cards/hsk/3/) |
| HSK 4 | 972 | [hsk-4.csv](csv/hsk-4.csv) | [hsk-4.txt](anki/hsk-4.txt) | [HSK 4 word list](https://ouro-apps.vercel.app/hanzi-cards/hsk/4/) |
| HSK 5 | 1,059 | [hsk-5.csv](csv/hsk-5.csv) | [hsk-5.txt](anki/hsk-5.txt) | [HSK 5 word list](https://ouro-apps.vercel.app/hanzi-cards/hsk/5/) |
| HSK 6 | 1,124 | [hsk-6.csv](csv/hsk-6.csv) | [hsk-6.txt](anki/hsk-6.txt) | [HSK 6 word list](https://ouro-apps.vercel.app/hanzi-cards/hsk/6/) |
| All six | 5,367 | [hsk-1-6.csv](csv/hsk-1-6.csv) | [hsk-1-6.txt](anki/hsk-1-6.txt) | [All word lists](https://ouro-apps.vercel.app/hanzi-cards/hsk/) |

Every word also has its own page, with pinyin, its characters, related words and, for many, an example sentence
from a children's storybook: `https://ouro-apps.vercel.app/hanzi-cards/words/<word>/`, for example
[学习](https://ouro-apps.vercel.app/hanzi-cards/words/学习/). The pages have a search box that takes characters,
pinyin with or without tones, or English.

## What is in the files

**CSV** (`csv/`), UTF-8, one row per word:

| Column | Example |
|---|---|
| `hanzi` | 学习 |
| `pinyin` | xuéxí |
| `pinyin_plain` | xuexi |
| `english` | to study; to learn |
| `hsk_level` | 1 |
| `url` | the word's page |

Within each level, words run from most to least common in everyday Chinese (by SUBTLEX-CH word frequency), the
order the Hanzi Cards app teaches them in. A few grammar words such as 的, 了 and 吗 have a short usage note with an
example instead of a translation.

**Anki** (`anki/`): tab-separated text with Anki's header lines, one Basic card per word: the characters on the
front, pinyin and meaning on the back, tagged `HSK3.0` and `HSK1` to `HSK6`, in the deck `HSK 3.0::HSK n`.
In Anki on a computer choose File › Import, pick the file, check the preview and choose Import. The header lines
need Anki 2.1.54 or later; in an older version choose Tab as the separator and map the columns to Front, Back and
Tags.

## Sources, licence and attribution

- **Words, levels and pinyin:** the HSK 3.0 standard, *Chinese Proficiency Grading Standards for International
  Chinese Language Education* (GF 0025-2021), as transcribed in [elkmovie/hsk30](https://github.com/elkmovie/hsk30)
  (MIT licence, © 2021 Pleco Inc.) and mirrored in
  [drkameleon/complete-hsk-vocabulary](https://github.com/drkameleon/complete-hsk-vocabulary) (MIT licence,
  © 2026 Yanis Zafirópulos). Their licence notices are in [NOTICE.md](NOTICE.md). The 7–9 band is not included.
- **English meanings:** many come from [CC-CEDICT](https://cc-cedict.org/) (CC BY-SA 4.0, MDBG); the rest were
  written for Hanzi Cards.
- **Order:** SUBTLEX-CH word frequencies (Cai & Brysbaert, 2010, *PLoS ONE* 5(6): e10729) set the order only; no
  frequency figures are included, since that data is not ours to redistribute.

Because the meanings include CC-CEDICT, the lists are published under **CC BY-SA 4.0**. Credit them as
“HSK word lists by Hanzi Cards (Ouro), with CC-CEDICT”, link to this repository, and share changed versions under
the same licence.

Found a wrong meaning or reading? Open an issue.

## About Hanzi Cards

The lists come from [Hanzi Cards](https://ouro-apps.vercel.app/hanzi-cards/), a free iPhone app by Ouro that
teaches every one of these words on spaced-repetition flashcards with pinyin and audio, then 28 illustrated
storybooks and 12 Tang poems that teach each page's words before you read it. No account, no ads. On the App Store:
search “Hanzi Cards: Learn Mandarin”, or [open it on the App Store](https://apps.apple.com/app/id6832296387).
