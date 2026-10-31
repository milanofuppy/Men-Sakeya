# Quiz Menu Sakeya

Web app per aiutare i nuovi camerieri a imparare il menu autunnale 2026 di Sakeya.

## Funzioni
- **Quiz** a scelta multipla, con quattro modalità:
  - Nome → Piatto
  - Piatto → Nome
  - Nome → Significato (che cosa vuol dire il nome giapponese)
  - Parole giapponesi (glossario: wagyu, don, aburi, negi…)
- Filtro per sezione del menu
- Le risposte sbagliate vengono riproposte più avanti
- **Menu** completo per sezione, con kanji, significato del nome e ricerca
- **Parole**: glossario dei termini che ricorrono nei nomi dei piatti

## Uso
Apri `index.html` nel browser. Nessuna installazione necessaria.

### GitHub Pages
1. Carica i file in un repository
2. Settings → Pages → Branch `main`, cartella `/ (root)`
3. Il quiz sarà su `https://<utente>.github.io/<repo>/`

## Modificare il menu
- Piatti: array `D` in `index.html`, ogni riga è
  `[sezione, nome, kanji, piatto, dettagli, prezzo, significato, scomposizione del nome]`
- Glossario: array `G`, ogni riga è `[parola, kanji, significato]`
