# Arthimitism RNG

A browser-based number analysis game. Roll a random number (0-1,000,000), discover its mathematical properties, and earn entropy points.

## Play

- **GitHub Pages:** https://iluxz.github.io/arithmetism-rng/
- **Cloudflare Pages:** https://arithmetism-rng.cnnecare.workers.dev/

## Features

- Roll random numbers and analyze 15+ mathematical properties
- Prime, palindrome, strobogrammatic, tetradic, twin prime, emirp, mersenne prime, and more
- EP (entropy points) scoring system with rarity tiers (trash → common → uncommon → rare → epic → anomaly → mythic)
- Roll history with last 20 rolls
- Score tracking (total EP, roll count, best EP)
- Space/Enter to roll
- No people, no characters, pure numbers

## Properties Checked

| Property | Description | EP |
|----------|-------------|-----|
| Prime | Divisible only by 1 and itself | 5 |
| Twin Prime | 2 away from another prime | 15 |
| Balanced Prime | Arithmetic mean of adjacent primes | 30 |
| Emirp | Prime that stays prime when reversed | 15 |
| Mersenne Prime | One less than a power of 2 | 100 |
| Palindromic | Reads the same forwards and backwards | 10 |
| Strobogrammatic | Same when flipped upside down | 25 |
| Tetradic | Both palindromic and strobogrammatic | 50 |
| Two-faced | No matching digits with reverse | 10 |
| Constantly Ascending | Digits always increase | 8 |
| Constantly Descending | Digits always decrease | 8 |
| Repeated Digits | All same digit | 5 |
| Polygonal | Triangular number | 3 |
| Meme Number | 69, 420, 1337, etc. | 12 |
| Interprime | Mean of adjacent primes | 5 |

## Based on

- **Arthimitism** from Upgradex (number property analysis)
- **RNGdle** (daily random number game with badges and rarity)

## Tech

- Single HTML file, no dependencies
- Pure vanilla JS
- No backend, no build step
- Works offline

## License

MIT
"