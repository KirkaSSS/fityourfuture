# Ojler za tajkune

Kompleksni brojevi i Ojlerova formula kroz satiričnu priču o tajkunu: realni deo je prijavljeni novac, imaginarni deo je crna kasa, a `e^(iφ)` vrti novac u krug kroz ofšor firme. Nastavak priče [Brak kao kvadratna jednačina](../), koja se završava kod `D < 0` i kompleksnih korena.

**Aplikacija:** https://kirkasss.github.io/fityourfuture/tajkuni/

**Nastavna jedinica (PDF):** [Kompleksni brojevi i Ojlerova formula kroz priču o tajkunima](Kompleksni_brojevi_i_Ojlerova_formula.pdf), materijal za III i IV razred srednje škole i pripremu za prijemni ispit

**QR kod:** [PNG](media/qr_ojler_za_tajkune.png) · [SVG](media/qr_ojler_za_tajkune.svg)

## Četiri lekcije u aplikaciji

| Lekcija | Formula | U priči |
|---|---|---|
| 1 · Kamatna spirala | `z(t) = e^((r + iω)t)` | `r` pravi rast, `ω` kruženje; `r = 0` je pranje novca, `e^(2πi) = 1` |
| 2 · Dvojno knjigovodstvo | `\|z\| = √(a² + b²)`, `z + z̄ = 2a`, `z·z̄ = \|z\|²` | inspektor vidi `Re z`, tajkun ima `\|z\|` |
| 3 · Ofšor koreni | `zⁿ = 1`, `Σ z_k = 0` | zbir svih ofšor firmi je nula |
| 4 · Zaokret posle izbora | `z·e^(iθ)`, `e^(iπ) = −1`, `i² = −1` | bogatstvo isto, stav okrenut |

## Most ka kvadratnoj jednačini

Za `a·x² − L·x + c = 0` sa `D < 0` koreni su konjugovani par i po Vijetu važi `|z|² = c/a`. Koreni zato leže na krugu poluprečnika `√(c/a)`, tačno u tački braka:

```
z₁,₂ = √(c/a) · e^(±iφ),   cos φ = L / (2√(ac))
```

## Instagram

- Karusel, 9 slajdova: [media/karusel](media/karusel)
- Rils, 35 s: [media/ojler_za_tajkune_reel.mp4](media/ojler_za_tajkune_reel.mp4)
- Tekstovi objava: [media/instagram_tekstovi.md](media/instagram_tekstovi.md)
- Izvorni fajlovi (HTML za ponovno renderovanje): [media/src](media/src)

## Tehnički

Jedan samostalan `index.html` (HTML, CSS, JavaScript, SVG), bez zavisnosti i bez build koraka, isti stil kao aplikacija o braku. Satira je namerno uopštena: tajkun je izmišljen lik, bez imena, stranke i grada.

## Autorka

Snežana Đurković · [ORCID](https://orcid.org/0009-0007-6638-0682) · [GitHub](https://github.com/KirkaSSS)
