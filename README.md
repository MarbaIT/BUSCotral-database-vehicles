# Cotral Vehicles Information

Questa repository contiene informazioni sulle vetture bus della Cotral. I dati sono strutturati in formato JSON, facilmente utilizzabili per applicazioni o analisi.

## Leggenda

La repository contiene un file JSON chiamato `cotral_vehicles.json` che contiene le informazioni. Ogni veicolo è rappresentato da un oggetto con vari campi, come:

- **freshman**: Un identificativo univoco del veicolo.
- **model**: Il modello del veicolo.
- **accessibility**: Disponibilità di accesso per persone con disabilità.
- **deposit**: La rimessa in cui il veicolo è stazionato.
- **photo (facoltativo)**: Un oggetto contenente l'URL dell'immagine del veicolo e il credito per la foto.

### Esempio di dato

Un esempio di veicolo in formato JSON:

```json
{
  "freshman": "6197",
  "model": "Solaris Interurbino 12",
  "accessibility": true,
  "deposit": "Civita Castellana",
  "photo": {
    "image_url": "https://images.com/photo.jpg",
    "image_credit": "Mario Rossi"
  }
}
