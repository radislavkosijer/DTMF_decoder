# DTMF Decoder

Ovaj projekat implementira dekoder za DTMF (Dual-Tone Multi-Frequency) signale korištenjem vremenski zavisne Furijeove transformacije (STFT). DTMF je metoda signalizacije koja koristi kombinaciju dvije sinusoide za predstavljanje svakog tastera na telefonskoj tastaturi.

## Opis

Svaki taster generiše signal koji se sastoji od dvije različite frekvencije – jedna iz niskofrekventne, a druga iz visokofrekventne grupe. Projekat koristi STFT za detekciju ovih frekvencija i dekodovanje pozivanog broja iz audio signala.

Korišteni su test signali iz tri `.mat` fajla:
- `dtmf1.mat`: čist signal bez šuma
- `dtmf2.mat`: signal sa dodatim Gausovim bijelim šumom
- `dtmf3.mat`: signal sa šumom i uskopojasnom interferencijom

## Pokretanje

Notebook `DTMF_decoder.ipynb` sadrži kompletnu implementaciju i analizu. Potrebno je samo imati Python okruženje sa navedenim bibliotekama i `.mat` fajlove.

