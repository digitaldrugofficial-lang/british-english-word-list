# British English Word List for Word Puzzles

A clean list of **61,127 British English words** (3 to 15 letters) built for word puzzles: codewords, word wheels, anagrams, the Countdown letters round and conundrum, and similar games.

It is the word list behind the free solvers at **[LetterCracker](https://lettercracker.co.uk/)**, including the [codeword solver](https://lettercracker.co.uk/), [word wheel solver](https://lettercracker.co.uk/word-wheel-solver/) and [Countdown solver](https://lettercracker.co.uk/countdown-solver/).

## What is in it

| File | Contents |
|---|---|
| `words.txt` | All 61,127 words, one per line, upper case, A to Z only |
| `by-length/03-letter-words.txt` … `15-letter-words.txt` | The same words split by length |

### How the list is built

1. **Source:** [SCOWL](http://wordlist.aspell.net/) (Spell Checker Oriented Word Lists) by Kevin Atkinson, English and British English entries up to size 50.
2. **British spelling only:** US-only spellings are removed, so you get COLOUR, CENTRE and ORGANISE, not COLOR or CENTER.
3. **Puzzle rules:** only words of 3 to 15 letters; no proper nouns, abbreviations, hyphenated words or words with apostrophes.
4. **Family friendly:** slurs and offensive words removed by hand.

## Words by length

| Letters | Words | | Letters | Words |
|---|---|---|---|---|
| 3 | 581 | | 10 | 7,202 |
| 4 | 2,282 | | 11 | 4,951 |
| 5 | 4,417 | | 12 | 3,145 |
| 6 | 7,012 | | 13 | 1,770 |
| 7 | 9,555 | | 14 | 786 |
| 8 | 10,067 | | 15 | 373 |
| 9 | 8,986 | | **Total** | **61,127** |

## Letter frequency in the list

Across all 507,153 letters, the order is **E S I A R N T O L C D U G P M H B Y F V K W X Q J Z**.

| Letter | Share | Letter | Share |
|---|---|---|---|
| E | 11.66% | O | 5.91% |
| S | 9.20% | L | 5.15% |
| I | 8.70% | C | 4.04% |
| A | 7.31% | D | 4.00% |
| R | 7.18% | … | … |
| N | 7.05% | Q | 0.19% |
| T | 6.91% | J, Z | 0.18% each |

The full A to Z table, compared with everyday English text and codeword grids, is in the [letter frequency guide](https://lettercracker.co.uk/letter-frequency/).

## Some facts from the data

- 95% of the 8,986 nine-letter words have only one anagram, which is why nine letters suit word wheels and the Countdown conundrum. See [nine-letter words](https://lettercracker.co.uk/nine-letter-words/).
- 31.5% of words end in S, and 12.1% start with S.
- 68% of words contain at least one E.

## Usage

```python
words = open("words.txt").read().split()
nine = [w for w in words if len(w) == 9]
```

```js
const words = (await (await fetch("words.txt")).text()).split("\n").filter(Boolean);
```

## Licence

The word list is derived from SCOWL. See [LICENSE](LICENSE) for the SCOWL copyright and permission notice, which must be kept with any copy.

## Corrections

Found a missing or wrong word? Open an issue here or use the contact page at [lettercracker.co.uk/contact](https://lettercracker.co.uk/contact/).

Maintained by Muhammad Moazzam, founder of [LetterCracker](https://lettercracker.co.uk/about/).
