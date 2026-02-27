# ECG Filter Wizard

Wizard interattivo per la configurazione dei filtri sul dispositivo ECG **Lepu PCECG-500**.

## Cosa fa

Propone preset deterministici per i filtri ECG più comuni e un fallback a configurazione step-by-step per casi non standard.

### Preset disponibili

- **ADS** — filtro per artefatti da derivazione
- **EMG** — filtro per interferenza muscolare
- **Lowpass** — filtro passa-basso generico

Se nessun preset è adeguato, il wizard guida l'utente nella configurazione manuale dei singoli parametri di filtraggio. È sempre possibile tornare indietro con il pulsante **Indietro**.

## Contesto clinico

L'elettrocardiografo portatile Lepu PCECG-500 offre diverse opzioni di filtraggio che incidono sulla qualità del tracciato. La scelta del filtro corretto dipende dal contesto clinico (ambulatorio, domicilio, screening) e dal tipo di artefatto prevalente. Questo wizard semplifica la decisione.

## Come usarlo

👉 **[Apri il wizard](https://salvofedele.github.io/ecg-filter-wizard)**

Funziona direttamente nel browser, senza installazione.

## Stack

HTML / CSS / JavaScript — single-page, nessuna dipendenza esterna.

## Autore

**Salvatore Fedele** — pediatra, esploratore di strumenti digitali per la clinica.

## Vedi anche

- [PFT Interpretazione Wizard](https://github.com/salvofedele/pft-interpretazione-wizard) — interpretazione prove di funzionalità respiratoria
- [NIV Decision Wizard](https://github.com/salvofedele/niv-decision-wizard) — settaggio ventilazione non invasiva
- [EP-DD Wizard](https://github.com/salvofedele/ep-dd-wizard) — diagnostica TC torace
- [Segnale e Rumore](https://github.com/salvofedele/segnale-e-rumore) — educazione perinatale
