# Changelog - FolderSize Viewer Pro âš¡

Tutte le modifiche rilevanti, i miglioramenti e le nuove versioni di **FolderSize Viewer Pro** sono documentati in questo file.

---

## ðŸ“Œ Cos'Ã¨ FolderSize Viewer Pro?

**FolderSize Viewer Pro** Ã¨ un'applicazione desktop nativa ad altissime prestazioni per Windows (.NET WPF a 64 bit) progettata per analizzare lo spazio su disco ed esplorare l'intero File System in tempo reale con una **struttura ad albero interattiva**. 

A differenza di Esplora File di Windows (che non mostra la dimensione delle cartelle e richiede di aprire manualmente le "ProprietÃ " di ciascuna), FolderSize Viewer calcola e ordina istantaneamente il peso effettivo di ogni directory e sottodirectory, permettendo di individuare e liberare gigabyte di spazio sprecato in pochi secondi.

---

## ðŸŒŸ Caratteristiche Principali

- **Analisi e Aggregazione Istantanea**:
  - Calcolo immediato della dimensione totale aggregata di ogni cartella e sottocartella.
  - Conteggio in tempo reale del numero di file e cartelle contenuti.
  - Ordinamento automatico per dimensione decrescente: i file e le cartelle piÃ¹ pesanti sono sempre posizionati in cima.
  - Barre visive dell'occupazione percentuale (%) con indicatore cromatico intuitivo (Rosso > 50%, Arancione 20-50%, Ciano < 20%).

- **âš¡ Motore di Eliminazione Turbo Ultra-Veloce**:
  - **Eliminazione Turbo (Tasto `Canc`)**: rimozione parallela multi-thread su 16-32 thread ad alte prestazioni. Ridenomina istantaneamente la cartella facendola sparire dall'interfaccia in 1 millisecondo e cancellando gigabyte di dati in background senza congelare il PC.
  - **Cestino Standard (Tasto `Ctrl + Canc`)**: opzione per inviare i file al Cestino tradizionale di Windows.

- **ðŸ›¡ï¸ Protezione File di Sistema (Safety Guard)**:
  - Sistema di sicurezza attivo che impedisce la cancellazione accidentale delle cartelle e dei file critici del sistema operativo (`C:\`, `C:\Windows`, `System32`, `Program Files`, `ProgramData`, cartelle utente di root, file di paging).

- **ðŸŽ¨ Interfaccia Grafica Moderna e Raffinata**:
  - Design scuro (Dark Theme) ad alto contrasto e affaticamento visivo ridotto.
  - Finestre di dialogo e notifiche personalizzate ed eleganti con badge luminosi a tema (informazioni, avvisi, pericolo ed eliminazione turbo).

- **ðŸ”„ Aggiornamenti Automatici Integrati (Auto-Updater)**:
  - Controllo automatico e non invasivo della presenza di nuove versioni all'apertura del programma.
  - Finestra di aggiornamento moderna con visualizzazione delle note di rilascio e barra di download in tempo reale.
  - Sostituzione atomica del programma ed auto-riavvio in loco, con elevazione automatica dei permessi (UAC) se installato in `Program Files`.

- **ðŸ“¦ Standalone a Singolo File & Installer Ufficiale**:
  - **Nessuna dipendenza esterna**: non necessita dell'installazione del runtime .NET (Self-Contained).
  - Disponibile sia come eseguibile portatile singolo (`FolderSizeViewer.exe`) sia con installatore guidato Inno Setup (`Setup.exe`) integrato nel menu contestuale (tasto destro del mouse su qualsiasi cartella).

---

## ðŸ“ Registro Versioni

### [4.0.0] - 2026-09-26
#### NovitÃ  & Sicurezza
- **Architettura di Rilascio Closed-Source**: separazione tra repository privato del codice sorgente e repository pubblico per la distribuzione degli aggiornamenti, garantendo la totale privacy del codice.
- **Modulo di Protezione Avanzata `SystemSafetyGuard`**: blocco preventivo assoluto su percorsi vitali di Windows per prevenire arresti o danneggiamenti del sistema operativo.
- **Nuove Finestre di Messaggio `ModernMessageBox`**: sostituzione completa di tutti i dialoghi standard Win32 con finestre moderne scure e coerenti con la grafica dell'applicazione.
- **Script di Rilascio a 1-Click**: procedura automatica per la compilazione, creazione del setup e pubblicazione degli aggiornamenti.

### [3.0.0] - 2026-09-25
#### NovitÃ  & Miglioramenti
- **Controllo Aggiornamenti all'Avvio**: l'app verifica automaticamente in background la presenza di nuove versioni all'avvio.
- **Finestra di Aggiornamento `UpdateDialog`**: nuova interfaccia scura con pill badge di versione, cronologia novitÃ  formattata e avanzamento del download in tempo reale.

### [2.0.0] - 2026-09-25
#### NovitÃ 
- **Installer Inno Setup**: creazione del file di installazione ufficiale con icona personalizzata sul Desktop e nel Menu Start.
- **Integrazione Menu Contestuale di Windows**: voce *"Analizza dimensione con FolderSize Viewer"* presente cliccando con il tasto destro su qualsiasi cartella o disco in Esplora Risorse.
- **Compilazione Standalone Single-File**: inclusione completa del runtime per l'utilizzo immediato senza prerequisiti su qualsiasi PC a 64 bit.

### [1.0.0] - 2026-09-24
#### Rilascio Iniziale
- Esploratore ad albero multi-livello con calcolo istantaneo delle dimensioni aggregate.
- Ordinamento automatico per dimensione decrescente.
- Motore Turbo Fast-Deleter multi-thread per l'eliminazione rapida.
- Interfaccia scura reattiva basata su WPF e .NET.
