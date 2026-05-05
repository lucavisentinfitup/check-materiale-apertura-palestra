# Check Materiale IT - Apertura Palestra

Webapp statica per il controllo del materiale IT in fase di apertura palestra.

## Funzioni

- Checklist divisa per macro-categorie
- Checkbox materiale arrivato
- Salvataggio automatico nel browser tramite `localStorage`
- Campo sede/palestra
- Ricerca materiale
- Note per ogni voce
- Export CSV
- Reset checklist

## Pubblicazione su GitHub Pages

1. Crea un nuovo repository GitHub, ad esempio:
   `check-materiale-palestra`

2. Carica questi file nella root del repository:
   - `index.html`
   - `README.md`

3. Vai in:
   `Settings > Pages`

4. In **Build and deployment** seleziona:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`

5. Salva.

Dopo qualche minuto GitHub genera un link tipo:

`https://TUO-UTENTE.github.io/check-materiale-palestra/`

## Uso

Apri il link, inserisci il nome della sede e spunta il materiale man mano che arriva.
I dati sono salvati localmente sul browser del dispositivo utilizzato.
