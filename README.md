```js
const ranks = new Array("A", "2", "3", "4", "5", "6", "7", "8", "9", "10", "J", "Q", "K");
const suits = new Array("Clubs", "Diamonds", "Hears", "Spades")
```

### Randomize Array List

- Fisher-Yates (Knuth) Shuffle: embaralhamento uniforme verdadeiro
- Sattolo’s Algorithm: garante que nenhum elemento permaneça na mesma posição
- Sorting Shuffle: apresentar pequenos vieses ou overheads maiores

### Poker Randomize Logic

- Wash `Fisher–Yates`
- Box
- Riffle Shuffle (2x)
- Cut three parts --> Invert parts
- Riffle Shuffle
- Cutting
- Circular delivery of cards from the top of the deck: Perfect

#### Riffle Shuffle

- Cutting -> Perfect or imperfect
- Interleave -> Perfect or imperfect
- Diller's random performance rate -> 0.6 imperfect - 0.98 perfect 

### Poker Glossary

https://iprc.soest.hawaii.edu/users/jimp/personal/poker/glossary.html
