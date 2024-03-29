# Japanese Pokemon API Version 1


## Card Object

* * * 

### name _string_

The name of the card.

* * * 

### sequenceNumber _integer_

The sequential number of the card (applicable to Secret Rares).

* * * 

### printedNumber _integer_

The number printed on the card, will be the same as `sequenceNumber` almost always. Is relevant for Promotional cards such as `SWSH001`

* * * 

### hp _int_

The amount of HP the card has. If it does not have hp, then the value will be `-1`.

* * * 

### type _string_

The energy type the card is.

* * * 

### evolvesFrom _string_

If the card evolves from another card, this field will denote the name of the pre-evolution.

* * * 

### effect _string_

Describes the card's effect. Mainly for Trainers and Special Energies.

* * * 

### attacks _string_

Unparsed string describing all attacks the card has. Includes energy cost, attack name, attack damage, and any description or further effects.

* * * 

### rules _string_

Describes rules the card is bound to. Mainly for cards with a Rule Box and certain Trainers.

* * * 

### weakness _string_

The type of energy the card is weak to. Does not include weakness modifier, only the type.

* * * 

### resistance _string_

The type of energy the card is resistant to. Does not include resistance modifier, only the type.

* * * 

### rarity _string_

The rarity of the card.

* * * 

### retreatCost _string_

The amount of energy required to retreat.

* * * 

### cardType _string_

The subset that the card falls into. For example, `Single Strike Pokemon`, `Pokemon VMAX`, etc.

* * * 

### illustrator _string_

The card art's illustrator.

* * * 

### setName _string_

The name of the set which the card belongs to.

* * * 

### imageUrl _string_

The url pointing to the card's image. If there is no card image, then this will instead point to `https://assets.tcgcollector.com/build/images/default-card-image.789f6232.png`.

* * * 

### cardUrl _string_

The URL which leads to the original card URL data.

* * * 

## Set Object

* * * 

### name _string_

The name of the set.

* * * 

### year _string_

The year the set was released.

* * * 

### total _integer_

The total number of cards in the set.

* * * 

### printedTotal _integer_

The number of cards in the set that is printed on the card. This differs from the set's `total` in sets with Secret Rare cards.

* * *

### language _string_

The language that the cards in the set are printed in.

* * * 

### setUrl _string_

The URL to a page which has more information about the set.

* * * 

### shorthand _string_

The shorthand code for the set.

* * * 

### image _string_

A URL to the official set's image.

* * * 
