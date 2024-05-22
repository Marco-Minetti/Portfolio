<script>
    import cod from '$lib/img/img_cod.png';
    import lib1 from '$lib/img/libro-1.jpg';
    import lib2 from '$lib/img/libro-2.jpg';
</script>


<div  style="width: 1050px; padding-left: 30px; text-align: justify">
    <h1 class="title">2022 - 2023</h1>

    <h2 class="sub-title">TPSI</h2> 
    
    <p>
        Il mondo della tecnologia in 3D è in costante evoluzione. Una dei protagonisti degli ultimi anni è senza dubbio la realtà virtuale.
        Quando parliamo di realtà virtuale, parliamo di un mondo virtuale modellato in 3D in cui possiamo muoverci e interagire con l’ambiente immaginario che ci circonda.
        Ovviamente, questo mondo non ha nulla di reale. Possiamo accedervi tramite periferiche come visori, auricolari, guanti e addirittura tute integrali. L’ambiente virtuale è quindi progettato a livello sonoro, visivo e tattile per ricreare un’esperienza il più possibile simile alla realtà
        In contemporanea, si è sviluppato un’altra tecnologia, la realtà aumentata.
        La realtà aumentata è una tecnologia che consente di arricchire l’esperienza sensoriale umana, offrendo informazioni che non sarebbero altrimenti accessibili nel mondo reale. Mentre la realtà virtuale è molto immersiva, la realtà aumentata integra nuove informazioni nell’ambiente reale che ci circonda. Un esempio di realtà aumentata sono gli ologrammi.
    </p>


    <iframe
        src="https://prof.mancusoa.it/blog/virtual-reality/"
        frameborder="0"
        width="985"
        height="560"
        allowfullscreen="true"
        mozallowfullscreen="true"
        webkitallowfullscreen="true"
        title="Programming language"
        style="margin-left: 30px"
    />

    <h2 class="sub-title">Inglese</h2>

    <p>
        I linguaggi di programmazione sono la base dello sviluppo software, senza di essi i programmatori non potrebbero comunicare in modo semplice le istruzioni ai computer e di conseguenza sarebbe impossibile scrivere le applicazioni e i servizi che usiamo quotidianamente tramite terminale, sia esso un PC Desktop o uno smartphone.
        Un linguaggio di programmazione è una lingua formale pensata per realizzare set di istruzioni (input) con cui si producono dati in uscita (output).
    </p>
    <div class="container">
        <p>
            Fondamentalmente i linguaggi di sviluppo convertono i concetti astratti dell’uomo in codice macchina, ovvero la lingua con cui opera il computer. Tutti i sistemi informatici moderni lavorano tramite una serie di direttive comunemente chiamate codice binario. Le macchine infatti immagazzinano e gestiscono le informazioni tramite una serie complessa di bit (binary digit), cioè di 0 e 1.
            Leggere e scrivere degli enormi gruppi di dati dati in questo formato è ovviamente impossibile per l’uomo ed ecco perché sono stati creati dei sistemi, i linguaggi di programmazione appunto, che traducono il binario in una lingua molto simile a quella parlata dai developer.
        </p>
        <div style="margin-top: 25px">
            <iframe
                src="https://docs.google.com/presentation/d/1B9y8aoxLGk6ededOE6imELai8KX2SBx-qaZLGB68lNs/embed?start=false&loop=false&delayms=3000"
                frameborder="0"
                width="505"
                height="360"
                allowfullscreen="true"
                mozallowfullscreen="true"
                webkitallowfullscreen="true"
                title="Programming language"
            />
        </div>
    </div>
    <h2 class="sub-title">Informatica</h2>

    <div class="container invert">
        <img
            src={cod}
            alt="img_agnelli"
            style="width: 550px; height: 350px; padding-top: 20px;"
        /> 

        <p>
            Il codice fiscale è uno strumento essenziale per l'identificazione dei cittadini in Italia. 
            Viene utilizzato in molteplici contesti, sia pubblici che privati, e permette di svolgere varie attività burocratiche, fiscali e amministrative.
            Durante il corso di informatica abbiamo creato un programma che inserendo i dati di nome, cognome, data e luogo di nascita, 
            restituisce il codice fiscale dell'interessato.
            <br>Qui sotto è inserito il link al codice per eseguire il programma.<br>
            <a href="https://github.com/Marco-Minetti/Codice_fiscale">Codice</a>
        </p>
    </div>

    <h2 class="sub-title">Italiano</h2>

    <div class="container">
        <p>
            La pena di morte è una sanzione penale la cui esecuzione consiste nel togliere la vita alla persona condannata. <br>
            «La pena di morte non è un diritto, ma è una guerra della nazione contro un suo cittadino». Così
            scriveva Cesare Beccaria in "<a href="https://docenti.unimc.it/raffaella.coppier/teaching/2023/28236/files/beccaria/dei-delitti-e-delle-pene">Dei delitti e delle Pene</a>".
            Beccaria si esprimeva contro la pena di morte, argomentando che con questa pena lo Stato, per punire un delitto, ne commetterebbe uno a sua volta. <br>
            "<a href="https://books.google.com.ec/books?id=JrB9UKmfukgC&printsec=frontcover&source=gbs_atb#v=onepage&q&f=false">L'ultimo giorno di un condannato a morte</a>" è un romanzo scritto da Victor Hugo nel 1829. Sono narrati, in prima persona, gli ultimi giorni di vita di un prigioniero del carcere di Bicêtre, destinato al patibolo.
            Non appena la condanna è stata pronunciata, il prigioniero ha avvertito di aver varcato una linea invisibile e di aver perduto agli occhi dei suoi simili la sua condizione di essere umano.
        </p>
        <img src={lib2} alt="becca" style="width: 500px; height: 485px; padding-top: 20px">
    </div>
</div>

<style>
    .title {
        text-align: center; 
        color: #005F6A; 
        font-size: 70px;
    }

    .sub-title {
        text-align: center; 
        color: #4ac992; 
        font-size: 50px;
    }

    .container {
        width: 1050px;
        display: grid;
        margin: 0 auto;
        grid-template-columns: 510px 1fr;
        gap: 30px;
    }

    .invert {
        width: 1000px;
        grid-template-columns: 550px 1fr;
    }
</style>