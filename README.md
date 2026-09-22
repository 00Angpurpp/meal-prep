# Pasti

App per comporre i pasti della settimana: scegli proteina, base, verdura e condimento
per ogni pranzo e cena, e l'app calcola calorie e macro, la media settimanale e la
lista della spesa divisa per reparto.

È una **PWA**: si installa sulla schermata Home dell'iPhone e funziona anche offline.

## Installare su iPhone

1. Apri l'indirizzo del sito con **Safari** (non Chrome).
2. Tocca il pulsante **Condividi** (il quadrato con la freccia in su).
3. Scegli **Aggiungi a Home**.

L'icona compare tra le app. Da lì si apre a schermo intero, senza barra del browser,
e continua a funzionare senza connessione.

## Dove finiscono i dati

I pasti che inserisci restano **solo sul tuo dispositivo** (memoria locale del browser)
e nel link stesso. Non vengono inviati da nessuna parte: questo sito non ha un server,
sono solo file statici.

## File

| File | A cosa serve |
|---|---|
| `index.html` | tutta l'app: struttura, stile e logica in un unico file |
| `manifest.json` | nome, icona e modalità a schermo intero per l'installazione |
| `sw.js` | service worker: tiene la copia locale per il funzionamento offline |
| `icon-*.png`, `apple-touch-icon.png` | icone della app |
| `.nojekyll` | dice a GitHub Pages di pubblicare i file così come sono |
