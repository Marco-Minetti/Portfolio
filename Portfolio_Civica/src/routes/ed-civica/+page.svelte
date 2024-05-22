<script>
	import civic from '$lib/img/edu-civica.png';
</script>


<div  style="width: 1050px; padding-left: 30px; text-align: justify">
    <h1 class="title">EDUCAZIONE CIVICA</h1>

    <div class="container">
        
        <p>
            La Legge, ponendo a fondamento dell’educazione civica la conoscenza della Costituzione Italiana, la
            riconosce non solo come norma cardine del nostro ordinamento, ma anche come criterio per
            identificare diritti, doveri, compiti, comportamenti personali e istituzionali, finalizzati a promuovere il
            pieno sviluppo della persona e la partecipazione di tutti i cittadini all’organizzazione politica, economica
            e sociale del Paese. <br> La Carta è in sostanza un codice chiaro e organico di valenza culturale e pedagogica,
            capace di accogliere e dare senso e orientamento in particolare alle persone che vivono nella scuola e
            alle discipline e alle attività che vi si svolgono.
        </p>
        
        <img src={civic} alt="foto_italia" style="width: 350px; height:340px;">
    </div>

    <div class="container non-cont">
        <h3 style="color: blue; font-size: 25px;">I nuclei tematici che la costituiscono sono:</h3>

        <p>
            1. COSTITUZIONE, diritto (nazionale e internazionale), legalità e solidarietà <br>

            2. SVILUPPO SOSTENIBILE, educazione ambientale, conoscenza e tutela del patrimonio e
            del territorio <br>

            3. CITTADINANZA DIGITALE
    </p>
    </div>
</div>

<style>
    .title {
        text-align: center; 
        color: #005F6A; 
        font-size: 70px;
    }

    .container {
        width: 900px;
        display: grid;
        margin: 0 auto;
        grid-template-columns: 550px 1fr;
        gap: 50px;
    }

    .non-cont {
        padding-top: 50px;
        display:block;
    }
</style>