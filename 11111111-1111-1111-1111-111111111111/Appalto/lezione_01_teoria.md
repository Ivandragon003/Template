# Lezione 01 - Introduction to Web Technologies

## Architettura generale di una full-stack web application

Una **full-stack web app architecture** puo essere letta come una catena di responsabilita. Da un lato c'e il **Web Browser**, cioe il programma con cui l'utente interagisce direttamente. Dall'altro lato ci sono uno o piu **Web Server(s)**, cioe componenti remoti che ricevono richieste, elaborano dati, accedono eventualmente a database o servizi esterni e restituiscono risposte.

La comunicazione tra browser e server avviene **per lo piu tramite HTTP**, cioe il protocollo applicativo alla base del Web. Nelle applicazioni moderne, in realta, si usa quasi sempre **HTTPS**, che e HTTP sopra una connessione cifrata tramite **TLS**. Dal punto di vista architetturale, pero, il modello resta quello fondamentale: un **client** invia una richiesta a un **server**, e il server restituisce una risposta.

La slide distingue tre livelli: **architecture**, **components** e **technologies**. A livello di architettura vedo browser e server. A livello di componenti vedo **front-end** e **back-end**. A livello di tecnologie compaiono esempi del mondo front-end, come **HTML**, **CSS**, **JavaScript**, framework e librerie UI, ed esempi del mondo back-end e server-side, come web server, runtime e framework applicativi. Questa distinzione e fondamentale: **front-end** e **back-end** non sono linguaggi, ma responsabilita architetturali; le tecnologie sono strumenti concreti usati per implementare tali responsabilita.

Il **front-end** e la parte dell'applicazione che gestisce l'interfaccia utente, l'interazione, la presentazione dei dati e spesso una parte della logica applicativa eseguita nel browser. Il **back-end** e la parte che gestisce dati, regole di business, autenticazione, autorizzazione, persistenza, integrazione con altri servizi e generazione delle risposte. In una web app moderna, front-end e back-end comunicano spesso tramite **API HTTP**, ad esempio **REST APIs**.

## The World Wide Web: introduzione

**Internet** e l'infrastruttura globale di reti interconnesse. E una rete mondiale di computer collegati che condividono informazioni usando protocolli Internet. Internet e quindi il livello infrastrutturale: reti, collegamenti, indirizzamento, protocolli di trasporto e comunicazione tra macchine.

Il **World Wide Web**, spesso abbreviato in **WWW** o semplicemente **Web**, e invece un sottoinsieme dell'Internet piu ampio. Il Web e un sistema di documenti ipertestuali interconnessi, collegati tra loro tramite **hyperlinks**. I suoi componenti centrali sono **HTTP** e **HTML**.

La differenza e essenziale: posso usare Internet senza usare il Web, ad esempio con email, SSH o altri protocolli; quando invece uso un browser per navigare pagine collegate tra loro tramite link e recuperate con HTTP, sto usando il Web.

## Hypertext documents

Un documento tradizionale puo essere visto come una semplice sequenza di caratteri. Leggo dall'inizio alla fine, con una struttura lineare. Un **hypertext**, invece, e un documento che contiene anche **links**, detti anche **hyperlinks**, verso altri contenuti. Questi contenuti possono essere altri ipertesti, documenti, immagini, video, file o altre risorse.

Il concetto di collegamento e cio che rende il Web diverso da un archivio statico di documenti. Un link permette di passare da una risorsa a un'altra seguendo relazioni semantiche, non solo la sequenza fisica delle pagine. In altre parole, il Web e una rete di risorse collegate, e non semplicemente una collezione di file.

## HTTP: Hypertext Transfer Protocol

**HTTP**, cioe **Hypertext Transfer Protocol**, e un **application protocol** costruito sopra **TCP/IP**. Dire che HTTP e un protocollo applicativo significa che si colloca a un livello alto della comunicazione: definisce come client e server si scambiano messaggi applicativi, non come i singoli bit viaggiano fisicamente sulla rete.

HTTP e la fondazione e la spina dorsale del **World Wide Web**. E nato per trasferire ipertesti, ma oggi viene usato anche per molte altre risorse: immagini, video, file JSON, API, fogli di stile, script, font, documenti, dati strutturati e contenuti generati dinamicamente.

Il modello base e semplice: un **Client** richiede una particolare risorsa e un **Server** risponde. Nel Web, il client e spesso un browser, ma puo essere anche un'app mobile, uno script, un tool da terminale, un'app desktop o un altro server. Il server e il componente che espone risorse e servizi. Le risorse sono identificate tramite **URLs**, cioe **Uniform Resource Locators**.

La sequenza logica e:

```text
Client -- HTTP Request --> Server
Client <-- HTTP Response -- Server
```

Questa struttura richiesta/risposta e il cuore del Web tradizionale. Ogni volta che digito un indirizzo nel browser, clicco un link, carico un'immagine o invio un form, sto generando una o piu richieste HTTP e ricevendo una o piu risposte HTTP.

## URL: Uniform Resource Locator

Una **URL**, cioe **Uniform Resource Locator**, e un identificatore che indica dove si trova una risorsa e come accedervi. L'esempio delle slide e:

```text
https://www.informatica.it:4242/corsi/tecweb.html
```

Una URL puo essere scomposta in piu parti: **scheme**, **domain name**, **port** e **path**. Le slide indicano anche che le URL possono contenere **query parameters** e **anchors**.

## Scheme o protocollo della URL

La prima parte della URL e lo **scheme**, chiamato anche protocollo:

```text
https
```

Lo scheme specifica il protocollo usato per accedere alla risorsa. Nel Web, i protocolli piu comuni sono **http** e **https**. Quando vedo **http://**, il browser usa HTTP senza cifratura a livello applicativo. Quando vedo **https://**, il browser usa **HTTP Secure**, cioe HTTP sopra una connessione cifrata.

La cifratura di HTTPS viene ottenuta tramite **Transport Layer Security (TLS)**. TLS fornisce proprieta di sicurezza fondamentali: cifratura del traffico, protezione dell'integrita dei dati e autenticazione del server tramite certificati. In pratica, TLS rende molto piu difficile per un attaccante leggere o modificare il traffico tra client e server.

Le slide sottolineano che HTTPS ha un ruolo importante nel mitigare alcune classi di attacchi alle web application. Non risolve tutti i problemi di sicurezza, ma e una base necessaria. Senza HTTPS, credenziali, cookie, dati personali e contenuti sensibili potrebbero essere esposti durante il transito.

## Domain name

La parte successiva dell'esempio e il **domain name**:

```text
www.informatica.it
```

Il domain name indica il nome di dominio del web server che ospita la risorsa. Un dominio e composto da piu parti separate da punti e si legge da destra verso sinistra. Nell'esempio **.it** e il **Top Level Domain (TLD)**. Il TLD e il livello piu alto della gerarchia dei nomi di dominio.

La parte **informatica** e il **Secondary Level Domain (SLD)**. E il nome registrato sotto il TLD. Eventuali parti aggiuntive a sinistra definiscono **subdomains**, usati per differenziare contenuti, servizi o sezioni dello stesso dominio.

Esempi di sottodomini indicati o coerenti con le slide sono:

```text
blog.mozilla.org

```

In **blog.mozilla.org**, il TLD e **.org**, il dominio di secondo livello e **mozilla**, e **blog** e un sottodominio. 

## Port

Nell'esempio delle slide la porta e:

```text
4242
```

La **port** indica la porta da usare quando si stabilisce una connessione al server. A livello pratico, un server puo offrire piu servizi sulla stessa macchina o sullo stesso indirizzo IP, e la porta serve a distinguere il servizio applicativo da contattare.

La porta puo essere omessa quando il server usa le porte standard. La porta standard di **HTTP** e **80**, mentre la porta standard di **HTTPS** e **443**. Se invece il server usa una porta non standard, come **4242**, questa deve essere specificata nella URL.

## Path

La parte finale dell'esempio principale e il **path**:

```text
/corsi/tecweb.html
```

Il path indica la posizione specifica sul server in cui e memorizzata o resa disponibile la risorsa. Nelle applicazioni web semplici, il path puo corrispondere direttamente a un file dentro una directory del server. Nelle applicazioni moderne, invece, il path puo essere gestito da un router applicativo e non corrispondere a un file fisico.

il path e tipicamente relativo a una **web root directory** sul server. Il server deve servire solo file dentro la web root directory. Questo e un punto di sicurezza molto importante: non vogliamo che tutti i file del server siano accessibili dal Web. File di configurazione, codice sorgente, variabili d'ambiente, backup, chiavi private o dati interni non devono essere esposti pubblicamente.

La web root crea quindi un confine: cio che e dentro puo essere esposto secondo le regole del server, cio che e fuori non deve essere raggiungibile tramite URL. Molte vulnerabilita web nascono proprio quando questo confine viene gestito male, ad esempio tramite path traversal o configurazioni errate.

## Query parameters e anchors

 le URL possono contenere anche **query parameters** e **anchors**.

I **query parameters** sono tipicamente la parte dopo il simbolo **?** e servono a passare parametri alla risorsa, ad esempio filtri, ricerche, paginazione o opzioni. Un esempio generico e:

```text
https://example.com/search?q=web&page=2
```

Gli **anchors**, o frammenti, sono la parte dopo il simbolo **#**  e rappresenta una sorta di **bookmark** all'interno della risorsa. Serve a dire al browser di mostrare il contenuto localizzato in quel punto del documento. Un esempio generico e:

```text
https://example.com/docs#installation
```

## HTTP messages

HTTP prevede due tipi principali di messaggi: **Request** e **Response**.

La struttura concettuale e:

```text
Request:
Verb URI HTTP Version
Request Headers
Request Body

Response:
HTTP Version Status
Response Headers
Response Body
```

Quando una web app non funziona, spesso il debugging parte proprio dal guardare request e response.

## HTTP request verbs o methods

I **HTTP request verbs**, detti anche **methods**, indicano l'azione desiderata da eseguire su una risorsa. I metodi comuni indicati dalle slide sono **GET**, **POST**, **PUT** e **DELETE**.

**GET** serve a recuperare una rappresentazione di una risorsa. GET dovrebbe essere usato per leggere dati, non per modificarli.

**POST** serve a inviare nuovi dati alla risorsa specificata. E usato, ad esempio, per inviare form, creare nuove entita, avviare operazioni o mandare payload al server. POST include tipicamente un body con dati.

**PUT** serve a sostituire la risorsa corrente con il payload specificato.

**DELETE** serve a cancellare la risorsa specificata. 

## HTTP request headers

Gli **headers** sono un modo per passare informazioni aggiuntive nelle richieste e nelle risposte HTTP. Un header e composto da un nome, non sensibile al maiuscolo/minuscolo, seguito da due punti e poi dal valore:

```text
HEADER_NAME: value
```

Il fatto che il nome sia **case-insensitive** significa che, per il protocollo, **Content-Type**, **content-type** e **CONTENT-TYPE** indicano lo stesso header. In pratica, pero, conviene usare la capitalizzazione standard per leggibilita.

 E anche possibile definire **custom headers**, cioe header personalizzati, spesso usati da applicazioni, API o infrastrutture specifiche. I custom headers vanno usati con criterio, perche aumentano accoppiamento e complessita se non documentati bene.

Gli header possono comunicare informazioni come il tipo di contenuto accettato, il tipo di contenuto inviato, la lingua preferita, la lunghezza del body, dati di autenticazione, gestione cache, cookie, compressione, connessione e molte altre proprieta.

## HTTP request example

Le slide mostrano un esempio di richiesta HTTP:

```http
GET /wisdom/grain.txt HTTP/1.1
Host: bookofprogramming.com
User-Agent: Mozilla/5.0
Accept: text/plain
Accept-Language: en-us
Connection: keep-alive
```

La prima riga contiene **Method**, **URL/URI** e **Protocol Version**. Il metodo e **GET**, quindi il client vuole recuperare una risorsa. La risorsa richiesta e **/wisdom/grain.txt**. La versione del protocollo e **HTTP/1.1**.

L'header **Host: bookofprogramming.com** specifica il nome dell'host richiesto. Questo e particolarmente importante in HTTP/1.1 perche piu siti possono essere ospitati sullo stesso indirizzo IP, e il server deve sapere quale dominio il client sta chiedendo.

L'header **User-Agent: Mozilla/5.0** comunica informazioni sul client. Storicamente il valore User-Agent identifica browser, motore di rendering, sistema operativo o compatibilita, anche se nella pratica moderna questi valori possono essere complessi e non sempre affidabili.

L'header **Accept: text/plain** indica che il client accetta una risposta in formato testo semplice. L'header **Accept-Language: en-us** indica una preferenza linguistica per l'inglese statunitense. L'header **Connection: keep-alive** indica il desiderio di mantenere aperta la connessione per riutilizzarla, riducendo overhead rispetto all'apertura di una nuova connessione per ogni risorsa.

dopo gli header c'e una **blank line**. Questa riga vuota e importante perche separa gli header dal body.

## HTTP response status codes

Gli **HTTP response status codes** indicano se una richiesta e stata completata con successo o quale tipo di esito si e verificato. Gli status code sono raggruppati in cinque classi.

La classe **100-199**, detta **Informational**, indica risposte informative.

La classe **200-299**, detta **Success**, indica che la richiesta e stata gestita con successo.

La classe **300-399**, detta **Redirection**, indica che il client deve compiere un'azione ulteriore, spesso seguire un'altra URL.

La classe **400-499**, detta **Client Error**, indica che il problema e attribuibile alla richiesta del client. **400 Bad Request** indica una richiesta malformata o non valida. **403 Forbidden** indica che il server ha capito la richiesta ma rifiuta di autorizzarla. **404 Not Found** indica che la risorsa richiesta non e stata trovata.

La classe **500-599**, detta **Server Error**, indica che il server non e riuscito a completare una richiesta apparentemente valida. **500** indica un errore interno generico dell'applicazione o del server. **503 Service Unavailable** indica che il servizio non e disponibile, ad esempio per sovraccarico o manutenzione.

## HTTP response example

Le slide mostrano un esempio di risposta HTTP:

```http
HTTP/1.1 200 OK
Content-Type: text/plain
Content-Length: 153

Fu-Tzu said: 'When you cut against
the grain of the wood, much strength
is needed. When you program against
the grain of a problem, much code is
needed.'
```

La prima riga contiene **Protocol Version**, **Status** e **Status Message**. In questo caso la versione e **HTTP/1.1**, lo status code e **200** e il messaggio e **OK**. Significa che la richiesta e stata completata correttamente.

L'header **Content-Type: text/plain** indica che il corpo della risposta e testo semplice. Questo e fondamentale per il client, perche il browser o il programma che riceve la risposta deve sapere come interpretare il body. Se il Content-Type fosse **text/html**, il browser lo tratterebbe come HTML; se fosse **application/json**, come JSON; se fosse **image/png**, come immagine PNG.

L'header **Content-Length: 153** indica la lunghezza del body in byte. Questa informazione aiuta il client a sapere quanti dati aspettarsi.

## HTTP statelessness

Una proprieta fondamentale di HTTP e la **statelessness**. Dire che HTTP e **stateless** significa che ogni richiesta e indipendente dalle precedenti. Il server, a livello di protocollo HTTP puro, non mantiene automaticamente informazioni sulle richieste precedenti fatte dallo stesso client.

Questo ha vantaggi e svantaggi. Il vantaggio principale e la semplicita: ogni richiesta contiene cio che serve per essere interpretata, e il server non e costretto dal protocollo a mantenere uno stato di conversazione per ogni client. Questo favorisce scalabilita, distribuzione e possibilita di gestire richieste indipendenti.

Lo svantaggio e che molte applicazioni web reali hanno bisogno di stato. Ad esempio, quando faccio login, aggiungo prodotti al carrello, salvo preferenze o navigo in un'area personale, l'applicazione deve riconoscermi tra richieste diverse. Poiche HTTP non mantiene automaticamente questo stato, servono meccanismi specifici.

Le slide citano i **cookies** come esempio di meccanismo per permettere comunicazione stateful sopra un protocollo altrimenti stateless. l'idea base e che il server invia al client un piccolo dato, e il client lo reinvia nelle richieste successive, permettendo al server di collegare piu richieste alla stessa sessione.

## HTTP for web browsing: overview

Le slide mostrano cosa succede quando digitiamo nel browser:

```text
http://example.com/dir/file.txt
```

Il processo puo essere spiegato in piu passi.

Per prima cosa, il browser deve capire a quale macchina corrisponde il nome **example.com**. Per questo effettua una richiesta al **DNS**, cioe **Domain Name System**. Il DNS traduce il nome di dominio in un indirizzo IP. Nell'esempio delle slide, **example.com** viene risolto in **93.184.216.34**.

Dopo aver ottenuto l'indirizzo IP, il browser apre una **TCP connection** verso il server HTTP. TCP fornisce un canale di comunicazione affidabile su cui HTTP puo inviare i propri messaggi. In caso di HTTPS, prima dello scambio HTTP ci sarebbe anche la negoziazione TLS per creare una connessione cifrata.

Una volta aperta la connessione, il browser invia una **HTTP request**.

Il server riceve la richiesta, la interpreta, recupera o genera la risorsa richiesta e invia una **HTTP response**.

Infine, il browser riceve la risposta e mostra o usa il contenuto. Se la risorsa fosse una pagina HTML, il browser potrebbe poi generare ulteriori richieste per caricare CSS, JavaScript, immagini, font e altre risorse collegate.
## HTML: Hypertext Markup Language

**HTML**, cioe **Hypertext Markup Language**, e lo standard per rappresentare documenti ipertestuali nel Web. Le pagine web con cui interagiamo nei browser sono documenti definiti usando HTML.

HTML permette di definire pagine con **headings**, **paragraphs**, **images**, **lists**, **tables** e molti altri elementi. Il suo ruolo non e principalmente quello di programmare comportamento, ma di descrivere la struttura e il contenuto del documento. Per lo stile si usa CSS, per il comportamento JavaScript, ma HTML e la base semantica della pagina.

La parola **Hypertext** richiama il fatto che i documenti HTML possono contenere link verso altre risorse. La parola **Markup** indica che il testo viene arricchito con marcatori, cioe tag, che ne descrivono struttura e significato. **Language** indica che esiste una sintassi standard interpretata dai browser.

