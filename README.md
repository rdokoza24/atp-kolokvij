# atp-kolokvij

## Wikipedija je globalan, višejezični projekt s ciljem izgradnje slobodne internetske enciklopedije koja je svima javno dostupna. Njezini su suradnici dobrovoljci. Wikipedijom danas rukovodi neprofitna organizacija

![Slika](https://images.pexels.com/photos/965879/pexels-photo-965879.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)

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
2. [Slika izvučena sa Pexels](https://images.pexels.com/photos/965879/pexels-photo-965879.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)



### Numerički popis:
1. Dodavanje naslova.
2. Dodavanje podnaslova.
3. Dodavanje slike.
4. Dodavanje bloka koda.
5. Dodavanje izvora.

### Ne-numerčki popis
-Dodavanje naslova.
-Dodavanje podnaslova.
-Dodavanje slika.
-Dodavanje Bloka koda.
-Dodavanje izvora.


### Tablica
|**Naziv projekta**|**Verzija**|**Autor**|
|--------------------|-------------|---------------|
| Kolokvij| 1.0 | Roko Dokoza|

## Check lista

- [x] Kreirati GitHub repozitorij nazvan atp-kolokvij
- [x] Dodati naslov projekta (H1)
- [x] Dodati kratki opis projekta (H2) – preuzeti tekst s Wikipedije
- [x] Dodati sliku – preuzeti s Unsplash ili Pexels
- [x] Dodati primjer koda – preuzeti s Gists
- [x] Dodati link na izvor slike i teksta
- [x] Linkati README.md i LICENSE.md (obostrano)
- [x] Napraviti popis (numerički i ne-numerički)
- [x] Izraditi kratku tablicu s informacijama o projektu
- [x] Napraviti commit promjena s odgovarajućom porukom
- [x] Otvoriti pull request unutar vlastitog repozitorija
- [x] Dodati LICENSE.md datoteku s MIT licencom
- [x] Aktivirati GitHub Pages za repozitorij

[Read LICENSE](LICENSE.md)
