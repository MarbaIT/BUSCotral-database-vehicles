# BUSCotral database vehicles

Questa repository contiene informazioni sui veicoli autobus della Cotral. I dati sono strutturati in formato JSON, facilmente utilizzabili per applicazioni o analisi.

## Leggenda

La repository contiene un file JSON chiamato `cotral_vehicles.json`, che include le informazioni. Ogni veicolo è rappresentato da un oggetto con vari campi, come:

- **freshman**: Matricola univoca del veicolo.
- **model**: Modello del veicolo.
- **accessibility**: Disponibilità di accesso per persone con disabilità.
- **deposit**: Rimessa in cui il veicolo è stazionato.
- **photo (facoltativo)**:
    - **image_url**: URL contenente un'immagine rappresentativa del veicolo.
    - **image_credit**: Crediti autore e licenza.
    - **image_description**: Descrizione dell'immagine.

## Esempio di dato

Un esempio di veicolo in formato JSON:

```json
{
    "freshman": "0101",
    "model": "Neoplan Skyliner L",
    "accessibility": true,
    "deposit": "Subiaco",
    "photo": {
      "image_url": "https://raw.githubusercontent.com/MarbaIT/BUSCotral-database-vehicles/refs/heads/main/image/0101.png",
      "image_credit": "Marba - cc-by-sa-2.5",
      "image_description": "Skyliner in sosta a Roma Tiburtina"
    }
}
```
