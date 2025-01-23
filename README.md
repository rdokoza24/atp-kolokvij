# atp-kolokvij

## Wikipedija je globalan, višejezični projekt s ciljem izgradnje slobodne internetske enciklopedije koja je svima javno dostupna. Njezini su suradnici dobrovoljci. Wikipedijom danas rukovodi neprofitna organizacija

![Slika](https://www.pexels.com/photo/photo-of-two-red-dices-965879/)

```
const isProd = process.env.NODE_ENV === 'production'
let manifest

if(isProd) {
  try {
    manifest = require('../dist/.vite/manifest.json')
  } catch (e) {
    throw new Error(`Vite manifest.json not found. Have you run 'yarn run build'?`)
  }
}
```

### Izvori

1. [Wikipedia](https://hr.wikipedia.org/wiki/Glavna_stranica)
2. [Slika izvučena sa Pexels](https://www.pexels.com/photo/photo-of-two-red-dices-965879/)



### Numerički popis:
1. Dodavanje naslova.
2. Dodavanje podnaslova.
3. Dodavanje slike.
4. Dodavanje bloka koda.
5. Dodavanje izvora.

### Ne-numerčki popis
Dodavanje naslova.
Dodavanje podnaslova.
Dodavanje slika.
Dodavanje Bloka koda.
Dodavanje izvora.


### Tablica
|**Naziv projekta**|**Verzija**|**Autor**|
|--------------------|-------------|---------------|
| Kolokvij| 1.0 | Roko Dokoza|
