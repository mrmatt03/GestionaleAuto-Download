<p align="center">
  <img src="https://github.com/user-attachments/assets/0038b33f-9efb-4f0e-8ab9-f188bf78e559" width="120" height="120" alt="AutomatePro Logo" />
</p>

<h1 align="center">AutomatePro</h1>

<p align="center">
  <strong>Gestionale Professionale per Concessionarie Auto</strong><br>
  Sviluppato in JavaFX.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=java" alt="Java" />
  <img src="https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows" alt="Platform" />
  <img src="https://img.shields.io/badge/Version-1.2.0--MSI-green?style=for-the-badge" alt="Version" />
</p>


---

##  Panoramica

**AutomatePro** è una soluzione desktop stand-alone progettata per ottimizzare il flusso di lavoro delle concessionarie auto. L'applicativo elimina la necessità di fogli di calcolo disordinati, offrendo un database centralizzato (SQLite) per la gestione del parco veicoli, delle anagrafiche clienti e della documentazione contrattuale.

L'interfaccia utente è costruita su **JavaFX** utilizzando il tema *Cupertino Dark*, garantendo un ambiente di lavoro coerente, moderno e a basso affaticamento visivo.

---

##  Funzionalità

### Gestione Parco Auto
* **Doppia Visualizzazione:** Vista tabellare per operazioni massive e vista a griglia (Card View) per la consultazione rapida.
* **Stati Dinamici:** Tracking automatico dello stato del veicolo (*Disponibile, In Trattativa, Venduta*).
* **Filtri Avanzati:** Ricerca in tempo reale per targa, modello o telaio.

### Modulo Burocratico & PDF
Generazione automatica della documentazione pre-compilata:
* Contratti di Vendita e Ricevute di Caparra.
* Moduli per Prova su Strada (Scarico Responsabilità).
* **Registro Pubblica Sicurezza:** Export conforme per il registro di carico/scarico.

### Analytics
Dashboard integrata per il monitoraggio dei KPI aziendali:
* Margini di profitto e fatturato.
* Analisi dei trend di vendita e giacenze medie.

---

##  Interfaccia Utente

### Dashboard
Una panoramica immediata delle performance aziendali e delle scadenze imminenti.
<p align="center">
  <img width="1913" height="973" alt="Screenshot 2026-01-28 224727" src="https://github.com/user-attachments/assets/8c971f95-677b-49b9-b267-ea1616434058" />
</p>


### Parco Auto (Vista Griglia)
Gestione visiva del magazzino con indicatori di stato e miniature.
<p align="center">
 <img width="1536" height="866" alt="Screenshot 2026-01-28 225124" src="https://github.com/user-attachments/assets/6e51540d-fa19-48e4-8847-c9fb94d8d95e" />

</p>

### Scheda Tecnica Dettagliata
Visualizzazione completa dei dati veicolo, storico lavori e galleria fotografica.
<p align="center">
  <img width="1188" height="699" alt="Screenshot 2026-01-29 202511" src="https://github.com/user-attachments/assets/29882652-f058-43a0-b4ce-474a5965a3d2" />

</p>

---

## 🛠️ Specifiche Tecniche

* **Linguaggio:** Java 17+
* **Framework UI:** JavaFX + AtlantaFX (Cupertino Dark Theme)
* **Database:** SQLite (Locale, criptato)
* **Reporting:** Librerie iText/OpenPDF per la generazione documentale.

---

##  Installazione

L'applicazione è distribuita come pacchetto nativo `.msi` per Windows, non richiede configurazione di server esterni.

1. Scarica l'ultima versione dalla sezione **[Releases](https://github.com/mrmatt03/GestionaleAuto-Download/releases)**.
2. Esegui l'installer e segui la procedura guidata.
3. Al primo avvio, compila i dati aziendali nel pannello impostazioni.

---

##  Licenza

AutomatePro è un software commerciale. È disponibile una versione di prova completa.

* **Trial:** 14 giorni di prova gratuita con tutte le funzionalità attive (Watermark sui PDF).
* **Licenza Pro:** Rimuove i limiti e include aggiornamenti a vita.

Gestione pagamenti e licenze sicura tramite **Lemon Squeezy**.

[👉 **Acquista Licenza**](https://automatepro.lemonsqueezy.com/checkout/buy/22126732-0d80-4de1-a1f5-2b8576bf4cc5)

---

<p align="center">
  <sub>Developed in Italy. Per supporto tecnico: support@automatepro.it</sub>
</p>
