Vzpostavljena metoda omogoča analizo periodičnih števnih podatkov. Uporabljena je metoda cosinor v kombinaciji z različnimi regresijskimi modeli, ki so primerni za števne podatke. Uporabljenih je pet računskih modelov, tj. Poissonov model, negativen binomski model, generaliziran Poissonov model, Poissonov model z inflacijo ničel in negativen binomski model z inflacijo ničel.

Vzpostavljena metoda omogoča vrednotenje zgrajenih modelov. S pomočjo F testa poiščemo optimalno število komponent za metodo cosinor, na podlagi Voungovega testa pa določimo najustreznejši tip modela. Ocenimo lahko parametre ritma - amplituda, vrednost MESOR, lokacije vrhov, izračunamo pa lahko tudi intervale zaupanja za posamezen parameter ritma.

Podrobnejša implementacija vzpostavljene metode je dostopna v [RhythmCount modulu](RhythmCount).

Celotna metoda je bila testirana na realnih podatkih COVID-19 obolenj v Sloveniji. Podatki so pridobljeni s strani [COVID-19 sledilnik](https://covid-19.sledilnik.org/sl/data) (uporabljeni podatki so dostopni v mapi [data](data)).
Uporabili smo tri podatkovne zbirke. Prva vsebuje podatke od 20.10.2020 do 10.2.2021, druga od 11.2.2021 do 26.4.2021 in tretja od 20.10.2020 do 26.4.2021.
Zgled analize z vmesnimi  rezultati je dostopen v datoteki [zgled_analize.ipynb](zgled_analize.ipynb). Generirani reultati analize so shranjeni v mapi [results](results).
