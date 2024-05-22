<script>
	import foto from '$lib/img/maxresdefault.png';
</script>

<div  style="width: 1050px; padding-left: 30px; text-align: justify">
    <h1 class="title">Mi Presento</h1>
    <div class="container">
        <img
            src={foto}
            alt="img_agnelli"
            style="width: 400px; height: 260px; padding-top: 70px;"
        />
        <div>
            <p style="width: 600px; padding-left: 30px;">
                Buongiorno a tutti, mi chiamo Marco Minetti, sono nato il 31 ottobre
                2005 a Torino e frequento la 5 ITT presso l'Istituto Internazionale
                Edoardo Agnelli. Questo Portfolio ha l'obiettivo di racchiudere
                tutti gli argomenti di educazione civica affrontati durante il mio
                percorso di studi nella scuola superiore. In particolare, nei primi
                due anni, passati presso l'Istituto A. Volta, ho imparato i
                principali articoli della Costituzione italiana; a partire dal terzo
                anno, invece, ho approfondito argomenti tra cui i più importanti
                sono: lo sviluppo della società e le sue negatività, l'emancipazione
                femminile, lo specchio rovesciato della società, manicomi e
                prigioni, e la cittadinanza digitale. Questo Portfolio è scritto
                allo scopo di essere condiviso con altre persone interessate
                all'argomento.
            </p>
        </div>
    </div>
</div>
<style>
    .container {
        display: grid;
        grid-template-columns: 400px 700px;
    }

    .title {
        text-align: center;
        color: #005f6a;
        font-size: 70px;
    }
</style>
