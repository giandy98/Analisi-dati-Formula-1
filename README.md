# Analisi-dati-Formula-1
Analisi dei risultati del Campionato Mondiale di Formula 1 della stagione 2008


Il progetto prevede l'implementazione delle seguenti funzionalità:

1. Funzione per l'analisi delle performance individuali dei piloti
La prima funzione riceve in input il nome di un pilota e restituisce una lista contenente tre informazioni chiave: - Il totale dei punti accumulati dal pilota durante il campionato. - Il numero di vittorie, ovvero quante volte il pilota è arrivato primo in un Gran Premio. - Il numero di podi, ovvero quante volte il pilota è arrivato tra i primi tre classificati.

Questa funzione sarà utile per analizzare le performance individuali dei piloti e avere una chiara visione delle loro posizioni nel corso della stagione.

2. Funzione per la creazione della classifica finale dei piloti
La seconda funzione genera un dizionario contenente i nomi dei piloti come chiavi e il loro punteggio totale come valori. Il dizionario viene poi utilizzato per creare una classifica generale dei piloti.

Infine, la classifica sarà salvata in un file di testo (Drivers_Standings_2008.txt) con il seguente formato:

Drivers Standings 2008 Formula 1
NomePilota1: PunteggioTotale
NomePilota2: PunteggioTotale

3. Funzione per la classifica dei costruttori
La terza funzione crea un dizionario con i nomi dei team/costruttori come chiavi e il loro punteggio totale come valori. Il punteggio di ciascun team è la somma dei punti ottenuti dai piloti che hanno gareggiato per quel costruttore.

Questa funzione utilizza i dati precedentemente generati per i piloti e calcola la classifica dei costruttori. Anche questa informazione è essenziale per avere una visione chiara delle prestazioni dei team durante l'anno.
