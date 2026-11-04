# Grafika

Osobny folder na przyszłe rysunki i ich edytowalne źródła.
W materiałach pierwszej części nie ma rysunków wymagających odtworzenia.

Rysunki wstawiaj przez względne ścieżki, używając `\includegraphics`,
`\label` i `\ref`. Samodzielne źródła `.tex` w tym folderze są
kompilowane przez `kompiluj.ps1` do plików PDF w tym samym folderze.

## Wykład 4

- `aproksymacja-przedzialu.tex` - odtworzenie osi z IMG_6935: przedział
  domknięty wewnątrz przedziału otwartego z przesuniętymi końcami.
- `otoczenie-punktu.tex` - ilustracje z IMG_6939: otoczenie punktu na prostej
  oraz prostokąty wewnątrz koła.
- `roznica-i-rozlacznienie.tex` - rozkład zbioru z IMG_6943 oraz schemat
  rozłącznienia ciągu z IMG_6944. W prawym panelu wyróżniono części B_1,
  B_2 i B_3; okręgi oznaczają odpowiednio A_1, A_2 i A_3.

## Wykład 5

- `miara-punktowa.tex` - schemat skończenie wielu punktów z wagami,
  odtworzony na podstawie IMG_6967. Zastosowano ogólne oznaczenia z tablicy,
  ponieważ konkretne wartości przy szkicu nie są dostatecznie czytelne.

## Wykład 7

- `dystrybuanty-lebesgue-dirac.tex` - wykresy F_lambda(t)=t oraz
  dystrybuanty delta_0 ze zdjęć IMG_7022, IMG_7024 i IMG_7025.
- `dystrybuanty-atomowa-szkic.tex` - dystrybuanta miary
  (1/4)delta_{-1}+(1/2)delta_0+(1/4)delta_1, z normalizacją w zerze,
  oraz schemat dystrybuanty miary na zbiorze Cantora z IMG_7025,
  zgodnie z doprecyzowaniem użytkownika. Wykres Cantora odtworzono
  za pomocą skończonego przybliżenia; nie dodano konstrukcji miary.

## Wykład 8

- `funkcje-minimum-maksimum.tex` - punktowe minimum i maksimum dwóch
  funkcji z IMG_7081; ciemniejsza krzywa oznacza maksimum, jaśniejsza minimum.
- `funkcja-ciagla-przeciwobraz.tex` - schemat otwartego przeciwobrazu
  półprostej przez funkcję ciągłą z IMG_7084.
- `calka-podzialy.tex` - schematy prostokątów z IMG_7086: podział
  dziedziny oraz podział wartości funkcji.
- `funkcje-proste.tex` - funkcja charakterystyczna z IMG_7086
  oraz przykład 2*1_[0,1]+1_(1,2] z IMG_7087. Poziome fragmenty
  i oznaczenia końców określają wartości funkcji w punktach 0, 1 i 2.

Wykresy są odtworzeniami schematów z tablicy. Pomocnicze krzywe
nie wprowadzają dodatkowych przykładów z zadanymi wzorami.

## Okładka

- `okladka-kreskowkowa.png` - zatwierdzona ilustracja: postać patrząca
  w górę, napis „PRAWDZIWE σ-CIAŁO” na cokole oraz wybór jednego kwiatu
  z każdej donicy. Wielokropki oznaczają kontynuację rodziny i wyborów.
- `okladka.tex` i `okladka.pdf` - wspólna okładka A4 obu wariantów skryptu,
  osadzająca zatwierdzony obraz wraz z tekstowym odpowiednikiem napisów.

Przebudowa przez `kompiluj.ps1` zachowuje ilustrację.
Repozytorium wraz z okładką jest publiczne.
