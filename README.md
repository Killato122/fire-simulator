# fire-simulator

Calcolatore FIRE per l'Italia: una pagina HTML statica per stimare versamenti, capitale futuro, fiscalita' e rendita mensile.

## Come usarlo

Apri `index.html` in un browser. Non serve build step, backend o installazione di dipendenze.

I grafici usano Chart.js da CDN. Se la CDN non e' disponibile, la pagina resta utilizzabile e mostra comunque risultati numerici, timeline e riepiloghi.

## Funzioni

- Modalita' obiettivo: scegli rendita mensile netta desiderata, eta' FIRE e capitale iniziale; il simulatore calcola il versamento mensile necessario.
- Modalita' accumulo: scegli quanto versi al mese e l'eta' target; il simulatore stima capitale lordo, netto e rendita.
- Preset rendimento: prudente 4%, base 6%, ottimistico 8%.
- Mensilita' extra reinvestite: 13a, 14a o importi annuali equivalenti.
- Confronto strumenti: ETF low-cost, PAC Trade Republic e fondo bancario.
- Breakdown fiscale: bollo, CGT stimata e capitale netto.
- Link condivisibili: quando pubblicato via HTTP/HTTPS, lo stato della simulazione viene salvato nella query string.

## Assunzioni principali

- Rendimento annuo lordo di base: 6%.
- TER base della simulazione principale: 0,20%.
- Inflazione: 2%.
- Safe Withdrawal Rate: 3,5%.
- Imposta di bollo: 0,20% annuo.
- Capital gain tax: 26% sulla plusvalenza stimata.
- La rendita desiderata e' espressa in euro di oggi; i capitali target/finali sono mostrati come euro futuri stimati.

## Limiti

Questa e' una simulazione educativa, non consulenza finanziaria o fiscale. Il modello semplifica fiscalita', sequenza dei rendimenti, volatilita', drawdown, minusvalenze, strumenti con tassazione diversa, cripto, ETC, titoli di Stato e situazioni personali. Prima di prendere decisioni reali, verifica numeri e regole con fonti ufficiali o un professionista.
