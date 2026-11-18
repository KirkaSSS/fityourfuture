# fityourfuture: matematika kroz priču

Srednjoškolska matematika ispričana kroz priče koje se pamte, za nastavu, pripremu za prijemni ispit i Instagram. Svaka celina ima interaktivnu aplikaciju, PDF nastavnu jedinicu sa zadacima i rešenjima i QR kod za brz pristup.

| Celina | Tema | Aplikacija | Materijal |
|---|---|---|---|
| **Brak kao kvadratna jednačina** | diskriminanta, dvostruki koren, Vijetove formule (II razred) | [otvori](https://kirkasss.github.io/fityourfuture/) | [PDF](Kvadratna_jednacina_diskriminanta_i_priroda_resenja.pdf) |
| **Ojler za tajkune** (novo) | kompleksni brojevi, Ojlerova formula, Moavr, koreni jedinice (III i IV razred) | [otvori](https://kirkasss.github.io/fityourfuture/tajkuni/) | [PDF](tajkuni/Kompleksni_brojevi_i_Ojlerova_formula.pdf) · [opis, QR kodovi, Instagram](tajkuni/) |

Druga celina počinje tamo gde se prva završava: kod `D < 0` i kompleksnih korena („imaginarna veza”).

---

# Brak kao kvadratna jednačina

Interaktivna aplikacija koja prikazuje brak kao rešenje kvadratne jednačine: dvoje ljudi su dva korena, a brak je trenutak kada postanu **dvostruki koren**, jedina tačka u kojoj se njihove krive dodirnu i ostanu.

**Aplikacija:** https://kirkasss.github.io/fityourfuture/

**Nastavna jedinica (PDF):** [Kvadratna jednačina: diskriminanta, priroda rešenja i Vijetove formule](Kvadratna_jednacina_diskriminanta_i_priroda_resenja.pdf), materijal za II razred srednje škole i pripremu za prijemni ispit

## Ideja

Jednačina zajedničkog života:

```
a·x² − L·x + c = 0
```

| Simbol | Značenje |
|---|---|
| `x` | zajednički život, nepoznata koju oboje traže |
| `a` | ona, fizičarka: koeficijent uz najviši stepen, određuje oblik cele parabole |
| `c` | on: iskustvo, godine, stabilnost, moć, resursi; slobodni član, temelj |
| `L` | ljubav; stoji sa minusom jer vuče rešenje na pozitivnu stranu |

Diskriminanta odlučuje o sudbini:

```
D = L² − 4ac
```

- `D > 0`: dva različita rešenja. Vole se, ali žive dva paralelna života.
- `D < 0`: kompleksna rešenja. Veza je imaginarna i postoji samo u mašti.
- `D = 0`: jedno, dvostruko rešenje. To je brak.

Uslov za brak je `L = 2√(a·c)`: ljubav mora biti tačno dvostruka geometrijska sredina njenog uma i njegove moći. Tada je rešenje `x = √(c/a)`, a jednačina postaje potpun kvadrat:

```
a·(x − √(c/a))² = 0
```

## Za prirodnjakušu (MINT*)

Kada je `D = 0`, parabola dodiruje x-osu u samo jednoj tački, kao tangenta. U kvantnoj mehanici se to zove degeneracija: dva stanja, ista energija.

```
Ĥ|ona⟩ = E|ona⟩,   Ĥ|on⟩ = E|on⟩
⟹ |mi⟩ = α|ona⟩ + β|on⟩,   Ĥ|mi⟩ = E|mi⟩

[ −ħ²/2m ∇² + V(r) ] ψ(r) = E ψ(r)
```

\* MINT = **M**athematik, **I**nformatik, **N**aturwissenschaften, **T**echnik: matematika, informatika, prirodne nauke i tehnika. Pojam potiče iz nemačkog govornog područja; u engleskom i na nivou EU poznat je kao STEM.

## Kako se koristi

1. Pomeraj klizače za ljubav (`L`), nju (`a`) i njega (`c`).
2. Parabola se crta uživo, a pored nje su vrednost diskriminante i stanje veze.
3. Dugme **Postavi D = 0** samo izračunava ljubav potrebnu za brak.

## Tehnički

Jedan samostalan `index.html` (HTML, CSS, JavaScript, SVG), bez zavisnosti i bez build koraka. Fontovi Lora i Inter učitavaju se sa Google Fonts. Stranica se objavljuje preko GitHub Pages sa grane `main`.

## Autorka

Snežana Đurković · [ORCID](https://orcid.org/0009-0007-6638-0682) · [GitHub](https://github.com/KirkaSSS)
