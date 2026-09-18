Informativa sulla Privacy - Rclone Server Integration

Ultimo aggiornamento: 18/09/2026

1. Tipologia di dati raccolti

L'applicazione richiede l'autorizzazione di accesso tramite OAuth 2.0 all'account Google Drive dell'utente al solo scopo di sincronizzare e trasferire file tra il server dell'utente e il proprio Google Drive. Non raccogliamo, memorizziamo su server esterni né tracciamo dati personali, indirizzi email o metadati degli utenti.

2. Utilizzo degli ambiti di accesso (OAuth Scopes)

L'applicazione richiede l'accesso a Google Drive ([https://www.googleapis.com/auth/drive](https://www.googleapis.com/auth/drive) o ambiti limitati come drive.file). Questo accesso viene utilizzato esclusivamente per:

    Leggere, creare e aggiornare i file e le cartelle autorizzate dall'utente per le operazioni di sincronizzazione/backup.

3. Archiviazione delle Credenziali

I token di aggiornamento e d'accesso ottenuti durante la procedura OAuth sono memorizzati unicamente nel file di configurazione locale di Rclone (rclone.conf) gestito direttamente dall'utente sul proprio server. Nessun token o dato di accesso viene trasmesso a server esterni di terze parti.

4. Limite d'uso e Garanzie dei dati degli utenti Google

L'uso delle informazioni ricevute dalle API di Google da parte di questa applicazione rispetta la Google API Services User Data Policy, inclusi i requisiti di utilizzo limitato (Limited Use requirements). I dati non vengono utilizzati per finalità pubblicitarie né condivisi con terzi.

5. Contatti

Per qualsiasi chiarimento sull'integrazione, è possibile contattare l'amministratore tramite mail.
