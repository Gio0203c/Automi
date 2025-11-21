# La Favola della Formalizzazione della Matematica
Cosa significa che alcune scienze (come la geometria euclidea, la meccanica, la teoria degli insiemi, etc.) sono **formalizzate**?

Il concetto di **formalizzazione** si basa sull'idea di rendere l'oggetto di studi un sistema costituito in questo modo:
- Esistono degli assiomi principali
- Dati veri gli assiomi principali, vi sono una serie di teoremi, dimostrazioni, conseguenze che permettono di dimostrare qualsiasi affermazione all'interno del sistema.

Un esempio concreto relativo alla formalizzazione di una materia di studi è quello dell'aritmetica di Peano. In particolare, come studiato nel corso di **Algebra**, gli assiomi di Peano sono i seguenti:
1) Zero è un *numero naturale*.
2) Per ogni numero naturale, *esiste sempre il suo successivo*.
3) Numeri diversi *hanno* successivi *diversi*.
4) Zero *non è il successivo di nessun numero*.
5) Se un insieme $A$ di numeri *contiene lo zero* e di ogni numero *contiene anche il successivo*, allora $A$ contiene **tutti** i numeri naturali.

Da questi $5$ assiomi è possibile generare tutti i numeri naturali, ma anche i numeri interi, i razionali, etc. Tutta l'aritmetica deriva da queste regole.

Uno dei primi esempi trattati quando si parla di formalizzazione è quello della Geometria Euclidea. Lo stesso Euclide aveva cercato di basare tutti i suoi teoremi con relative dimostrazioni su questi $5$ postulati:
1. Tra due punti qualsiasi è possibile tracciare una ed una sola retta.
2. Si può prolungare un segmento oltre i due punti indefinitamente
3. Dato un punto ed una lunghezza, è possibile descrivere un cerchio.
4. Tutti gli angoli retti sono uguali tra loro.
5. Il postulato delle rette parallele.
	- **In modo pulito:** Data una retta ed un punto esterno, passa una ed una sola parallela alla retta.
	- **In modo sporco:** In particolare, se una retta taglia altre due rette determinando dallo stesso lato angoli interni la cui somma è minore di due angoli retti, prolungando le due rette, esse si incontreranno nella parte di tali angoli.

Il problema principale però era che il sistema di Euclide non era puramente formale, ma si affidava spesso all'intuizione visiva.

Nel 1899 però, David Hilbert, nel suo libro *Grundlagen der Geometrie* (Fondamenti della Geometria), riscrisse la geometria euclidea per renderla una struttura puramente logica, eliminando le intuizioni.

La sua frase celebre fu:
>[!quote] Citazione
>Si deve poter dire 'tavoli' , 'sedie' e 'boccali' al posto di 'punti', 'rette' e 'piani'. 

Nel senso che non importa cosa siano gli oggetti, importano solo le regole che li governano. Hilbert quindi sostituì i 5 postulati di Euclide con 20 assiomi divisi in 5 gruppi.

Perciò Hilbert si chiese se fosse possibile espandere questo concetto a tutta la matematica, che ultimamente era vista come in crisi, perché in seguito a nuove teorie sull'infinito erano sorti paradossi che formavano delle "crepe" logiche. Un esempio famoso è quello del paradosso di Russel:
>[!quote] Citazione
>L'insieme di tutti gli insiemi che non appartengono a sé stessi appartiene a sé stesso se e solo sé non appartiene a sé stesso.

Nasce quindi il **progetto di Hilbert**, che consisteva nel formalizzare tutte le teorie di matematica esistenti, attraverso un insieme finito di assiomi, e dimostrare che essi non conducessero a contraddizioni.

I punti del suo progetto erano:
1. **Formalizzazione:** Hilbert voleva che tutta la matematica fosse riscritta in sistema, scritto come un linguaggio rigoroso di simboli. L'idea era di smettere di affidarsi all'intuizione o al significato filosofico dei numeri.
2. **Coerenza:** Hilbert voleva che all'interno di un sistema non si potesse dimostrare che un affermazione è vera e che contemporaneamente è falsa
3. **Completezza:** Hilbert voleva un sistema in grado di rispondere a tutto. Per qualsiasi affermazione matematica formulata correttamente, il sistema deve contenere al suo interno la capacità di dimostrare se è vera o se è falsa.
4. **Decidibilità:** Hilbert cercava un metodo meccanico, una procedura per stabilire se un affermazione è valida oppure no.

Il suo motto divenne:
>[!quote] Citazione
>Wir müssen wissen. Wir werden wissen.
>(Dobbiamo sapere. Sapremo.)

Nel 1930 si tenne un convegno a Königsberg riguardo l'epistemologia delle scienze esatte (ovvero cercare di dare risposte alle domande come "cosa rende una scienza esatta?). In quei giorni ci fu una discussione finale al convegno, una sorta di chiacchierata. Quasi alla fine della discussione, un giovane (24 anni) di nome Kurt Gödel interviene dicendo:
>[!quote] Citazione
>Se assumiamo che la matematica sia coerente, si possono costruire proposizioni che sono vere ma non dimostrabili.

Nessuno aveva capito ciò che Gödel aveva detto, tranne una persona: **John von Neumann**. Se Gödel avesse avuto ragione, il programma di Hilbert sarebbe morto. Appena finita la sessione ci fu un confronto tra Von Neumann e Gödel, che divenne uno scambiarsi di lettere.

In sintesi, Gödel riuscì a dimostrare che:
1. **La completezza è impossibile:** In qualsiasi sistema matematico, esisteranno sempre affermazioni vere che il sistema non riesce a dimostrare.
2. **La coerenza non si può auto certificare:** Un sistema non può dimostrare la propria coerenza usando solo i propri mezzi.

Poco dopo, **Alan Turing** dimostrò inoltre che anche la decidibilità è impossibile: per ogni problema matematico non esiste una procedura meccanica che possa risolverlo.

Il progetto di Hilbert, nella sua forma originale, era finito.

