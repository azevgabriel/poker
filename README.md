```js
const ranks = new Array("A", "2", "3", "4", "5", "6", "7", "8", "9", "10", "J", "Q", "K");
const suits = new Array("Clubs", "Diamonds", "Hears", "Spades")
```

### Randomize Array List

- Fisher-Yates (Knuth) Shuffle: embaralhamento uniforme verdadeiro
- Sattolo’s Algorithm: garante que nenhum elemento permaneça na mesma posição
- Sorting Shuffle: apresentar pequenos vieses ou overheads maiores

### Poker Randomize Logic

- Wash
- Box
- Riffle Shuffle (2x)
- Slice three parts - Invert
- Riffle Shuffle
- Cutting
- Circular delivery of cards from the top of the deck
